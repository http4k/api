[http4k](../../index.md) / [org.http4k.routing](../index.md) / [RoutingHttpHandler](index.md) / [withBasePath](./with-base-path.md)

# withBasePath

`abstract fun withBasePath(new: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`RoutingHttpHandler`](index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/routing/routing.kt#L46)

Returns a RoutingHttpHandler which prepends the passed base path to the logic determining the match()
To follow the trend of immutability, this will generally be a new instance.

