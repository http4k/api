[http4k](../../index.md) / [org.http4k.server](../index.md) / [kotlin.Function1](./index.md)

### Extensions for kotlin.Function1

| Name | Summary |
|---|---|
| [asServer](as-server.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asServer(fn: (`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`) -> `[`ServerConfig`](../-server-config/index.md)`, port: `[`Port`](../../org.http4k.cloudnative.env/-port/index.md)`): `[`Http4kServer`](../-http4k-server/index.md)<br>`fun `[`WsConsumer`](../../org.http4k.websocket/-ws-consumer.md)`.asServer(config: `[`PolyServerConfig`](../-poly-server-config/index.md)`): `[`Http4kServer`](../-http4k-server/index.md)<br>`fun `[`SseConsumer`](../../org.http4k.sse/-sse-consumer.md)`.asServer(config: `[`PolyServerConfig`](../-poly-server-config/index.md)`): `[`Http4kServer`](../-http4k-server/index.md)<br>`fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asServer(config: `[`ServerConfig`](../-server-config/index.md)`): `[`Http4kServer`](../-http4k-server/index.md)<br>`fun `[`SseHandler`](../../org.http4k.sse/-sse-handler.md)`.asServer(config: `[`PolyServerConfig`](../-poly-server-config/index.md)`): `[`Http4kServer`](../-http4k-server/index.md)<br>`fun `[`WsHandler`](../../org.http4k.websocket/-ws-handler.md)`.asServer(config: `[`PolyServerConfig`](../-poly-server-config/index.md)`): `[`Http4kServer`](../-http4k-server/index.md) |
| [toJettyHandler](to-jetty-handler.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.toJettyHandler(): ServletContextHandler` |
| [toJettyNegotiator](to-jetty-negotiator.md) | `fun `[`WsHandler`](../../org.http4k.websocket/-ws-handler.md)`.toJettyNegotiator(): AbstractNegotiator` |
