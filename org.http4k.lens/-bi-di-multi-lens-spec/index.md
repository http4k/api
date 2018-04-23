[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiMultiLensSpec](./index.md)

# BiDiMultiLensSpec

`interface BiDiMultiLensSpec<in IN, OUT> : `[`MultiLensSpec`](../-multi-lens-spec/index.md)`<`[`IN`](index.md#IN)`, `[`OUT`](index.md#OUT)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/lensSpec.kt#L117)

Represents a bi-directional extraction of a list of entities from a target, or an insertion into a target.

### Functions

| Name | Summary |
|---|---|
| [defaulted](defaulted.md) | `abstract fun defaulted(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, default: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](index.md#OUT)`>, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiLens`](../-bi-di-lens/index.md)`<`[`IN`](index.md#IN)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](index.md#OUT)`>>` |
| [optional](optional.md) | `abstract fun optional(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiLens`](../-bi-di-lens/index.md)`<`[`IN`](index.md#IN)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](index.md#OUT)`>?>` |
| [required](required.md) | `abstract fun required(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiLens`](../-bi-di-lens/index.md)`<`[`IN`](index.md#IN)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](index.md#OUT)`>>` |
