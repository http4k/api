[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiWsMessageLens](./index.md)

# BiDiWsMessageLens

`class BiDiWsMessageLens<FINAL> : `[`WsMessageLens`](../-ws-message-lens/index.md)`<`[`FINAL`](index.md#FINAL)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/wsMessageLens.kt#L65)

A BiDiWsMessageLens provides the bi-directional extraction of an entity from a target body, or the insertion of an entity
into a target WsMessage.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BiDiWsMessageLens(get: (`[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`) -> `[`FINAL`](index.md#FINAL)`, setLens: (`[`FINAL`](index.md#FINAL)`, `[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`) -> `[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`)`<br>A BiDiWsMessageLens provides the bi-directional extraction of an entity from a target body, or the insertion of an entity into a target WsMessage. |

### Functions

| Name | Summary |
|---|---|
| [create](create.md) | `fun create(value: `[`FINAL`](index.md#FINAL)`): `[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md) |
| [invoke](invoke.md) | `operator fun invoke(target: `[`FINAL`](index.md#FINAL)`): `[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md) |

### Inherited Functions

| Name | Summary |
|---|---|
| [invoke](../-ws-message-lens/invoke.md) | `open operator fun invoke(target: `[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`): `[`FINAL`](../-ws-message-lens/index.md#FINAL)<br>Lens operation to get the value from the target |
