# `loops.video/api/v0/user/self/update-bio`

## Request

<details>
<summary>Raw request</summary>
<pre>
POST https://loops.video/api/v0/user/self/update-bio HTTP/2.0
accept: application/json
content-type: application/json
accept-encoding: gzip, deflate, br
content-length: 43
user-agent: Loops/4 CFNetwork/1568.200.51 Darwin/24.1.0
accept-language: en-US,en;q=0.9
authorization: Bearer [[ redacted ]]

{"bio":"senior frontend engineer | 28 y/o"}
</pre>
</details>

## Response

<details>
<summary>Raw response</summary>
<pre>
HTTP/2.0 200 
date: Mon, 04 Nov 2024 23:25:37 GMT
content-type: application/json
vary: Accept-Encoding
cache-control: no-cache, private
access-control-allow-origin: *
x-frame-options: SAMEORIGIN
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
cf-cache-status: DYNAMIC
report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v4?s=SVbVDZSsxaGgQQ0iYTJ4JwyjJOPMfRqAPgLku3N48CG10kPf7RUAXZdEj%2BfhIChyDsF7iq4C2f7eQxhjiWxV4E9ZfAreIDJ%2FLn9Re8UTccelVFnGTSc6CTozHa4sXHfvdx7633dIMekdPQ%3D%3D"}],"group":"cf-nel","max_age":604800}
nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
server: cloudflare
cf-ray: 8dd85d453a4af1a4-CDG
alt-svc: h3=":443"; ma=86400
server-timing: cfL4;desc="?proto=TCP&rtt=31930&sent=8520&recv=15021&lost=0&retrans=0&sent_bytes=65527&recv_bytes=20337572&delivery_rate=418689&cwnd=208&unsent_bytes=0&cid=104658e4ec02a8a3&ts=135720&x=0"
content-length: 345

{"id":"80229455741718528","name":"pixeldesu","avatar":"https:\/\/pxscdn.com\/cache\/avatars\/default.jpg","username":"pixeldesu","is_owner":true,"bio":"senior frontend engineer | 28 y\/o","post_count":1,"follower_count":0,"following_count":0,"url":"https:\/\/loops.video\/@pixeldesu","is_blocking":false,"created_at":"2024-11-04T20:45:05+00:00"}
</pre>
</details>