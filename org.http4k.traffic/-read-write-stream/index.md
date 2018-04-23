[http4k](../../index.md) / [org.http4k.traffic](../index.md) / [ReadWriteStream](./index.md)

# ReadWriteStream

`interface ReadWriteStream : `[`Sink`](../-sink/index.md)`, `[`Replay`](../-replay/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/traffic/ReadWriteStream.kt#L10)

Combined Read/Write storage models, optimised for replay.

### Inherited Functions

| Name | Summary |
|---|---|
| [requests](../-replay/requests.md) | `abstract fun requests(): `[`Sequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)`<`[`Request`](../../org.http4k.core/-request/index.md)`>` |
| [responses](../-replay/responses.md) | `abstract fun responses(): `[`Sequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)`<`[`Response`](../../org.http4k.core/-response/index.md)`>` |
| [set](../-sink/set.md) | `abstract operator fun set(request: `[`Request`](../../org.http4k.core/-request/index.md)`, response: `[`Response`](../../org.http4k.core/-response/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [Disk](-disk.md) | `fun Disk(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = ".", shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }): `[`ReadWriteStream`](./index.md)<br>Serialise and replay HTTP traffic to/from the FS in order. |
| [Memory](-memory.md) | `fun Memory(stream: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`Response`](../../org.http4k.core/-response/index.md)`>> = mutableListOf(), shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }): `[`ReadWriteStream`](./index.md)<br>Serialise and replay HTTP traffic to/from Memory in order. |
