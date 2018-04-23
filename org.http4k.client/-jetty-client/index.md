[http4k](../../index.md) / [org.http4k.client](../index.md) / [JettyClient](./index.md)

# JettyClient

`class JettyClient : `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, `[`AsyncHttpClient`](../-async-http-client/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-client-jetty/src/main/kotlin/org/http4k/client/JettyClient.kt#L23)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `JettyClient(client: HttpClient = defaultHttpClient(), bodyMode: `[`BodyMode`](../../org.http4k.core/-body-mode/index.md)` = BodyMode.Memory, requestModifier: (Request) -> Request = { it })` |

### Functions

| Name | Summary |
|---|---|
| [close](close.md) | `fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [invoke](invoke.md) | `fun invoke(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md)<br>`fun invoke(request: `[`Request`](../../org.http4k.core/-request/index.md)`, fn: (`[`Response`](../../org.http4k.core/-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [asServer](../../org.http4k.server/kotlin.-function1/as-server.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asServer(config: `[`ServerConfig`](../../org.http4k.server/-server-config/index.md)`): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md) |
| [asServlet](../../org.http4k.servlet/kotlin.-function1/as-servlet.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asServlet(): `[`HttpHandlerServlet`](../../org.http4k.servlet/-http-handler-servlet/index.md) |
| [withAsyncApi](../kotlin.-function1/with-async-api.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.withAsyncApi(): `[`AsyncHttpClient`](../-async-http-client/index.md)<br>Convert a synchronous HttpHandler API to mimic AsyncHttpClient |
