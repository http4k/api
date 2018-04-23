[http4k](../../index.md) / [org.http4k.contract](../index.md) / [RouteBinder](./index.md)

# RouteBinder

`interface RouteBinder<in T>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/extensions.kt#L22)

### Functions

| Name | Summary |
|---|---|
| [newRequest](new-request.md) | `abstract fun newRequest(baseUri: `[`Uri`](../../org.http4k.core/-uri/index.md)` = Uri.of("")): `[`Request`](../../org.http4k.core/-request/index.md) |
| [to](to.md) | `abstract infix fun to(fn: `[`T`](index.md#T)`): `[`ContractRoute`](../-contract-route/index.md) |
