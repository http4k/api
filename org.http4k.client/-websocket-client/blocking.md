[http4k](../../index.md) / [org.http4k.client](../index.md) / [WebsocketClient](index.md) / [blocking](./blocking.md)

# blocking

`fun blocking(uri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, headers: `[`Headers`](../../org.http4k.core/-headers.md)` = emptyList(), timeout: `[`Duration`](https://docs.oracle.com/javase/9/docs/api/java/time/Duration.html)` = ZERO, autoReconnection: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false, draft: Draft = Draft_6455()): `[`WsClient`](../../org.http4k.websocket/-ws-client/index.md)

Provides a client-side WsClient connected to a remote Websocket. This is a blocking API, so accessing the sequence of "received"
messages will block on iteration until all messages are received (or the socket it closed). This call will also
block while connection happens.

