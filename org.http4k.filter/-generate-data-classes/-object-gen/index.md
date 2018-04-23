[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [GenerateDataClasses](../index.md) / [ObjectGen](./index.md)

# ObjectGen

`data class ObjectGen : `[`Gen`](../-gen/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/GenerateDataClasses.kt#L58)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ObjectGen(clazz: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", fields: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Gen`](../-gen/index.md)`> = emptyMap())` |

### Properties

| Name | Summary |
|---|---|
| [fields](fields.md) | `val fields: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Gen`](../-gen/index.md)`>` |

### Functions

| Name | Summary |
|---|---|
| [asClassName](as-class-name.md) | `fun asClassName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [asDefinitionString](as-definition-string.md) | `fun asDefinitionString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [iterator](iterator.md) | `fun iterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`Gen`](../-gen/index.md)`>` |
