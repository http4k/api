[http4k](../../index.md) / [org.http4k.server](../index.md) / [Jetty](./index.md)

# Jetty

`class Jetty : `[`WsServerConfig`](../-ws-server-config/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-server-jetty/src/main/kotlin/org/http4k/server/jetty.kt#L21)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Jetty(port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 8000)`<br>`Jetty(vararg inConnectors: `[`ConnectorBuilder`](../-connector-builder.md)`)`<br>`Jetty(server: Server)` |

### Functions

| Name | Summary |
|---|---|
| [toServer](to-server.md) | `fun toServer(httpHandler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`?, wsHandler: `[`WsHandler`](../../org.http4k.websocket/-ws-handler.md)`?): `[`Http4kServer`](../-http4k-server/index.md) |

### Inherited Functions

| Name | Summary |
|---|---|
| [toServer](../-ws-server-config/to-server.md) | `open fun toServer(httpHandler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`Http4kServer`](../-http4k-server/index.md) |
| [toWsServer](../-ws-server-config/to-ws-server.md) | `open fun toWsServer(wsHandler: `[`WsHandler`](../../org.http4k.websocket/-ws-handler.md)`): `[`Http4kServer`](../-http4k-server/index.md) |
