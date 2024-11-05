# `loops.video/api/v0/comments/id/{{ id }}`

## Request

<details>
<summary>Raw request</summary>
<pre>
GET https://loops.video/api/v0/comments/id/80263145645543424 HTTP/2.0
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
date: Mon, 04 Nov 2024 23:09:32 GMT
content-type: application/json
vary: Accept-Encoding
cache-control: no-cache, private
access-control-allow-origin: *
x-frame-options: SAMEORIGIN
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
cf-cache-status: DYNAMIC
report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v4?s=FIjXfqq1xB94tEWtXCc%2BbtX7IyfVNG36V8zkTWFuWiurl6M4kdQ8uMVHpBXF%2BDRWLJM0AkZQp9lAljMp0vzAG%2FuPmYiOfeoVklzfITLEthqYZMq%2BPA7%2FKEyGn4SHsx0gagjpyL9C5t0eLQ%3D%3D"}],"group":"cf-nel","max_age":604800}
nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
server: cloudflare
cf-ray: 8dd845b41a47d276-FRA
alt-svc: h3=":443"; ma=86400
server-timing: cfL4;desc="?proto=TCP&rtt=21593&sent=63&recv=39&lost=0&retrans=0&sent_bytes=16154&recv_bytes=2102&delivery_rate=281456&cwnd=255&unsent_bytes=0&cid=eecba703c8e425bd&ts=75444&x=0"
content-length: 842

{"data":[{"id":"80264487726354432","account":{"id":"80229406907437056","name":"catsalad","avatar":"https:\/\/loopsusercontent.com\/avatars\/80229406907437056\/v0.jpg","username":"catsalad","is_owner":false,"bio":"CatSalad\ud83d\udc08\ud83e\udd57 (the many) :3\nhttps:\/\/infosec.exchange\/@catsalad","post_count":1,"follower_count":0,"following_count":0,"url":"https:\/\/loops.video\/@catsalad","is_blocking":false,"created_at":"2024-11-04T20:44:54+00:00"},"caption":"Marvelous Pumpkin!","likes":0,"replies":0,"liked":false,"url":"https:\/\/loops.video\/c\/5vbZgjJi0O\/5vRzhO2vcO_5vbxJfg1K4","created_at":"2024-11-04T23:04:18+00:00","children":[]}],"links":{"first":null,"last":null,"prev":null,"next":null},"meta":{"path":"https:\/\/loops.video\/api\/v0\/comments\/id\/80263145645543424","per_page":10,"next_cursor":null,"prev_cursor":null}}
</pre>
</details>