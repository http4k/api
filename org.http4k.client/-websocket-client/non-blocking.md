[http4k](../../index.md) / [org.http4k.client](../index.md) / [WebsocketClient](index.md) / [nonBlocking](./non-blocking.md)

# nonBlocking

`fun nonBlocking(uri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, headers: `[`Headers`](../../org.http4k.core/-headers.md)` = emptyList(), timeout: `[`Duration`](https://docs.oracle.com/javase/9/docs/api/java/time/Duration.html)` = ZERO, onError: (`[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = {}, draft: Draft = Draft_6455(), onConnect: `[`WsConsumer`](../../org.http4k.websocket/-ws-consumer.md)` = {}): `[`Websocket`](../../org.http4k.websocket/-websocket/index.md)

Provides a client-side Websocket instance connected to a remote Websocket. The resultant object
can be have listeners attached to it. Optionally pass a WsConsumer which will be called onConnect

