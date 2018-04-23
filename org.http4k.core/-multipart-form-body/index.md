[http4k](../../index.md) / [org.http4k.core](../index.md) / [MultipartFormBody](./index.md)

# MultipartFormBody

`data class MultipartFormBody : `[`Body`](../-body/index.md)`, `[`Closeable`](http://docs.oracle.com/javase/6/docs/api/java/io/Closeable.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-multipart/src/main/kotlin/org/http4k/core/MultipartFormBody.kt#L47)

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
| [length](length.md) | `val length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [payload](payload.md) | `val payload: `[`ByteBuffer`](http://docs.oracle.com/javase/6/docs/api/java/nio/ByteBuffer.html) |
| [stream](stream.md) | `val stream: `[`InputStream`](http://docs.oracle.com/javase/6/docs/api/java/io/InputStream.html) |

### Functions

| Name | Summary |
|---|---|
| [close](close.md) | `fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [field](field.md) | `fun field(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [fields](fields.md) | `fun fields(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [file](file.md) | `fun file(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`FormFile`](../-form-file/index.md)`?` |
| [files](files.md) | `fun files(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`FormFile`](../-form-file/index.md)`>` |
| [plus](plus.md) | `fun plus(field: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`MultipartFormBody`](./index.md)<br>`fun plus(field: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`FormFile`](../-form-file/index.md)`>): `[`MultipartFormBody`](./index.md) |
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
| [gzipped](../../org.http4k.filter/gzipped.md) | `fun `[`Body`](../-body/index.md)`.gzipped(): `[`Body`](../-body/index.md) |
