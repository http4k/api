[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ResilienceFilters](../index.md) / [RetryFailures](index.md) / [invoke](./invoke.md)

# invoke

`operator fun invoke(retry: Retry = ofDefaults("Retrying"), isError: (`[`Response`](../../../org.http4k.core/-response/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { it.status.serverError }): <ERROR CLASS>`