[http4k](../../index.md) / [org.http4k.core](../index.md) / [MultipartFormBody](./index.md)

# MultipartFormBody

`data class MultipartFormBody : `[`Body`](../-body/index.md)`, `[`Closeable`](https://docs.oracle.com/javase/9/docs/api/java/io/Closeable.html)

Represents a Multi-part that is backed by a stream, which should be closed after handling the content. The gotchas
which apply to StreamBody also apply here..

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `MultipartFormBody(boundary: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = UUID.randomUUID().toString())` |

### Properties

| Name | Summary |
|---|---|
| [boundary](boundary.md) | `val boundary: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [length](length.md) | Will be `null` for bodies where it's impossible to a priori determine - e.g. StreamBody`val length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [payload](payload.md) | `val payload: `[`ByteBuffer`](https://docs.oracle.com/javase/9/docs/api/java/nio/ByteBuffer.html) |
| [stream](stream.md) | `val stream: `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html) |

### Functions

| Name | Summary |
|---|---|
| [close](close.md) | `fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [field](field.md) | `fun field(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`MultipartFormField`](../../org.http4k.lens/-multipart-form-field/index.md)`?` |
| [fields](fields.md) | `fun fields(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`MultipartFormField`](../../org.http4k.lens/-multipart-form-field/index.md)`>` |
| [fieldValue](field-value.md) | `fun fieldValue(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [fieldValues](field-values.md) | `fun fieldValues(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [file](file.md) | `fun file(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`MultipartFormFile`](../../org.http4k.lens/-multipart-form-file/index.md)`?` |
| [files](files.md) | `fun files(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`MultipartFormFile`](../../org.http4k.lens/-multipart-form-file/index.md)`>` |
| [plus](plus.md) | `operator fun plus(field: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`MultipartFormBody`](./index.md)<br>`operator fun plus(field: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`MultipartFormField`](../../org.http4k.lens/-multipart-form-field/index.md)`>): `[`MultipartFormBody`](./index.md)<br>`operator fun plus(field: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`MultipartFormFile`](../../org.http4k.lens/-multipart-form-file/index.md)`>): `[`MultipartFormBody`](./index.md) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [DEFAULT_DISK_THRESHOLD](-d-e-f-a-u-l-t_-d-i-s-k_-t-h-r-e-s-h-o-l-d.md) | `const val DEFAULT_DISK_THRESHOLD: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [from](from.md) | `fun from(httpMessage: `[`HttpMessage`](../-http-message/index.md)`, diskThreshold: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = DEFAULT_DISK_THRESHOLD): `[`MultipartFormBody`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [gunzipped](../../org.http4k.filter/gunzipped.md) | `fun `[`Body`](../-body/index.md)`.gunzipped(): `[`Body`](../-body/index.md) |
| [gunzippedStream](../../org.http4k.filter/gunzipped-stream.md) | `fun `[`Body`](../-body/index.md)`.gunzippedStream(): `[`Body`](../-body/index.md) |
| [gzipped](../../org.http4k.filter/gzipped.md) | `fun `[`Body`](../-body/index.md)`.gzipped(): `[`CompressionResult`](../../org.http4k.filter/-compression-result/index.md) |
| [gzippedStream](../../org.http4k.filter/gzipped-stream.md) | `fun `[`Body`](../-body/index.md)`.gzippedStream(): `[`CompressionResult`](../../org.http4k.filter/-compression-result/index.md) |
