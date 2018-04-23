[http4k](../../index.md) / [org.http4k.client](../index.md) / [OkHttp](./index.md)

# OkHttp

`class OkHttp : `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, `[`AsyncHttpClient`](../-async-http-client/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-client-okhttp/src/main/kotlin/org/http4k/client/OkHttp.kt#L18)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `OkHttp(client: OkHttpClient = defaultOkHttpClient(), bodyMode: `[`BodyMode`](../../org.http4k.core/-body-mode/index.md)` = BodyMode.Memory)` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md)<br>`operator fun invoke(request: `[`Request`](../../org.http4k.core/-request/index.md)`, fn: (`[`Response`](../../org.http4k.core/-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inherited Functions

| Name | Summary |
|---|---|
| [close](../-async-http-client/close.md) | `open fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [asServer](../../org.http4k.server/kotlin.-function1/as-server.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asServer(config: `[`ServerConfig`](../../org.http4k.server/-server-config/index.md)`): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md) |
| [asServlet](../../org.http4k.servlet/kotlin.-function1/as-servlet.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asServlet(): `[`HttpHandlerServlet`](../../org.http4k.servlet/-http-handler-servlet/index.md) |
| [withAsyncApi](../kotlin.-function1/with-async-api.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.withAsyncApi(): `[`AsyncHttpClient`](../-async-http-client/index.md)<br>Convert a synchronous HttpHandler API to mimic AsyncHttpClient |
