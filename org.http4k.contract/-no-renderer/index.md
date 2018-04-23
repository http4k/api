[http4k](../../index.md) / [org.http4k.contract](../index.md) / [NoRenderer](./index.md)

# NoRenderer

`object NoRenderer : `[`ContractRenderer`](../-contract-renderer/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/NoRenderer.kt#L9)

### Functions

| Name | Summary |
|---|---|
| [badRequest](bad-request.md) | `fun badRequest(failures: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Failure`](../../org.http4k.lens/-failure/index.md)`>): `[`Response`](../../org.http4k.core/-response/index.md) |
| [description](description.md) | `fun description(contractRoot: `[`PathSegments`](../-path-segments/index.md)`, security: `[`Security`](../-security/index.md)`, routes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ContractRoute`](../-contract-route/index.md)`>): `[`Response`](../../org.http4k.core/-response/index.md) |
| [notFound](not-found.md) | `fun notFound(): `[`Response`](../../org.http4k.core/-response/index.md) |
