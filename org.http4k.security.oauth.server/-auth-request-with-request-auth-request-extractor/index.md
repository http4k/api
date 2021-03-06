[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AuthRequestWithRequestAuthRequestExtractor](./index.md)

# AuthRequestWithRequestAuthRequestExtractor

`class AuthRequestWithRequestAuthRequestExtractor : `[`AuthRequestExtractor`](../-auth-request-extractor/index.md)

### Types

| Name | Summary |
|---|---|
| [CombineAuthRequestRequestStrategy](-combine-auth-request-request-strategy/index.md) | `sealed class CombineAuthRequestRequestStrategy` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AuthRequestWithRequestAuthRequestExtractor(requestJWTValidator: `[`RequestJWTValidator`](../../org.http4k.security.oauth.server.request/-request-j-w-t-validator/index.md)`, combineAuthRequestRequestStrategy: CombineAuthRequestRequestStrategy)` |

### Functions

| Name | Summary |
|---|---|
| [extract](extract.md) | `fun extract(request: `[`Request`](../../org.http4k.core/-request/index.md)`): Result<`[`AuthRequest`](../-auth-request/index.md)`, `[`InvalidAuthorizationRequest`](../-invalid-authorization-request/index.md)`>` |
