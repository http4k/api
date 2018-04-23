[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractRoutingHttpHandler](./index.md)

# ContractRoutingHttpHandler

`data class ContractRoutingHttpHandler : `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/ContractRoutingHttpHandler.kt#L18)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ContractRoutingHttpHandler(renderer: `[`ContractRenderer`](../-contract-renderer/index.md)`, security: `[`Security`](../-security/index.md)`, descriptionPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, routes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ContractRoute`](../-contract-route/index.md)`> = emptyList(), rootAsString: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", preSecurityFilter: `[`Filter`](../../org.http4k.core/-filter/index.md)` = Filter.NoOp, postSecurityFilter: `[`Filter`](../../org.http4k.core/-filter/index.md)` = Filter.NoOp)` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |
| [match](match.md) | `fun match(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`?`<br>Attempt to supply an HttpHandler which can service the passed request. |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [withBasePath](with-base-path.md) | `fun withBasePath(new: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ContractRoutingHttpHandler`](./index.md)<br>Returns a RoutingHttpHandler which prepends the passed base path to the logic determining the match() To follow the trend of immutability, this will generally be a new instance. |
| [withFilter](with-filter.md) | `fun withFilter(new: `[`Filter`](../../org.http4k.core/-filter/index.md)`): `[`ContractRoutingHttpHandler`](./index.md)<br>NOTE: By default, filters for Contracts are applied *after* the Security filter. Use withPreSecurityFilter() to achieve population of filters before security. |
| [withPostSecurityFilter](with-post-security-filter.md) | `fun withPostSecurityFilter(new: `[`Filter`](../../org.http4k.core/-filter/index.md)`): `[`ContractRoutingHttpHandler`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [asServer](../../org.http4k.server/kotlin.-function1/as-server.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asServer(config: `[`ServerConfig`](../../org.http4k.server/-server-config/index.md)`): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md) |
| [asServlet](../../org.http4k.servlet/kotlin.-function1/as-servlet.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asServlet(): `[`HttpHandlerServlet`](../../org.http4k.servlet/-http-handler-servlet/index.md) |
| [withAsyncApi](../../org.http4k.client/kotlin.-function1/with-async-api.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.withAsyncApi(): `[`AsyncHttpClient`](../../org.http4k.client/-async-http-client/index.md)<br>Convert a synchronous HttpHandler API to mimic AsyncHttpClient |
