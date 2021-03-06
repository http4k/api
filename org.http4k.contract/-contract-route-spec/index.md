[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractRouteSpec](./index.md)

# ContractRouteSpec

`abstract class ContractRouteSpec`

### Types

| Name | Summary |
|---|---|
| [ContractRequestBuilder](-contract-request-builder/index.md) | `open inner class ContractRequestBuilder` |

### Properties

| Name | Summary |
|---|---|
| [pathFn](path-fn.md) | `val pathFn: (`[`PathSegments`](../-path-segments/index.md)`) -> `[`PathSegments`](../-path-segments/index.md) |
| [pathLenses](path-lenses.md) | `vararg val pathLenses: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<out `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<*>>` |
| [routeMeta](route-meta.md) | `val routeMeta: `[`RouteMeta`](../-route-meta/index.md) |

### Functions

| Name | Summary |
|---|---|
| [bindContract](bind-contract.md) | `abstract infix fun bindContract(method: `[`Method`](../../org.http4k.core/-method/index.md)`): ContractRequestBuilder` |
| [div](div.md) | `abstract infix operator fun <T> div(next: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<T>): `[`ContractRouteSpec`](./index.md)<br>`open infix operator fun div(next: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ContractRouteSpec`](./index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [ContractRouteSpec0](../-contract-route-spec0/index.md) | `class ContractRouteSpec0 : `[`ContractRouteSpec`](./index.md) |
| [ContractRouteSpec1](../-contract-route-spec1/index.md) | `class ContractRouteSpec1<out A> : `[`ContractRouteSpec`](./index.md) |
| [ContractRouteSpec10](../-contract-route-spec10/index.md) | `class ContractRouteSpec10<out A, out B, out C, out D, out E, out F, out G, out H, out I, out J> : `[`ContractRouteSpec`](./index.md) |
| [ContractRouteSpec2](../-contract-route-spec2/index.md) | `class ContractRouteSpec2<out A, out B> : `[`ContractRouteSpec`](./index.md) |
| [ContractRouteSpec3](../-contract-route-spec3/index.md) | `class ContractRouteSpec3<out A, out B, out C> : `[`ContractRouteSpec`](./index.md) |
| [ContractRouteSpec4](../-contract-route-spec4/index.md) | `class ContractRouteSpec4<out A, out B, out C, out D> : `[`ContractRouteSpec`](./index.md) |
| [ContractRouteSpec5](../-contract-route-spec5/index.md) | `class ContractRouteSpec5<out A, out B, out C, out D, out E> : `[`ContractRouteSpec`](./index.md) |
| [ContractRouteSpec6](../-contract-route-spec6/index.md) | `class ContractRouteSpec6<out A, out B, out C, out D, out E, out F> : `[`ContractRouteSpec`](./index.md) |
| [ContractRouteSpec7](../-contract-route-spec7/index.md) | `class ContractRouteSpec7<out A, out B, out C, out D, out E, out F, out G> : `[`ContractRouteSpec`](./index.md) |
| [ContractRouteSpec8](../-contract-route-spec8/index.md) | `class ContractRouteSpec8<out A, out B, out C, out D, out E, out F, out G, out H> : `[`ContractRouteSpec`](./index.md) |
| [ContractRouteSpec9](../-contract-route-spec9/index.md) | `class ContractRouteSpec9<out A, out B, out C, out D, out E, out F, out G, out H, out I> : `[`ContractRouteSpec`](./index.md) |
