[http4k](../../index.md) / [org.http4k.contract.openapi.v2](../index.md) / [OpenApi2](./index.md)

# OpenApi2

`open class OpenApi2<out NODE> : `[`ContractRenderer`](../../org.http4k.contract/-contract-renderer/index.md)`, `[`ErrorResponseRenderer`](../../org.http4k.contract/-error-response-renderer/index.md)

Contract renderer for OpenApi2 format JSON. Note that for the JSON schema generation, auto-naming of
object models is used as the input relies on JSON objects and not JVM classees.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Contract renderer for OpenApi2 format JSON. Note that for the JSON schema generation, auto-naming of object models is used as the input relies on JSON objects and not JVM classees.`OpenApi2(apiInfo: `[`ApiInfo`](../../org.http4k.contract.openapi/-api-info/index.md)`, json: `[`Json`](../../org.http4k.format/-json/index.md)`<NODE>, baseUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`? = null, extensions: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OpenApiExtension`](../../org.http4k.contract.openapi/-open-api-extension/index.md)`> = emptyList(), securityRenderer: `[`SecurityRenderer`](../../org.http4k.contract.openapi/-security-renderer/index.md)` = OpenApi2SecurityRenderer, schemaGenerator: `[`JsonSchemaCreator`](../../org.http4k.util/-json-schema-creator/index.md)`<NODE, NODE> = JsonToJsonSchema(json), errorResponseRenderer: `[`ErrorResponseRenderer`](../../org.http4k.contract/-error-response-renderer/index.md)` = JsonErrorResponseRenderer(json))` |

### Functions

| Name | Summary |
|---|---|
| [badRequest](bad-request.md) | `open fun badRequest(lensFailure: `[`LensFailure`](../../org.http4k.lens/-lens-failure/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |
| [description](description.md) | `open fun description(contractRoot: `[`PathSegments`](../../org.http4k.contract/-path-segments/index.md)`, security: `[`Security`](../../org.http4k.contract.security/-security/index.md)`?, routes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ContractRoute`](../../org.http4k.contract/-contract-route/index.md)`>): `[`Response`](../../org.http4k.core/-response/index.md) |
| [notFound](not-found.md) | `open fun notFound(): `[`Response`](../../org.http4k.core/-response/index.md) |
