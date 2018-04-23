[http4k](../../index.md) / [org.http4k.server](../index.md) / [HttpUndertowHandler](./index.md)

# HttpUndertowHandler

`class HttpUndertowHandler : HttpHandler` [(source)](https://github.com/http4k/http4k/blob/master/http4k-server-undertow/src/main/kotlin/org/http4k/server/Undertow.kt#L20)

Exposed to allow for insertion into a customised Undertow server instance

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `HttpUndertowHandler(handler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`)`<br>Exposed to allow for insertion into a customised Undertow server instance |

### Functions

| Name | Summary |
|---|---|
| [handleRequest](handle-request.md) | `fun handleRequest(exchange: HttpServerExchange): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
