[http4k](../../index.md) / [org.http4k.lens](../index.md) / [PathLens](./index.md)

# PathLens

`open class PathLens<out FINAL> : `[`Lens`](../-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`FINAL`](index.md#FINAL)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/path.kt#L20)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `PathLens(meta: `[`Meta`](../-meta/index.md)`, get: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`FINAL`](index.md#FINAL)`)` |

### Inherited Properties

| Name | Summary |
|---|---|
| [meta](../-lens/meta.md) | `val meta: `[`Meta`](../-meta/index.md) |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(target: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`FINAL`](index.md#FINAL) |
| [toString](to-string.md) | `open fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Inherited Functions

| Name | Summary |
|---|---|
| [invoke](../-lens/invoke.md) | `open operator fun invoke(target: `[`IN`](../-lens/index.md#IN)`): `[`FINAL`](../-lens/index.md#FINAL)<br>Lens operation to get the value from the target |
| [iterator](../-lens/iterator.md) | `open fun iterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`Meta`](../-meta/index.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [bindContract](../../org.http4k.contract/bind-contract.md) | `infix fun <A> `[`PathLens`](./index.md)`<`[`A`](../../org.http4k.contract/bind-contract.md#A)`>.bindContract(method: `[`Method`](../../org.http4k.core/-method/index.md)`): `[`RouteBinder`](../../org.http4k.contract/-route-binder/index.md)`<(`[`A`](../../org.http4k.contract/bind-contract.md#A)`) -> `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`>` |
| [div](../../org.http4k.contract/div.md) | `operator fun <A, B> `[`PathLens`](./index.md)`<`[`A`](../../org.http4k.contract/div.md#A)`>.div(next: `[`PathLens`](./index.md)`<`[`B`](../../org.http4k.contract/div.md#B)`>): `[`ContractRouteSpec2`](../../org.http4k.contract/-contract-route-spec2/index.md)`<`[`A`](../../org.http4k.contract/div.md#A)`, `[`B`](../../org.http4k.contract/div.md#B)`>` |

### Inheritors

| Name | Summary |
|---|---|
| [BiDiPathLens](../-bi-di-path-lens/index.md) | `class BiDiPathLens<FINAL> : `[`LensInjector`](../-lens-injector/index.md)`<`[`FINAL`](../-bi-di-path-lens/index.md#FINAL)`, `[`Request`](../../org.http4k.core/-request/index.md)`>, `[`PathLens`](./index.md)`<`[`FINAL`](../-bi-di-path-lens/index.md#FINAL)`>` |
