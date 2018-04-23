[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiPathLensSpec](./index.md)

# BiDiPathLensSpec

`open class BiDiPathLensSpec<OUT> : `[`PathLensSpec`](../-path-lens-spec/index.md)`<`[`OUT`](index.md#OUT)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/path.kt#L56)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BiDiPathLensSpec(paramMeta: `[`ParamMeta`](../-param-meta/index.md)`, get: `[`LensGet`](../-lens-get/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`OUT`](index.md#OUT)`>, set: `[`LensSet`](../-lens-set/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`OUT`](index.md#OUT)`>)` |

### Inherited Properties

| Name | Summary |
|---|---|
| [paramMeta](../-path-lens-spec/param-meta.md) | `val paramMeta: `[`ParamMeta`](../-param-meta/index.md) |

### Functions

| Name | Summary |
|---|---|
| [map](map.md) | `fun <NEXT> map(nextIn: (`[`OUT`](index.md#OUT)`) -> `[`NEXT`](map.md#NEXT)`, nextOut: (`[`NEXT`](map.md#NEXT)`) -> `[`OUT`](index.md#OUT)`): `[`BiDiPathLensSpec`](./index.md)`<`[`NEXT`](map.md#NEXT)`>`<br>Create another BiDiPathLensSpec which applies the bi-directional transformations to the result. Any resultant Lens can be used to extract or insert the final type from/into a path segment. |
| [of](of.md) | `open fun of(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiPathLens`](../-bi-di-path-lens/index.md)`<`[`OUT`](index.md#OUT)`>`<br>Create a lens for this Spec |

### Inherited Functions

| Name | Summary |
|---|---|
| [map](../-path-lens-spec/map.md) | `fun <NEXT> map(nextIn: (`[`OUT`](../-path-lens-spec/index.md#OUT)`) -> `[`NEXT`](../-path-lens-spec/map.md#NEXT)`): `[`PathLensSpec`](../-path-lens-spec/index.md)`<`[`NEXT`](../-path-lens-spec/map.md#NEXT)`>`<br>Create another PathLensSpec which applies the uni-directional transformation to the result. Any resultant Lens can only be used to extract the final type from a target path segment. |

### Inheritors

| Name | Summary |
|---|---|
| [Path](../-path/index.md) | `object Path : `[`BiDiPathLensSpec`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
