[http4k](../../index.md) / [org.http4k.lens](../index.md) / [PathLensSpec](./index.md)

# PathLensSpec

`open class PathLensSpec<out OUT>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/path.kt#L42)

Represents a uni-directional extraction of an entity from a target path segment.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `PathLensSpec(paramMeta: `[`ParamMeta`](../-param-meta/index.md)`, get: `[`LensGet`](../-lens-get/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`OUT`](index.md#OUT)`>)`<br>Represents a uni-directional extraction of an entity from a target path segment. |

### Properties

| Name | Summary |
|---|---|
| [paramMeta](param-meta.md) | `val paramMeta: `[`ParamMeta`](../-param-meta/index.md) |

### Functions

| Name | Summary |
|---|---|
| [map](map.md) | `fun <NEXT> map(nextIn: (`[`OUT`](index.md#OUT)`) -> `[`NEXT`](map.md#NEXT)`): `[`PathLensSpec`](./index.md)`<`[`NEXT`](map.md#NEXT)`>`<br>Create another PathLensSpec which applies the uni-directional transformation to the result. Any resultant Lens can only be used to extract the final type from a target path segment. |
| [of](of.md) | `open fun of(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`PathLens`](../-path-lens/index.md)`<`[`OUT`](index.md#OUT)`>` |

### Inheritors

| Name | Summary |
|---|---|
| [BiDiPathLensSpec](../-bi-di-path-lens-spec/index.md) | `open class BiDiPathLensSpec<OUT> : `[`PathLensSpec`](./index.md)`<`[`OUT`](../-bi-di-path-lens-spec/index.md#OUT)`>` |
