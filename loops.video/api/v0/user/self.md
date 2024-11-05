# `loops.video/api/v0/user/self`

## Request

<details>
<summary>Raw request</summary>
<pre>
GET https://loops.video/api/v0/user/self HTTP/2.0
accept: */*
accept-encoding: gzip, deflate, br
user-agent: Loops/4 CFNetwork/1568.200.51 Darwin/24.1.0
accept-language: en-US,en;q=0.9
authorization: [[ redacted ]]
content-length: 0
</pre>
</details>

## Response

<details>
<summary>Raw response</summary>
<pre>
HTTP/2.0 200 
date: Mon, 04 Nov 2024 23:18:17 GMT
content-type: application/json
vary: Accept-Encoding
cache-control: no-cache, private
access-control-allow-origin: *
x-frame-options: SAMEORIGIN
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
cf-cache-status: DYNAMIC
report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v4?s=PBlGevvqVfLgyYysONR4Q3DwmLKnEflNy2eHuevJ6NTqXkW6PvYZ%2B2qvoQJV8%2BoGTGTyehK6wRPtPNx99nlkrUeccbRiaWgR%2Fig8Zh8FbTgb4pai%2B%2FNW7VMSEjTbyzU5rCbYjKB%2FYakeqw%3D%3D"}],"group":"cf-nel","max_age":604800}
nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
server: cloudflare
cf-ray: 8dd852843ce225e9-NRT
alt-svc: h3=":443"; ma=86400
server-timing: cfL4;desc="?proto=TCP&rtt=266268&sent=15&recv=7&lost=0&retrans=0&sent_bytes=6386&recv_bytes=868&delivery_rate=16020&cwnd=35&unsent_bytes=0&cid=b751fa3d146d6e73&ts=1164&x=0"
content-length: 313

{"id":"80229455741718528","name":"pixeldesu","avatar":"https:\/\/pxscdn.com\/cache\/avatars\/default.jpg","username":"pixeldesu","is_owner":true,"bio":null,"post_count":0,"follower_count":0,"following_count":0,"url":"https:\/\/loops.video\/@pixeldesu","is_blocking":false,"created_at":"2024-11-04T20:45:05+00:00"}
</pre>
</details>