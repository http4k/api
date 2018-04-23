[http4k](../../index.md) / [org.http4k.lens](../index.md) / [RequestContextKey](index.md) / [defaulted](./defaulted.md)

# defaulted

`inline fun <reified T> defaulted(contexts: `[`RequestContexts`](../../org.http4k.core/-request-contexts/index.md)`, default: `[`T`](defaulted.md#T)`, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = UUID.randomUUID().toString()): `[`BiDiLens`](../-bi-di-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`T`](defaulted.md#T)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/RequestContextKey.kt#L27)