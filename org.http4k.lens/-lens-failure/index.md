[http4k](../../index.md) / [org.http4k.lens](../index.md) / [LensFailure](./index.md)

# LensFailure

`class LensFailure : `[`Exception`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/lensFailure.kt#L3)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `LensFailure(vararg failures: `[`Failure`](../-failure/index.md)`, cause: `[`Exception`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)`? = null, target: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`? = null)`<br>`LensFailure(failures: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Failure`](../-failure/index.md)`>, cause: `[`Exception`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)`? = null, target: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [cause](cause.md) | `val cause: `[`Exception`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)`?` |
| [failures](failures.md) | `val failures: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Failure`](../-failure/index.md)`>` |
| [target](target.md) | `val target: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?` |

### Functions

| Name | Summary |
|---|---|
| [overall](overall.md) | `fun overall(): `[`Type`](../-failure/-type/index.md) |
