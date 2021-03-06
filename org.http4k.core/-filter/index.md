[http4k](../../index.md) / [org.http4k.core](../index.md) / [Filter](./index.md)

# Filter

`interface Filter : (`[`HttpHandler`](../-http-handler.md)`) -> `[`HttpHandler`](../-http-handler.md)

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(fn: (`[`HttpHandler`](../-http-handler.md)`) -> `[`HttpHandler`](../-http-handler.md)`): `[`Filter`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [appliedWhen](../../org.http4k.chaos/applied-when.md) | `fun `[`Behaviour`](../../org.http4k.chaos/-behaviour.md)`.appliedWhen(trigger: `[`Trigger`](../../org.http4k.chaos/-trigger.md)`): `[`Stage`](../../org.http4k.chaos/-stage.md) |
| [then](../then.md) | `fun `[`Filter`](./index.md)`.then(next: `[`Filter`](./index.md)`): `[`Filter`](./index.md)<br>`fun `[`Filter`](./index.md)`.then(next: `[`HttpHandler`](../-http-handler.md)`): `[`HttpHandler`](../-http-handler.md)<br>`fun `[`Filter`](./index.md)`.then(routingHttpHandler: `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
| [then](../../org.http4k.serverless/then.md) | `fun `[`Filter`](./index.md)`.then(appLoader: `[`AppLoader`](../../org.http4k.serverless/-app-loader.md)`): `[`AppLoader`](../../org.http4k.serverless/-app-loader.md)<br>`fun `[`Filter`](./index.md)`.then(appLoader: `[`AppLoaderWithContexts`](../../org.http4k.serverless/-app-loader-with-contexts.md)`): `[`AppLoaderWithContexts`](../../org.http4k.serverless/-app-loader-with-contexts.md) |

### Companion Object Extension Properties

| Name | Summary |
|---|---|
| [NoOp](../-no-op.md) | `val Filter.Companion.NoOp: `[`Filter`](./index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [AuthRequestTrackingFilter](../../org.http4k.security.oauth.server/-auth-request-tracking-filter/index.md) | `class AuthRequestTrackingFilter : `[`Filter`](./index.md) |
| [ChaosEngine](../../org.http4k.chaos/-chaos-engine/index.md) | The Chaos Engine controls the lifecycle of applying Chaotic behaviour to traffic, which is exposed as a standard Http4k Filter. Chaos can be programmatically updated and enabled/disabled. By default, the engine is deactivated, so activate() needs to be called to witness any change in behaviour,`class ChaosEngine : `[`Filter`](./index.md) |
| [ClientValidationFilter](../../org.http4k.security.oauth.server/-client-validation-filter/index.md) | `class ClientValidationFilter : `[`Filter`](./index.md) |
| [GenerateDataClasses](../../org.http4k.filter/-generate-data-classes/index.md) | This Filter is used to generate Data class definitions from a Response containing JSON. The Filter will try and reduce the number of class definitions by selecting the definition with the most fields (for cases where lists of items have different fields).`class GenerateDataClasses<out NODE> : `[`Filter`](./index.md) |
| [GenerateXmlDataClasses](../../org.http4k.filter/-generate-xml-data-classes/index.md) | This Filter is used to generate Data class definitions from a Response containing XML. The Filter will try and reduce the number of class definitions by selecting the definition with the most fields (for cases where lists of items have different fields).`class GenerateXmlDataClasses<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`Filter`](./index.md) |
| [OAuthRedirectionFilter](../../org.http4k.security/-o-auth-redirection-filter/index.md) | `class OAuthRedirectionFilter : `[`Filter`](./index.md) |
