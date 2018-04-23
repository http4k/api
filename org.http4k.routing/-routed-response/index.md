[http4k](../../index.md) / [org.http4k.routing](../index.md) / [RoutedResponse](./index.md)

# RoutedResponse

`class RoutedResponse : `[`Response`](../../org.http4k.core/-response/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/routing/routing.kt#L123)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RoutedResponse(delegate: `[`Response`](../../org.http4k.core/-response/index.md)`, xUriTemplate: `[`UriTemplate`](../../org.http4k.core/-uri-template/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [xUriTemplate](x-uri-template.md) | `val xUriTemplate: `[`UriTemplate`](../../org.http4k.core/-uri-template/index.md) |

### Functions

| Name | Summary |
|---|---|
| [body](body.md) | `fun body(body: `[`Body`](../../org.http4k.core/-body/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md)<br>`fun body(body: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Response`](../../org.http4k.core/-response/index.md)<br>`fun body(body: `[`InputStream`](http://docs.oracle.com/javase/6/docs/api/java/io/InputStream.html)`, length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?): `[`Response`](../../org.http4k.core/-response/index.md) |
| [equals](equals.md) | `fun equals(other: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hashCode](hash-code.md) | `fun hashCode(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [header](header.md) | `fun header(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Response`](../../org.http4k.core/-response/index.md) |
| [removeHeader](remove-header.md) | `fun removeHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Response`](../../org.http4k.core/-response/index.md) |
| [replaceHeader](replace-header.md) | `fun replaceHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Response`](../../org.http4k.core/-response/index.md) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [cookie](../../org.http4k.core.cookie/cookie.md) | `fun `[`Response`](../../org.http4k.core/-response/index.md)`.cookie(cookie: `[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |
| [cookies](../../org.http4k.core.cookie/cookies.md) | `fun `[`Response`](../../org.http4k.core/-response/index.md)`.cookies(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`>` |
| [invalidateCookie](../../org.http4k.core.cookie/invalidate-cookie.md) | `fun `[`Response`](../../org.http4k.core/-response/index.md)`.invalidateCookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, domain: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Response`](../../org.http4k.core/-response/index.md) |
| [maxAge](../../org.http4k.core/max-age.md) | `fun `[`Response`](../../org.http4k.core/-response/index.md)`.maxAge(duration: Duration): `[`Response`](../../org.http4k.core/-response/index.md) |
| [multipartIterator](../../org.http4k.core/multipart-iterator.md) | `fun `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`.multipartIterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`MultipartEntity`](../../org.http4k.core/-multipart-entity/index.md)`>` |
| [mustRevalidate](../../org.http4k.core/must-revalidate.md) | `fun `[`Response`](../../org.http4k.core/-response/index.md)`.mustRevalidate(): `[`Response`](../../org.http4k.core/-response/index.md) |
| [noCache](../../org.http4k.core/no-cache.md) | `fun `[`Response`](../../org.http4k.core/-response/index.md)`.noCache(): `[`Response`](../../org.http4k.core/-response/index.md) |
| [noStore](../../org.http4k.core/no-store.md) | `fun `[`Response`](../../org.http4k.core/-response/index.md)`.noStore(): `[`Response`](../../org.http4k.core/-response/index.md) |
| [onlyIfCached](../../org.http4k.core/only-if-cached.md) | `fun `[`Response`](../../org.http4k.core/-response/index.md)`.onlyIfCached(): `[`Response`](../../org.http4k.core/-response/index.md) |
| [private](../../org.http4k.core/private.md) | `fun `[`Response`](../../org.http4k.core/-response/index.md)`.private(): `[`Response`](../../org.http4k.core/-response/index.md) |
| [public](../../org.http4k.core/public.md) | `fun `[`Response`](../../org.http4k.core/-response/index.md)`.public(): `[`Response`](../../org.http4k.core/-response/index.md) |
| [removeCookie](../../org.http4k.core.cookie/remove-cookie.md) | `fun `[`Response`](../../org.http4k.core/-response/index.md)`.removeCookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Response`](../../org.http4k.core/-response/index.md) |
| [replaceCookie](../../org.http4k.core.cookie/replace-cookie.md) | `fun `[`Response`](../../org.http4k.core/-response/index.md)`.replaceCookie(cookie: `[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |
| [staleIfError](../../org.http4k.core/stale-if-error.md) | `fun `[`Response`](../../org.http4k.core/-response/index.md)`.staleIfError(duration: Duration): `[`Response`](../../org.http4k.core/-response/index.md) |
| [staleWhileRevalidate](../../org.http4k.core/stale-while-revalidate.md) | `fun `[`Response`](../../org.http4k.core/-response/index.md)`.staleWhileRevalidate(duration: Duration): `[`Response`](../../org.http4k.core/-response/index.md) |
