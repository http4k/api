[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiWsMessageLensSpec](./index.md)

# BiDiWsMessageLensSpec

`open class BiDiWsMessageLensSpec<OUT> : `[`WsMessageLensSpec`](../-ws-message-lens-spec/index.md)`<`[`OUT`](index.md#OUT)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/wsMessageLens.kt#L27)

Represents a bi-directional extraction of an entity from a target Body, or an insertion into a target WsMessage.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BiDiWsMessageLensSpec(get: `[`LensGet`](../-lens-get/index.md)`<`[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`, `[`OUT`](index.md#OUT)`>, set: `[`LensSet`](../-lens-set/index.md)`<`[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`, `[`OUT`](index.md#OUT)`>)`<br>Represents a bi-directional extraction of an entity from a target Body, or an insertion into a target WsMessage. |

### Functions

| Name | Summary |
|---|---|
| [map](map.md) | `fun <NEXT> map(nextIn: (`[`OUT`](index.md#OUT)`) -> `[`NEXT`](map.md#NEXT)`, nextOut: (`[`NEXT`](map.md#NEXT)`) -> `[`OUT`](index.md#OUT)`): `[`BiDiWsMessageLensSpec`](./index.md)`<`[`NEXT`](map.md#NEXT)`>`<br>Create another BiDiWsMessageLensSpec which applies the bi-directional transformations to the result. Any resultant Lens can be used to extract or insert the final type from/into a WsMessage. |
| [toLens](to-lens.md) | `open fun toLens(): `[`BiDiWsMessageLens`](../-bi-di-ws-message-lens/index.md)`<`[`OUT`](index.md#OUT)`>`<br>Create a lens for this Spec |

### Inherited Functions

| Name | Summary |
|---|---|
| [map](../-ws-message-lens-spec/map.md) | `fun <NEXT> map(nextIn: (`[`OUT`](../-ws-message-lens-spec/index.md#OUT)`) -> `[`NEXT`](../-ws-message-lens-spec/map.md#NEXT)`): `[`WsMessageLensSpec`](../-ws-message-lens-spec/index.md)`<`[`NEXT`](../-ws-message-lens-spec/map.md#NEXT)`>`<br>Create another WsMessageLensSpec which applies the uni-directional transformation to the result. Any resultant Lens can only be used to extract the final type from a WsMessage. |
