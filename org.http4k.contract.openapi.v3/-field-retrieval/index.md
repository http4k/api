[http4k](../../index.md) / [org.http4k.contract.openapi.v3](../index.md) / [FieldRetrieval](./index.md)

# FieldRetrieval

`interface FieldRetrieval : (`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`Field`](../-field/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/openapi/v3/FieldRetrieval.kt#L7)

### Companion Object Functions

| Name | Summary |
|---|---|
| [compose](compose.md) | `fun compose(vararg retrieval: `[`FieldRetrieval`](./index.md)`): `[`FieldRetrieval`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [JacksonAnnotated](../-jackson-annotated/index.md) | `object JacksonAnnotated : `[`FieldRetrieval`](./index.md) |
| [SimpleLookup](../-simple-lookup/index.md) | `object SimpleLookup : `[`FieldRetrieval`](./index.md) |