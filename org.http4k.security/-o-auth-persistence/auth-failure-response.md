[http4k](../../index.md) / [org.http4k.security](../index.md) / [OAuthPersistence](index.md) / [authFailureResponse](./auth-failure-response.md)

# authFailureResponse

`open fun authFailureResponse(): `[`Response`](../../org.http4k.core/-response/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/OAuthPersistence.kt#L40)

Build the default failure response which occurs when a failure occurs during the callback process (eg. a mismatch/missing
CSRF or failure occurring when calling into the end-service for the access-token.

