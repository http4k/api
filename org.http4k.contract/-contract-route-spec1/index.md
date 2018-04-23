[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractRouteSpec1](./index.md)

# ContractRouteSpec1

`class ContractRouteSpec1<out A> : `[`ContractRouteSpec`](../-contract-route-spec/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/routeSpec.kt#L43)

### Properties

| Name | Summary |
|---|---|
| [a](a.md) | `val a: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`A`](index.md#A)`>` |

### Inherited Properties

| Name | Summary |
|---|---|
| [pathFn](../-contract-route-spec/path-fn.md) | `val pathFn: (`[`PathSegments`](../-path-segments/index.md)`) -> `[`PathSegments`](../-path-segments/index.md) |
| [pathLenses](../-contract-route-spec/path-lenses.md) | `vararg val pathLenses: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<out `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<*>>` |
| [routeMeta](../-contract-route-spec/route-meta.md) | `val routeMeta: `[`RouteMeta`](../-route-meta/index.md) |

### Functions

| Name | Summary |
|---|---|
| [div](div.md) | `operator infix fun div(next: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ContractRouteSpec2`](../-contract-route-spec2/index.md)`<`[`A`](index.md#A)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>`<br>`operator infix fun <NEXT> div(next: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`NEXT`](div.md#NEXT)`>): `[`ContractRouteSpec2`](../-contract-route-spec2/index.md)`<`[`A`](index.md#A)`, `[`NEXT`](div.md#NEXT)`>` |
| [with](with.md) | `fun with(new: `[`RouteMeta`](../-route-meta/index.md)`): `[`ContractRouteSpec1`](./index.md)`<`[`A`](index.md#A)`>` |

### Inherited Functions

| Name | Summary |
|---|---|
| [invoke](../-contract-route-spec/invoke.md) | `open fun invoke(nextHandler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [bindContract](../bind-contract.md) | `infix fun <A> `[`ContractRouteSpec1`](./index.md)`<`[`A`](../bind-contract.md#A)`>.bindContract(method: `[`Method`](../../org.http4k.core/-method/index.md)`): `[`RouteBinder`](../-route-binder/index.md)`<(`[`A`](../bind-contract.md#A)`) -> `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`>` |
| [meta](../meta.md) | `infix fun <A> `[`ContractRouteSpec1`](./index.md)`<`[`A`](../meta.md#A)`>.meta(new: `[`RouteMetaDsl`](../-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec1`](./index.md)`<`[`A`](../meta.md#A)`>` |
| [then](../../org.http4k.core/then.md) | `fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(next: `[`Filter`](../../org.http4k.core/-filter/index.md)`): `[`Filter`](../../org.http4k.core/-filter/index.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(next: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(routingHttpHandler: `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
