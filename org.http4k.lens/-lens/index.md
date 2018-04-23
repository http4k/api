[http4k](../../index.md) / [org.http4k.lens](../index.md) / [Lens](./index.md)

# Lens

`open class Lens<in IN, out FINAL> : `[`LensExtractor`](../-lens-extractor/index.md)`<`[`IN`](index.md#IN)`, `[`FINAL`](index.md#FINAL)`>, `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Meta`](../-meta/index.md)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/lens.kt#L6)

A Lens provides the uni-directional extraction of an entity from a target.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Lens(meta: `[`Meta`](../-meta/index.md)`, lensGet: (`[`IN`](index.md#IN)`) -> `[`FINAL`](index.md#FINAL)`)`<br>A Lens provides the uni-directional extraction of an entity from a target. |

### Properties

| Name | Summary |
|---|---|
| [meta](meta.md) | `val meta: `[`Meta`](../-meta/index.md) |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `open operator fun invoke(target: `[`IN`](index.md#IN)`): `[`FINAL`](index.md#FINAL)<br>Lens operation to get the value from the target |
| [iterator](iterator.md) | `open fun iterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`Meta`](../-meta/index.md)`>` |
| [toString](to-string.md) | `open fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Inherited Functions

| Name | Summary |
|---|---|
| [extract](../-lens-extractor/extract.md) | `open fun extract(target: `[`IN`](../-lens-extractor/index.md#IN)`): `[`OUT`](../-lens-extractor/index.md#OUT)<br>Lens operation to get the value from the target. Synonym for invoke(IN) |
| [get](../-lens-extractor/get.md) | `open operator fun <R : `[`IN`](../-lens-extractor/index.md#IN)`> get(target: `[`R`](../-lens-extractor/get.md#R)`): `[`OUT`](../-lens-extractor/index.md#OUT)<br>Lens operation to get the value from the target. Synonym for invoke(IN) |

### Inheritors

| Name | Summary |
|---|---|
| [BiDiLens](../-bi-di-lens/index.md) | `class BiDiLens<in IN, FINAL> : `[`LensInjector`](../-lens-injector/index.md)`<`[`FINAL`](../-bi-di-lens/index.md#FINAL)`, `[`IN`](../-bi-di-lens/index.md#IN)`>, `[`Lens`](./index.md)`<`[`IN`](../-bi-di-lens/index.md#IN)`, `[`FINAL`](../-bi-di-lens/index.md#FINAL)`>`<br>A BiDiLens provides the bi-directional extraction of an entity from a target, or the insertion of an entity into a target. |
| [PathLens](../-path-lens/index.md) | `open class PathLens<out FINAL> : `[`Lens`](./index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`FINAL`](../-path-lens/index.md#FINAL)`>` |
