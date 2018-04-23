[http4k](../../index.md) / [org.http4k.client](../index.md) / [WebsocketClient](index.md) / [nonBlocking](./non-blocking.md)

# nonBlocking

`fun nonBlocking(uri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, headers: `[`Headers`](../../org.http4k.core/-headers.md)` = emptyList(), timeout: Duration = ZERO, onConnect: `[`WsConsumer`](../../org.http4k.websocket/-ws-consumer.md)` = {}): `[`Websocket`](../../org.http4k.websocket/-websocket/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-client-websocket/src/main/kotlin/org/http4k/client/WebsocketClient.kt#L32)

Provides a client-side Websocket instance connected to a remote Websocket. The resultant object
can be have listeners attached to it. Optionally pass a WsConsumer which will be called onConnect

