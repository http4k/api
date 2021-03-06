[http4k](../../index.md) / [org.http4k.core](../index.md) / [Body](./index.md)

# Body

`interface Body : `[`Closeable`](https://docs.oracle.com/javase/9/docs/api/java/io/Closeable.html)

If this Body is NOT being returned to the caller (via a Server implementation or otherwise), close() should be
called.

### Properties

| Name | Summary |
|---|---|
| [length](length.md) | Will be `null` for bodies where it's impossible to a priori determine - e.g. StreamBody`abstract val length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [payload](payload.md) | `abstract val payload: `[`ByteBuffer`](https://docs.oracle.com/javase/9/docs/api/java/nio/ByteBuffer.html) |
| [stream](stream.md) | `abstract val stream: `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [EMPTY](-e-m-p-t-y.md) | `val EMPTY: `[`Body`](./index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(body: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Body`](./index.md)<br>`operator fun invoke(body: `[`ByteBuffer`](https://docs.oracle.com/javase/9/docs/api/java/nio/ByteBuffer.html)`): `[`Body`](./index.md)<br>`operator fun invoke(body: `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html)`, length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`? = null): `[`Body`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [gunzipped](../../org.http4k.filter/gunzipped.md) | `fun `[`Body`](./index.md)`.gunzipped(): `[`Body`](./index.md) |
| [gunzippedStream](../../org.http4k.filter/gunzipped-stream.md) | `fun `[`Body`](./index.md)`.gunzippedStream(): `[`Body`](./index.md) |
| [gzipped](../../org.http4k.filter/gzipped.md) | `fun `[`Body`](./index.md)`.gzipped(): `[`CompressionResult`](../../org.http4k.filter/-compression-result/index.md) |
| [gzippedStream](../../org.http4k.filter/gzipped-stream.md) | `fun `[`Body`](./index.md)`.gzippedStream(): `[`CompressionResult`](../../org.http4k.filter/-compression-result/index.md) |

### Companion Object Extension Functions

| Name | Summary |
|---|---|
| [binary](../../org.http4k.lens/binary.md) | `fun Body.Companion.binary(contentType: `[`ContentType`](../-content-type/index.md)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = None): <ERROR CLASS>` |
| [multipartForm](../../org.http4k.lens/multipart-form.md) | `fun Body.Companion.multipartForm(validator: `[`Validator`](../../org.http4k.lens/-validator/index.md)`, vararg parts: `[`Lens`](../../org.http4k.lens/-lens/index.md)`<`[`MultipartForm`](../../org.http4k.lens/-multipart-form/index.md)`, *>, defaultBoundary: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = MULTIPART_BOUNDARY, diskThreshold: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = DEFAULT_DISK_THRESHOLD, contentTypeFn: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`ContentType`](../-content-type/index.md)` = ::MultipartFormWithBoundary): `[`BiDiBodyLensSpec`](../../org.http4k.lens/-bi-di-body-lens-spec/index.md)`<`[`MultipartForm`](../../org.http4k.lens/-multipart-form/index.md)`>` |
| [nonEmptyString](../../org.http4k.lens/non-empty-string.md) | `fun Body.Companion.nonEmptyString(contentType: `[`ContentType`](../-content-type/index.md)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = None): <ERROR CLASS>` |
| [regex](../../org.http4k.lens/regex.md) | `fun Body.Companion.regex(pattern: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, group: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 1, contentType: `[`ContentType`](../-content-type/index.md)` = ContentType.TEXT_PLAIN, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = None): <ERROR CLASS>` |
| [string](../../org.http4k.lens/string.md) | `fun Body.Companion.string(contentType: `[`ContentType`](../-content-type/index.md)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = None): <ERROR CLASS>` |
| [viewModel](../../org.http4k.template/view-model.md) | `fun Body.Companion.viewModel(renderer: `[`TemplateRenderer`](../../org.http4k.template/-template-renderer.md)`, contentType: `[`ContentType`](../-content-type/index.md)`): <ERROR CLASS>` |
| [webForm](../../org.http4k.lens/web-form.md) | `fun Body.Companion.webForm(validator: `[`Validator`](../../org.http4k.lens/-validator/index.md)`, vararg formFields: `[`Lens`](../../org.http4k.lens/-lens/index.md)`<`[`WebForm`](../../org.http4k.lens/-web-form/index.md)`, *>): `[`BiDiBodyLensSpec`](../../org.http4k.lens/-bi-di-body-lens-spec/index.md)`<`[`WebForm`](../../org.http4k.lens/-web-form/index.md)`>` |

### Inheritors

| Name | Summary |
|---|---|
| [MemoryBody](../-memory-body/index.md) | Represents a body that is backed by an in-memory ByteBuffer. Closing this has no effect.`data class MemoryBody : `[`Body`](./index.md) |
| [MultipartFormBody](../-multipart-form-body/index.md) | Represents a Multi-part that is backed by a stream, which should be closed after handling the content. The gotchas which apply to StreamBody also apply here..`data class MultipartFormBody : `[`Body`](./index.md)`, `[`Closeable`](https://docs.oracle.com/javase/9/docs/api/java/io/Closeable.html) |
| [StreamBody](../-stream-body/index.md) | Represents a body that is backed by a (lazy) InputStream. Operating with StreamBody has a number of potential gotchas:`class StreamBody : `[`Body`](./index.md) |
