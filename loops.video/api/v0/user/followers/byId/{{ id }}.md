# `loops.video/api/v0/user/followers/byId/{{ id }}`

## Request

<details>
<summary>Raw request</summary>
<pre>
GET https://loops.video/api/v0/user/followers/byId/80229455741718528 HTTP/1.1
Authorization: Bearer [[ redacted ]]
Host: loops.video
</pre>
</details>

## Response

<details>
<summary>Raw response</summary>
<pre>
200 OK
date: Wed, 06 Nov 2024 02:14:23 GMT
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
report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v4?s=bimopC3N618he6TdeJlYosu%2F1N%2FL%2FfeyNyK3geweTCJkRwkPhI%2F0XAWTqsexRxcNlVKfj%2FHILBJco%2BJ6FXcwotKZzdzP1nWcot8fVXi05%2FPAZtF36%2Bw2gcZwerhd3CT2De3otsK7Yqu7aw%3D%3D"}],"group":"cf-nel","max_age":604800}
nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
server: cloudflare
cf-ray: 8de191da7f06dcd1-FRA
alt-svc: h3=":443"; ma=86400
server-timing: cfL4;desc="?proto=TCP&rtt=34911&sent=5&recv=5&lost=0&retrans=0&sent_bytes=2809&recv_bytes=676&delivery_rate=182077&cwnd=230&unsent_bytes=0&cid=1ec42d40fe170023&ts=320&x=0"

{
  "data": [],
  "links": {
    "first": null,
    "last": null,
    "prev": null,
    "next": null
  },
  "meta": {
    "path": "https://loops.video/api/v0/user/followers/byId/80229455741718528",
    "per_page": 10,
    "next_cursor": null,
    "prev_cursor": null
  }
}
</pre>
</details>