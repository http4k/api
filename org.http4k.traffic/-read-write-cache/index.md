[http4k](../../index.md) / [org.http4k.traffic](../index.md) / [ReadWriteCache](./index.md)

# ReadWriteCache

`interface ReadWriteCache : `[`Sink`](../-sink/index.md)`, `[`Source`](../-source/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/traffic/ReadWriteCache.kt#L10)

Combined Read/Write storage models, optimised for retrieval.

### Inherited Functions

| Name | Summary |
|---|---|
| [get](../-source/get.md) | `abstract operator fun get(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md)`?` |
| [set](../-sink/set.md) | `abstract operator fun set(request: `[`Request`](../../org.http4k.core/-request/index.md)`, response: `[`Response`](../../org.http4k.core/-response/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [Disk](-disk.md) | `fun Disk(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = ".", shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }): `[`ReadWriteCache`](./index.md)<br>Serialise and retrieve HTTP traffic to/from the FS. |
| [Memory](-memory.md) | `fun Memory(cache: `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`Response`](../../org.http4k.core/-response/index.md)`> = mutableMapOf(), shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }): `[`ReadWriteCache`](./index.md)<br>Serialise and retrieve HTTP traffic to/from Memory. |
