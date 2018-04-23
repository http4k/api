[http4k](../../index.md) / [org.http4k.security](../index.md) / [InsecureCookieBasedOAuthPersistence](index.md) / [assignToken](./assign-token.md)

# assignToken

`open fun assignToken(request: `[`Request`](../../org.http4k.core/-request/index.md)`, redirect: `[`Response`](../../org.http4k.core/-response/index.md)`, accessToken: `[`AccessTokenContainer`](../-access-token-container/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/InsecureCookieBasedOAuthPersistence.kt#L32)

Overrides [OAuthPersistence.assignToken](../-o-auth-persistence/assign-token.md)

Assign the swapped AccessTokenContainer returned by the end-service. Opportunity here to modify the
response returned to the user when the redirection happens.

