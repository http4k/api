[http4k](../../index.md) / [org.http4k.lens](../index.md) / [Failure](./index.md)

# Failure

`sealed class Failure` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/lensFailure.kt#L16)

### Types

| Name | Summary |
|---|---|
| [Type](-type/index.md) | `enum class Type` |

### Properties

| Name | Summary |
|---|---|
| [meta](meta.md) | `abstract val meta: `[`Meta`](../-meta/index.md) |
| [type](type.md) | `val type: `[`Type`](-type/index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [Invalid](../-invalid/index.md) | `data class Invalid : `[`Failure`](./index.md) |
| [Missing](../-missing/index.md) | `data class Missing : `[`Failure`](./index.md) |
| [Unsupported](../-unsupported/index.md) | `data class Unsupported : `[`Failure`](./index.md) |
