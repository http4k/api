[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiPathLens](./index.md)

# BiDiPathLens

`class BiDiPathLens<FINAL> : `[`LensInjector`](../-lens-injector/index.md)`<`[`FINAL`](index.md#FINAL)`, `[`Request`](../../org.http4k.core/-request/index.md)`>, `[`PathLens`](../-path-lens/index.md)`<`[`FINAL`](index.md#FINAL)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/path.kt#L33)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BiDiPathLens(meta: `[`Meta`](../-meta/index.md)`, get: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`FINAL`](index.md#FINAL)`, set: (`[`FINAL`](index.md#FINAL)`, `[`Request`](../../org.http4k.core/-request/index.md)`) -> `[`Request`](../../org.http4k.core/-request/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun <R : `[`Request`](../../org.http4k.core/-request/index.md)`> invoke(value: `[`FINAL`](index.md#FINAL)`, target: `[`R`](invoke.md#R)`): `[`R`](invoke.md#R)<br>Lens operation to set the value into the target |

### Inherited Functions

| Name | Summary |
|---|---|
| [inject](../-lens-injector/inject.md) | `open fun <R : `[`OUT`](../-lens-injector/index.md#OUT)`> inject(value: `[`IN`](../-lens-injector/index.md#IN)`, target: `[`R`](../-lens-injector/inject.md#R)`): `[`R`](../-lens-injector/inject.md#R)<br>Lens operation to set the value into the target. Synomym for invoke(IN, OUT) |
| [invoke](../-path-lens/invoke.md) | `operator fun invoke(target: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`FINAL`](../-path-lens/index.md#FINAL) |
| [of](../-lens-injector/of.md) | `open infix fun <R : `[`OUT`](../-lens-injector/index.md#OUT)`> of(value: `[`IN`](../-lens-injector/index.md#IN)`): (`[`R`](../-lens-injector/of.md#R)`) -> `[`R`](../-lens-injector/of.md#R)<br>Bind this Lens to a value, so we can set it into a target |
| [set](../-lens-injector/set.md) | `open operator fun <R : `[`OUT`](../-lens-injector/index.md#OUT)`> set(target: `[`R`](../-lens-injector/set.md#R)`, value: `[`IN`](../-lens-injector/index.md#IN)`): `[`R`](../-lens-injector/set.md#R)<br>Lens operation to set the value into the target. Synomym for invoke(IN, OUT) |

### Extension Functions

| Name | Summary |
|---|---|
| [bindContract](../../org.http4k.contract/bind-contract.md) | `infix fun <A> `[`PathLens`](../-path-lens/index.md)`<`[`A`](../../org.http4k.contract/bind-contract.md#A)`>.bindContract(method: `[`Method`](../../org.http4k.core/-method/index.md)`): `[`RouteBinder`](../../org.http4k.contract/-route-binder/index.md)`<(`[`A`](../../org.http4k.contract/bind-contract.md#A)`) -> `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`>` |
| [div](../../org.http4k.contract/div.md) | `operator fun <A, B> `[`PathLens`](../-path-lens/index.md)`<`[`A`](../../org.http4k.contract/div.md#A)`>.div(next: `[`PathLens`](../-path-lens/index.md)`<`[`B`](../../org.http4k.contract/div.md#B)`>): `[`ContractRouteSpec2`](../../org.http4k.contract/-contract-route-spec2/index.md)`<`[`A`](../../org.http4k.contract/div.md#A)`, `[`B`](../../org.http4k.contract/div.md#B)`>` |
