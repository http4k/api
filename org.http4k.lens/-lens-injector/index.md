[http4k](../../index.md) / [org.http4k.lens](../index.md) / [LensInjector](./index.md)

# LensInjector

`interface LensInjector<in IN, in OUT>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/LensInjector.kt#L3)

### Functions

| Name | Summary |
|---|---|
| [inject](inject.md) | `open fun <R : `[`OUT`](index.md#OUT)`> inject(value: `[`IN`](index.md#IN)`, target: `[`R`](inject.md#R)`): `[`R`](inject.md#R)<br>Lens operation to set the value into the target. Synomym for invoke(IN, OUT) |
| [invoke](invoke.md) | `abstract operator fun <R : `[`OUT`](index.md#OUT)`> invoke(value: `[`IN`](index.md#IN)`, target: `[`R`](invoke.md#R)`): `[`R`](invoke.md#R)<br>Lens operation to set the value into the target |
| [of](of.md) | `open infix fun <R : `[`OUT`](index.md#OUT)`> of(value: `[`IN`](index.md#IN)`): (`[`R`](of.md#R)`) -> `[`R`](of.md#R)<br>Bind this Lens to a value, so we can set it into a target |
| [set](set.md) | `open operator fun <R : `[`OUT`](index.md#OUT)`> set(target: `[`R`](set.md#R)`, value: `[`IN`](index.md#IN)`): `[`R`](set.md#R)<br>Lens operation to set the value into the target. Synomym for invoke(IN, OUT) |

### Inheritors

| Name | Summary |
|---|---|
| [BiDiBodyLens](../-bi-di-body-lens/index.md) | `class BiDiBodyLens<FINAL> : `[`LensInjector`](./index.md)`<`[`FINAL`](../-bi-di-body-lens/index.md#FINAL)`, `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>, `[`BodyLens`](../-body-lens/index.md)`<`[`FINAL`](../-bi-di-body-lens/index.md#FINAL)`>`<br>A BiDiBodyLens provides the bi-directional extraction of an entity from a target body, or the insertion of an entity into a target body. |
| [BiDiLens](../-bi-di-lens/index.md) | `class BiDiLens<in IN, FINAL> : `[`LensInjector`](./index.md)`<`[`FINAL`](../-bi-di-lens/index.md#FINAL)`, `[`IN`](../-bi-di-lens/index.md#IN)`>, `[`Lens`](../-lens/index.md)`<`[`IN`](../-bi-di-lens/index.md#IN)`, `[`FINAL`](../-bi-di-lens/index.md#FINAL)`>`<br>A BiDiLens provides the bi-directional extraction of an entity from a target, or the insertion of an entity into a target. |
| [BiDiPathLens](../-bi-di-path-lens/index.md) | `class BiDiPathLens<FINAL> : `[`LensInjector`](./index.md)`<`[`FINAL`](../-bi-di-path-lens/index.md#FINAL)`, `[`Request`](../../org.http4k.core/-request/index.md)`>, `[`PathLens`](../-path-lens/index.md)`<`[`FINAL`](../-bi-di-path-lens/index.md#FINAL)`>` |
| [Companion](../../org.http4k.core/-request-context/-companion/index.md) | `companion object Companion : `[`LensExtractor`](../-lens-extractor/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`UUID`](http://docs.oracle.com/javase/6/docs/api/java/util/UUID.html)`>, `[`LensInjector`](./index.md)`<`[`UUID`](http://docs.oracle.com/javase/6/docs/api/java/util/UUID.html)`, `[`Request`](../../org.http4k.core/-request/index.md)`>` |
| [Store](../../org.http4k.core/-store/index.md) | `interface Store<OUT> : `[`LensInjector`](./index.md)`<`[`OUT`](../../org.http4k.core/-store/index.md#OUT)`, `[`Request`](../../org.http4k.core/-request/index.md)`>, `[`LensExtractor`](../-lens-extractor/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`OUT`](../../org.http4k.core/-store/index.md#OUT)`>` |
