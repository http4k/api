[http4k](../../index.md) / [org.http4k.filter](../index.md) / [StaleWhenRevalidateTtl](./index.md)

# StaleWhenRevalidateTtl

`data class StaleWhenRevalidateTtl : `[`CacheControlHeaderPart`](../-cache-control-header-part/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/CachingFilters.kt#L24)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `StaleWhenRevalidateTtl(valueD: Duration)` |

### Inherited Properties

| Name | Summary |
|---|---|
| [name](../-cache-control-header-part/name.md) | `open val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [value](../-cache-control-header-part/value.md) | `val value: Duration` |

### Inherited Functions

| Name | Summary |
|---|---|
| [replaceIn](../-cache-control-header-part/replace-in.md) | `fun replaceIn(header: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [toHeaderValue](../-cache-control-header-part/to-header-value.md) | `fun toHeaderValue(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
