[http4k](../../index.md) / [org.http4k.lens](../index.md) / [LensGet](./index.md)

# LensGet

`class LensGet<in IN, out OUT>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/lensSpec.kt#L16)

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): (`[`IN`](index.md#IN)`) -> `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](index.md#OUT)`>` |
| [map](map.md) | `fun <NEXT> map(nextFn: (`[`OUT`](index.md#OUT)`) -> `[`NEXT`](map.md#NEXT)`): `[`LensGet`](./index.md)`<`[`IN`](index.md#IN)`, `[`NEXT`](map.md#NEXT)`>` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun <IN, OUT> invoke(getFn: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`IN`](invoke.md#IN)`) -> `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](invoke.md#OUT)`>): `[`LensGet`](./index.md)`<`[`IN`](invoke.md#IN)`, `[`OUT`](invoke.md#OUT)`>` |
