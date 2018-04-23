[http4k](../../index.md) / [org.http4k.traffic](../index.md) / [ReadWriteCache](index.md) / [Memory](./-memory.md)

# Memory

`fun Memory(cache: `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`Response`](../../org.http4k.core/-response/index.md)`> = mutableMapOf(), shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }): `[`ReadWriteCache`](index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/traffic/ReadWriteCache.kt#L22)

Serialise and retrieve HTTP traffic to/from Memory.

