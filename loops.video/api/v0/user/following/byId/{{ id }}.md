# `loops.video/api/v0/user/following/byId/{{ id }}`

## Request

<details>
<summary>Raw request</summary>
<pre>
GET https://loops.video/api/v0/user/following/byId/80229455741718528 HTTP/1.1
Authorization: Bearer [[ redacted ]]
Host: loops.video
</pre>
</details>

## Response

<details>
<summary>Raw response</summary>
<pre>
200 OK
date: Wed, 06 Nov 2024 02:11:13 GMT
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
report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v4?s=XQS2K2dxEkCtx%2BL%2Fm%2BHDRj76Tvo0L8%2FEdoBLTn5ZdZ0TsoOP%2B2NY%2FebeZ9jaeJa36Ww9d8s9YDLmauNESOeleWbq5QzPkjd6KbQ8bzPs7LYeJLGAM726gy2zcPcksCvUqUZdClLA%2BoX0%2FQ%3D%3D"}],"group":"cf-nel","max_age":604800}
nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
server: cloudflare
cf-ray: 8de18d3a4c36d2ee-FRA
alt-svc: h3=":443"; ma=86400
server-timing: cfL4;desc="?proto=TCP&rtt=20190&sent=5&recv=5&lost=0&retrans=0&sent_bytes=2810&recv_bytes=676&delivery_rate=186199&cwnd=250&unsent_bytes=0&cid=4b49f59ae1f4f856&ts=309&x=0"

{
  "data": [],
  "links": {
    "first": null,
    "last": null,
    "prev": null,
    "next": null
  },
  "meta": {
    "path": "https://loops.video/api/v0/user/following/byId/80229455741718528",
    "per_page": 10,
    "next_cursor": null,
    "prev_cursor": null
  }
}
</pre>
</details>