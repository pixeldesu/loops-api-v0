# `loops.video/api/v0/report/video`

## Request

<details>
<summary>Raw request</summary>
<pre>
POST https://loops.video/api/v0/report/video HTTP/2.0
accept: application/json
content-type: application/json
accept-encoding: gzip, deflate, br
content-length: 62
user-agent: Loops/7 CFNetwork/1568.200.51 Darwin/24.1.0
accept-language: en-US,en;q=0.9
authorization: Bearer [[ redacted ]]

{"report_type":"1012","reported_video_id":"[[ redacted ]]"}
</pre>
</details>

## Response

<details>
<summary>Raw response</summary>
<pre>
HTTP/2.0 200 
date: Thu, 07 Nov 2024 02:03:34 GMT
content-type: application/json
vary: Accept-Encoding
cache-control: no-cache, private
access-control-allow-origin: *
x-frame-options: SAMEORIGIN
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
cf-cache-status: DYNAMIC
report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v4?s=YKL%2BCa%2FIt6fFoBcCgCA4mepgxkJ8rrPECENF6b7jG%2BwCrSAluS5Khq7VVBsKgLJqatPcwEfb%2FFfbI9jLziIl7TTjLYmvFTalallstCGgmYpUU8Ql95rIkJRiLeqMlxWN3Dwcf58LRzSLPA%3D%3D"}],"group":"cf-nel","max_age":604800}
nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
server: cloudflare
cf-ray: 8de9bf61e9fb2c4a-FRA
alt-svc: h3=":443"; ma=86400
server-timing: cfL4;desc="?proto=TCP&rtt=37091&sent=100&recv=55&lost=0&retrans=1&sent_bytes=36564&recv_bytes=3097&delivery_rate=402010&cwnd=242&unsent_bytes=0&cid=13282fa449336872&ts=463518&x=0"
content-length: 14

{"status":200}
</pre>
</details>