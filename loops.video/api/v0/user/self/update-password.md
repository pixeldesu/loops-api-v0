# `loops.video/api/v0/user/self/update-password`

## Request

<details>
<summary>Raw request</summary>
<pre>
POST https://loops.video/api/v0/user/self/update-password HTTP/2.0
accept: application/json
content-type: application/json
accept-encoding: gzip, deflate, br
content-length: 256
user-agent: Loops/4 CFNetwork/1568.200.51 Darwin/24.1.0
accept-language: en-US,en;q=0.9
authorization: Bearer [[ redacted ]]

{"current_password":"[[ redacted ]]","password":"[[ redacted ]]","password_confirmation":"[[ redacted ]]"}
</pre>
</details>

## Response

<details>
<summary>Raw response</summary>
<pre>
HTTP/2.0 200 
date: Tue, 05 Nov 2024 01:31:04 GMT
content-type: application/json
vary: Accept-Encoding
cache-control: no-cache, private
access-control-allow-origin: *
x-frame-options: SAMEORIGIN
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
cf-cache-status: DYNAMIC
report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v4?s=C2g%2FylAyVe6Qz5XMWV09p%2BdPrBjn6bzssTo08nyGekzkfEzyYsM9I8ZPOIXENK9qbVOWqoW0X7YIv6Tx46q6NAizPSjK1DEmLR2%2FGoworj6%2FTpbWrGpXIU%2F93uioHIKxfEz2djxUoT0flQ%3D%3D"}],"group":"cf-nel","max_age":604800}
nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
server: cloudflare
cf-ray: 8dd9150088ac9e60-CDG
alt-svc: h3=":443"; ma=86400
server-timing: cfL4;desc="?proto=TCP&rtt=39621&sent=13&recv=12&lost=0&retrans=0&sent_bytes=4208&recv_bytes=1473&delivery_rate=118254&cwnd=38&unsent_bytes=0&cid=9e0d6766d3d62eee&ts=62456&x=0"
content-length: 57

{"status":200,"message":"Successfully updated password!"}
</pre>
</details>