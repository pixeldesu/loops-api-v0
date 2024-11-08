# `loops.video/api/v0/user/self/delete-avatar`

## Request

<details>
<summary>Raw request</summary>
<pre>
POST https://loops.video/api/v0/user/self/delete-avatar HTTP/2.0
accept: application/json
content-type: application/json
accept-encoding: gzip, deflate, br
content-length: 2
user-agent: Loops/7 CFNetwork/1568.200.51 Darwin/24.1.0
accept-language: en-US,en;q=0.9
authorization: Bearer [[ redacted ]]

{}
</pre>
</details>

## Response

<details>
<summary>Raw response</summary>
<pre>
HTTP/2.0 200 
date: Fri, 08 Nov 2024 22:55:48 GMT
content-type: application/json
vary: Accept-Encoding
cache-control: no-cache, private
access-control-allow-origin: *
x-frame-options: SAMEORIGIN
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
cf-cache-status: DYNAMIC
report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v4?s=mKJPuCsO7jR9IauqdYAg8BkgM%2FGqaGr8%2FlpHYbJGrRT3Wg6AWlaiP20wL%2FecpZ%2Bp8QlMXrI7%2FZsJpHlSmTaOVbe%2BtnD4NXTTF0n5fZitKENMtSjiYsrHrKloXIwpmOYK8NgFD7LdzPfqJA%3D%3D"}],"group":"cf-nel","max_age":604800}
nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
server: cloudflare
cf-ray: 8df927167a209f52-FRA
alt-svc: h3=":443"; ma=86400
server-timing: cfL4;desc="?proto=TCP&rtt=21273&sent=78&recv=77&lost=0&retrans=0&sent_bytes=14067&recv_bytes=60841&delivery_rate=232306&cwnd=256&unsent_bytes=0&cid=aad1ebb5051eb5cb&ts=33270&x=0"
content-length: 356

{"id":"80229455741718528","name":"pixeldesu","avatar":"https:\/\/pxscdn.com\/cache\/avatars\/default.jpg","username":"pixeldesu","is_owner":false,"bio":"<img src=\"test.png\" onerror=\"alert(1)\"\/>","post_count":1,"follower_count":0,"following_count":0,"url":"https:\/\/loops.video\/@pixeldesu","is_blocking":null,"created_at":"2024-11-04T20:45:05+00:00"}
</pre>
</details>