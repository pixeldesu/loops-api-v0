# `loops.video/api/v0/client/onboarding`

## Request

<details>
<summary>Raw request</summary>
<pre>
GET https://loops.video/api/v0/client/onboarding HTTP/2.0
user-agent: Loops/4 CFNetwork/1568.200.51 Darwin/24.1.0
accept: */*
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
content-length: 0
</pre>
</details>

## Response

<details>
<summary>Raw response</summary>
<pre>
HTTP/2.0 200 
date: Mon, 04 Nov 2024 23:18:27 GMT
content-type: application/json
vary: Accept-Encoding
cache-control: no-cache, private
access-control-allow-origin: *
x-frame-options: SAMEORIGIN
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
cf-cache-status: DYNAMIC
report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v4?s=ylJSTSWo0ujVcNQokB%2F2xZm6fSdyL%2BNRemldajT26VBJW1pjxd1PGWIrS4qyxjpd1LVEcJdbqtadnBdiLnhXcAwdgMvWkyOgN4i5UT3eLLqVGT5w1deuyEbjyN6wPKO6ophOrsvhM3xhQA%3D%3D"}],"group":"cf-nel","max_age":604800}
nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
server: cloudflare
cf-ray: 8dd852c5080125e9-NRT
alt-svc: h3=":443"; ma=86400
server-timing: cfL4;desc="?proto=TCP&rtt=267521&sent=29&recv=18&lost=0&retrans=0&sent_bytes=9014&recv_bytes=1015&delivery_rate=59795&cwnd=42&unsent_bytes=0&cid=b751fa3d146d6e73&ts=11098&x=0"
content-length: 72

{"can_signup":true,"can_weblogin":true,"can_reset":true,"min_build":"2"}
</pre>
<details>