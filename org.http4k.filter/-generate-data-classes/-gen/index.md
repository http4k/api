[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [GenerateDataClasses](../index.md) / [Gen](./index.md)

# Gen

`interface Gen : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Gen`](./index.md)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/GenerateDataClasses.kt#L37)

### Functions

| Name | Summary |
|---|---|
| [asClassName](as-class-name.md) | `abstract fun asClassName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [asDefinitionString](as-definition-string.md) | `open fun asDefinitionString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [iterator](iterator.md) | `open fun iterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`Gen`](./index.md)`>` |

### Inheritors

| Name | Summary |
|---|---|
| [ArrayGen](../-array-gen/index.md) | `data class ArrayGen : `[`Gen`](./index.md) |
| [ObjectGen](../-object-gen/index.md) | `data class ObjectGen : `[`Gen`](./index.md) |
| [Primitives](../-primitives/index.md) | `enum class Primitives : `[`Gen`](./index.md) |
