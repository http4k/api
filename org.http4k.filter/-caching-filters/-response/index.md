[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [CachingFilters](../index.md) / [Response](./index.md)

# Response

`object Response` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/CachingFilters.kt#L55)

These filters operate on Responses (post-flight)

### Types

| Name | Summary |
|---|---|
| [AddETag](-add-e-tag/index.md) | `object AddETag`<br>Hash algo stolen from http://stackoverflow.com/questions/26423662/scalatra-response-hmac-calulation By default, only applies when the status code of the response is &lt; 400. This is overridable. |
| [FallbackCacheControl](-fallback-cache-control/index.md) | `object FallbackCacheControl`<br>Applies the passed cache timings (Cache-Control, Expires, Vary) to responses, but only if they are not there already. Use this for adding default cache settings. By default, only applies when the status code of the response is &lt; 400. This is overridable. |
| [MaxAge](-max-age/index.md) | `object MaxAge`<br>By default, only applies when the status code of the response is &lt; 400. This is overridable. |
| [NoCache](-no-cache/index.md) | `object NoCache`<br>By default, only applies when the status code of the response is &lt; 400. This is overridable and useful - For example you could combine this with a MaxAge for everything &gt;= 400 |
