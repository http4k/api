[http4k](../../index.md) / [org.http4k.security](../index.md) / [InsecureCookieBasedOAuthPersistence](index.md) / [assignCsrf](./assign-csrf.md)

# assignCsrf

`open fun assignCsrf(redirect: `[`Response`](../../org.http4k.core/-response/index.md)`, csrf: `[`CrossSiteRequestForgeryToken`](../-cross-site-request-forgery-token/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/InsecureCookieBasedOAuthPersistence.kt#L30)

Overrides [OAuthPersistence.assignCsrf](../-o-auth-persistence/assign-csrf.md)

Assign a CSRF token to this OAuth auth redirection (to the end-service) response. Opportunity here to modify the
response returned to the user when the redirection happens.

