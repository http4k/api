[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractRoutingHttpHandler](index.md) / [withBasePath](./with-base-path.md)

# withBasePath

`fun withBasePath(new: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ContractRoutingHttpHandler`](index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/ContractRoutingHttpHandler.kt#L36)

Overrides [RoutingHttpHandler.withBasePath](../../org.http4k.routing/-routing-http-handler/with-base-path.md)

Returns a RoutingHttpHandler which prepends the passed base path to the logic determining the match()
To follow the trend of immutability, this will generally be a new instance.

