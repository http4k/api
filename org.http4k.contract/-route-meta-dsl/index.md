[http4k](../../index.md) / [org.http4k.contract](../index.md) / [RouteMetaDsl](./index.md)

# RouteMetaDsl

`class RouteMetaDsl`

### Properties

| Name | Summary |
|---|---|
| [consumes](consumes.md) | `val consumes: `[`Appendable`](../../org.http4k.util/-appendable/index.md)`<`[`ContentType`](../../org.http4k.core/-content-type/index.md)`>` |
| [cookies](cookies.md) | `val cookies: `[`Appendable`](../../org.http4k.util/-appendable/index.md)`<`[`Lens`](../../org.http4k.lens/-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, *>>` |
| [description](description.md) | `var description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [headers](headers.md) | `val headers: `[`Appendable`](../../org.http4k.util/-appendable/index.md)`<`[`Lens`](../../org.http4k.lens/-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, *>>` |
| [operationId](operation-id.md) | `var operationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [preFlightExtraction](pre-flight-extraction.md) | `var preFlightExtraction: `[`PreFlightExtraction`](../-pre-flight-extraction/index.md)`?` |
| [produces](produces.md) | `val produces: `[`Appendable`](../../org.http4k.util/-appendable/index.md)`<`[`ContentType`](../../org.http4k.core/-content-type/index.md)`>` |
| [queries](queries.md) | `val queries: `[`Appendable`](../../org.http4k.util/-appendable/index.md)`<`[`Lens`](../../org.http4k.lens/-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, *>>` |
| [security](security.md) | `var security: `[`Security`](../../org.http4k.contract.security/-security/index.md)`?` |
| [summary](summary.md) | `var summary: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [tags](tags.md) | `val tags: `[`Appendable`](../../org.http4k.util/-appendable/index.md)`<`[`Tag`](../-tag/index.md)`>` |

### Functions

| Name | Summary |
|---|---|
| [markAsDeprecated](mark-as-deprecated.md) | `fun markAsDeprecated(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [receiving](receiving.md) | Add an example request (using a Lens and a value) to this Route. It is also possible to pass in the definitionId for this request body which will override the naturally generated one.`fun <T> receiving(body: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`BiDiBodyLens`](../../org.http4k.lens/-bi-di-body-lens/index.md)`<T>, T>, definitionId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Add request metadata to this Route. A route only supports a single possible request.`fun receiving(requestMeta: `[`HttpMessageMeta`](../-http-message-meta/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Set the input body type for this request WITHOUT an example. Hence the content-type will be registered but no example schema will be generated.`fun <T> receiving(bodyLens: `[`BiDiBodyLens`](../../org.http4k.lens/-bi-di-body-lens/index.md)`<T>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [returning](returning.md) | Add possible responses to this Route.`fun returning(vararg descriptionToResponse: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Response`](../../org.http4k.core/-response/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Add possible response metadata to this Route. A route supports multiple possible responses.`fun returning(vararg responseMetas: `[`HttpMessageMeta`](../-http-message-meta/index.md)`<`[`Response`](../../org.http4k.core/-response/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Add a possible response description/reason and status to this Route`fun returning(vararg statusesToDescriptions: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`Status`](../../org.http4k.core/-status/index.md)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Add possible response statuses to this Route with no example.`fun returning(vararg statuses: `[`Status`](../../org.http4k.core/-status/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Add an example response (using a Lens and a value) to this Route. It is also possible to pass in the definitionId for this response body which will override the naturally generated one.`fun <T> returning(status: `[`Status`](../../org.http4k.core/-status/index.md)`, body: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`BiDiBodyLens`](../../org.http4k.lens/-bi-di-body-lens/index.md)`<T>, T>, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, definitionId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
