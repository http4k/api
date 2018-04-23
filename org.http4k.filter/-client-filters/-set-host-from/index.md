[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ClientFilters](../index.md) / [SetHostFrom](./index.md)

# SetHostFrom

`object SetHostFrom` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ClientFilters.kt#L46)

Sets the host on an outbound request. This is useful to separate configuration of remote endpoints
from the logic required to construct the rest of the request.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(uri: `[`Uri`](../../../org.http4k.core/-uri/index.md)`): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
