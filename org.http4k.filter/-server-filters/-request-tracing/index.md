[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ServerFilters](../index.md) / [RequestTracing](./index.md)

# RequestTracing

`object RequestTracing` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ServerFilters.kt#L62)

Adds Zipkin request tracing headers to the incoming request and outbound response. (traceid, spanid, parentspanid)

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(startReportFn: (`[`Request`](../../../org.http4k.core/-request/index.md)`, `[`ZipkinTraces`](../../-zipkin-traces/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = { _, _ -> }, endReportFn: (`[`Request`](../../../org.http4k.core/-request/index.md)`, `[`Response`](../../../org.http4k.core/-response/index.md)`, `[`ZipkinTraces`](../../-zipkin-traces/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = { _, _, _ -> }): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
