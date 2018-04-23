[http4k](../../index.md) / [org.http4k.routing](../index.md) / [RoutingHttpHandler](./index.md)

# RoutingHttpHandler

`interface RoutingHttpHandler : `[`Router`](../-router/index.md)`, `[`HttpHandler`](../../org.http4k.core/-http-handler.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/routing/routing.kt#L35)

Composite HttpHandler which can potentially service many different URL patterns. Should
return a 404 Response if it cannot service a particular Request.

Note that generally there should be no reason for the API user to implement this interface over and above the
implementations that already exist. The interface is public only because we have not found a way to hide it from
the API user in an API-consistent manner.

### Functions

| Name | Summary |
|---|---|
| [withBasePath](with-base-path.md) | `abstract fun withBasePath(new: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`RoutingHttpHandler`](./index.md)<br>Returns a RoutingHttpHandler which prepends the passed base path to the logic determining the match() To follow the trend of immutability, this will generally be a new instance. |
| [withFilter](with-filter.md) | `abstract fun withFilter(new: `[`Filter`](../../org.http4k.core/-filter/index.md)`): `[`RoutingHttpHandler`](./index.md)<br>Returns a RoutingHttpHandler which applies the passed Filter to all received requests before servicing them. To follow the trend of immutability, this will generally be a new instance. |

### Inherited Functions

| Name | Summary |
|---|---|
| [match](../-router/match.md) | `abstract fun match(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`?`<br>Attempt to supply an HttpHandler which can service the passed request. |

### Extension Functions

| Name | Summary |
|---|---|
| [asServer](../../org.http4k.server/kotlin.-function1/as-server.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asServer(config: `[`ServerConfig`](../../org.http4k.server/-server-config/index.md)`): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md) |
| [asServlet](../../org.http4k.servlet/kotlin.-function1/as-servlet.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asServlet(): `[`HttpHandlerServlet`](../../org.http4k.servlet/-http-handler-servlet/index.md) |
| [withAsyncApi](../../org.http4k.client/kotlin.-function1/with-async-api.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.withAsyncApi(): `[`AsyncHttpClient`](../../org.http4k.client/-async-http-client/index.md)<br>Convert a synchronous HttpHandler API to mimic AsyncHttpClient |

### Inheritors

| Name | Summary |
|---|---|
| [ContractRoutingHttpHandler](../../org.http4k.contract/-contract-routing-http-handler/index.md) | `data class ContractRoutingHttpHandler : `[`RoutingHttpHandler`](./index.md) |
