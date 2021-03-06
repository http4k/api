[http4k](../../index.md) / [org.http4k.websocket](../index.md) / [PolyHandler](./index.md)

# PolyHandler

`class PolyHandler`

A PolyHandler represents the combined routing logic of an Http handler and a Websocket handler.
ws:// and http:// protocol calls are passed relevantly.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | A PolyHandler represents the combined routing logic of an Http handler and a Websocket handler. ws:// and http:// protocol calls are passed relevantly.`PolyHandler(http: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, ws: `[`WsHandler`](../-ws-handler.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [http](http.md) | `val http: `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [asServer](../../org.http4k.server/as-server.md) | `fun `[`PolyHandler`](./index.md)`.asServer(config: `[`WsServerConfig`](../../org.http4k.server/-ws-server-config/index.md)`): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md) |
| [testWsClient](../../org.http4k.testing/test-ws-client.md) | `fun `[`PolyHandler`](./index.md)`.testWsClient(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`TestWsClient`](../../org.http4k.testing/-test-ws-client/index.md)`?` |
