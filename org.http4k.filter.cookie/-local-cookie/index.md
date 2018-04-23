[http4k](../../index.md) / [org.http4k.filter.cookie](../index.md) / [LocalCookie](./index.md)

# LocalCookie

`data class LocalCookie` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/cookie/clientCookies.kt#L9)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `LocalCookie(cookie: `[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`, created: LocalDateTime)` |

### Properties

| Name | Summary |
|---|---|
| [cookie](cookie.md) | `val cookie: `[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md) |

### Functions

| Name | Summary |
|---|---|
| [isExpired](is-expired.md) | `fun isExpired(now: LocalDateTime): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
