[http4k](../index.md) / [org.http4k.server](./index.md)

## Package org.http4k.server

### Types

| Name | Summary |
|---|---|
| [ApacheServer](-apache-server/index.md) | `data class ApacheServer : `[`ServerConfig`](-server-config/index.md) |
| [Http4kChannelHandler](-http4k-channel-handler/index.md) | `class Http4kChannelHandler : SimpleChannelInboundHandler<FullHttpRequest>`<br>Exposed to allow for insertion into a customised Netty server instance |
| [Http4kRequestHandler](-http4k-request-handler/index.md) | `class Http4kRequestHandler : HttpRequestHandler`<br>Exposed to allow for insertion into a customised Apache WebServer instance |
| [Http4kServer](-http4k-server/index.md) | `interface Http4kServer : `[`Closeable`](http://docs.oracle.com/javase/6/docs/api/java/io/Closeable.html) |
| [HttpUndertowHandler](-http-undertow-handler/index.md) | `class HttpUndertowHandler : HttpHandler`<br>Exposed to allow for insertion into a customised Undertow server instance |
| [Jetty](-jetty/index.md) | `class Jetty : `[`WsServerConfig`](-ws-server-config/index.md) |
| [Netty](-netty/index.md) | `data class Netty : `[`ServerConfig`](-server-config/index.md) |
| [ServerConfig](-server-config/index.md) | `interface ServerConfig`<br>Standard interface for creating a configured WebServer |
| [SunHttp](-sun-http/index.md) | `data class SunHttp : `[`ServerConfig`](-server-config/index.md) |
| [Undertow](-undertow/index.md) | `data class Undertow : `[`ServerConfig`](-server-config/index.md) |
| [WsServerConfig](-ws-server-config/index.md) | `interface WsServerConfig : `[`ServerConfig`](-server-config/index.md)<br>Standard interface for creating a configured WebServer which supports Websockets |

### Type Aliases

| Name | Summary |
|---|---|
| [ConnectorBuilder](-connector-builder.md) | `typealias ConnectorBuilder = (Server) -> ServerConnector` |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.Function1](kotlin.-function1/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [asServer](as-server.md) | `fun `[`PolyHandler`](../org.http4k.websocket/-poly-handler/index.md)`.asServer(config: `[`WsServerConfig`](-ws-server-config/index.md)`): `[`Http4kServer`](-http4k-server/index.md) |
| [http](http.md) | `fun http(httpPort: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`ConnectorBuilder`](-connector-builder.md) |
| [http2](http2.md) | `fun http2(http2Port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, keystorePath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, keystorePassword: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ConnectorBuilder`](-connector-builder.md) |
