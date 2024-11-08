# `loops.video/api/v0/user/self/update-avatar`

## Request

<details>
<summary>Raw request</summary>
<pre>
POST https://loops.video/api/v0/user/self/update-avatar HTTP/2.0
accept: application/json
content-type: multipart/form-data; boundary=Kc2pVghn7-eIjuPw-yGhJTRV3JGaCGsTxXSZX.hfQ507lDm007yb_ZEpLHGo-jmSbZjvvF
accept-encoding: gzip, deflate, br
content-length: 59251
user-agent: Loops/7 CFNetwork/1568.200.51 Darwin/24.1.0
accept-language: en-US,en;q=0.9
authorization: Bearer [[ redacted ]]

--

content-disposition: form-data; name="avatar"; filename="7B434023-5802-451D-B2D6-496358978283.png"; filename*=utf-8''7B434023-5802-451D-B2D6-496358978283.png
content-type: image/png


[[ raw image data ]]
--
</pre>
</details>

## Response

<details>
<summary>Raw response</summary>
<pre>
HTTP/2.0 200 
date: Fri, 08 Nov 2024 22:55:30 GMT
content-type: application/json
vary: Accept-Encoding
cache-control: no-cache, private
access-control-allow-origin: *
x-frame-options: SAMEORIGIN
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
cf-cache-status: DYNAMIC
report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v4?s=RZnQNTxbqsSnM5Doj80pM%2FNhm%2F1M2GLD7IWy7wlVwkA4jCuk7GuNcJYA2nRc6dmGQlg5fwDrNRer5sIkVnZjfG3WVCWHT8VqD4gVlcf07KLIdl21jpB%2FsWUtXLSUPJd5T8nLuXoi5v5P%2Fg%3D%3D"}],"group":"cf-nel","max_age":604800}
nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
server: cloudflare
cf-ray: 8df926a4da739f52-FRA
alt-svc: h3=":443"; ma=86400
server-timing: cfL4;desc="?proto=TCP&rtt=22475&sent=57&recv=64&lost=0&retrans=0&sent_bytes=9161&recv_bytes=60498&delivery_rate=229445&cwnd=4&unsent_bytes=0&cid=aad1ebb5051eb5cb&ts=15093&x=0"
content-length: 373

{"id":"80229455741718528","name":"pixeldesu","avatar":"https:\/\/loopsusercontent.com\/avatars\/80229455741718528\/v0.jpg","username":"pixeldesu","is_owner":false,"bio":"<img src=\"test.png\" onerror=\"alert(1)\"\/>","post_count":1,"follower_count":0,"following_count":0,"url":"https:\/\/loops.video\/@pixeldesu","is_blocking":null,"created_at":"2024-11-04T20:45:05+00:00"}
</pre>
</details>