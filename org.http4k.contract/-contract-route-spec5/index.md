[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractRouteSpec5](./index.md)

# ContractRouteSpec5

`class ContractRouteSpec5<out A, out B, out C, out D, out E> : `[`ContractRouteSpec`](../-contract-route-spec/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/routeSpec.kt#L78)

### Properties

| Name | Summary |
|---|---|
| [a](a.md) | `val a: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`A`](index.md#A)`>` |
| [b](b.md) | `val b: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`B`](index.md#B)`>` |
| [c](c.md) | `val c: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`C`](index.md#C)`>` |
| [d](d.md) | `val d: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`D`](index.md#D)`>` |
| [e](e.md) | `val e: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`E`](index.md#E)`>` |

### Inherited Properties

| Name | Summary |
|---|---|
| [pathFn](../-contract-route-spec/path-fn.md) | `val pathFn: (`[`PathSegments`](../-path-segments/index.md)`) -> `[`PathSegments`](../-path-segments/index.md) |
| [pathLenses](../-contract-route-spec/path-lenses.md) | `vararg val pathLenses: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<out `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<*>>` |
| [routeMeta](../-contract-route-spec/route-meta.md) | `val routeMeta: `[`RouteMeta`](../-route-meta/index.md) |

### Functions

| Name | Summary |
|---|---|
| [div](div.md) | `operator infix fun div(next: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ContractRouteSpec6`](../-contract-route-spec6/index.md)`<`[`A`](index.md#A)`, `[`B`](index.md#B)`, `[`C`](index.md#C)`, `[`D`](index.md#D)`, `[`E`](index.md#E)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>`<br>`operator infix fun <NEXT> div(next: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`NEXT`](div.md#NEXT)`>): `[`ContractRouteSpec6`](../-contract-route-spec6/index.md)`<`[`A`](index.md#A)`, `[`B`](index.md#B)`, `[`C`](index.md#C)`, `[`D`](index.md#D)`, `[`E`](index.md#E)`, `[`NEXT`](div.md#NEXT)`>` |
| [with](with.md) | `fun with(new: `[`RouteMeta`](../-route-meta/index.md)`): `[`ContractRouteSpec5`](./index.md)`<`[`A`](index.md#A)`, `[`B`](index.md#B)`, `[`C`](index.md#C)`, `[`D`](index.md#D)`, `[`E`](index.md#E)`>` |

### Inherited Functions

| Name | Summary |
|---|---|
| [invoke](../-contract-route-spec/invoke.md) | `open fun invoke(nextHandler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [bindContract](../bind-contract.md) | `infix fun <A, B, C, D, E> `[`ContractRouteSpec5`](./index.md)`<`[`A`](../bind-contract.md#A)`, `[`B`](../bind-contract.md#B)`, `[`C`](../bind-contract.md#C)`, `[`D`](../bind-contract.md#D)`, `[`E`](../bind-contract.md#E)`>.bindContract(method: `[`Method`](../../org.http4k.core/-method/index.md)`): `[`RouteBinder`](../-route-binder/index.md)`<(`[`A`](../bind-contract.md#A)`, `[`B`](../bind-contract.md#B)`, `[`C`](../bind-contract.md#C)`, `[`D`](../bind-contract.md#D)`, `[`E`](../bind-contract.md#E)`) -> `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`>` |
| [meta](../meta.md) | `infix fun <A, B, C, D, E> `[`ContractRouteSpec5`](./index.md)`<`[`A`](../meta.md#A)`, `[`B`](../meta.md#B)`, `[`C`](../meta.md#C)`, `[`D`](../meta.md#D)`, `[`E`](../meta.md#E)`>.meta(new: `[`RouteMetaDsl`](../-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec5`](./index.md)`<`[`A`](../meta.md#A)`, `[`B`](../meta.md#B)`, `[`C`](../meta.md#C)`, `[`D`](../meta.md#D)`, `[`E`](../meta.md#E)`>` |
| [then](../../org.http4k.core/then.md) | `fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(next: `[`Filter`](../../org.http4k.core/-filter/index.md)`): `[`Filter`](../../org.http4k.core/-filter/index.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(next: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(routingHttpHandler: `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
