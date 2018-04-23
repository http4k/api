[http4k](../../index.md) / [org.http4k.core](../index.md) / [StreamBody](./index.md)

# StreamBody

`class StreamBody : `[`Body`](../-body/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/http.kt#L59)

Represents a body that is backed by a (lazy) InputStream. Operating with StreamBody has a number of potential
gotchas:

1. Attempts to consume the stream will pull all of the contents into memory, and should thus be avoided.
This includes calling `equals()` and `payload`
2. If this Body is NOT being returned to the caller (via a Server implementation or otherwise), close() should be called.
3. Depending on the source of the stream, this body may or may not contain a known length. Attempts to get the
length when there is none will cause an IllegalStateException to be thrown.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `StreamBody(stream: `[`InputStream`](http://docs.oracle.com/javase/6/docs/api/java/io/InputStream.html)`, length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?)`<br>Represents a body that is backed by a (lazy) InputStream. Operating with StreamBody has a number of potential gotchas: |

### Properties

| Name | Summary |
|---|---|
| [length](length.md) | `val length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [payload](payload.md) | `val payload: `[`ByteBuffer`](http://docs.oracle.com/javase/6/docs/api/java/nio/ByteBuffer.html) |
| [stream](stream.md) | `val stream: `[`InputStream`](http://docs.oracle.com/javase/6/docs/api/java/io/InputStream.html) |

### Functions

| Name | Summary |
|---|---|
| [close](close.md) | `fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [equals](equals.md) | `fun equals(other: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hashCode](hash-code.md) | `fun hashCode(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [gunzipped](../../org.http4k.filter/gunzipped.md) | `fun `[`Body`](../-body/index.md)`.gunzipped(): `[`Body`](../-body/index.md) |
| [gzipped](../../org.http4k.filter/gzipped.md) | `fun `[`Body`](../-body/index.md)`.gzipped(): `[`Body`](../-body/index.md) |
