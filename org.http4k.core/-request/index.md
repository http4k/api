[http4k](../../index.md) / [org.http4k.core](../index.md) / [Request](./index.md)

# Request

`interface Request : `[`HttpMessage`](../-http-message/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/http.kt#L122)

### Properties

| Name | Summary |
|---|---|
| [method](method.md) | `abstract val method: `[`Method`](../-method/index.md) |
| [uri](uri.md) | `abstract val uri: `[`Uri`](../-uri/index.md) |

### Inherited Properties

| Name | Summary |
|---|---|
| [body](../-http-message/body.md) | `abstract val body: `[`Body`](../-body/index.md) |
| [headers](../-http-message/headers.md) | `abstract val headers: `[`Headers`](../-headers.md) |
| [version](../-http-message/version.md) | `abstract val version: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [body](body.md) | `abstract fun body(body: `[`Body`](../-body/index.md)`): `[`Request`](./index.md)<br>`abstract fun body(body: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](./index.md)<br>`abstract fun body(body: `[`InputStream`](http://docs.oracle.com/javase/6/docs/api/java/io/InputStream.html)`, length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?): `[`Request`](./index.md) |
| [header](header.md) | `abstract fun header(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Request`](./index.md) |
| [headers](headers.md) | `abstract fun headers(headers: `[`Headers`](../-headers.md)`): `[`Request`](./index.md) |
| [method](method.md) | `abstract fun method(method: `[`Method`](../-method/index.md)`): `[`Request`](./index.md) |
| [queries](queries.md) | `abstract fun queries(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>` |
| [query](query.md) | `abstract fun query(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](./index.md)<br>`abstract fun query(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [removeHeader](remove-header.md) | `abstract fun removeHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](./index.md) |
| [replaceHeader](replace-header.md) | `abstract fun replaceHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Request`](./index.md) |
| [toMessage](to-message.md) | `open fun toMessage(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [uri](uri.md) | `abstract fun uri(uri: `[`Uri`](../-uri/index.md)`): `[`Request`](./index.md) |

### Inherited Functions

| Name | Summary |
|---|---|
| [bodyString](../-http-message/body-string.md) | `open fun bodyString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>This will realise any underlying stream |
| [close](../-http-message/close.md) | `open fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [header](../-http-message/header.md) | `open fun header(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [headerValues](../-http-message/header-values.md) | `open fun headerValues(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(method: `[`Method`](../-method/index.md)`, uri: `[`Uri`](../-uri/index.md)`, version: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = HTTP_1_1): `[`Request`](./index.md)<br>`operator fun invoke(method: `[`Method`](../-method/index.md)`, uri: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, version: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = HTTP_1_1): `[`Request`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [cookie](../../org.http4k.core.cookie/cookie.md) | `fun `[`Request`](./index.md)`.cookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](./index.md)<br>`fun `[`Request`](./index.md)`.cookie(new: `[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`): `[`Request`](./index.md)<br>`fun `[`Request`](./index.md)`.cookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`?` |
| [cookies](../../org.http4k.core.cookie/cookies.md) | `fun `[`Request`](./index.md)`.cookies(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`>` |
| [form](../../org.http4k.core.body/form.md) | `fun `[`Request`](./index.md)`.form(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>`fun `[`Request`](./index.md)`.form(): `[`Form`](../../org.http4k.core.body/-form.md)<br>`fun `[`Request`](./index.md)`.form(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](./index.md) |
| [multipartIterator](../multipart-iterator.md) | `fun `[`HttpMessage`](../-http-message/index.md)`.multipartIterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`MultipartEntity`](../-multipart-entity/index.md)`>` |
| [path](../../org.http4k.routing/path.md) | `fun `[`Request`](./index.md)`.path(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [toCurl](../to-curl.md) | `fun `[`Request`](./index.md)`.toCurl(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Extension Functions

| Name | Summary |
|---|---|
| [parse](../parse.md) | `fun Request.Companion.parse(request: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](./index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [MemoryRequest](../-memory-request/index.md) | `data class MemoryRequest : `[`Request`](./index.md) |
| [RoutedRequest](../../org.http4k.routing/-routed-request/index.md) | `data class RoutedRequest : `[`Request`](./index.md) |
