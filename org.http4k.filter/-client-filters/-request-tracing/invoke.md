[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ClientFilters](../index.md) / [RequestTracing](index.md) / [invoke](./invoke.md)

# invoke

`operator fun invoke(startReportFn: (`[`Request`](../../../org.http4k.core/-request/index.md)`, `[`ZipkinTraces`](../../-zipkin-traces/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = { _, _ -> }, endReportFn: (`[`Request`](../../../org.http4k.core/-request/index.md)`, `[`Response`](../../../org.http4k.core/-response/index.md)`, `[`ZipkinTraces`](../../-zipkin-traces/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = { _, _, _ -> }): `[`Filter`](../../../org.http4k.core/-filter.md)