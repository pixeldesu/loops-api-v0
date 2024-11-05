# `loops.video/example`

## Request

<details>
<summary>Raw request</summary>
<pre>
POST https://loops.video/api/v0/unfollow/79155014135844864 HTTP/2.0
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
date: Mon, 04 Nov 2024 23:08:22 GMT
content-type: application/json
vary: Accept-Encoding
cache-control: no-cache, private
access-control-allow-origin: *
x-frame-options: SAMEORIGIN
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
cf-cache-status: DYNAMIC
report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v4?s=48txbDAB9FOFeLy3cQuAq7YK%2B4WcV%2FdXCpxqZhaZ12iHD2OJWS%2F3NZ50x5VuSwJ6%2F%2F%2B%2FX2hkqv6KQTqqByulcUemtds7B0AWOVMKaGXdfNu9HsMM1Q52uEk9q3DA5JIHFNVq3A2KZ7EVtw%3D%3D"}],"group":"cf-nel","max_age":604800}
nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
server: cloudflare
cf-ray: 8dd844016b84d276-FRA
alt-svc: h3=":443"; ma=86400
server-timing: cfL4;desc="?proto=TCP&rtt=21505&sent=15&recv=12&lost=0&retrans=0&sent_bytes=4984&recv_bytes=1020&delivery_rate=217995&cwnd=255&unsent_bytes=0&cid=eecba703c8e425bd&ts=5964&x=0"
content-length: 39

{"following":false,"followed_by":false}
</pre>
</details>