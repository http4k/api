[http4k](../index.md) / [org.http4k.filter](./index.md)

## Package org.http4k.filter

### Types

| Name | Summary |
|---|---|
| [CacheControlHeaderPart](-cache-control-header-part/index.md) | `open class CacheControlHeaderPart` |
| [CachingFilters](-caching-filters/index.md) | `object CachingFilters`<br>Useful filters for applying Cache-Controls to request/responses |
| [CanonicalPayload](-canonical-payload/index.md) | `data class CanonicalPayload` |
| [ClientFilters](-client-filters/index.md) | `object ClientFilters` |
| [CorsPolicy](-cors-policy/index.md) | `data class CorsPolicy` |
| [DebuggingFilters](-debugging-filters/index.md) | `object DebuggingFilters` |
| [DefaultCacheTimings](-default-cache-timings/index.md) | `data class DefaultCacheTimings` |
| [GenerateDataClasses](-generate-data-classes/index.md) | `class GenerateDataClasses<ROOT : `[`NODE`](-generate-data-classes/index.md#NODE)`, out NODE> : `[`Filter`](../org.http4k.core/-filter/index.md)<br>This Filter is used to generate Data class definitions from a Response containing JSON. The Filter will try and reduce the number of class definitions by selecting the definition with the most fields (for cases where lists of items have different fields). |
| [GenerateXmlDataClasses](-generate-xml-data-classes/index.md) | `class GenerateXmlDataClasses : `[`Filter`](../org.http4k.core/-filter/index.md) |
| [MaxAgeTtl](-max-age-ttl/index.md) | `data class MaxAgeTtl : `[`CacheControlHeaderPart`](-cache-control-header-part/index.md) |
| [MetricFilters](-metric-filters/index.md) | `object MetricFilters` |
| [Payload](-payload/index.md) | `object Payload` |
| [RequestFilters](-request-filters/index.md) | `object RequestFilters` |
| [ResilienceFilters](-resilience-filters/index.md) | `object ResilienceFilters` |
| [ResponseFilters](-response-filters/index.md) | `object ResponseFilters` |
| [ServerFilters](-server-filters/index.md) | `object ServerFilters` |
| [StaleIfErrorTtl](-stale-if-error-ttl/index.md) | `data class StaleIfErrorTtl : `[`CacheControlHeaderPart`](-cache-control-header-part/index.md) |
| [StaleWhenRevalidateTtl](-stale-when-revalidate-ttl/index.md) | `data class StaleWhenRevalidateTtl : `[`CacheControlHeaderPart`](-cache-control-header-part/index.md) |
| [TraceId](-trace-id/index.md) | `data class TraceId` |
| [TrafficFilters](-traffic-filters/index.md) | `object TrafficFilters` |
| [ZipkinTraces](-zipkin-traces/index.md) | `data class ZipkinTraces` |

### Type Aliases

| Name | Summary |
|---|---|
| [HttpTransactionLabeller](-http-transaction-labeller.md) | `typealias HttpTransactionLabeller = (`[`HttpTransaction`](../org.http4k.core/-http-transaction/index.md)`) -> `[`HttpTransaction`](../org.http4k.core/-http-transaction/index.md) |

### Functions

| Name | Summary |
|---|---|
| [AwsAuth](-aws-auth.md) | `fun `[`ClientFilters`](-client-filters/index.md)`.AwsAuth(scope: `[`AwsCredentialScope`](../org.http4k.aws/-aws-credential-scope/index.md)`, credentials: `[`AwsCredentials`](../org.http4k.aws/-aws-credentials/index.md)`, clock: Clock = Clock.systemDefaultZone(), payloadMode: `[`Mode`](-payload/-mode/index.md)` = Payload.Mode.Signed): `[`Filter`](../org.http4k.core/-filter/index.md) |
| [gunzipped](gunzipped.md) | `fun `[`Body`](../org.http4k.core/-body/index.md)`.gunzipped(): `[`Body`](../org.http4k.core/-body/index.md) |
| [gzipped](gzipped.md) | `fun `[`Body`](../org.http4k.core/-body/index.md)`.gzipped(): `[`Body`](../org.http4k.core/-body/index.md) |
