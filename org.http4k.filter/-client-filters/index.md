[http4k](../../index.md) / [org.http4k.filter](../index.md) / [ClientFilters](./index.md)

# ClientFilters

`object ClientFilters` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ClientFilters.kt#L21)

### Types

| Name | Summary |
|---|---|
| [BasicAuth](-basic-auth/index.md) | `object BasicAuth` |
| [Cookies](-cookies/index.md) | `object Cookies` |
| [FollowRedirects](-follow-redirects/index.md) | `object FollowRedirects` |
| [GZip](-g-zip/index.md) | `object GZip`<br>Basic GZip and Gunzip support of Request/Response. Does not currently support GZipping streams. Only Gunzip responses when the response contains "transfer-encoding" header containing 'gzip' |
| [RequestTracing](-request-tracing/index.md) | `object RequestTracing`<br>Adds Zipkin request tracing headers to the outbound request. (traceid, spanid, parentspanid) |
| [SetHostFrom](-set-host-from/index.md) | `object SetHostFrom`<br>Sets the host on an outbound request. This is useful to separate configuration of remote endpoints from the logic required to construct the rest of the request. |

### Extension Functions

| Name | Summary |
|---|---|
| [AwsAuth](../-aws-auth.md) | `fun `[`ClientFilters`](./index.md)`.AwsAuth(scope: `[`AwsCredentialScope`](../../org.http4k.aws/-aws-credential-scope/index.md)`, credentials: `[`AwsCredentials`](../../org.http4k.aws/-aws-credentials/index.md)`, clock: Clock = Clock.systemDefaultZone(), payloadMode: `[`Mode`](../-payload/-mode/index.md)` = Payload.Mode.Signed): `[`Filter`](../../org.http4k.core/-filter/index.md) |
