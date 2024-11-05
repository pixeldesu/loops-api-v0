# `loops.video/auth/start`

## Request

<details>
<summary>Raw request</summary>
<pre>
POST https://loops.video/auth/start HTTP/2.0
accept: application/json
content-type: multipart/form-data; boundary=q80BZS8drE7aUewhHRJTJpYHFTX0o2tLgPWFrLmBT42fkem4QPtpvLVM2af0flSHsuQ9mn
accept-encoding: gzip, deflate, br
user-agent: Loops/4 CFNetwork/1568.200.51 Darwin/24.1.0
content-length: 708
accept-language: en-US,en;q=0.9

--

content-disposition: form-data; name="email"

[[ redacted ]]

--

content-disposition: form-data; name="password"

[[ redacted ]]

--

content-disposition: form-data; name="build"

4

--

content-disposition: form-data; name="device_name"

Loops for ios

--
</pre>
</details>

## Response

<details>
<summary>Raw response</summary>
<pre>
HTTP/2.0 200 
date: Mon, 04 Nov 2024 23:19:27 GMT
content-type: application/json
vary: Accept-Encoding
cache-control: no-cache, private
x-ratelimit-limit: 5
x-ratelimit-remaining: 4
x-frame-options: SAMEORIGIN
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
cf-cache-status: DYNAMIC
report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v4?s=q0vCEwEAEYQhktKGoBVOocH8e%2FvK6V8fUoWFzBssN6I78mWz56nwKarklgrwgKh4%2BxAubrjQx2CCyVCdwf%2FhJ6%2FrWv0RxSAuagBW5qplq7dhrP9fJhHUxvAlRbZ4s5%2Fno7R5anb3JxTHiw%3D%3D"}],"group":"cf-nel","max_age":604800}
nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
server: cloudflare
cf-ray: 8dd854393d802a6d-CDG
alt-svc: h3=":443"; ma=86400
server-timing: cfL4;desc="?proto=TCP&rtt=117455&sent=7&recv=7&lost=0&retrans=0&sent_bytes=3410&recv_bytes=1523&delivery_rate=37330&cwnd=35&unsent_bytes=0&cid=c99d2d1a2a8deeb7&ts=1098&x=0"
content-length: 70

{"auth_token":"[[ redacted ]]"}
</pre>
</details>