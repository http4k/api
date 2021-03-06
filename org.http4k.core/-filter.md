[http4k](../index.md) / [org.http4k.core](index.md) / [Filter](./-filter.md)

# Filter

`interface Filter : (`[`HttpHandler`](-http-handler.md)`) -> `[`HttpHandler`](-http-handler.md)

### Extension Functions

| Name | Summary |
|---|---|
| [appliedWhen](../org.http4k.chaos/applied-when.md) | `fun `[`Behaviour`](../org.http4k.chaos/-behaviour.md)`.appliedWhen(trigger: `[`Trigger`](../org.http4k.chaos/-trigger.md)`): `[`Stage`](../org.http4k.chaos/-stage.md) |
| [inIntelliJOnly](../org.http4k.filter/in-intelli-j-only.md) | `fun `[`Filter`](./-filter.md)`.inIntelliJOnly(): `[`Filter`](./-filter.md) |
| [then](then.md) | `fun `[`Filter`](./-filter.md)`.then(next: `[`Filter`](./-filter.md)`): `[`Filter`](./-filter.md)<br>`fun `[`Filter`](./-filter.md)`.then(next: `[`HttpHandler`](-http-handler.md)`): `[`HttpHandler`](-http-handler.md)<br>`fun `[`Filter`](./-filter.md)`.then(routingHttpHandler: `[`RoutingHttpHandler`](../org.http4k.routing/-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](../org.http4k.routing/-routing-http-handler/index.md) |
| [then](../org.http4k.serverless/then.md) | `fun `[`Filter`](./-filter.md)`.then(appLoader: `[`AppLoader`](../org.http4k.serverless/-app-loader.md)`): `[`AppLoader`](../org.http4k.serverless/-app-loader.md)<br>`fun `[`Filter`](./-filter.md)`.then(appLoader: `[`AppLoaderWithContexts`](../org.http4k.serverless/-app-loader-with-contexts.md)`): <ERROR CLASS>` |

### Companion Object Extension Properties

| Name | Summary |
|---|---|
| [NoOp](-no-op.md) | `val Filter.Companion.NoOp: `[`Filter`](./-filter.md) |

### Inheritors

| Name | Summary |
|---|---|
| [AuthRequestTrackingFilter](../org.http4k.security.oauth.server/-auth-request-tracking-filter/index.md) | `class AuthRequestTrackingFilter : `[`Filter`](./-filter.md) |
| [ChaosEngine](../org.http4k.chaos/-chaos-engine/index.md) | The Chaos Engine controls the lifecycle of applying Chaotic behaviour to traffic, which is exposed as a standard Http4k Filter. Chaos can be programmatically updated and enabled/disabled. By default, the engine is deactivated, so activate() needs to be called to witness any change in behaviour,`class ChaosEngine : `[`Filter`](./-filter.md) |
| [ClientValidationFilter](../org.http4k.security.oauth.server/-client-validation-filter/index.md) | `class ClientValidationFilter : `[`Filter`](./-filter.md) |
| [OAuthRedirectionFilter](../org.http4k.security/-o-auth-redirection-filter/index.md) | `class OAuthRedirectionFilter : `[`Filter`](./-filter.md) |
