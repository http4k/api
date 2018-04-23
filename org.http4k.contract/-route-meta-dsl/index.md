[http4k](../../index.md) / [org.http4k.contract](../index.md) / [RouteMetaDsl](./index.md)

# RouteMetaDsl

`class RouteMetaDsl` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/routeMeta.kt#L20)

### Properties

| Name | Summary |
|---|---|
| [body](body.md) | `var body: `[`BodyLens`](../../org.http4k.lens/-body-lens/index.md)`<*>?` |
| [consumes](consumes.md) | `val consumes: `[`Appendable`](../../org.http4k.util/-appendable/index.md)`<`[`ContentType`](../../org.http4k.core/-content-type/index.md)`>` |
| [description](description.md) | `var description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [headers](headers.md) | `var headers: `[`Appendable`](../../org.http4k.util/-appendable/index.md)`<`[`Lens`](../../org.http4k.lens/-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, *>>` |
| [operationId](operation-id.md) | `var operationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [produces](produces.md) | `val produces: `[`Appendable`](../../org.http4k.util/-appendable/index.md)`<`[`ContentType`](../../org.http4k.core/-content-type/index.md)`>` |
| [queries](queries.md) | `var queries: `[`Appendable`](../../org.http4k.util/-appendable/index.md)`<`[`Lens`](../../org.http4k.lens/-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, *>>` |
| [summary](summary.md) | `var summary: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [tags](tags.md) | `val tags: `[`Appendable`](../../org.http4k.util/-appendable/index.md)`<`[`Tag`](../-tag/index.md)`>` |

### Functions

| Name | Summary |
|---|---|
| [receiving](receiving.md) | `fun <T> receiving(bodyToDefinitionId: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`BiDiBodyLens`](../../org.http4k.lens/-bi-di-body-lens/index.md)`<`[`T`](receiving.md#T)`>, `[`T`](receiving.md#T)`>, definitionId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Add an example request (using a Lens and a value) to this Route. It is also possible to pass in the definitionId for this request body which will override the naturally generated one. |
| [returning](returning.md) | `fun returning(descriptionToResponse: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Response`](../../org.http4k.core/-response/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`fun returning(responseMeta: `[`ResponseMeta`](../-response-meta/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Add a possible response metadata to this Route`fun returning(descriptionToStatus: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Status`](../../org.http4k.core/-status/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Add a possible response description/reason and status to this Route`fun returning(status: `[`Status`](../../org.http4k.core/-status/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Add a possible response status to this Route |
