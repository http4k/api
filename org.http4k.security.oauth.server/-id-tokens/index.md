[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [IdTokens](./index.md)

# IdTokens

`interface IdTokens` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/IdTokens.kt#L7)

### Functions

| Name | Summary |
|---|---|
| [createForAccessToken](create-for-access-token.md) | `abstract fun createForAccessToken(code: `[`AuthorizationCode`](../-authorization-code/index.md)`): `[`IdTokenContainer`](../../org.http4k.security.openid/-id-token-container/index.md) |
| [createForAuthorization](create-for-authorization.md) | `abstract fun createForAuthorization(request: `[`Request`](../../org.http4k.core/-request/index.md)`, authRequest: `[`AuthRequest`](../-auth-request/index.md)`, response: `[`Response`](../../org.http4k.core/-response/index.md)`): `[`IdTokenContainer`](../../org.http4k.security.openid/-id-token-container/index.md) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [Unsupported](-unsupported.md) | `val Unsupported: `[`IdTokens`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |