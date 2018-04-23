[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractRoutingHttpHandler](index.md) / [withFilter](./with-filter.md)

# withFilter

`fun withFilter(new: `[`Filter`](../../org.http4k.core/-filter/index.md)`): `[`ContractRoutingHttpHandler`](index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/ContractRoutingHttpHandler.kt#L34)

Overrides [RoutingHttpHandler.withFilter](../../org.http4k.routing/-routing-http-handler/with-filter.md)

NOTE: By default, filters for Contracts are applied *after* the Security filter. Use withPreSecurityFilter()
to achieve population of filters before security.

