[http4k](../../index.md) / [org.http4k.client](../index.md) / [AsyncHttpClient](./index.md)

# AsyncHttpClient

`interface AsyncHttpClient : `[`Closeable`](http://docs.oracle.com/javase/6/docs/api/java/io/Closeable.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/client/ext.kt#L10)

### Functions

| Name | Summary |
|---|---|
| [close](close.md) | `open fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [invoke](invoke.md) | `abstract operator fun invoke(request: `[`Request`](../../org.http4k.core/-request/index.md)`, fn: (`[`Response`](../../org.http4k.core/-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [ApacheAsyncClient](../-apache-async-client/index.md) | `class ApacheAsyncClient : `[`AsyncHttpClient`](./index.md) |
| [JettyClient](../-jetty-client/index.md) | `class JettyClient : `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, `[`AsyncHttpClient`](./index.md) |
| [OkHttp](../-ok-http/index.md) | `class OkHttp : `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, `[`AsyncHttpClient`](./index.md) |
