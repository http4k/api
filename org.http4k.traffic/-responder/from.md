[http4k](../../index.md) / [org.http4k.traffic](../index.md) / [Responder](index.md) / [from](./from.md)

# from

`fun from(source: `[`Source`](../-source/index.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/traffic/Responder.kt#L21)

An HTTP Handler which responds to particular requests with the matching cached responses, or a 503.

`fun from(replay: `[`Replay`](../-replay/index.md)`, shouldReplay: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }): `[`HttpHandler`](../../org.http4k.core/-http-handler.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/traffic/Responder.kt#L26)

An HTTP Handler which responds to from a stream of cached responses, or a 503 once the stream is exhausted.

