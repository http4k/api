[http4k](../../index.md) / [org.http4k.lens](../index.md) / [LensSet](./index.md)

# LensSet

`class LensSet<IN, in OUT>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/lensSpec.kt#L26)

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): (`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](index.md#OUT)`>, `[`IN`](index.md#IN)`) -> `[`IN`](index.md#IN) |
| [map](map.md) | `fun <NEXT> map(nextFn: (`[`NEXT`](map.md#NEXT)`) -> `[`OUT`](index.md#OUT)`): `[`LensSet`](./index.md)`<`[`IN`](index.md#IN)`, `[`NEXT`](map.md#NEXT)`>` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun <IN, OUT> invoke(setFn: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](invoke.md#OUT)`>, `[`IN`](invoke.md#IN)`) -> `[`IN`](invoke.md#IN)`): `[`LensSet`](./index.md)`<`[`IN`](invoke.md#IN)`, `[`OUT`](invoke.md#OUT)`>` |
