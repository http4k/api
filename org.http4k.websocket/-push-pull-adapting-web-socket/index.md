[http4k](../../index.md) / [org.http4k.websocket](../index.md) / [PushPullAdaptingWebSocket](./index.md)

# PushPullAdaptingWebSocket

`abstract class PushPullAdaptingWebSocket : `[`Websocket`](../-websocket/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `PushPullAdaptingWebSocket(upgradeRequest: `[`Request`](../../org.http4k.core/-request/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [upgradeRequest](upgrade-request.md) | `open val upgradeRequest: `[`Request`](../../org.http4k.core/-request/index.md) |

### Functions

| Name | Summary |
|---|---|
| [onClose](on-close.md) | `open fun onClose(fn: (`[`WsStatus`](../-ws-status/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onError](on-error.md) | `open fun onError(fn: (`[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onMessage](on-message.md) | `open fun onMessage(fn: (`[`WsMessage`](../-ws-message/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [triggerClose](trigger-close.md) | `fun triggerClose(status: `[`WsStatus`](../-ws-status/index.md)` = NORMAL): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [triggerError](trigger-error.md) | `fun triggerError(throwable: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [triggerMessage](trigger-message.md) | `fun triggerMessage(message: `[`WsMessage`](../-ws-message/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [AdaptingWebSocket](../../org.http4k.client.internal/-adapting-web-socket/index.md) | `class AdaptingWebSocket : `[`PushPullAdaptingWebSocket`](./index.md) |
