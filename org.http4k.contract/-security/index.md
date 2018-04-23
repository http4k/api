[http4k](../../index.md) / [org.http4k.contract](../index.md) / [Security](./index.md)

# Security

`interface Security` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/Security.kt#L15)

Endpoint security. Provides filter to be applied to endpoints for all requests.

### Properties

| Name | Summary |
|---|---|
| [filter](filter.md) | `abstract val filter: `[`Filter`](../../org.http4k.core/-filter/index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [ApiKey](../-api-key/index.md) | `interface ApiKey<out T> : `[`Security`](./index.md)<br>Checks the presence of the named Api Key parameter. Filter returns 401 if Api-Key is not found in request. |
| [NoSecurity](../-no-security/index.md) | `object NoSecurity : `[`Security`](./index.md)<br>Default NoOp security filter. Filter allows all traffic through. |
