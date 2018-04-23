[http4k](../../../index.md) / [org.http4k.core](../../index.md) / [RequestContext](../index.md) / [Companion](./index.md)

# Companion

`companion object Companion : `[`LensExtractor`](../../../org.http4k.lens/-lens-extractor/index.md)`<`[`Request`](../../-request/index.md)`, `[`UUID`](http://docs.oracle.com/javase/6/docs/api/java/util/UUID.html)`>, `[`LensInjector`](../../../org.http4k.lens/-lens-injector/index.md)`<`[`UUID`](http://docs.oracle.com/javase/6/docs/api/java/util/UUID.html)`, `[`Request`](../../-request/index.md)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/RequestContext.kt)

### Inherited Functions

| Name | Summary |
|---|---|
| [extract](../../../org.http4k.lens/-lens-extractor/extract.md) | `open fun extract(target: `[`IN`](../../../org.http4k.lens/-lens-extractor/index.md#IN)`): `[`OUT`](../../../org.http4k.lens/-lens-extractor/index.md#OUT)<br>Lens operation to get the value from the target. Synonym for invoke(IN) |
| [get](../../../org.http4k.lens/-lens-extractor/get.md) | `open operator fun <R : `[`IN`](../../../org.http4k.lens/-lens-extractor/index.md#IN)`> get(target: `[`R`](../../../org.http4k.lens/-lens-extractor/get.md#R)`): `[`OUT`](../../../org.http4k.lens/-lens-extractor/index.md#OUT)<br>Lens operation to get the value from the target. Synonym for invoke(IN) |
| [inject](../../../org.http4k.lens/-lens-injector/inject.md) | `open fun <R : `[`OUT`](../../../org.http4k.lens/-lens-injector/index.md#OUT)`> inject(value: `[`IN`](../../../org.http4k.lens/-lens-injector/index.md#IN)`, target: `[`R`](../../../org.http4k.lens/-lens-injector/inject.md#R)`): `[`R`](../../../org.http4k.lens/-lens-injector/inject.md#R)<br>Lens operation to set the value into the target. Synomym for invoke(IN, OUT) |
| [of](../../../org.http4k.lens/-lens-injector/of.md) | `open infix fun <R : `[`OUT`](../../../org.http4k.lens/-lens-injector/index.md#OUT)`> of(value: `[`IN`](../../../org.http4k.lens/-lens-injector/index.md#IN)`): (`[`R`](../../../org.http4k.lens/-lens-injector/of.md#R)`) -> `[`R`](../../../org.http4k.lens/-lens-injector/of.md#R)<br>Bind this Lens to a value, so we can set it into a target |
| [set](../../../org.http4k.lens/-lens-injector/set.md) | `open operator fun <R : `[`OUT`](../../../org.http4k.lens/-lens-injector/index.md#OUT)`> set(target: `[`R`](../../../org.http4k.lens/-lens-injector/set.md#R)`, value: `[`IN`](../../../org.http4k.lens/-lens-injector/index.md#IN)`): `[`R`](../../../org.http4k.lens/-lens-injector/set.md#R)<br>Lens operation to set the value into the target. Synomym for invoke(IN, OUT) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun <R : `[`Request`](../../-request/index.md)`> invoke(value: `[`UUID`](http://docs.oracle.com/javase/6/docs/api/java/util/UUID.html)`, target: `[`R`](invoke.md#R)`): `[`R`](invoke.md#R)<br>Lens operation to set the value into the target`fun invoke(target: `[`Request`](../../-request/index.md)`): `[`UUID`](http://docs.oracle.com/javase/6/docs/api/java/util/UUID.html)<br>Lens operation to get the value from the target |
