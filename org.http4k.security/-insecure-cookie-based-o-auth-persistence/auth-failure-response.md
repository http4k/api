[http4k](../../index.md) / [org.http4k.security](../index.md) / [InsecureCookieBasedOAuthPersistence](index.md) / [authFailureResponse](./auth-failure-response.md)

# authFailureResponse

`fun authFailureResponse(): `[`Response`](../../org.http4k.core/-response/index.md)

Build the default failure response which occurs when a failure occurs during the callback process (eg. a mismatch/missing
CSRF or failure occurring when calling into the end-service for the access-token.

