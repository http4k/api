[http4k](../../index.md) / [org.http4k.security.oauth.server.refreshtoken](../index.md) / [RefreshTokens](./index.md)

# RefreshTokens

`interface RefreshTokens`

### Functions

| Name | Summary |
|---|---|
| [refreshAccessToken](refresh-access-token.md) | `abstract fun refreshAccessToken(clientId: `[`ClientId`](../../org.http4k.security.oauth.server/-client-id/index.md)`, tokenRequest: `[`TokenRequest`](../../org.http4k.security.oauth.server/-token-request/index.md)`, refreshToken: `[`RefreshToken`](../-refresh-token/index.md)`): Result<`[`AccessToken`](../../org.http4k.security/-access-token/index.md)`, `[`AccessTokenError`](../../org.http4k.security.oauth.server/-access-token-error.md)`>` |

### Companion Object Properties

| Name | Summary |
|---|---|
| [unsupported](unsupported.md) | `val unsupported: <ERROR CLASS>` |
