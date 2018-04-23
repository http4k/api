[http4k](../../index.md) / [org.http4k.lens](../index.md) / [RequestContextKey](./index.md)

# RequestContextKey

`object RequestContextKey` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/RequestContextKey.kt#L11)

### Functions

| Name | Summary |
|---|---|
| [defaulted](defaulted.md) | `fun <T> defaulted(contexts: `[`RequestContexts`](../../org.http4k.core/-request-contexts/index.md)`, default: `[`T`](defaulted.md#T)`, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = UUID.randomUUID().toString()): `[`BiDiLens`](../-bi-di-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`T`](defaulted.md#T)`>` |
| [optional](optional.md) | `fun <T> optional(contexts: `[`RequestContexts`](../../org.http4k.core/-request-contexts/index.md)`, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = UUID.randomUUID().toString()): `[`BiDiLens`](../-bi-di-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`T`](optional.md#T)`?>` |
| [required](required.md) | `fun <T> required(contexts: `[`RequestContexts`](../../org.http4k.core/-request-contexts/index.md)`, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = UUID.randomUUID().toString()): `[`RequestContextLens`](../-request-context-lens.md)`<`[`T`](required.md#T)`>` |
