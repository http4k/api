[http4k](../../index.md) / [org.http4k.contract](../index.md) / [PathSegments](./index.md)

# PathSegments

`sealed class PathSegments` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/PathSegments.kt#L5)

### Properties

| Name | Summary |
|---|---|
| [parent](parent.md) | `abstract val parent: `[`PathSegments`](./index.md) |

### Functions

| Name | Summary |
|---|---|
| [div](div.md) | `operator fun div(child: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`PathSegments`](./index.md)<br>`operator fun div(child: `[`PathSegments`](./index.md)`): `[`PathSegments`](./index.md) |
| [startsWith](starts-with.md) | `abstract fun startsWith(other: `[`PathSegments`](./index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [toList](to-list.md) | `abstract fun toList(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(str: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`PathSegments`](./index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [Root](../-root/index.md) | `object Root : `[`PathSegments`](./index.md) |
| [Slash](../-slash/index.md) | `data class Slash : `[`PathSegments`](./index.md) |
