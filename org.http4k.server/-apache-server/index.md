[http4k](../../index.md) / [org.http4k.server](../index.md) / [ApacheServer](./index.md)

# ApacheServer

`data class ApacheServer : `[`ServerConfig`](../-server-config/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-server-apache/src/main/kotlin/org/http4k/server/ApacheServer.kt#L57)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ApacheServer(port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 8000)` |

### Properties

| Name | Summary |
|---|---|
| [port](port.md) | `val port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

### Functions

| Name | Summary |
|---|---|
| [toServer](to-server.md) | `fun toServer(httpHandler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`Http4kServer`](../-http4k-server/index.md) |
