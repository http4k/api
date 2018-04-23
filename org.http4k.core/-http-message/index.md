[http4k](../../index.md) / [org.http4k.core](../index.md) / [HttpMessage](./index.md)

# HttpMessage

`interface HttpMessage : `[`Closeable`](http://docs.oracle.com/javase/6/docs/api/java/io/Closeable.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/http.kt#L82)

### Properties

| Name | Summary |
|---|---|
| [body](body.md) | `abstract val body: `[`Body`](../-body/index.md) |
| [headers](headers.md) | `abstract val headers: `[`Headers`](../-headers.md) |
| [version](version.md) | `abstract val version: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [body](body.md) | `abstract fun body(body: `[`Body`](../-body/index.md)`): `[`HttpMessage`](./index.md)<br>`abstract fun body(body: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`HttpMessage`](./index.md)<br>`abstract fun body(body: `[`InputStream`](http://docs.oracle.com/javase/6/docs/api/java/io/InputStream.html)`, length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`? = null): `[`HttpMessage`](./index.md) |
| [bodyString](body-string.md) | `open fun bodyString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>This will realise any underlying stream |
| [close](close.md) | `open fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [header](header.md) | `open fun header(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>`abstract fun header(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`HttpMessage`](./index.md) |
| [headerValues](header-values.md) | `open fun headerValues(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>` |
| [headers](headers.md) | `abstract fun headers(headers: `[`Headers`](../-headers.md)`): `[`HttpMessage`](./index.md) |
| [removeHeader](remove-header.md) | `abstract fun removeHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`HttpMessage`](./index.md) |
| [replaceHeader](replace-header.md) | `abstract fun replaceHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`HttpMessage`](./index.md) |
| [toMessage](to-message.md) | `abstract fun toMessage(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [HTTP_1_1](-h-t-t-p_1_1.md) | `const val HTTP_1_1: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [HTTP_2](-h-t-t-p_2.md) | `const val HTTP_2: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [multipartIterator](../multipart-iterator.md) | `fun `[`HttpMessage`](./index.md)`.multipartIterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`MultipartEntity`](../-multipart-entity/index.md)`>` |

### Inheritors

| Name | Summary |
|---|---|
| [Request](../-request/index.md) | `interface Request : `[`HttpMessage`](./index.md) |
| [Response](../-response/index.md) | `interface Response : `[`HttpMessage`](./index.md) |
