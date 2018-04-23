[http4k](../../index.md) / [org.http4k.server](../index.md) / [Http4kRequestHandler](./index.md)

# Http4kRequestHandler

`class Http4kRequestHandler : HttpRequestHandler` [(source)](https://github.com/http4k/http4k/blob/master/http4k-server-apache/src/main/kotlin/org/http4k/server/ApacheServer.kt#L26)

Exposed to allow for insertion into a customised Apache WebServer instance

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Http4kRequestHandler(handler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`)`<br>Exposed to allow for insertion into a customised Apache WebServer instance |

### Functions

| Name | Summary |
|---|---|
| [handle](handle.md) | `fun handle(request: HttpRequest, response: HttpResponse, context: HttpContext): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
