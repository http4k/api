[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ResponseFilters](../index.md) / [ReportLatency](./index.md)

# ReportLatency

`object ~~ReportLatency~~` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ResponseFilters.kt#L48)
**Deprecated:** Use ReportHttpTransaction instead

Measure and report the latency of a request to the passed function.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(clock: Clock = Clock.systemUTC(), recordFn: (`[`Request`](../../../org.http4k.core/-request/index.md)`, `[`Response`](../../../org.http4k.core/-response/index.md)`, Duration) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
