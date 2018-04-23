[http4k](../../index.md) / [org.http4k.core.cookie](../index.md) / [Cookie](./index.md)

# Cookie

`data class Cookie` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/cookie/Cookie.kt#L11)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Cookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, maxAge: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`? = null, expires: LocalDateTime? = null, domain: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, secure: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false, httpOnly: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false)` |

### Properties

| Name | Summary |
|---|---|
| [domain](domain.md) | `val domain: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [expires](expires.md) | `val expires: LocalDateTime?` |
| [httpOnly](http-only.md) | `val httpOnly: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [maxAge](max-age.md) | `val maxAge: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [path](path.md) | `val path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [secure](secure.md) | `val secure: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [value](value.md) | `val value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [domain](domain.md) | `fun domain(domain: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Cookie`](./index.md) |
| [expires](expires.md) | `fun expires(date: LocalDateTime): `[`Cookie`](./index.md) |
| [fullCookieString](full-cookie-string.md) | `fun fullCookieString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [httpOnly](http-only.md) | `fun httpOnly(): `[`Cookie`](./index.md) |
| [keyValueCookieString](key-value-cookie-string.md) | `fun keyValueCookieString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [maxAge](max-age.md) | `fun maxAge(seconds: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Cookie`](./index.md) |
| [path](path.md) | `fun path(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Cookie`](./index.md) |
| [secure](secure.md) | `fun secure(): `[`Cookie`](./index.md) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [parse](parse.md) | `fun parse(cookieValue: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Cookie`](./index.md)`?` |

### Extension Functions

| Name | Summary |
|---|---|
| [invalidate](../invalidate.md) | `fun `[`Cookie`](./index.md)`.invalidate(): `[`Cookie`](./index.md) |
