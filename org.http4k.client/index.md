[http4k](../index.md) / [org.http4k.client](./index.md)

## Package org.http4k.client

### Types

| Name | Summary |
|---|---|
| [ApacheAsyncClient](-apache-async-client/index.md) | `class ApacheAsyncClient : `[`AsyncHttpClient`](-async-http-client/index.md) |
| [ApacheClient](-apache-client/index.md) | `class ApacheClient : `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [AsyncHttpClient](-async-http-client/index.md) | `interface AsyncHttpClient : `[`Closeable`](http://docs.oracle.com/javase/6/docs/api/java/io/Closeable.html) |
| [JavaHttpClient](-java-http-client/index.md) | `class JavaHttpClient : `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [JettyClient](-jetty-client/index.md) | `class JettyClient : `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, `[`AsyncHttpClient`](-async-http-client/index.md) |
| [OkHttp](-ok-http/index.md) | `class OkHttp : `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, `[`AsyncHttpClient`](-async-http-client/index.md) |
| [WebsocketClient](-websocket-client/index.md) | `object WebsocketClient` |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.Function1](kotlin.-function1/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [describeClientError](describe-client-error.md) | `fun `[`Status`](../org.http4k.core/-status/index.md)`.describeClientError(e: `[`Exception`](http://docs.oracle.com/javase/6/docs/api/java/lang/Exception.html)`): `[`Status`](../org.http4k.core/-status/index.md) |
