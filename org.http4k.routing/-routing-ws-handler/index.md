[http4k](../../index.md) / [org.http4k.routing](../index.md) / [RoutingWsHandler](./index.md)

# RoutingWsHandler

`interface RoutingWsHandler : `[`WsHandler`](../../org.http4k.websocket/-ws-handler.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/routing/routing.kt#L56)

### Functions

| Name | Summary |
|---|---|
| [withBasePath](with-base-path.md) | `abstract fun withBasePath(new: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`RoutingWsHandler`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [asServer](../../org.http4k.server/kotlin.-function1/as-server.md) | `fun `[`WsHandler`](../../org.http4k.websocket/-ws-handler.md)`.asServer(config: `[`WsServerConfig`](../../org.http4k.server/-ws-server-config/index.md)`): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md) |
| [testWsClient](../../org.http4k.testing/kotlin.-function1/test-ws-client.md) | `fun `[`WsHandler`](../../org.http4k.websocket/-ws-handler.md)`.testWsClient(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`TestWsClient`](../../org.http4k.testing/-test-ws-client/index.md)`?` |
