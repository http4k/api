[http4k](../../index.md) / [org.http4k.traffic](../index.md) / [Source](./index.md)

# Source

`interface Source` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/traffic/Source.kt#L11)

Tries to retrieve a stored response for a given request.

### Functions

| Name | Summary |
|---|---|
| [get](get.md) | `abstract operator fun get(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md)`?` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [DiskTree](-disk-tree.md) | `fun DiskTree(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "."): `[`Source`](./index.md)<br>Looks up traffic from the FS, based on tree storage format. |
| [MemoryMap](-memory-map.md) | `fun MemoryMap(cache: `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`Response`](../../org.http4k.core/-response/index.md)`>): `[`Source`](./index.md)<br>Looks up traffic from Memory, based on map storage format. |

### Inheritors

| Name | Summary |
|---|---|
| [ReadWriteCache](../-read-write-cache/index.md) | `interface ReadWriteCache : `[`Sink`](../-sink/index.md)`, `[`Source`](./index.md)<br>Combined Read/Write storage models, optimised for retrieval. |
