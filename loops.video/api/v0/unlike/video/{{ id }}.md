# `loops.video/api/v0/unlike/video/{{ id }}`

## Request

<details>
<summary>Raw request</summary>
<pre>
POST https://loops.video/api/v0/unlike/video/80265224652984320 HTTP/2.0
accept: application/json
content-type: application/json
accept-encoding: gzip, deflate, br
content-length: 2
user-agent: Loops/4 CFNetwork/1568.200.51 Darwin/24.1.0
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
date: Mon, 04 Nov 2024 23:08:45 GMT
content-type: application/json
vary: Accept-Encoding
cache-control: no-cache, private
access-control-allow-origin: *
x-frame-options: SAMEORIGIN
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
cf-cache-status: DYNAMIC
report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v4?s=63ThHkJSToLA6fAuwjecBtfpPIithoMdF%2F74ZBK8jCSVXHs%2BQee7bWU8%2Fd9ajdDwcusZ7UYc8EejCK7nmVXcLVNRfqY4FjnKDEy7xlHqKtbO%2Bj4Ix8ubzi9Q5d%2FWjjd6Z3j5ymJaSKhWDg%3D%3D"}],"group":"cf-nel","max_age":604800}
nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
server: cloudflare
cf-ray: 8dd8448c5ff1d276-FRA
alt-svc: h3=":443"; ma=86400
server-timing: cfL4;desc="?proto=TCP&rtt=21833&sent=34&recv=22&lost=0&retrans=0&sent_bytes=9163&recv_bytes=1383&delivery_rate=217995&cwnd=255&unsent_bytes=0&cid=eecba703c8e425bd&ts=28190&x=0"
content-length: 892

{"id":"80265224652984320","account":{"id":"79163771913900032","name":"Nick D","avatar":"https:\/\/loopsusercontent.com\/avatars\/79163771913900032\/v0.jpg","username":"nickde","is_owner":false,"bio":"Taking videos around Boston. Formerly California.","post_count":4,"follower_count":9,"following_count":7,"url":"https:\/\/loops.video\/@nickde","is_blocking":false,"created_at":"2024-11-01T22:10:27+00:00"},"caption":"Cambridge Cat!","url":"https:\/\/loops.video\/v\/5qZOb5IsdM_5vcAI3l3jM","is_owner":false,"is_sensitive":false,"media":{"width":1280,"height":720,"thumbnail":"https:\/\/loopsusercontent.com\/videos\/79163771913900032\/80265224652984320\/mfVxtn9ivMxAgy6652HttaJx58ODlbag707GVbrW.jpg","src_url":"https:\/\/loopsusercontent.com\/videos\/79163771913900032\/80265224652984320\/mfVxtn9ivMxAgy6652HttaJx58ODlbag707GVbrW.720p.mp4"},"likes":1,"shares":0,"comments":0,"has_liked":false}
</pre>
</details>