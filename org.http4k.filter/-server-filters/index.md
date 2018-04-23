[http4k](../../index.md) / [org.http4k.filter](../index.md) / [ServerFilters](./index.md)

# ServerFilters

`object ServerFilters` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ServerFilters.kt#L39)

### Types

| Name | Summary |
|---|---|
| [BasicAuth](-basic-auth/index.md) | `object BasicAuth`<br>Simple Basic Auth credential checking. |
| [CatchAll](-catch-all/index.md) | `object CatchAll`<br>Last gasp filter which catches all exceptions and returns a formatted Internal Server Error. |
| [CatchLensFailure](-catch-lens-failure.md) | `object CatchLensFailure : `[`Filter`](../../org.http4k.core/-filter/index.md)<br>Converts Lens extraction failures into correct HTTP responses (Bad Requests/UnsupportedMediaType). This is required when using lenses to automatically unmarshall inbound requests. Note that LensFailures from unmarshalling upstream Response objects are NOT caught to avoid incorrect server behaviour. |
| [CopyHeaders](-copy-headers/index.md) | `object CopyHeaders`<br>Copy headers from the incoming request to the outbound response. |
| [Cors](-cors/index.md) | `object Cors`<br>Add Cors headers to the Response, according to the passed CorsPolicy |
| [GZip](-g-zip/index.md) | `object GZip`<br>Basic GZip and Gunzip support of Request/Response. Does not currently support GZipping streams. Only Gunzips requests which contain "transfer-encoding" header containing 'gzip' Only Gzips responses when request contains "accept-encoding" header containing 'gzip'. |
| [InitialiseRequestContext](-initialise-request-context/index.md) | `object InitialiseRequestContext`<br>Initialise a RequestContext for each request which passes through the Filter stack, |
| [ReplaceResponseContentsWithStaticFile](-replace-response-contents-with-static-file/index.md) | `object ReplaceResponseContentsWithStaticFile`<br>Intercepts responses and replaces the contents with contents of the statically loaded resource. By default, this Filter replaces the contents of unsuccessful requests with the contents of a file named after the status code. |
| [RequestTracing](-request-tracing/index.md) | `object RequestTracing`<br>Adds Zipkin request tracing headers to the incoming request and outbound response. (traceid, spanid, parentspanid) |
| [SetContentType](-set-content-type/index.md) | `object SetContentType`<br>Sets the Content Type response header on the Response. |

### Functions

| Name | Summary |
|---|---|
| [CatchLensFailure](-catch-lens-failure.md) | `fun CatchLensFailure(failResponseFn: (`[`LensFailure`](../../org.http4k.lens/-lens-failure/index.md)`) -> `[`Response`](../../org.http4k.core/-response/index.md)` = {
        Response(BAD_REQUEST.description(it.failures.joinToString("; ")))
    }): `[`Filter`](../../org.http4k.core/-filter/index.md)<br>Converts Lens extraction failures into correct HTTP responses (Bad Requests/UnsupportedMediaType). This is required when using lenses to automatically unmarshall inbound requests. Note that LensFailures from unmarshalling upstream Response objects are NOT caught to avoid incorrect server behaviour. |

### Extension Functions

| Name | Summary |
|---|---|
| [ProcessFiles](../../org.http4k/-process-files.md) | `fun `[`ServerFilters`](./index.md)`.ProcessFiles(fileConsumer: (`[`File`](../../org.http4k.core/-multipart-entity/-file/index.md)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Filter`](../../org.http4k.core/-filter/index.md)<br>Process files on upload using the passed consumer, which returns a reference. The form file is replaced in the form with this reference. |
