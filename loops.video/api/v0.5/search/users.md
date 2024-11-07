# `loops.video/api/v0.5/search/users`

## Request

<details>
<summary>Raw request</summary>
<pre>
POST https://loops.video/api/v0.5/search/users HTTP/2.0
accept: application/json
content-type: application/json
accept-encoding: gzip, deflate, br
content-length: 17
user-agent: Loops/7 CFNetwork/1568.200.51 Darwin/24.1.0
accept-language: en-US,en;q=0.9
authorization: Bearer [[ redacted ]]

{"q":"pixeldesu"}
</pre>
</details>

## Response

<details>
<summary>Raw response</summary>
<pre>
HTTP/2.0 200 
date: Thu, 07 Nov 2024 02:21:52 GMT
content-type: application/json
vary: Accept-Encoding
cache-control: no-cache, private
access-control-allow-origin: *
x-frame-options: SAMEORIGIN
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
cf-cache-status: DYNAMIC
report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v4?s=z%2FdHHKwffrXaLaqMksYYfGqSJ2fujHPlV58G2Ot8GtuqZbfsO540iB1GrlgaKqA9lYFOSVN6dF4D6n8FmZWOTVnXoMpPqhBsOZK5SDuYmBsxLUQNeZH9%2BIsS9Y1hA1GzpcVomAsbR3qpyw%3D%3D"}],"group":"cf-nel","max_age":604800}
nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
server: cloudflare
cf-ray: 8de9da34eb46d36d-FRA
alt-svc: h3=":443"; ma=86400
server-timing: cfL4;desc="?proto=TCP&rtt=38557&sent=12&recv=10&lost=0&retrans=0&sent_bytes=4921&recv_bytes=938&delivery_rate=162162&cwnd=257&unsent_bytes=0&cid=c80adfd7785ddb94&ts=1997&x=0"
content-length: 544

{"data":[{"id":"80229455741718528","name":"pixeldesu","avatar":"https:\/\/pxscdn.com\/cache\/avatars\/default.jpg","username":"pixeldesu","is_owner":false,"bio":"<img src=\"test.png\" onerror=\"alert(1)\"\/>","post_count":1,"follower_count":0,"following_count":0,"url":"https:\/\/loops.video\/@pixeldesu","is_blocking":null,"created_at":"2024-11-04T20:45:05+00:00"}],"links":{"first":null,"last":null,"prev":null,"next":null},"meta":{"path":"https:\/\/loops.video\/api\/v0.5\/search\/users","per_page":10,"next_cursor":null,"prev_cursor":null}}
</pre>
</details>