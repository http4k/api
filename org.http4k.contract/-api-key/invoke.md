[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ApiKey](index.md) / [invoke](./invoke.md)

# invoke

`operator fun <T> invoke(param: `[`Lens`](../../org.http4k.lens/-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`T`](invoke.md#T)`>, validateKey: (`[`T`](invoke.md#T)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, authorizeOptionsRequests: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = true): `[`ApiKey`](index.md)`<`[`T`](invoke.md#T)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/Security.kt#L37)

Default implementation of ApiKey. Includes an option to NOT authorise OPTIONS requests, which is
currently not enabled for OpenAPI.

