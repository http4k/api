[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ResilienceFilters](../index.md) / [CircuitBreak](index.md) / [invoke](./invoke.md)

# invoke

`operator fun invoke(circuitBreaker: CircuitBreaker = CircuitBreaker.ofDefaults("Circuit"), isError: (`[`Response`](../../../org.http4k.core/-response/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { it.status.serverError }, onError: () -> `[`Response`](../../../org.http4k.core/-response/index.md)` = { Response(SERVICE_UNAVAILABLE.description("Circuit is open")) }): `[`Filter`](../../../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-resilience4j/src/main/kotlin/org/http4k/filter/ResilienceFilters.kt#L25)