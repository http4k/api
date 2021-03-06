[http4k](../../index.md) / [org.http4k.server](../index.md) / [Undertow](./index.md)

# Undertow

`data class Undertow : `[`PolyServerConfig`](../-poly-server-config/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Undertow(port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 8000)`<br>`Undertow(port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 8000, enableHttp2: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [enableHttp2](enable-http2.md) | `val enableHttp2: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [port](port.md) | `val port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

### Functions

| Name | Summary |
|---|---|
| [toServer](to-server.md) | `fun toServer(http: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`?, ws: `[`WsHandler`](../../org.http4k.websocket/-ws-handler.md)`?, sse: `[`SseHandler`](../../org.http4k.sse/-sse-handler.md)`?): `[`Http4kServer`](../-http4k-server/index.md) |
