# `loops.video/api/v0/meta-app/feedback/submit`

## Request

<details>
<summary>Raw request</summary>
<pre>
POST https://loops.video/api/v0/meta-app/feedback/submit HTTP/2.0
accept: application/json
content-type: application/json
accept-encoding: gzip, deflate, br
content-length: 54
user-agent: Loops/4 CFNetwork/1568.200.51 Darwin/24.1.0
accept-language: en-US,en;q=0.9
authorization: Bearer [[ redacted ]]

{"category":"bug","body":"Can't delete videos in app"}
</pre>
</details>

## Response

<details>
<summary>Raw response</summary>
<pre>
HTTP/2.0 201 
date: Mon, 04 Nov 2024 23:24:57 GMT
content-type: application/json
cache-control: no-cache, private
access-control-allow-origin: *
x-frame-options: SAMEORIGIN
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
cf-cache-status: DYNAMIC
report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v4?s=diKM4qK0DPfttJszXvt2k8Z3fhx846BgwR5yhjvCsmFgTYjrH%2FY915MayCx1Bk%2FbBz8ehjM6ZUOdyckNjnoflwVQ57gRP6AbZNFkcx7OU%2FIh7u02%2FvjB%2FIv0eVL6sA0x0jREEJw2a%2BMkRQ%3D%3D"}],"group":"cf-nel","max_age":604800}
nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
server: cloudflare
cf-ray: 8dd85c4bef46f1a4-CDG
alt-svc: h3=":443"; ma=86400
server-timing: cfL4;desc="?proto=TCP&rtt=30122&sent=8510&recv=15014&lost=0&retrans=0&sent_bytes=63434&recv_bytes=20337321&delivery_rate=418689&cwnd=208&unsent_bytes=0&cid=104658e4ec02a8a3&ts=95819&x=0"
content-length: 106

{"id":222,"type":"bug","body":"Can't delete videos in app","response_requested":null,"admin_seen_at":null}
</pre>
</details>