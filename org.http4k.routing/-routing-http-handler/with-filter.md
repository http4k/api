[http4k](../../index.md) / [org.http4k.routing](../index.md) / [RoutingHttpHandler](index.md) / [withFilter](./with-filter.md)

# withFilter

`abstract fun withFilter(new: `[`Filter`](../../org.http4k.core/-filter/index.md)`): `[`RoutingHttpHandler`](index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/routing/routing.kt#L40)

Returns a RoutingHttpHandler which applies the passed Filter to all received requests before servicing them.
To follow the trend of immutability, this will generally be a new instance.

