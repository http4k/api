[http4k](../../index.md) / [org.http4k.contract](../index.md) / [Slash](./index.md)

# Slash

`data class Slash : `[`PathSegments`](../-path-segments/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/PathSegments.kt#L27)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Slash(parent: `[`PathSegments`](../-path-segments/index.md)`, child: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [parent](parent.md) | `val parent: `[`PathSegments`](../-path-segments/index.md) |

### Functions

| Name | Summary |
|---|---|
| [startsWith](starts-with.md) | `fun startsWith(other: `[`PathSegments`](../-path-segments/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [toList](to-list.md) | `fun toList(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Inherited Functions

| Name | Summary |
|---|---|
| [div](../-path-segments/div.md) | `operator fun div(child: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`PathSegments`](../-path-segments/index.md)<br>`operator fun div(child: `[`PathSegments`](../-path-segments/index.md)`): `[`PathSegments`](../-path-segments/index.md) |
