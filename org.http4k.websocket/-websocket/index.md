[http4k](../../index.md) / [org.http4k.websocket](../index.md) / [Websocket](./index.md)

# Websocket

`interface Websocket` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/websocket/websocket.kt#L13)

Represents a connected Websocket instance, and can be passed around an application. This is configured
to react to events on the WS event stream by attaching listeners.

### Properties

| Name | Summary |
|---|---|
| [upgradeRequest](upgrade-request.md) | `abstract val upgradeRequest: `[`Request`](../../org.http4k.core/-request/index.md) |

### Functions

| Name | Summary |
|---|---|
| [close](close.md) | `abstract fun close(status: `[`WsStatus`](../-ws-status/index.md)` = NORMAL): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onClose](on-close.md) | `abstract fun onClose(fn: (`[`WsStatus`](../-ws-status/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onError](on-error.md) | `abstract fun onError(fn: (`[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onMessage](on-message.md) | `abstract fun onMessage(fn: (`[`WsMessage`](../-ws-message/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [send](send.md) | `abstract fun send(message: `[`WsMessage`](../-ws-message/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [PushPullAdaptingWebSocket](../-push-pull-adapting-web-socket/index.md) | `abstract class PushPullAdaptingWebSocket : `[`Websocket`](./index.md) |
