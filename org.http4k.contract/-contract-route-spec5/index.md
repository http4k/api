[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractRouteSpec5](./index.md)

# ContractRouteSpec5

`class ContractRouteSpec5<out A, out B, out C, out D, out E> : `[`ContractRouteSpec`](../-contract-route-spec/index.md)

### Types

| Name | Summary |
|---|---|
| [Binder](-binder/index.md) | `inner class Binder<out A, out B, out C, out D, out E> : ContractRequestBuilder` |

### Properties

| Name | Summary |
|---|---|
| [a](a.md) | `val a: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<A>` |
| [b](b.md) | `val b: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<B>` |
| [c](c.md) | `val c: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<C>` |
| [d](d.md) | `val d: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<D>` |
| [e](e.md) | `val e: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<E>` |

### Functions

| Name | Summary |
|---|---|
| [bindContract](bind-contract.md) | `infix fun bindContract(method: `[`Method`](../../org.http4k.core/-method/index.md)`): Binder<A, B, C, D, E>` |
| [div](div.md) | `infix operator fun div(next: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ContractRouteSpec6`](../-contract-route-spec6/index.md)`<A, B, C, D, E, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>`<br>`infix operator fun <NEXT> div(next: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<NEXT>): `[`ContractRouteSpec6`](../-contract-route-spec6/index.md)`<A, B, C, D, E, NEXT>` |

### Extension Functions

| Name | Summary |
|---|---|
| [meta](../meta.md) | `infix fun <A, B, C, D, E> `[`ContractRouteSpec5`](./index.md)`<A, B, C, D, E>.meta(new: `[`RouteMetaDsl`](../-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec5`](./index.md)`<A, B, C, D, E>` |
