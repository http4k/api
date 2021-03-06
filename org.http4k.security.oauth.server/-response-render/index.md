[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [ResponseRender](./index.md)

# ResponseRender

`interface ResponseRender`

### Functions

| Name | Summary |
|---|---|
| [addParameter](add-parameter.md) | `abstract fun addParameter(key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`ResponseRender`](./index.md) |
| [complete](complete.md) | `abstract fun complete(): `[`Response`](../../org.http4k.core/-response/index.md) |
| [withDocumentationUri](with-documentation-uri.md) | `open fun withDocumentationUri(documentationUri: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`ResponseRender`](./index.md) |
| [withState](with-state.md) | `open fun withState(state: `[`State`](../../org.http4k.security/-state/index.md)`?): `[`ResponseRender`](./index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [forAuthRequest](for-auth-request.md) | `fun forAuthRequest(authorizationRequest: `[`AuthRequest`](../-auth-request/index.md)`): `[`ResponseRender`](./index.md)<br>`fun forAuthRequest(responseMode: `[`ResponseMode`](../../org.http4k.security/-response-mode/index.md)`?, responseType: `[`ResponseType`](../../org.http4k.security/-response-type/index.md)`, redirectUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`): `[`ResponseRender`](./index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [FragmentResponseRender](../-fragment-response-render/index.md) | `class FragmentResponseRender : `[`ResponseRender`](./index.md) |
| [QueryResponseRender](../-query-response-render/index.md) | `class QueryResponseRender : `[`ResponseRender`](./index.md) |
