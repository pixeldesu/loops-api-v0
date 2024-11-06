# `loops.video/api/v0/notifications/self`

## Request

<details>
<summary>Raw request</summary>
<pre>
GET https://loops.video/api/v0/notifications/self HTTP/1.1
Authorization: Bearer [[ redacted ]]
Host: loops.video
</pre>
</details>

## Response

<details>
<summary>Raw response</summary>
<pre>
200 OK
date: Wed, 06 Nov 2024 02:34:07 GMT
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
report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v4?s=kyYGSQ3NZvhQAOMS6LXEdt4JfNqpuEplR5Fih1x3AdPZeYPsPQZRyDLn8igvLmEr0XPToJRxJDdKD1gUINMFtBHSVVTWeLKJsf2%2FrErWsZ5lFprYwHx0FnIp4wYCAeuD0CBHRm7z%2B4iYJw%3D%3D"}],"group":"cf-nel","max_age":604800}
nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
server: cloudflare
cf-ray: 8de1aec45a779760-FRA
alt-svc: h3=":443"; ma=86400
server-timing: cfL4;desc="?proto=TCP&rtt=21466&sent=5&recv=5&lost=0&retrans=0&sent_bytes=2809&recv_bytes=657&delivery_rate=205355&cwnd=249&unsent_bytes=0&cid=c39d7f30e42487ce&ts=327&x=0"

{
  "data": [
    {
      "id": "5638",
      "type": "video.like",
      "video_id": "80269331673518080",
      "video_thumbnail": "https://loopsusercontent.com/videos/80229455741718528/80269331673518080/jB2b015vpk4fGFp0BvgWSkFNlG5v8fDFNJBWU3GZ.jpg",
      "actor": {
        "id": "79162100718637056",
        "name": "Greg Clarke",
        "username": "greg",
        "avatar": "https://loopsusercontent.com/avatars/79162100718637056/v0.jpg"
      },
      "created_at": "2024-11-05T01:02:25.000000Z"
    },
    {
      "id": "5624",
      "type": "video.like",
      "video_id": "80269331673518080",
      "video_thumbnail": "https://loopsusercontent.com/videos/80229455741718528/80269331673518080/jB2b015vpk4fGFp0BvgWSkFNlG5v8fDFNJBWU3GZ.jpg",
      "actor": {
        "id": "80018688148901888",
        "name": "Bradley",
        "username": "Bradley",
        "avatar": "https://pxscdn.com/cache/avatars/default.jpg"
      },
      "created_at": "2024-11-05T00:59:05.000000Z"
    }
  ],
  "links": {
    "first": null,
    "last": null,
    "prev": null,
    "next": null
  },
  "meta": {
    "path": "https://loops.video/api/v0/notifications/self",
    "per_page": 20,
    "next_cursor": null,
    "prev_cursor": null
  }
}
</pre>
</details>