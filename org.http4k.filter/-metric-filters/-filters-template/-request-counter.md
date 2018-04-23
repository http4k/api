[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [MetricFilters](../index.md) / [FiltersTemplate](index.md) / [RequestCounter](./-request-counter.md)

# RequestCounter

`fun RequestCounter(meterRegistry: MeterRegistry, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = defaultCounter.first, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = defaultCounter.second, labeller: `[`HttpTransactionLabeller`](../../-http-transaction-labeller.md)` = defaultLabeller): `[`Filter`](../../../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-metrics-micrometer/src/main/kotlin/org/http4k/filter/MetricFilters.kt#L25)