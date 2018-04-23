[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractRouteSpec9](./index.md)

# ContractRouteSpec9

`class ContractRouteSpec9<out A, out B, out C, out D, out E, out F, out G, out H, out I> : `[`ContractRouteSpec`](../-contract-route-spec/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/routeSpec.kt#L116)

### Properties

| Name | Summary |
|---|---|
| [a](a.md) | `val a: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`A`](index.md#A)`>` |
| [b](b.md) | `val b: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`B`](index.md#B)`>` |
| [c](c.md) | `val c: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`C`](index.md#C)`>` |
| [d](d.md) | `val d: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`D`](index.md#D)`>` |
| [e](e.md) | `val e: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`E`](index.md#E)`>` |
| [f](f.md) | `val f: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`F`](index.md#F)`>` |
| [g](g.md) | `val g: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`G`](index.md#G)`>` |
| [h](h.md) | `val h: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`H`](index.md#H)`>` |
| [i](i.md) | `val i: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`I`](index.md#I)`>` |

### Inherited Properties

| Name | Summary |
|---|---|
| [pathFn](../-contract-route-spec/path-fn.md) | `val pathFn: (`[`PathSegments`](../-path-segments/index.md)`) -> `[`PathSegments`](../-path-segments/index.md) |
| [pathLenses](../-contract-route-spec/path-lenses.md) | `vararg val pathLenses: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<out `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<*>>` |
| [routeMeta](../-contract-route-spec/route-meta.md) | `val routeMeta: `[`RouteMeta`](../-route-meta/index.md) |

### Functions

| Name | Summary |
|---|---|
| [div](div.md) | `operator infix fun div(next: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ContractRouteSpec10`](../-contract-route-spec10/index.md)`<`[`A`](index.md#A)`, `[`B`](index.md#B)`, `[`C`](index.md#C)`, `[`D`](index.md#D)`, `[`E`](index.md#E)`, `[`F`](index.md#F)`, `[`G`](index.md#G)`, `[`H`](index.md#H)`, `[`I`](index.md#I)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>`<br>`operator infix fun <NEXT> div(next: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`NEXT`](div.md#NEXT)`>): `[`ContractRouteSpec10`](../-contract-route-spec10/index.md)`<`[`A`](index.md#A)`, `[`B`](index.md#B)`, `[`C`](index.md#C)`, `[`D`](index.md#D)`, `[`E`](index.md#E)`, `[`F`](index.md#F)`, `[`G`](index.md#G)`, `[`H`](index.md#H)`, `[`I`](index.md#I)`, `[`NEXT`](div.md#NEXT)`>` |
| [with](with.md) | `fun with(new: `[`RouteMeta`](../-route-meta/index.md)`): `[`ContractRouteSpec9`](./index.md)`<`[`A`](index.md#A)`, `[`B`](index.md#B)`, `[`C`](index.md#C)`, `[`D`](index.md#D)`, `[`E`](index.md#E)`, `[`F`](index.md#F)`, `[`G`](index.md#G)`, `[`H`](index.md#H)`, `[`I`](index.md#I)`>` |

### Inherited Functions

| Name | Summary |
|---|---|
| [invoke](../-contract-route-spec/invoke.md) | `open fun invoke(nextHandler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [bindContract](../bind-contract.md) | `infix fun <A, B, C, D, E, F, G, H, I> `[`ContractRouteSpec9`](./index.md)`<`[`A`](../bind-contract.md#A)`, `[`B`](../bind-contract.md#B)`, `[`C`](../bind-contract.md#C)`, `[`D`](../bind-contract.md#D)`, `[`E`](../bind-contract.md#E)`, `[`F`](../bind-contract.md#F)`, `[`G`](../bind-contract.md#G)`, `[`H`](../bind-contract.md#H)`, `[`I`](../bind-contract.md#I)`>.bindContract(method: `[`Method`](../../org.http4k.core/-method/index.md)`): `[`RouteBinder`](../-route-binder/index.md)`<(`[`A`](../bind-contract.md#A)`, `[`B`](../bind-contract.md#B)`, `[`C`](../bind-contract.md#C)`, `[`D`](../bind-contract.md#D)`, `[`E`](../bind-contract.md#E)`, `[`F`](../bind-contract.md#F)`, `[`G`](../bind-contract.md#G)`, `[`H`](../bind-contract.md#H)`, `[`I`](../bind-contract.md#I)`) -> `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`>` |
| [meta](../meta.md) | `infix fun <A, B, C, D, E, F, G, H, I> `[`ContractRouteSpec9`](./index.md)`<`[`A`](../meta.md#A)`, `[`B`](../meta.md#B)`, `[`C`](../meta.md#C)`, `[`D`](../meta.md#D)`, `[`E`](../meta.md#E)`, `[`F`](../meta.md#F)`, `[`G`](../meta.md#G)`, `[`H`](../meta.md#H)`, `[`I`](../meta.md#I)`>.meta(new: `[`RouteMetaDsl`](../-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec9`](./index.md)`<`[`A`](../meta.md#A)`, `[`B`](../meta.md#B)`, `[`C`](../meta.md#C)`, `[`D`](../meta.md#D)`, `[`E`](../meta.md#E)`, `[`F`](../meta.md#F)`, `[`G`](../meta.md#G)`, `[`H`](../meta.md#H)`, `[`I`](../meta.md#I)`>` |
| [then](../../org.http4k.core/then.md) | `fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(next: `[`Filter`](../../org.http4k.core/-filter/index.md)`): `[`Filter`](../../org.http4k.core/-filter/index.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(next: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(routingHttpHandler: `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
