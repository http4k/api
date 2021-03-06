[http4k](../../index.md) / [org.http4k.routing](../index.md) / [RoutingHttpHandler](./index.md)

# RoutingHttpHandler

`interface RoutingHttpHandler : `[`Router`](../-router/index.md)`, `[`HttpHandler`](../../org.http4k.core/-http-handler.md)

Composite HttpHandler which can potentially service many different URL patterns. Should
return a 404 Response if it cannot service a particular Request.

Note that generally there should be no reason for the API user to implement this interface over and above the
implementations that already exist. The interface is public only because we have not found a way to hide it from
the API user in an API-consistent manner.

### Functions

| Name | Summary |
|---|---|
| [withBasePath](with-base-path.md) | Returns a Router which prepends the passed base path to the logic determining the match().`abstract fun withBasePath(new: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`RoutingHttpHandler`](./index.md) |
| [withFilter](with-filter.md) | Returns a Router which applies the passed Filter to all received requests before servicing them.`abstract fun withFilter(new: `[`Filter`](../../org.http4k.core/-filter.md)`): `[`RoutingHttpHandler`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [and](../and.md) | `infix fun `[`Router`](../-router/index.md)`.and(that: `[`Router`](../-router/index.md)`): `[`Router`](../-router/index.md) |
| [bind](../bind.md) | `infix fun `[`Router`](../-router/index.md)`.bind(handler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`RoutingHttpHandler`](./index.md)<br>`infix fun `[`Router`](../-router/index.md)`.bind(handler: `[`RoutingHttpHandler`](./index.md)`): `[`RoutingHttpHandler`](./index.md) |
| [withChaosApi](../../org.http4k.chaos/with-chaos-api.md) | Mixin the set of remote Chaos API endpoints to a standard HttpHandler, using the passed ChaosStage. Optionally a Security can be passed to limit access to the chaos controls.`fun `[`RoutingHttpHandler`](./index.md)`.withChaosApi(engine: `[`ChaosEngine`](../../org.http4k.chaos/-chaos-engine/index.md)` = ChaosEngine(), security: `[`Security`](../../org.http4k.contract.security/-security/index.md)` = NoSecurity, controlsPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/chaos", openApiPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", corsPolicy: `[`CorsPolicy`](../../org.http4k.filter/-cors-policy/index.md)` = UnsafeGlobalPermissive, clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = Clock.systemUTC(), apiName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "http4k"): `[`RoutingHttpHandler`](./index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [ContractRoutingHttpHandler](../../org.http4k.contract/-contract-routing-http-handler/index.md) | `data class ContractRoutingHttpHandler : `[`RoutingHttpHandler`](./index.md) |
