[http4k](../../../../index.md) / [org.http4k.filter](../../../index.md) / [CachingFilters](../../index.md) / [Response](../index.md) / [AddETag](./index.md)

# AddETag

`object AddETag`

Hash algo stolen from http://stackoverflow.com/questions/26423662/scalatra-response-hmac-calulation
By default, only applies when the status code of the response is &lt; 400. This is overridable.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(predicate: (`[`Response`](../../../../org.http4k.core/-response/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { it.status.code < 400 }): `[`Filter`](../../../../org.http4k.core/-filter.md) |
