[http4k](../../index.md) / [org.http4k.client](../index.md) / [ApacheAsyncClient](./index.md)

# ApacheAsyncClient

`class ApacheAsyncClient : `[`AsyncHttpClient`](../-async-http-client/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-client-apache-async/src/main/kotlin/org/http4k/client/ApacheAsyncClient.kt#L29)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ApacheAsyncClient(client: CloseableHttpAsyncClient = defaultApacheAsyncHttpClient(), responseBodyMode: `[`BodyMode`](../../org.http4k.core/-body-mode/index.md)` = Memory, requestBodyMode: `[`BodyMode`](../../org.http4k.core/-body-mode/index.md)` = Memory)` |

### Functions

| Name | Summary |
|---|---|
| [close](close.md) | `fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [invoke](invoke.md) | `fun invoke(request: `[`Request`](../../org.http4k.core/-request/index.md)`, fn: (`[`Response`](../../org.http4k.core/-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
