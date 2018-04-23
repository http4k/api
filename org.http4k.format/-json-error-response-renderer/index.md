[http4k](../../index.md) / [org.http4k.format](../index.md) / [JsonErrorResponseRenderer](./index.md)

# JsonErrorResponseRenderer

`class JsonErrorResponseRenderer<ROOT : `[`NODE`](index.md#NODE)`, out NODE>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/format/JsonErrorResponseRenderer.kt#L8)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `JsonErrorResponseRenderer(json: `[`Json`](../-json/index.md)`<`[`ROOT`](index.md#ROOT)`, `[`NODE`](index.md#NODE)`>)` |

### Functions

| Name | Summary |
|---|---|
| [badRequest](bad-request.md) | `fun badRequest(failures: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Failure`](../../org.http4k.lens/-failure/index.md)`>): `[`Response`](../../org.http4k.core/-response/index.md) |
| [notFound](not-found.md) | `fun notFound(): `[`Response`](../../org.http4k.core/-response/index.md) |
