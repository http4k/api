[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiBodyLens](./index.md)

# BiDiBodyLens

`class BiDiBodyLens<FINAL> : `[`LensInjector`](../-lens-injector/index.md)`<`[`FINAL`](index.md#FINAL)`, `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>, `[`BodyLens`](../-body-lens/index.md)`<`[`FINAL`](index.md#FINAL)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/body.kt#L31)

A BiDiBodyLens provides the bi-directional extraction of an entity from a target body, or the insertion of an entity
into a target body.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BiDiBodyLens(metas: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Meta`](../-meta/index.md)`>, contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`, get: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`FINAL`](index.md#FINAL)`, setLens: (`[`FINAL`](index.md#FINAL)`, `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`)`<br>A BiDiBodyLens provides the bi-directional extraction of an entity from a target body, or the insertion of an entity into a target body. |

### Inherited Properties

| Name | Summary |
|---|---|
| [contentType](../-body-lens/content-type.md) | `val contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md) |
| [metas](../-body-lens/metas.md) | `val metas: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Meta`](../-meta/index.md)`>` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun <R : `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`> invoke(value: `[`FINAL`](index.md#FINAL)`, target: `[`R`](invoke.md#R)`): `[`R`](invoke.md#R)<br>Lens operation to set the value into the target |

### Inherited Functions

| Name | Summary |
|---|---|
| [inject](../-lens-injector/inject.md) | `open fun <R : `[`OUT`](../-lens-injector/index.md#OUT)`> inject(value: `[`IN`](../-lens-injector/index.md#IN)`, target: `[`R`](../-lens-injector/inject.md#R)`): `[`R`](../-lens-injector/inject.md#R)<br>Lens operation to set the value into the target. Synomym for invoke(IN, OUT) |
| [invoke](../-body-lens/invoke.md) | `open operator fun invoke(target: `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`): `[`FINAL`](../-body-lens/index.md#FINAL)<br>Lens operation to get the value from the target |
| [of](../-lens-injector/of.md) | `open infix fun <R : `[`OUT`](../-lens-injector/index.md#OUT)`> of(value: `[`IN`](../-lens-injector/index.md#IN)`): (`[`R`](../-lens-injector/of.md#R)`) -> `[`R`](../-lens-injector/of.md#R)<br>Bind this Lens to a value, so we can set it into a target |
| [set](../-lens-injector/set.md) | `open operator fun <R : `[`OUT`](../-lens-injector/index.md#OUT)`> set(target: `[`R`](../-lens-injector/set.md#R)`, value: `[`IN`](../-lens-injector/index.md#IN)`): `[`R`](../-lens-injector/set.md#R)<br>Lens operation to set the value into the target. Synomym for invoke(IN, OUT) |
