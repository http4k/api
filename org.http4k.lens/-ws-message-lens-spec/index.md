[http4k](../../index.md) / [org.http4k.lens](../index.md) / [WsMessageLensSpec](./index.md)

# WsMessageLensSpec

`open class WsMessageLensSpec<out OUT>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/wsMessageLens.kt#L12)

Represents a extraction of an entity from a target WsMessage.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `WsMessageLensSpec(get: `[`LensGet`](../-lens-get/index.md)`<`[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`, `[`OUT`](index.md#OUT)`>)`<br>Represents a extraction of an entity from a target WsMessage. |

### Functions

| Name | Summary |
|---|---|
| [map](map.md) | `fun <NEXT> map(nextIn: (`[`OUT`](index.md#OUT)`) -> `[`NEXT`](map.md#NEXT)`): `[`WsMessageLensSpec`](./index.md)`<`[`NEXT`](map.md#NEXT)`>`<br>Create another WsMessageLensSpec which applies the uni-directional transformation to the result. Any resultant Lens can only be used to extract the final type from a WsMessage. |
| [toLens](to-lens.md) | `open fun toLens(): `[`WsMessageLens`](../-ws-message-lens/index.md)`<`[`OUT`](index.md#OUT)`>`<br>Create a lens for this Spec |

### Inheritors

| Name | Summary |
|---|---|
| [BiDiWsMessageLensSpec](../-bi-di-ws-message-lens-spec/index.md) | `open class BiDiWsMessageLensSpec<OUT> : `[`WsMessageLensSpec`](./index.md)`<`[`OUT`](../-bi-di-ws-message-lens-spec/index.md#OUT)`>`<br>Represents a bi-directional extraction of an entity from a target Body, or an insertion into a target WsMessage. |
