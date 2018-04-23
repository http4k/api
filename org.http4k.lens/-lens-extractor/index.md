[http4k](../../index.md) / [org.http4k.lens](../index.md) / [LensExtractor](./index.md)

# LensExtractor

`interface LensExtractor<in IN, out OUT> : (`[`IN`](index.md#IN)`) -> `[`OUT`](index.md#OUT) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/LensExtractor.kt#L3)

### Functions

| Name | Summary |
|---|---|
| [extract](extract.md) | `open fun extract(target: `[`IN`](index.md#IN)`): `[`OUT`](index.md#OUT)<br>Lens operation to get the value from the target. Synonym for invoke(IN) |
| [get](get.md) | `open operator fun <R : `[`IN`](index.md#IN)`> get(target: `[`R`](get.md#R)`): `[`OUT`](index.md#OUT)<br>Lens operation to get the value from the target. Synonym for invoke(IN) |
| [invoke](invoke.md) | `abstract operator fun invoke(target: `[`IN`](index.md#IN)`): `[`OUT`](index.md#OUT)<br>Lens operation to get the value from the target |

### Inheritors

| Name | Summary |
|---|---|
| [BodyLens](../-body-lens/index.md) | `open class BodyLens<out FINAL> : `[`LensExtractor`](./index.md)`<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`, `[`FINAL`](../-body-lens/index.md#FINAL)`>`<br>A BodyLens provides the uni-directional extraction of an entity from a target body. |
| [Companion](../../org.http4k.core/-request-context/-companion/index.md) | `companion object Companion : `[`LensExtractor`](./index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`UUID`](http://docs.oracle.com/javase/6/docs/api/java/util/UUID.html)`>, `[`LensInjector`](../-lens-injector/index.md)`<`[`UUID`](http://docs.oracle.com/javase/6/docs/api/java/util/UUID.html)`, `[`Request`](../../org.http4k.core/-request/index.md)`>` |
| [Lens](../-lens/index.md) | `open class Lens<in IN, out FINAL> : `[`LensExtractor`](./index.md)`<`[`IN`](../-lens/index.md#IN)`, `[`FINAL`](../-lens/index.md#FINAL)`>, `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Meta`](../-meta/index.md)`>`<br>A Lens provides the uni-directional extraction of an entity from a target. |
| [Store](../../org.http4k.core/-store/index.md) | `interface Store<OUT> : `[`LensInjector`](../-lens-injector/index.md)`<`[`OUT`](../../org.http4k.core/-store/index.md#OUT)`, `[`Request`](../../org.http4k.core/-request/index.md)`>, `[`LensExtractor`](./index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`OUT`](../../org.http4k.core/-store/index.md#OUT)`>` |
| [WsMessageLens](../-ws-message-lens/index.md) | `open class WsMessageLens<out FINAL> : `[`LensExtractor`](./index.md)`<`[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`, `[`FINAL`](../-ws-message-lens/index.md#FINAL)`>`<br>A WsMessageLens provides the extraction of an entity from a target WsMessage. |
