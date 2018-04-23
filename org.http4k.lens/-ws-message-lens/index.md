[http4k](../../index.md) / [org.http4k.lens](../index.md) / [WsMessageLens](./index.md)

# WsMessageLens

`open class WsMessageLens<out FINAL> : `[`LensExtractor`](../-lens-extractor/index.md)`<`[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`, `[`FINAL`](index.md#FINAL)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/wsMessageLens.kt#L51)

A WsMessageLens provides the extraction of an entity from a target WsMessage.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `WsMessageLens(getLens: (`[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`) -> `[`FINAL`](index.md#FINAL)`)`<br>A WsMessageLens provides the extraction of an entity from a target WsMessage. |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `open operator fun invoke(target: `[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`): `[`FINAL`](index.md#FINAL)<br>Lens operation to get the value from the target |

### Inherited Functions

| Name | Summary |
|---|---|
| [extract](../-lens-extractor/extract.md) | `open fun extract(target: `[`IN`](../-lens-extractor/index.md#IN)`): `[`OUT`](../-lens-extractor/index.md#OUT)<br>Lens operation to get the value from the target. Synonym for invoke(IN) |
| [get](../-lens-extractor/get.md) | `open operator fun <R : `[`IN`](../-lens-extractor/index.md#IN)`> get(target: `[`R`](../-lens-extractor/get.md#R)`): `[`OUT`](../-lens-extractor/index.md#OUT)<br>Lens operation to get the value from the target. Synonym for invoke(IN) |

### Inheritors

| Name | Summary |
|---|---|
| [BiDiWsMessageLens](../-bi-di-ws-message-lens/index.md) | `class BiDiWsMessageLens<FINAL> : `[`WsMessageLens`](./index.md)`<`[`FINAL`](../-bi-di-ws-message-lens/index.md#FINAL)`>`<br>A BiDiWsMessageLens provides the bi-directional extraction of an entity from a target body, or the insertion of an entity into a target WsMessage. |
