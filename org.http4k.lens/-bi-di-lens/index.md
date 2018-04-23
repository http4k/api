[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiLens](./index.md)

# BiDiLens

`class BiDiLens<in IN, FINAL> : `[`LensInjector`](../-lens-injector/index.md)`<`[`FINAL`](index.md#FINAL)`, `[`IN`](index.md#IN)`>, `[`Lens`](../-lens/index.md)`<`[`IN`](index.md#IN)`, `[`FINAL`](index.md#FINAL)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/lens.kt#L25)

A BiDiLens provides the bi-directional extraction of an entity from a target, or the insertion of an entity
into a target.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BiDiLens(meta: `[`Meta`](../-meta/index.md)`, get: (`[`IN`](index.md#IN)`) -> `[`FINAL`](index.md#FINAL)`, lensSet: (`[`FINAL`](index.md#FINAL)`, `[`IN`](index.md#IN)`) -> `[`IN`](index.md#IN)`)`<br>A BiDiLens provides the bi-directional extraction of an entity from a target, or the insertion of an entity into a target. |

### Inherited Properties

| Name | Summary |
|---|---|
| [meta](../-lens/meta.md) | `val meta: `[`Meta`](../-meta/index.md) |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun <R : `[`IN`](index.md#IN)`> invoke(value: `[`FINAL`](index.md#FINAL)`, target: `[`R`](invoke.md#R)`): `[`R`](invoke.md#R)<br>Lens operation to set the value into the target |

### Inherited Functions

| Name | Summary |
|---|---|
| [inject](../-lens-injector/inject.md) | `open fun <R : `[`OUT`](../-lens-injector/index.md#OUT)`> inject(value: `[`IN`](../-lens-injector/index.md#IN)`, target: `[`R`](../-lens-injector/inject.md#R)`): `[`R`](../-lens-injector/inject.md#R)<br>Lens operation to set the value into the target. Synomym for invoke(IN, OUT) |
| [invoke](../-lens/invoke.md) | `open operator fun invoke(target: `[`IN`](../-lens/index.md#IN)`): `[`FINAL`](../-lens/index.md#FINAL)<br>Lens operation to get the value from the target |
| [iterator](../-lens/iterator.md) | `open fun iterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`Meta`](../-meta/index.md)`>` |
| [of](../-lens-injector/of.md) | `open infix fun <R : `[`OUT`](../-lens-injector/index.md#OUT)`> of(value: `[`IN`](../-lens-injector/index.md#IN)`): (`[`R`](../-lens-injector/of.md#R)`) -> `[`R`](../-lens-injector/of.md#R)<br>Bind this Lens to a value, so we can set it into a target |
| [set](../-lens-injector/set.md) | `open operator fun <R : `[`OUT`](../-lens-injector/index.md#OUT)`> set(target: `[`R`](../-lens-injector/set.md#R)`, value: `[`IN`](../-lens-injector/index.md#IN)`): `[`R`](../-lens-injector/set.md#R)<br>Lens operation to set the value into the target. Synomym for invoke(IN, OUT) |
