[http4k](../../index.md) / [org.http4k.contract](../index.md) / [HttpMessageMeta](./index.md)

# HttpMessageMeta

`sealed class HttpMessageMeta<out T : `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/routeMeta.kt#L16)

### Properties

| Name | Summary |
|---|---|
| [definitionId](definition-id.md) | `val definitionId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [message](message.md) | `val message: `[`T`](index.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [RequestMeta](../-request-meta/index.md) | `class RequestMeta : `[`HttpMessageMeta`](./index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`>` |
| [ResponseMeta](../-response-meta/index.md) | `class ResponseMeta : `[`HttpMessageMeta`](./index.md)`<`[`Response`](../../org.http4k.core/-response/index.md)`>` |
