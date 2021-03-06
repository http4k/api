[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AuthRequestTrackingFilter](./index.md)

# AuthRequestTrackingFilter

`class AuthRequestTrackingFilter : `[`Filter`](../../org.http4k.core/-filter.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AuthRequestTrackingFilter(tracking: `[`AuthRequestTracking`](../-auth-request-tracking/index.md)`, extractor: `[`AuthRequestExtractor`](../-auth-request-extractor/index.md)`, authoriseRequestErrorRender: `[`AuthoriseRequestErrorRender`](../-authorise-request-error-render/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(next: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): (`[`Request`](../../org.http4k.core/-request/index.md)`) -> `[`Response`](../../org.http4k.core/-response/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [appliedWhen](../../org.http4k.chaos/applied-when.md) | `fun `[`Behaviour`](../../org.http4k.chaos/-behaviour.md)`.appliedWhen(trigger: `[`Trigger`](../../org.http4k.chaos/-trigger.md)`): `[`Stage`](../../org.http4k.chaos/-stage.md) |
| [inIntelliJOnly](../../org.http4k.filter/in-intelli-j-only.md) | `fun `[`Filter`](../../org.http4k.core/-filter.md)`.inIntelliJOnly(): `[`Filter`](../../org.http4k.core/-filter.md) |
| [then](../../org.http4k.core/then.md) | `fun `[`Filter`](../../org.http4k.core/-filter.md)`.then(next: `[`Filter`](../../org.http4k.core/-filter.md)`): `[`Filter`](../../org.http4k.core/-filter.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter.md)`.then(next: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter.md)`.then(routingHttpHandler: `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
| [then](../../org.http4k.serverless/then.md) | `fun `[`Filter`](../../org.http4k.core/-filter.md)`.then(appLoader: `[`AppLoader`](../../org.http4k.serverless/-app-loader.md)`): `[`AppLoader`](../../org.http4k.serverless/-app-loader.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter.md)`.then(appLoader: `[`AppLoaderWithContexts`](../../org.http4k.serverless/-app-loader-with-contexts.md)`): <ERROR CLASS>` |
