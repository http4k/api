[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [RequestFilters](../index.md) / [Tap](./index.md)

# Tap

`object Tap` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/RequestFilters.kt#L11)

Intercept the request before it is sent to the next service.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(fn: (`[`Request`](../../../org.http4k.core/-request/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
