[http4k](../index.md) / [org.http4k.core.cookie](./index.md)

## Package org.http4k.core.cookie

### Types

| Name | Summary |
|---|---|
| [Cookie](-cookie/index.md) | `data class Cookie` |

### Functions

| Name | Summary |
|---|---|
| [cookie](cookie.md) | `fun `[`Response`](../org.http4k.core/-response/index.md)`.cookie(cookie: `[`Cookie`](-cookie/index.md)`): `[`Response`](../org.http4k.core/-response/index.md)<br>`fun `[`Request`](../org.http4k.core/-request/index.md)`.cookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](../org.http4k.core/-request/index.md)<br>`fun `[`Request`](../org.http4k.core/-request/index.md)`.cookie(new: `[`Cookie`](-cookie/index.md)`): `[`Request`](../org.http4k.core/-request/index.md)<br>`fun `[`Request`](../org.http4k.core/-request/index.md)`.cookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Cookie`](-cookie/index.md)`?` |
| [cookies](cookies.md) | `fun `[`Request`](../org.http4k.core/-request/index.md)`.cookies(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Cookie`](-cookie/index.md)`>`<br>`fun `[`Response`](../org.http4k.core/-response/index.md)`.cookies(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Cookie`](-cookie/index.md)`>` |
| [invalidate](invalidate.md) | `fun `[`Cookie`](-cookie/index.md)`.invalidate(): `[`Cookie`](-cookie/index.md) |
| [invalidateCookie](invalidate-cookie.md) | `fun `[`Response`](../org.http4k.core/-response/index.md)`.invalidateCookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, domain: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Response`](../org.http4k.core/-response/index.md) |
| [removeCookie](remove-cookie.md) | `fun `[`Response`](../org.http4k.core/-response/index.md)`.removeCookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Response`](../org.http4k.core/-response/index.md) |
| [replaceCookie](replace-cookie.md) | `fun `[`Response`](../org.http4k.core/-response/index.md)`.replaceCookie(cookie: `[`Cookie`](-cookie/index.md)`): `[`Response`](../org.http4k.core/-response/index.md) |
