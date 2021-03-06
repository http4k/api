[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AuthorizationCodes](./index.md)

# AuthorizationCodes

`interface AuthorizationCodes`

Provides a consistent way to manage authorization codes

### Functions

| Name | Summary |
|---|---|
| [create](create.md) | Create new authorization code to be given to client after the user successfully authorize access The generated authorization code needs to be associated with the clientId and redirectUri for later verification. It should also be associated with a given expire date (recommended to be shorter than 10 minutes)`abstract fun create(request: `[`Request`](../../org.http4k.core/-request/index.md)`, authRequest: `[`AuthRequest`](../-auth-request/index.md)`, response: `[`Response`](../../org.http4k.core/-response/index.md)`): Result<`[`AuthorizationCode`](../-authorization-code/index.md)`, `[`UserRejectedRequest`](../-user-rejected-request.md)`>` |
| [detailsFor](details-for.md) | Retrieve the details of an authorization code`abstract fun detailsFor(code: `[`AuthorizationCode`](../-authorization-code/index.md)`): `[`AuthorizationCodeDetails`](../-authorization-code-details/index.md) |
