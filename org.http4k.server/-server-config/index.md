[http4k](../../index.md) / [org.http4k.server](../index.md) / [ServerConfig](./index.md)

# ServerConfig

`interface ServerConfig` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/server/http4kServer.kt#L18)

Standard interface for creating a configured WebServer

### Functions

| Name | Summary |
|---|---|
| [toServer](to-server.md) | `abstract fun toServer(httpHandler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`Http4kServer`](../-http4k-server/index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [ApacheServer](../-apache-server/index.md) | `data class ApacheServer : `[`ServerConfig`](./index.md) |
| [Netty](../-netty/index.md) | `data class Netty : `[`ServerConfig`](./index.md) |
| [SunHttp](../-sun-http/index.md) | `data class SunHttp : `[`ServerConfig`](./index.md) |
| [Undertow](../-undertow/index.md) | `data class Undertow : `[`ServerConfig`](./index.md) |
| [WsServerConfig](../-ws-server-config/index.md) | `interface WsServerConfig : `[`ServerConfig`](./index.md)<br>Standard interface for creating a configured WebServer which supports Websockets |
