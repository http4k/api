[http4k](../index.md) / [org.http4k.filter](./index.md)

## Package org.http4k.filter

This is the base package for all Filter implementations.

### Types

| Name | Summary |
|---|---|
| [AllowAllOriginPolicy](-allow-all-origin-policy/index.md) | `object AllowAllOriginPolicy : `[`OriginPolicy`](-origin-policy.md) |
| [CacheControlHeaderPart](-cache-control-header-part/index.md) | `open class CacheControlHeaderPart` |
| [CachingFilters](-caching-filters/index.md) | Useful filters for applying Cache-Controls to request/responses`object CachingFilters` |
| [CanonicalPayload](-canonical-payload/index.md) | `data class CanonicalPayload` |
| [ClientFilters](-client-filters/index.md) | `object ClientFilters` |
| [CompressionResult](-compression-result/index.md) | `data class CompressionResult` |
| [CorsPolicy](-cors-policy/index.md) | `data class CorsPolicy` |
| [DebuggingFilters](-debugging-filters/index.md) | `object DebuggingFilters` |
| [DefaultCacheTimings](-default-cache-timings/index.md) | `data class DefaultCacheTimings` |
| [GzipCompressionMode](-gzip-compression-mode/index.md) | `sealed class GzipCompressionMode` |
| [HttpTransactionLabeler](-http-transaction-labeler.md) | `typealias HttpTransactionLabeler = (`[`HttpTransaction`](../org.http4k.core/-http-transaction/index.md)`) -> `[`HttpTransaction`](../org.http4k.core/-http-transaction/index.md) |
| [MaxAgeTtl](-max-age-ttl/index.md) | `data class MaxAgeTtl : `[`CacheControlHeaderPart`](-cache-control-header-part/index.md) |
| [MicrometerMetrics](-micrometer-metrics/index.md) | `class MicrometerMetrics` |
| [OpenTelemetryMetrics](-open-telemetry-metrics/index.md) | `class OpenTelemetryMetrics` |
| [OriginPolicy](-origin-policy.md) | For creating custom origin policy for allowing CORS`interface OriginPolicy : (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [Payload](-payload/index.md) | `object Payload` |
| [RequestFilters](-request-filters/index.md) | `object RequestFilters` |
| [ResilienceFilters](-resilience-filters/index.md) | `object ResilienceFilters` |
| [ResponseFilters](-response-filters/index.md) | `object ResponseFilters` |
| [SamplingDecision](-sampling-decision/index.md) | `data class SamplingDecision` |
| [ServerFilters](-server-filters/index.md) | `object ServerFilters` |
| [StaleIfErrorTtl](-stale-if-error-ttl/index.md) | `data class StaleIfErrorTtl : `[`CacheControlHeaderPart`](-cache-control-header-part/index.md) |
| [StaleWhenRevalidateTtl](-stale-when-revalidate-ttl/index.md) | `data class StaleWhenRevalidateTtl : `[`CacheControlHeaderPart`](-cache-control-header-part/index.md) |
| [TraceId](-trace-id/index.md) | `data class TraceId` |
| [TrafficFilters](-traffic-filters/index.md) | `object TrafficFilters` |
| [ZipkinTraces](-zipkin-traces/index.md) | `data class ZipkinTraces` |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.Function1](kotlin.-function1/index.md) |  |

### Properties

| Name | Summary |
|---|---|
| [MicrometerMetrics](-micrometer-metrics.md) | `val `[`ClientFilters`](-client-filters/index.md)`.MicrometerMetrics: `[`MicrometerMetrics`](-micrometer-metrics/index.md)<br>`val `[`ServerFilters`](-server-filters/index.md)`.MicrometerMetrics: `[`MicrometerMetrics`](-micrometer-metrics/index.md) |
| [OpenTelemetryMetrics](-open-telemetry-metrics.md) | `val `[`ClientFilters`](-client-filters/index.md)`.OpenTelemetryMetrics: `[`OpenTelemetryMetrics`](-open-telemetry-metrics/index.md)<br>`val `[`ServerFilters`](-server-filters/index.md)`.OpenTelemetryMetrics: `[`OpenTelemetryMetrics`](-open-telemetry-metrics/index.md) |

### Functions

| Name | Summary |
|---|---|
| [Assert](-assert.md) | Perform an assertThat on the incoming Request as a Filter operation`fun `[`RequestFilters`](-request-filters/index.md)`.Assert(matcher: Matcher<`[`Request`](../org.http4k.core/-request/index.md)`>): <ERROR CLASS>`<br>Perform an assertThat on the outgoing Response as a Filter operation`fun `[`ResponseFilters`](-response-filters/index.md)`.Assert(matcher: Matcher<`[`Response`](../org.http4k.core/-response/index.md)`>): <ERROR CLASS>`<br>Perform an assertion on the incoming Request as a Filter operation`fun `[`RequestFilters`](-request-filters/index.md)`.Assert(match: Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>): <ERROR CLASS>`<br>Perform an assertion on the outgoing Response as a Filter operation`fun `[`ResponseFilters`](-response-filters/index.md)`.Assert(match: Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>): <ERROR CLASS>` |
| [AwsAuth](-aws-auth.md) | Sign AWS requests using static credentials.`fun `[`ClientFilters`](-client-filters/index.md)`.AwsAuth(scope: `[`AwsCredentialScope`](../org.http4k.aws/-aws-credential-scope/index.md)`, credentials: `[`AwsCredentials`](../org.http4k.aws/-aws-credentials/index.md)`, clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = Clock.systemDefaultZone(), payloadMode: Mode = Payload.Mode.Signed): <ERROR CLASS>`<br>Sign AWS requests using dynamically provided (expiring) credentials.`fun `[`ClientFilters`](-client-filters/index.md)`.AwsAuth(scope: `[`AwsCredentialScope`](../org.http4k.aws/-aws-credential-scope/index.md)`, credentialsProvider: () -> `[`AwsCredentials`](../org.http4k.aws/-aws-credentials/index.md)`, clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = Clock.systemDefaultZone(), payloadMode: Mode = Payload.Mode.Signed): <ERROR CLASS>` |
| [gunzipped](gunzipped.md) | `fun `[`Body`](../org.http4k.core/-body/index.md)`.gunzipped(): `[`Body`](../org.http4k.core/-body/index.md) |
| [gunzippedStream](gunzipped-stream.md) | `fun `[`Body`](../org.http4k.core/-body/index.md)`.gunzippedStream(): `[`Body`](../org.http4k.core/-body/index.md) |
| [gzipped](gzipped.md) | `fun `[`Body`](../org.http4k.core/-body/index.md)`.gzipped(): `[`CompressionResult`](-compression-result/index.md) |
| [gzippedStream](gzipped-stream.md) | `fun `[`Body`](../org.http4k.core/-body/index.md)`.gzippedStream(): `[`CompressionResult`](-compression-result/index.md) |
| [HandleRemoteRequestFailed](-handle-remote-request-failed.md) | Handle exceptions from remote calls and convert them into sensible server-side errors. Optionally pass in a function to format the response body from the exception.`fun `[`ServerFilters`](-server-filters/index.md)`.HandleRemoteRequestFailed(exceptionToBody: `[`RemoteRequestFailed`](../org.http4k.cloudnative/-remote-request-failed/index.md)`.() -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = Throwable::getLocalizedMessage): `[`Filter`](../org.http4k.core/-filter.md)<br>Convert errors from remote calls into exceptions which can be handled at a higher level. Optionally pass in:`fun `[`ClientFilters`](-client-filters/index.md)`.HandleRemoteRequestFailed(responseWasSuccessful: `[`Response`](../org.http4k.core/-response/index.md)`.() -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { status.successful }, responseToMessage: `[`Response`](../org.http4k.core/-response/index.md)`.() -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = Response::bodyString): <ERROR CLASS>` |
| [inIntelliJOnly](in-intelli-j-only.md) | `fun `[`Filter`](../org.http4k.core/-filter.md)`.inIntelliJOnly(): `[`Filter`](../org.http4k.core/-filter.md) |
| [OpenTelemetryTracing](-open-telemetry-tracing.md) | `fun `[`ClientFilters`](-client-filters/index.md)`.OpenTelemetryTracing(tracer: Tracer = Http4kOpenTelemetry.tracer, spanNamer: (`[`Request`](../org.http4k.core/-request/index.md)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = { it.uri.toString() }, error: (`[`Request`](../org.http4k.core/-request/index.md)`, `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = { _, t -> t.localizedMessage }): `[`Filter`](../org.http4k.core/-filter.md)<br>`fun `[`ServerFilters`](-server-filters/index.md)`.OpenTelemetryTracing(tracer: Tracer = Http4kOpenTelemetry.tracer, spanNamer: (`[`Request`](../org.http4k.core/-request/index.md)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = { it.uri.toString() }, error: (`[`Request`](../org.http4k.core/-request/index.md)`, `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = { _, t -> t.localizedMessage }): `[`Filter`](../org.http4k.core/-filter.md) |
| [ProcessFiles](-process-files.md) | Process files on upload using the passed consumer, which returns a reference. The form file is replaced in the form with this reference.`fun `[`ServerFilters`](-server-filters/index.md)`.ProcessFiles(fileConsumer: (File) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): <ERROR CLASS>` |
| [SetAwsServiceUrl](-set-aws-service-url.md) | `fun `[`ClientFilters`](-client-filters/index.md)`.SetAwsServiceUrl(serviceName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, region: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Filter`](../org.http4k.core/-filter.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [AllowAll](-allow-all.md) | Allows all origins for CORS`fun OriginPolicy.Companion.AllowAll(): `[`AllowAllOriginPolicy`](-allow-all-origin-policy/index.md) |
| [AnyOf](-any-of.md) | Allows a given list of origins for CORS`fun OriginPolicy.Companion.AnyOf(allowedOrigins: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`OriginPolicy`](-origin-policy.md)<br>`fun OriginPolicy.Companion.AnyOf(vararg allowedOrigins: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`OriginPolicy`](-origin-policy.md) |
| [Only](-only.md) | Allows a given single origin for CORS`fun OriginPolicy.Companion.Only(allowedOrigin: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`OriginPolicy`](-origin-policy.md) |
| [Pattern](-pattern.md) | Allows origin(s) matching a Regex for CORS`fun OriginPolicy.Companion.Pattern(originRegex: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)`): `[`OriginPolicy`](-origin-policy.md) |
