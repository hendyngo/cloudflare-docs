---
pcx_content_type: concept
title: Protocols
meta:
  description: Supported protocols on the Workers platform.
---

# Protocols

Cloudflare Workers support the following protocols and interfaces:

| Protocol       | Inbound | Outbound |
|---|---|---|
| **HTTP / HTTPS**  | Handle incoming HTTP requests using the [`fetch()` handler](/workers/runtime-apis/handlers/fetch/)  | Make HTTP subrequests using the [`fetch()` API](/workers/runtime-apis/fetch/)  |
| **Direct TCP sockets**  | Support for handling inbound TCP connections is [coming soon](https://blog.cloudflare.com/workers-tcp-socket-api-connect-databases/)  | Create outbound TCP connections using the [`connect()` API](/workers/runtime-apis/tcp-sockets/) |
| **WebSockets**  | Accept incoming WebSocket connections using the [`WebSocket` API](/workers/runtime-apis/websockets/), or with [MQTT over WebSockets (Pub/Sub)](/pub-sub/learning/websockets-browsers/)  | [MQTT over WebSockets (Pub/Sub)](/pub-sub/learning/websockets-browsers/) |
| **MQTT** | Handle incoming messages to an MQTT broker with [Pub Sub](/pub-sub/learning/integrate-workers/) | Support for publishing MQTT messages to an MQTT topic is [coming soon](/pub-sub/learning/integrate-workers/) |
| **HTTP/3 (QUIC)** | Accept inbound requests over [HTTP/3](https://www.cloudflare.com/learning/performance/what-is-http3/) by enabling it on your [zone](/fundamentals/setup/accounts-and-zones/#zones) in **Speed** > **Optimization** > **Protocol Optimization** area of the [Cloudflare dashboard](https://dash.cloudflare.com/). | |
| **SMTP** | Use [Email Workers](/email-routing/email-workers/) to process and forward email, without having to manage TCP connections to SMTP email servers | [Email Workers](/email-routing/email-workers/) |