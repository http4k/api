[http4k](../../index.md) / [org.http4k.core](../index.md) / [Response](./index.md)

# Response

`interface Response : `[`HttpMessage`](../-http-message/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/http.kt#L194)

### Properties

| Name | Summary |
|---|---|
| [status](status.md) | `abstract val status: `[`Status`](../-status/index.md) |

### Inherited Properties

| Name | Summary |
|---|---|
| [body](../-http-message/body.md) | `abstract val body: `[`Body`](../-body/index.md) |
| [headers](../-http-message/headers.md) | `abstract val headers: `[`Headers`](../-headers.md) |
| [version](../-http-message/version.md) | `abstract val version: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [body](body.md) | `abstract fun body(body: `[`Body`](../-body/index.md)`): `[`Response`](./index.md)<br>`abstract fun body(body: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Response`](./index.md)<br>`abstract fun body(body: `[`InputStream`](http://docs.oracle.com/javase/6/docs/api/java/io/InputStream.html)`, length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?): `[`Response`](./index.md) |
| [header](header.md) | `abstract fun header(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Response`](./index.md) |
| [headers](headers.md) | `abstract fun headers(headers: `[`Headers`](../-headers.md)`): `[`Response`](./index.md) |
| [removeHeader](remove-header.md) | `abstract fun removeHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Response`](./index.md) |
| [replaceHeader](replace-header.md) | `abstract fun replaceHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Response`](./index.md) |
| [toMessage](to-message.md) | `open fun toMessage(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

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
| [invoke](invoke.md) | `operator fun invoke(status: `[`Status`](../-status/index.md)`, version: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = HTTP_1_1): `[`Response`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [cookie](../../org.http4k.core.cookie/cookie.md) | `fun `[`Response`](./index.md)`.cookie(cookie: `[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`): `[`Response`](./index.md) |
| [cookies](../../org.http4k.core.cookie/cookies.md) | `fun `[`Response`](./index.md)`.cookies(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`>` |
| [invalidateCookie](../../org.http4k.core.cookie/invalidate-cookie.md) | `fun `[`Response`](./index.md)`.invalidateCookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, domain: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Response`](./index.md) |
| [maxAge](../max-age.md) | `fun `[`Response`](./index.md)`.maxAge(duration: Duration): `[`Response`](./index.md) |
| [multipartIterator](../multipart-iterator.md) | `fun `[`HttpMessage`](../-http-message/index.md)`.multipartIterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`MultipartEntity`](../-multipart-entity/index.md)`>` |
| [mustRevalidate](../must-revalidate.md) | `fun `[`Response`](./index.md)`.mustRevalidate(): `[`Response`](./index.md) |
| [noCache](../no-cache.md) | `fun `[`Response`](./index.md)`.noCache(): `[`Response`](./index.md) |
| [noStore](../no-store.md) | `fun `[`Response`](./index.md)`.noStore(): `[`Response`](./index.md) |
| [onlyIfCached](../only-if-cached.md) | `fun `[`Response`](./index.md)`.onlyIfCached(): `[`Response`](./index.md) |
| [private](../private.md) | `fun `[`Response`](./index.md)`.private(): `[`Response`](./index.md) |
| [public](../public.md) | `fun `[`Response`](./index.md)`.public(): `[`Response`](./index.md) |
| [removeCookie](../../org.http4k.core.cookie/remove-cookie.md) | `fun `[`Response`](./index.md)`.removeCookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Response`](./index.md) |
| [replaceCookie](../../org.http4k.core.cookie/replace-cookie.md) | `fun `[`Response`](./index.md)`.replaceCookie(cookie: `[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`): `[`Response`](./index.md) |
| [staleIfError](../stale-if-error.md) | `fun `[`Response`](./index.md)`.staleIfError(duration: Duration): `[`Response`](./index.md) |
| [staleWhileRevalidate](../stale-while-revalidate.md) | `fun `[`Response`](./index.md)`.staleWhileRevalidate(duration: Duration): `[`Response`](./index.md) |

### Companion Object Extension Functions

| Name | Summary |
|---|---|
| [parse](../parse.md) | `fun Response.Companion.parse(response: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Response`](./index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [MemoryResponse](../-memory-response/index.md) | `data class MemoryResponse : `[`Response`](./index.md) |
| [RoutedResponse](../../org.http4k.routing/-routed-response/index.md) | `class RoutedResponse : `[`Response`](./index.md) |
