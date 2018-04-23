[http4k](../../index.md) / [org.http4k.core](../index.md) / [Store](./index.md)

# Store

`interface Store<OUT> : `[`LensInjector`](../../org.http4k.lens/-lens-injector/index.md)`<`[`OUT`](index.md#OUT)`, `[`Request`](../-request/index.md)`>, `[`LensExtractor`](../../org.http4k.lens/-lens-extractor/index.md)`<`[`Request`](../-request/index.md)`, `[`OUT`](index.md#OUT)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/Store.kt#L6)

### Functions

| Name | Summary |
|---|---|
| [remove](remove.md) | `abstract fun remove(value: `[`OUT`](index.md#OUT)`): `[`OUT`](index.md#OUT)`?` |

### Inherited Functions

| Name | Summary |
|---|---|
| [extract](../../org.http4k.lens/-lens-extractor/extract.md) | `open fun extract(target: `[`IN`](../../org.http4k.lens/-lens-extractor/index.md#IN)`): `[`OUT`](../../org.http4k.lens/-lens-extractor/index.md#OUT)<br>Lens operation to get the value from the target. Synonym for invoke(IN) |
| [get](../../org.http4k.lens/-lens-extractor/get.md) | `open operator fun <R : `[`IN`](../../org.http4k.lens/-lens-extractor/index.md#IN)`> get(target: `[`R`](../../org.http4k.lens/-lens-extractor/get.md#R)`): `[`OUT`](../../org.http4k.lens/-lens-extractor/index.md#OUT)<br>Lens operation to get the value from the target. Synonym for invoke(IN) |
| [inject](../../org.http4k.lens/-lens-injector/inject.md) | `open fun <R : `[`OUT`](../../org.http4k.lens/-lens-injector/index.md#OUT)`> inject(value: `[`IN`](../../org.http4k.lens/-lens-injector/index.md#IN)`, target: `[`R`](../../org.http4k.lens/-lens-injector/inject.md#R)`): `[`R`](../../org.http4k.lens/-lens-injector/inject.md#R)<br>Lens operation to set the value into the target. Synomym for invoke(IN, OUT) |
| [invoke](../../org.http4k.lens/-lens-injector/invoke.md) | `abstract operator fun <R : `[`OUT`](../../org.http4k.lens/-lens-injector/index.md#OUT)`> invoke(value: `[`IN`](../../org.http4k.lens/-lens-injector/index.md#IN)`, target: `[`R`](../../org.http4k.lens/-lens-injector/invoke.md#R)`): `[`R`](../../org.http4k.lens/-lens-injector/invoke.md#R)<br>Lens operation to set the value into the target |
| [invoke](../../org.http4k.lens/-lens-extractor/invoke.md) | `abstract operator fun invoke(target: `[`IN`](../../org.http4k.lens/-lens-extractor/index.md#IN)`): `[`OUT`](../../org.http4k.lens/-lens-extractor/index.md#OUT)<br>Lens operation to get the value from the target |
| [of](../../org.http4k.lens/-lens-injector/of.md) | `open infix fun <R : `[`OUT`](../../org.http4k.lens/-lens-injector/index.md#OUT)`> of(value: `[`IN`](../../org.http4k.lens/-lens-injector/index.md#IN)`): (`[`R`](../../org.http4k.lens/-lens-injector/of.md#R)`) -> `[`R`](../../org.http4k.lens/-lens-injector/of.md#R)<br>Bind this Lens to a value, so we can set it into a target |
| [set](../../org.http4k.lens/-lens-injector/set.md) | `open operator fun <R : `[`OUT`](../../org.http4k.lens/-lens-injector/index.md#OUT)`> set(target: `[`R`](../../org.http4k.lens/-lens-injector/set.md#R)`, value: `[`IN`](../../org.http4k.lens/-lens-injector/index.md#IN)`): `[`R`](../../org.http4k.lens/-lens-injector/set.md#R)<br>Lens operation to set the value into the target. Synomym for invoke(IN, OUT) |

### Inheritors

| Name | Summary |
|---|---|
| [RequestContexts](../-request-contexts/index.md) | `class RequestContexts : `[`Store`](./index.md)`<`[`RequestContext`](../-request-context/index.md)`>`<br>In-memory RequestContext store. |
