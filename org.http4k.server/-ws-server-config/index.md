[http4k](../../index.md) / [org.http4k.server](../index.md) / [WsServerConfig](./index.md)

# WsServerConfig

`interface WsServerConfig : `[`ServerConfig`](../-server-config/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/server/http4kServer.kt#L25)

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
