[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BodyLens](./index.md)

# BodyLens

`open class BodyLens<out FINAL> : `[`LensExtractor`](../-lens-extractor/index.md)`<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`, `[`FINAL`](index.md#FINAL)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/body.kt#L16)

A BodyLens provides the uni-directional extraction of an entity from a target body.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BodyLens(metas: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Meta`](../-meta/index.md)`>, contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`, getLens: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`FINAL`](index.md#FINAL)`)`<br>A BodyLens provides the uni-directional extraction of an entity from a target body. |

### Properties

| Name | Summary |
|---|---|
| [contentType](content-type.md) | `val contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md) |
| [metas](metas.md) | `val metas: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Meta`](../-meta/index.md)`>` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `open operator fun invoke(target: `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`): `[`FINAL`](index.md#FINAL)<br>Lens operation to get the value from the target |

### Inherited Functions

| Name | Summary |
|---|---|
| [extract](../-lens-extractor/extract.md) | `open fun extract(target: `[`IN`](../-lens-extractor/index.md#IN)`): `[`OUT`](../-lens-extractor/index.md#OUT)<br>Lens operation to get the value from the target. Synonym for invoke(IN) |
| [get](../-lens-extractor/get.md) | `open operator fun <R : `[`IN`](../-lens-extractor/index.md#IN)`> get(target: `[`R`](../-lens-extractor/get.md#R)`): `[`OUT`](../-lens-extractor/index.md#OUT)<br>Lens operation to get the value from the target. Synonym for invoke(IN) |

### Inheritors

| Name | Summary |
|---|---|
| [BiDiBodyLens](../-bi-di-body-lens/index.md) | `class BiDiBodyLens<FINAL> : `[`LensInjector`](../-lens-injector/index.md)`<`[`FINAL`](../-bi-di-body-lens/index.md#FINAL)`, `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>, `[`BodyLens`](./index.md)`<`[`FINAL`](../-bi-di-body-lens/index.md#FINAL)`>`<br>A BiDiBodyLens provides the bi-directional extraction of an entity from a target body, or the insertion of an entity into a target body. |
