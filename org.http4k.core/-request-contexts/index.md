[http4k](../../index.md) / [org.http4k.core](../index.md) / [RequestContexts](./index.md)

# RequestContexts

`class RequestContexts : `[`Store`](../-store/index.md)`<`[`RequestContext`](../-request-context/index.md)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/RequestContexts.kt#L9)

In-memory RequestContext store.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RequestContexts()`<br>In-memory RequestContext store. |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(target: `[`Request`](../-request/index.md)`): `[`RequestContext`](../-request-context/index.md)<br>Lens operation to get the value from the target`fun <R : `[`Request`](../-request/index.md)`> invoke(value: `[`RequestContext`](../-request-context/index.md)`, target: `[`R`](invoke.md#R)`): `[`R`](invoke.md#R)<br>Lens operation to set the value into the target |
| [remove](remove.md) | `fun remove(value: `[`RequestContext`](../-request-context/index.md)`): `[`RequestContext`](../-request-context/index.md)`?` |
