[http4k](../../index.md) / [org.http4k.routing](../index.md) / [PathMethod](./index.md)

# PathMethod

`data class PathMethod` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/routing/routing.kt#L70)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `PathMethod(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, method: `[`Method`](../../org.http4k.core/-method/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [method](method.md) | `val method: `[`Method`](../../org.http4k.core/-method/index.md) |
| [path](path.md) | `val path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [to](to.md) | `infix fun to(action: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`RoutingHttpHandler`](../-routing-http-handler/index.md) |
