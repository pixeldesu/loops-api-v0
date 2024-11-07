# `loops.video/api/v0/user/unblock/id/{{ id }}`

## Request

<details>
<summary>Raw request</summary>
<pre>
POST /api/v0/user/unblock/id/80229455741718528 HTTP/1.1
Authorization: Bearer [[ redacted ]]
Content-Type: application/json
Host: loops.video
</pre>
</details>

## Response

<details>
<summary>Raw response</summary>
<pre>
200 OK
date: Thu, 07 Nov 2024 02:33:54 GMT
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
report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v4?s=J4Qgk8ydLn2BFEuZ9enB5245c%2FGOg2HY1hNUXbkAxsXprvBw1EjagggjHEPA3Y5VGKZqJY5BS%2FX13szJ%2BdPJxCrs5biLTgyyBlOpxucjCv2jOq%2BvBPUBzbsM2xPCE3EzX5y9ZwQ4ys58cw%3D%3D"}],"group":"cf-nel","max_age":604800}
nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
server: cloudflare
cf-ray: 8de9ebd34dfb9748-FRA
alt-svc: h3=":443"; ma=86400
server-timing: cfL4;desc="?proto=TCP&rtt=22435&sent=5&recv=5&lost=0&retrans=0&sent_bytes=2810&recv_bytes=724&delivery_rate=140728&cwnd=252&unsent_bytes=0&cid=c8b3c52c6d11905b&ts=331&x=0"

{
  "is_blocking": false
}
</pre>
</details>