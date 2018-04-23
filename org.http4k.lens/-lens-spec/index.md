[http4k](../../index.md) / [org.http4k.lens](../index.md) / [LensSpec](./index.md)

# LensSpec

`open class LensSpec<IN, OUT>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/lensSpec.kt#L48)

Represents a uni-directional extraction of an entity from a target.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `LensSpec(location: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, paramMeta: `[`ParamMeta`](../-param-meta/index.md)`, get: `[`LensGet`](../-lens-get/index.md)`<`[`IN`](index.md#IN)`, `[`OUT`](index.md#OUT)`>)`<br>Represents a uni-directional extraction of an entity from a target. |

### Properties

| Name | Summary |
|---|---|
| [location](location.md) | `val location: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [multi](multi.md) | `open val multi: `[`MultiLensSpec`](../-multi-lens-spec/index.md)`<`[`IN`](index.md#IN)`, `[`OUT`](index.md#OUT)`>` |
| [paramMeta](param-meta.md) | `val paramMeta: `[`ParamMeta`](../-param-meta/index.md) |

### Functions

| Name | Summary |
|---|---|
| [defaulted](defaulted.md) | `open fun defaulted(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, default: `[`OUT`](index.md#OUT)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Lens`](../-lens/index.md)`<`[`IN`](index.md#IN)`, `[`OUT`](index.md#OUT)`>`<br>Make a concrete Lens for this spec that falls back to the default value if no value is found in the target. |
| [map](map.md) | `fun <NEXT> map(nextIn: (`[`OUT`](index.md#OUT)`) -> `[`NEXT`](map.md#NEXT)`): `[`LensSpec`](./index.md)`<`[`IN`](index.md#IN)`, `[`NEXT`](map.md#NEXT)`>`<br>Create another LensSpec which applies the uni-directional transformation to the result. Any resultant Lens can only be used to extract the final type from a target. |
| [optional](optional.md) | `open fun optional(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Lens`](../-lens/index.md)`<`[`IN`](index.md#IN)`, `[`OUT`](index.md#OUT)`?>`<br>Make a concrete Lens for this spec that looks for an optional value in the target. |
| [required](required.md) | `open fun required(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Lens`](../-lens/index.md)`<`[`IN`](index.md#IN)`, `[`OUT`](index.md#OUT)`>`<br>Make a concrete Lens for this spec that looks for a required value in the target. |

### Inheritors

| Name | Summary |
|---|---|
| [BiDiLensSpec](../-bi-di-lens-spec/index.md) | `open class BiDiLensSpec<IN, OUT> : `[`LensSpec`](./index.md)`<`[`IN`](../-bi-di-lens-spec/index.md#IN)`, `[`OUT`](../-bi-di-lens-spec/index.md#OUT)`>`<br>Represents a bi-directional extraction of an entity from a target, or an insertion into a target. |
