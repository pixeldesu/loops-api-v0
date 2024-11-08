# `loops.video/api/v0/video/delete/{{ id }}`

## Request

<details>
<summary>Raw request</summary>
<pre>
POST https://loops.video/api/v0/video/delete/80269331673518080 HTTP/2.0
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
date: Fri, 08 Nov 2024 23:02:36 GMT
content-type: application/json
vary: Accept-Encoding
cache-control: no-cache, private
access-control-allow-origin: *
x-frame-options: SAMEORIGIN
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
cf-cache-status: DYNAMIC
report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v4?s=hFerQDnlJ%2BLrG%2BpR8G8fx21ABIf8iCsLHuK8uOc4fMQYnG%2FELndBsnHOrhbKcg9bnk9Q1lsMEaNoS5stJlVB%2Fo5ocU%2Bu%2FtcHz0uWoD2iQ6q2jfyyzURTQ4mtKdfDJptnCEhr89lUz5oemQ%3D%3D"}],"group":"cf-nel","max_age":604800}
nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
server: cloudflare
cf-ray: 8df9310d7adad396-FRA
alt-svc: h3=":443"; ma=86400
server-timing: cfL4;desc="?proto=TCP&rtt=21322&sent=12&recv=10&lost=0&retrans=0&sent_bytes=4506&recv_bytes=886&delivery_rate=217937&cwnd=251&unsent_bytes=0&cid=c715cb3a91b6968f&ts=6058&x=0"
content-length: 53

{"status":200,"message":"Video successfully deleted"}
</pre>
</details>