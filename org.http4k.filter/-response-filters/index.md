[http4k](../../index.md) / [org.http4k.filter](../index.md) / [ResponseFilters](./index.md)

# ResponseFilters

`object ResponseFilters` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ResponseFilters.kt#L11)

### Types

| Name | Summary |
|---|---|
| [GZip](-g-zip/index.md) | `object GZip`<br>Basic UnGZipping of Response. Does not currently support GZipping streams |
| [GunZip](-gun-zip/index.md) | `object GunZip`<br>Basic UnGZipping of Response. Does not currently support GZipping streams |
| [ReportHttpTransaction](-report-http-transaction/index.md) | `object ReportHttpTransaction`<br>General reporting Filter for an ReportHttpTransaction. Pass an optional HttpTransactionLabeller to create custom labels. This is useful for logging metrics. Note that the passed function blocks the response from completing. |
| [ReportLatency](-report-latency/index.md) | `object ~~ReportLatency~~`<br>Measure and report the latency of a request to the passed function. |
| [ReportRouteLatency](-report-route-latency/index.md) | `object ReportRouteLatency`<br>Report the latency on a particular route to a callback function. This is useful for logging metrics. Note that the passed function blocks the response from completing. |
| [Tap](-tap/index.md) | `object Tap`<br>Intercept the response after it is sent to the next service. |
