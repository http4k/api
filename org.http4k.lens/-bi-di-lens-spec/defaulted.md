[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiLensSpec](index.md) / [defaulted](./defaulted.md)

# defaulted

`open fun defaulted(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, default: `[`OUT`](index.md#OUT)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiLens`](../-bi-di-lens/index.md)`<`[`IN`](index.md#IN)`, `[`OUT`](index.md#OUT)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/lensSpec.kt#L139)

Overrides [LensSpec.defaulted](../-lens-spec/defaulted.md)

Make a concrete Lens for this spec that falls back to the default value if no value is found in the target.

