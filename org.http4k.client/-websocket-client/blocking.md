[http4k](../../index.md) / [org.http4k.client](../index.md) / [WebsocketClient](index.md) / [blocking](./blocking.md)

# blocking

`fun blocking(uri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, headers: `[`Headers`](../../org.http4k.core/-headers.md)` = emptyList(), timeout: Duration = ZERO): `[`WsClient`](../../org.http4k.testing/-ws-client/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-client-websocket/src/main/kotlin/org/http4k/client/WebsocketClient.kt#L67)

Provides a client-side WsClient connected to a remote Websocket. This is a blocking API, so accessing the sequence of "received"
messages will block on iteration until all messages are received (or the socket it closed). This call will also
block while connection happens.

