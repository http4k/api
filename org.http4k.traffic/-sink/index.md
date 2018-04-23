[http4k](../../index.md) / [org.http4k.traffic](../index.md) / [Sink](./index.md)

# Sink

`interface Sink` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/traffic/Sink.kt#L13)

Consumes HTTP traffic for storage.

### Functions

| Name | Summary |
|---|---|
| [set](set.md) | `abstract operator fun set(request: `[`Request`](../../org.http4k.core/-request/index.md)`, response: `[`Response`](../../org.http4k.core/-response/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [DiskStream](-disk-stream.md) | `fun DiskStream(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = ".", shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }, id: () -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = { System.nanoTime().toString() + UUID.randomUUID().toString() }): `[`Sink`](./index.md)<br>Serialises HTTP traffic to the FS in order. |
| [DiskTree](-disk-tree.md) | `fun DiskTree(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = ".", shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }): `[`Sink`](./index.md)<br>Serialises HTTP traffic to the FS, optimised for retrieval. |
| [MemoryMap](-memory-map.md) | `fun MemoryMap(cache: `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`Response`](../../org.http4k.core/-response/index.md)`>, shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }): `[`Sink`](./index.md)<br>Serialises HTTP traffic in Memory, optimised for retrieval. |
| [MemoryStream](-memory-stream.md) | `fun MemoryStream(stream: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`Response`](../../org.http4k.core/-response/index.md)`>>, shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }): `[`Sink`](./index.md)<br>Serialises HTTP traffic to Memory in order. |

### Inheritors

| Name | Summary |
|---|---|
| [ReadWriteCache](../-read-write-cache/index.md) | `interface ReadWriteCache : `[`Sink`](./index.md)`, `[`Source`](../-source/index.md)<br>Combined Read/Write storage models, optimised for retrieval. |
| [ReadWriteStream](../-read-write-stream/index.md) | `interface ReadWriteStream : `[`Sink`](./index.md)`, `[`Replay`](../-replay/index.md)<br>Combined Read/Write storage models, optimised for replay. |
