[http4k](../../index.md) / [org.http4k.server](../index.md) / [WsServerConfig](./index.md)

# WsServerConfig

`interface WsServerConfig : `[`ServerConfig`](../-server-config/index.md)

Standard interface for creating a configured WebServer which supports Websockets

### Functions

| Name | Summary |
|---|---|
| [toServer](to-server.md) | `open fun toServer(httpHandler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`Http4kServer`](../-http4k-server/index.md)<br>`abstract fun toServer(httpHandler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`? = null, wsHandler: `[`WsHandler`](../../org.http4k.websocket/-ws-handler.md)`? = null): `[`Http4kServer`](../-http4k-server/index.md) |
| [toWsServer](to-ws-server.md) | `open fun toWsServer(wsHandler: `[`WsHandler`](../../org.http4k.websocket/-ws-handler.md)`): `[`Http4kServer`](../-http4k-server/index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [Jetty](../-jetty/index.md) | `class Jetty : `[`WsServerConfig`](./index.md) |
| [Netty](../-netty/index.md) | `data class Netty : `[`WsServerConfig`](./index.md) |
