[http4k](../../index.md) / [org.http4k.core](../index.md) / [HttpTransaction](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`HttpTransaction(request: `[`Request`](../-request/index.md)`, response: `[`Response`](../-response/index.md)`, duration: Duration, labels: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = when {
        response is RoutedResponse -> mapOf(ROUTING_GROUP_LABEL to response.xUriTemplate.toString())
        request is RoutedRequest -> mapOf(ROUTING_GROUP_LABEL to request.xUriTemplate.toString())
        else -> emptyMap()
    })`