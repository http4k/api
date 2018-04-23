[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BodyLensSpec](./index.md)

# BodyLensSpec

`open class BodyLensSpec<out OUT>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/body.kt#L44)

Represents a uni-directional extraction of an entity from a target Body.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BodyLensSpec(metas: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Meta`](../-meta/index.md)`>, contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`, get: `[`LensGet`](../-lens-get/index.md)`<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`, `[`OUT`](index.md#OUT)`>)`<br>Represents a uni-directional extraction of an entity from a target Body. |

### Functions

| Name | Summary |
|---|---|
| [map](map.md) | `fun <NEXT> map(nextIn: (`[`OUT`](index.md#OUT)`) -> `[`NEXT`](map.md#NEXT)`): `[`BodyLensSpec`](./index.md)`<`[`NEXT`](map.md#NEXT)`>`<br>Create another BodyLensSpec which applies the uni-directional transformation to the result. Any resultant Lens can only be used to extract the final type from a Body. |
| [toLens](to-lens.md) | `open fun toLens(): `[`BodyLens`](../-body-lens/index.md)`<`[`OUT`](index.md#OUT)`>`<br>Create a lens for this Spec |

### Inheritors

| Name | Summary |
|---|---|
| [BiDiBodyLensSpec](../-bi-di-body-lens-spec/index.md) | `open class BiDiBodyLensSpec<OUT> : `[`BodyLensSpec`](./index.md)`<`[`OUT`](../-bi-di-body-lens-spec/index.md#OUT)`>`<br>Represents a bi-directional extraction of an entity from a target Body, or an insertion into a target Body. |
