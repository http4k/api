[http4k](../../index.md) / [org.http4k.testing](../index.md) / [TestWsClient](./index.md)

# TestWsClient

`class TestWsClient : `[`WsClient`](../-ws-client/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/testing/wsClient.kt#L25)

A class that is used for *offline* testing of a routed Websocket, without starting up a Server. Calls
are routed synchronously to the receiving Websocket, and error are propagated to the caller.

### Functions

| Name | Summary |
|---|---|
| [close](close.md) | `fun close(status: `[`WsStatus`](../../org.http4k.websocket/-ws-status/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [error](error.md) | `fun error(throwable: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Push an error to the Websocket |
| [received](received.md) | `fun received(): `[`Sequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)`<`[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`>` |
| [send](send.md) | `fun send(message: `[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
