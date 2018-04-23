[http4k](../../index.md) / [org.http4k.traffic](../index.md) / [Replay](./index.md)

# Replay

`interface Replay` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/traffic/Replay.kt#L12)

Provides a stream of traffic for replaying purposes.

### Functions

| Name | Summary |
|---|---|
| [requests](requests.md) | `abstract fun requests(): `[`Sequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)`<`[`Request`](../../org.http4k.core/-request/index.md)`>` |
| [responses](responses.md) | `abstract fun responses(): `[`Sequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)`<`[`Response`](../../org.http4k.core/-response/index.md)`>` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [DiskStream](-disk-stream.md) | `fun DiskStream(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "."): `[`Replay`](./index.md)<br>Provides a stream of pre-stored HTTP traffic from the FS. |
| [MemoryStream](-memory-stream.md) | `fun MemoryStream(stream: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`Response`](../../org.http4k.core/-response/index.md)`>>): `[`Replay`](./index.md)<br>Provides a stream of pre-stored HTTP traffic from Memory. |

### Inheritors

| Name | Summary |
|---|---|
| [ReadWriteStream](../-read-write-stream/index.md) | `interface ReadWriteStream : `[`Sink`](../-sink/index.md)`, `[`Replay`](./index.md)<br>Combined Read/Write storage models, optimised for replay. |
