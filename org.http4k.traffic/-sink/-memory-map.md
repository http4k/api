[http4k](../../index.md) / [org.http4k.traffic](../index.md) / [Sink](index.md) / [MemoryMap](./-memory-map.md)

# MemoryMap

`fun MemoryMap(cache: `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`Response`](../../org.http4k.core/-response/index.md)`>, shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }): <ERROR CLASS>`

Serialises HTTP traffic in Memory, optimised for retrieval.

