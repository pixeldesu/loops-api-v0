# `loops.video/api/v0/user/block/id/{{ id }}`

## Request

<details>
<summary>Raw request</summary>
<pre>
POST /api/v0/user/block/id/80229455741718528 HTTP/1.1
Authorization: Bearer [[ redacted ]]
Host: loops.video
</pre>
</details>

## Response

<details>
<summary>Raw response</summary>
<pre>
200 OK
date: Thu, 07 Nov 2024 02:33:58 GMT
content-type: application/json
transfer-encoding: chunked
connection: keep-alive
vary: Accept-Encoding
cache-control: no-cache, private
access-control-allow-origin: *
x-frame-options: SAMEORIGIN
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
cf-cache-status: DYNAMIC
report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v4?s=wUE4QLRRXyXq0UhsXwwbQhLIEFwYSKn2tlnvlmS6mS%2FykW9w0l8%2Fx3Asn1%2FvZB8f7JoQQnT%2Fh54o6NKRa7n6S%2FZRREW3NZlWpdgwVR80%2FUCKoT%2BnXjJD8E4Psc9kfeVLCBjExvGRoalM4w%3D%3D"}],"group":"cf-nel","max_age":604800}
nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
server: cloudflare
cf-ray: 8de9ebeadda302b7-CDG
alt-svc: h3=":443"; ma=86400
server-timing: cfL4;desc="?proto=TCP&rtt=38885&sent=5&recv=5&lost=0&retrans=0&sent_bytes=2810&recv_bytes=722&delivery_rate=59913&cwnd=168&unsent_bytes=0&cid=78d45ef8c742c148&ts=377&x=0"

{
  "is_blocking": true
}
</pre>
</details>