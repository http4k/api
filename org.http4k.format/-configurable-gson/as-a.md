[http4k](../../index.md) / [org.http4k.format](../index.md) / [ConfigurableGson](index.md) / [asA](./as-a.md)

# asA

`open fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(s: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, c: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](as-a.md#T)`>): `[`T`](as-a.md#T) [(source)](https://github.com/http4k/http4k/blob/master/http4k-format-gson/src/main/kotlin/org/http4k/format/Gson.kt#L74)

Overrides [AutoMarshallingJson.asA](../-auto-marshalling-json/as-a.md)


`open fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(j: JsonElement, c: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](as-a.md#T)`>): `[`T`](as-a.md#T) [(source)](https://github.com/http4k/http4k/blob/master/http4k-format-gson/src/main/kotlin/org/http4k/format/Gson.kt#L75)

Overrides [JsonLibAutoMarshallingJson.asA](../-json-lib-auto-marshalling-json/as-a.md)


`inline fun <reified T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asA(): `[`T`](as-a.md#T) [(source)](https://github.com/http4k/http4k/blob/master/http4k-format-gson/src/main/kotlin/org/http4k/format/Gson.kt#L77)
`inline fun <reified T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> JsonElement.asA(): `[`T`](as-a.md#T) [(source)](https://github.com/http4k/http4k/blob/master/http4k-format-gson/src/main/kotlin/org/http4k/format/Gson.kt#L78)