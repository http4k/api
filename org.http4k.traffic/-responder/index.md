[http4k](../../index.md) / [org.http4k.traffic](../index.md) / [Responder](./index.md)

# Responder

`object Responder`

Provides HTTP Handlers which respond using pre-stored Requests.

### Functions

| Name | Summary |
|---|---|
| [from](from.md) | An HTTP Handler which responds to particular requests with the matching cached responses, or a 503.`fun from(source: `[`Source`](../-source/index.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)<br>An HTTP Handler which responds to from a stream of cached responses, or a 503 once the stream is exhausted.`fun from(replay: `[`Replay`](../-replay/index.md)`, shouldReplay: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }): `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |
