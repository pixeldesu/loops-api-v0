# `loops.video/api/v0/report/profile`

## Request

<details>
<summary>Raw request</summary>
<pre>
POST https://loops.video/api/v0/report/profile HTTP/2.0
accept: application/json
content-type: application/json
accept-encoding: gzip, deflate, br
content-length: 64
user-agent: Loops/7 CFNetwork/1568.200.51 Darwin/24.1.0
accept-language: en-US,en;q=0.9
authorization: Bearer [[ redacted ]]

{"report_type":"1012","reported_profile_id":"[[ redacted ]]"}
</pre>
</details>

## Response

<details>
<summary>Raw response</summary>
<pre>
HTTP/2.0 200 
date: Thu, 07 Nov 2024 02:05:23 GMT
content-type: application/json
vary: Accept-Encoding
cache-control: no-cache, private
access-control-allow-origin: *
x-frame-options: SAMEORIGIN
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
cf-cache-status: DYNAMIC
report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v4?s=it5C7ZIkdsPTSNvvtewHeSGLE%2BxM9hL7fCGAhvlwMLBUwNkM%2FOZpzZcs3yQGc6%2BHyLS5WwVUKqaD9MtH3egpmJJUtELCfTeQIDs9xKcgObzQTPXr4c0W4ck5iWdWxmcIjiwfBv3cfp8LKw%3D%3D"}],"group":"cf-nel","max_age":604800}
nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
server: cloudflare
cf-ray: 8de9c20dfc390363-CDG
alt-svc: h3=":443"; ma=86400
server-timing: cfL4;desc="?proto=TCP&rtt=38732&sent=12&recv=10&lost=0&retrans=0&sent_bytes=4544&recv_bytes=932&delivery_rate=114961&cwnd=258&unsent_bytes=0&cid=8c87ba31b8db5ded&ts=8676&x=0"
content-length: 14

{"status":200}
</pre>
</details>