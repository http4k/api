[http4k](../../index.md) / [org.http4k.filter](../index.md) / [MetricFilters](index.md) / [Server](./-server.md)

# Server

`object Server : `[`FiltersTemplate`](-filters-template/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-metrics-micrometer/src/main/kotlin/org/http4k/filter/MetricFilters.kt#L38)

### Inherited Functions

| Name | Summary |
|---|---|
| [RequestCounter](-filters-template/-request-counter.md) | `fun RequestCounter(meterRegistry: MeterRegistry, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = defaultCounter.first, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = defaultCounter.second, labeller: `[`HttpTransactionLabeller`](../-http-transaction-labeller.md)` = defaultLabeller): `[`Filter`](../../org.http4k.core/-filter/index.md) |
| [RequestTimer](-filters-template/-request-timer.md) | `fun RequestTimer(meterRegistry: MeterRegistry, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = defaultTimer.first, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = defaultTimer.second, labeller: `[`HttpTransactionLabeller`](../-http-transaction-labeller.md)` = defaultLabeller, clock: Clock = Clock.systemUTC()): `[`Filter`](../../org.http4k.core/-filter/index.md) |
