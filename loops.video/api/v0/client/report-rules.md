# `loops.video/api/v0/client/report-rules`

## Request

<details>
<summary>Raw request</summary>
<pre>
GET https://loops.video/api/v0/client/report-rules HTTP/1.1
Host: loops.video
</pre>
</details>

## Response

<details>
<summary>Raw response</summary>
<pre>
200 OK
date: Wed, 06 Nov 2024 02:46:12 GMT
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
report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v4?s=HFuXK28bv7zFAT71I9KA%2FRHWYYs%2BSKYtsVLDl395c3m2D73pBfj5ES2a3ZLtrL4zGmC86CG9Tb0MAn%2BpDaLdjCeQshgTkolIvcgOXgGkXmLat0Ite2LmQzlNE%2FpMUVXeP4EL79Nv500H1g%3D%3D"}],"group":"cf-nel","max_age":604800}
nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
server: cloudflare
cf-ray: 8de1c0751ce003fb-CDG
alt-svc: h3=":443"; ma=86400
server-timing: cfL4;desc="?proto=TCP&rtt=44441&sent=5&recv=5&lost=0&retrans=0&sent_bytes=2810&recv_bytes=581&delivery_rate=74080&cwnd=33&unsent_bytes=0&cid=95cfbfcd4e21a329&ts=356&x=0"

[
  {
    "key": "1010",
    "message": "Inappropriate and irrelevant search"
  },
  {
    "key": "1011",
    "message": "Violence, abuse, and criminal exploitation"
  },
  {
    "key": "1012",
    "message": "Hate and harassment"
  },
  {
    "key": "1013",
    "message": "Suicide and self-harm"
  },
  {
    "key": "1014",
    "message": "Disordered eating and unhealthy body image"
  },
  {
    "key": "1015",
    "message": "Dangerous activities and challenges"
  },
  {
    "key": "1016",
    "message": "Nudity and sexual content"
  },
  {
    "key": "1017",
    "message": "Shocking and graphic content"
  },
  {
    "key": "1018",
    "message": "Misinformation"
  },
  {
    "key": "1019",
    "message": "Deceptive behavior and spam"
  },
  {
    "key": "1020",
    "message": "Regulated goods and activities"
  },
  {
    "key": "1021",
    "message": "Frauds and scams"
  },
  {
    "key": "1022",
    "message": "Sharing personal information"
  },
  {
    "key": "1023",
    "message": "Report illegal content"
  },
  {
    "key": "1024",
    "message": "Counterfeits and intellectual property"
  },
  {
    "key": "1025",
    "message": "Undisclosed branded content"
  },
  {
    "key": "1026",
    "message": "Other"
  }
]
</pre>
</details>