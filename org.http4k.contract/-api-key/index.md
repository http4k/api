[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ApiKey](./index.md)

# ApiKey

`interface ApiKey<out T> : `[`Security`](../-security/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/Security.kt#L29)

Checks the presence of the named Api Key parameter. Filter returns 401 if Api-Key is not found in request.

### Properties

| Name | Summary |
|---|---|
| [param](param.md) | `abstract val param: `[`Lens`](../../org.http4k.lens/-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`T`](index.md#T)`>` |

### Inherited Properties

| Name | Summary |
|---|---|
| [filter](../-security/filter.md) | `abstract val filter: `[`Filter`](../../org.http4k.core/-filter/index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun <T> invoke(param: `[`Lens`](../../org.http4k.lens/-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`T`](invoke.md#T)`>, validateKey: (`[`T`](invoke.md#T)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, authorizeOptionsRequests: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = true): `[`ApiKey`](./index.md)`<`[`T`](invoke.md#T)`>`<br>Default implementation of ApiKey. Includes an option to NOT authorise OPTIONS requests, which is currently not enabled for OpenAPI. |
