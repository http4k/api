[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractRenderer](./index.md)

# ContractRenderer

`interface ContractRenderer` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/ContractRenderer.kt#L6)

### Functions

| Name | Summary |
|---|---|
| [badRequest](bad-request.md) | `abstract fun badRequest(failures: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Failure`](../../org.http4k.lens/-failure/index.md)`>): `[`Response`](../../org.http4k.core/-response/index.md) |
| [description](description.md) | `abstract fun description(contractRoot: `[`PathSegments`](../-path-segments/index.md)`, security: `[`Security`](../-security/index.md)`, routes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ContractRoute`](../-contract-route/index.md)`>): `[`Response`](../../org.http4k.core/-response/index.md) |
| [notFound](not-found.md) | `abstract fun notFound(): `[`Response`](../../org.http4k.core/-response/index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [NoRenderer](../-no-renderer/index.md) | `object NoRenderer : `[`ContractRenderer`](./index.md) |
| [OpenApi](../-open-api/index.md) | `class OpenApi<ROOT : `[`NODE`](../-open-api/index.md#NODE)`, out NODE> : `[`ContractRenderer`](./index.md) |
| [SimpleJson](../-simple-json/index.md) | `class SimpleJson<ROOT : `[`NODE`](../-simple-json/index.md#NODE)`, out NODE> : `[`ContractRenderer`](./index.md) |
