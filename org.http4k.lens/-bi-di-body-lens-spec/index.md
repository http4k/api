[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiBodyLensSpec](./index.md)

# BiDiBodyLensSpec

`open class BiDiBodyLensSpec<OUT> : `[`BodyLensSpec`](../-body-lens-spec/index.md)`<`[`OUT`](index.md#OUT)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/body.kt#L62)

Represents a bi-directional extraction of an entity from a target Body, or an insertion into a target Body.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BiDiBodyLensSpec(metas: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Meta`](../-meta/index.md)`>, contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`, get: `[`LensGet`](../-lens-get/index.md)`<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`, `[`OUT`](index.md#OUT)`>, set: `[`LensSet`](../-lens-set/index.md)`<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`, `[`OUT`](index.md#OUT)`>)`<br>Represents a bi-directional extraction of an entity from a target Body, or an insertion into a target Body. |

### Functions

| Name | Summary |
|---|---|
| [map](map.md) | `fun <NEXT> map(nextIn: (`[`OUT`](index.md#OUT)`) -> `[`NEXT`](map.md#NEXT)`, nextOut: (`[`NEXT`](map.md#NEXT)`) -> `[`OUT`](index.md#OUT)`): `[`BiDiBodyLensSpec`](./index.md)`<`[`NEXT`](map.md#NEXT)`>`<br>Create another BiDiBodyLensSpec which applies the bi-directional transformations to the result. Any resultant Lens can be used to extract or insert the final type from/into a Body. |
| [toLens](to-lens.md) | `open fun toLens(): `[`BiDiBodyLens`](../-bi-di-body-lens/index.md)`<`[`OUT`](index.md#OUT)`>`<br>Create a lens for this Spec |

### Inherited Functions

| Name | Summary |
|---|---|
| [map](../-body-lens-spec/map.md) | `fun <NEXT> map(nextIn: (`[`OUT`](../-body-lens-spec/index.md#OUT)`) -> `[`NEXT`](../-body-lens-spec/map.md#NEXT)`): `[`BodyLensSpec`](../-body-lens-spec/index.md)`<`[`NEXT`](../-body-lens-spec/map.md#NEXT)`>`<br>Create another BodyLensSpec which applies the uni-directional transformation to the result. Any resultant Lens can only be used to extract the final type from a Body. |
