[http4k](../../../../index.md) / [org.http4k.filter](../../../index.md) / [CachingFilters](../../index.md) / [Response](../index.md) / [FallbackCacheControl](./index.md)

# FallbackCacheControl

`object FallbackCacheControl` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/CachingFilters.kt#L120)

Applies the passed cache timings (Cache-Control, Expires, Vary) to responses, but only if they are not there already.
Use this for adding default cache settings.
By default, only applies when the status code of the response is &lt; 400. This is overridable.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(clock: Clock, defaultCacheTimings: `[`DefaultCacheTimings`](../../../-default-cache-timings/index.md)`, predicate: (`[`Response`](../../../../org.http4k.core/-response/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { it.status.code < 400 }): `[`Filter`](../../../../org.http4k.core/-filter/index.md) |
