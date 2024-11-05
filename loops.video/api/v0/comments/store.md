# `loops.video/api/v0/comments/store`

## Request

<details>
<summary>Raw request</summary>
<pre>
POST https://loops.video/api/v0/comments/store HTTP/2.0
accept: application/json
content-type: application/json
accept-encoding: gzip, deflate, br
content-length: 53
user-agent: Loops/4 CFNetwork/1568.200.51 Darwin/24.1.0
accept-language: en-US,en;q=0.9
authorization: Bearer [[ redacted ]]

{"video_id":"80263145645543424","comment":"Pumpkin!"}
</pre>
</details>

## Response

<details>
<summary>Raw response</summary>
<pre>
HTTP/2.0 201 
date: Mon, 04 Nov 2024 23:14:47 GMT
content-type: application/json
cache-control: no-cache, private
access-control-allow-origin: *
x-frame-options: SAMEORIGIN
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
cf-cache-status: DYNAMIC
report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v4?s=rtTej%2FRlwbkFG4UOSGPNm7%2FNf3xdiA7DXs%2FkT9aBTiuYcUnFtiwZBDmMIe5hsAPSGbwtjv1XSKF50hMjQRqucJFv4tnFmkL4lGuNkTTByqVTbf446rHOLfqiCyq93A%2F0yv0mXjQRaNdzOg%3D%3D"}],"group":"cf-nel","max_age":604800}
nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
server: cloudflare
cf-ray: 8dd84d62cee41992-FRA
alt-svc: h3=":443"; ma=86400
server-timing: cfL4;desc="?proto=TCP&rtt=20966&sent=7&recv=7&lost=0&retrans=0&sent_bytes=3411&recv_bytes=858&delivery_rate=187173&cwnd=253&unsent_bytes=0&cid=866338cc1cdafa50&ts=349&x=0"
content-length: 530

{"id":"80267125851295744","account":{"id":"80229455741718528","name":"pixeldesu","avatar":"https:\/\/pxscdn.com\/cache\/avatars\/default.jpg","username":"pixeldesu","is_owner":true,"bio":null,"post_count":0,"follower_count":0,"following_count":0,"url":"https:\/\/loops.video\/@pixeldesu","is_blocking":false,"created_at":"2024-11-04T20:45:05+00:00"},"caption":"Pumpkin!","likes":0,"replies":0,"liked":false,"url":"https:\/\/loops.video\/c\/5vbZgjJi0O\/5vS0Ygwb3Y_5vchlIpQHI","created_at":"2024-11-04T23:14:47+00:00","children":[]}
</pre>
</details>