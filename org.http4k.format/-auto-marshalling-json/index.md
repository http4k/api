[http4k](../../index.md) / [org.http4k.format](../index.md) / [AutoMarshallingJson](./index.md)

# AutoMarshallingJson

`abstract class AutoMarshallingJson` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/format/AutoMarshallingJson.kt#L5)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AutoMarshallingJson()` |

### Functions

| Name | Summary |
|---|---|
| [asA](as-a.md) | `abstract fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(s: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, c: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](as-a.md#T)`>): `[`T`](as-a.md#T)<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asA(c: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](as-a.md#T)`>): `[`T`](as-a.md#T) |
| [asJsonString](as-json-string.md) | `abstract fun asJsonString(a: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [ConfigurableMoshi](../-configurable-moshi/index.md) | `open class ConfigurableMoshi : `[`AutoMarshallingJson`](./index.md) |
| [JsonLibAutoMarshallingJson](../-json-lib-auto-marshalling-json/index.md) | `abstract class JsonLibAutoMarshallingJson<ROOT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`AutoMarshallingJson`](./index.md)`, `[`Json`](../-json/index.md)`<`[`ROOT`](../-json-lib-auto-marshalling-json/index.md#ROOT)`, `[`ROOT`](../-json-lib-auto-marshalling-json/index.md#ROOT)`>` |
