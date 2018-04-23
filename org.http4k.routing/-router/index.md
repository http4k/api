[http4k](../../index.md) / [org.http4k.routing](../index.md) / [Router](./index.md)

# Router

`interface Router` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/routing/routing.kt#L20)

Provides matching of a Request to an HttpHandler which can service it.

### Functions

| Name | Summary |
|---|---|
| [match](match.md) | `abstract fun match(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`?`<br>Attempt to supply an HttpHandler which can service the passed request. |

### Inheritors

| Name | Summary |
|---|---|
| [RoutingHttpHandler](../-routing-http-handler/index.md) | `interface RoutingHttpHandler : `[`Router`](./index.md)`, `[`HttpHandler`](../../org.http4k.core/-http-handler.md)<br>Composite HttpHandler which can potentially service many different URL patterns. Should return a 404 Response if it cannot service a particular Request. |
