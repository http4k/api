[http4k](../../index.md) / [org.http4k.core](../index.md) / [Filter](./index.md)

# Filter

`interface Filter : (`[`HttpHandler`](../-http-handler.md)`) -> `[`HttpHandler`](../-http-handler.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/Http4k.kt#L7)

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(fn: (`[`HttpHandler`](../-http-handler.md)`) -> `[`HttpHandler`](../-http-handler.md)`): `[`Filter`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [then](../then.md) | `fun `[`Filter`](./index.md)`.then(next: `[`Filter`](./index.md)`): `[`Filter`](./index.md)<br>`fun `[`Filter`](./index.md)`.then(next: `[`HttpHandler`](../-http-handler.md)`): `[`HttpHandler`](../-http-handler.md)<br>`fun `[`Filter`](./index.md)`.then(routingHttpHandler: `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |

### Companion Object Extension Properties

| Name | Summary |
|---|---|
| [NoOp](../-no-op.md) | `val Filter.Companion.NoOp: `[`Filter`](./index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [CatchLensFailure](../../org.http4k.filter/-server-filters/-catch-lens-failure.md) | `object CatchLensFailure : `[`Filter`](./index.md)<br>Converts Lens extraction failures into correct HTTP responses (Bad Requests/UnsupportedMediaType). This is required when using lenses to automatically unmarshall inbound requests. Note that LensFailures from unmarshalling upstream Response objects are NOT caught to avoid incorrect server behaviour. |
| [ContractRouteSpec](../../org.http4k.contract/-contract-route-spec/index.md) | `abstract class ContractRouteSpec : `[`Filter`](./index.md) |
| [GenerateDataClasses](../../org.http4k.filter/-generate-data-classes/index.md) | `class GenerateDataClasses<ROOT : `[`NODE`](../../org.http4k.filter/-generate-data-classes/index.md#NODE)`, out NODE> : `[`Filter`](./index.md)<br>This Filter is used to generate Data class definitions from a Response containing JSON. The Filter will try and reduce the number of class definitions by selecting the definition with the most fields (for cases where lists of items have different fields). |
| [GenerateXmlDataClasses](../../org.http4k.filter/-generate-xml-data-classes/index.md) | `class GenerateXmlDataClasses : `[`Filter`](./index.md) |
| [OAuthRedirectionFilter](../../org.http4k.security/-o-auth-redirection-filter/index.md) | `class OAuthRedirectionFilter : `[`Filter`](./index.md) |
