[http4k](../../index.md) / [org.http4k.security](../index.md) / [InsecureCookieBasedOAuthPersistence](index.md) / [retrieveCsrf](./retrieve-csrf.md)

# retrieveCsrf

`open fun retrieveCsrf(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`CrossSiteRequestForgeryToken`](../-cross-site-request-forgery-token/index.md)`?` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/InsecureCookieBasedOAuthPersistence.kt#L26)

Overrides [OAuthPersistence.retrieveCsrf](../-o-auth-persistence/retrieve-csrf.md)

Retrieve the stored CSRF token for this user request

