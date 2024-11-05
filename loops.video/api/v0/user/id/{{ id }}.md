# `loops.video/api/v0/user/id/{{ id }}`

## Request

<details>
<summary>Raw request</summary>
<pre>
GET https://loops.video/api/v0/user/id/79155014135844864?ext=1 HTTP/2.0
accept: */*
accept-encoding: gzip, deflate, br
user-agent: Loops/4 CFNetwork/1568.200.51 Darwin/24.1.0
accept-language: en-US,en;q=0.9
authorization: Bearer [[ redacted ]]
content-length: 0
</pre>
</details>

## Response

<details>
<summary>Raw response</summary>
<pre>
HTTP/2.0 200 
date: Mon, 04 Nov 2024 23:07:35 GMT
content-type: application/json
vary: Accept-Encoding
cache-control: no-cache, private
access-control-allow-origin: *
x-frame-options: SAMEORIGIN
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
cf-cache-status: DYNAMIC
report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v4?s=LJ%2FnxwZOuvCGWJMSqlf%2BRdNnhjLCB2icnENnLJ36BGL0E5l9agJcnvggp%2FIN8%2BkEXr9ne2dGOQihsfKhuXnmc5feOmk5HNURkOZ7KhndHK0ER35wsz9jgReYaNevGu6eMSWEDFdP34B8Dw%3D%3D"}],"group":"cf-nel","max_age":604800}
nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
server: cloudflare
cf-ray: 8dd842d92cd73a54-FRA
alt-svc: h3=":443"; ma=86400
server-timing: cfL4;desc="?proto=TCP&rtt=28100&sent=24&recv=14&lost=0&retrans=0&sent_bytes=7695&recv_bytes=977&delivery_rate=517897&cwnd=256&unsent_bytes=0&cid=157da146104b0c01&ts=66193&x=0"
content-length: 483

{"data":{"id":"79155014135844864","name":"beardedtechguy","avatar":"https:\/\/loopsusercontent.com\/avatars\/79155014135844864\/v0.jpg","username":"beardedtechguy","is_owner":false,"bio":"Your above average tech nerd.\n\nMain account: beardedtechguy@allthingstech.social","post_count":8,"follower_count":11,"following_count":7,"url":"https:\/\/loops.video\/@beardedtechguy","is_blocking":false,"created_at":"2024-11-01T21:35:38+00:00"},"meta":{"followed_by":false,"following":false}}
</pre>
</details>