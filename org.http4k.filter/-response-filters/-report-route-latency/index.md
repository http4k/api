[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ResponseFilters](../index.md) / [ReportRouteLatency](./index.md)

# ReportRouteLatency

`object ReportRouteLatency`

Report the latency on a particular route to a callback function.
This is useful for logging metrics. Note that the passed function blocks the response from completing.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = Clock.systemUTC(), recordFn: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Duration`](https://docs.oracle.com/javase/9/docs/api/java/time/Duration.html)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Filter`](../../../org.http4k.core/-filter.md) |
