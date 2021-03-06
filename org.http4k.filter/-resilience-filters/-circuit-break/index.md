[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ResilienceFilters](../index.md) / [CircuitBreak](./index.md)

# CircuitBreak

`object CircuitBreak`

Provide simple Circuit Breaker. Returns ServiceUnavailable when the circuit is open.
By default, uses a % failure rate of 50% detection and an Circuit Open period of 1minute

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(circuitBreaker: CircuitBreaker = CircuitBreaker.ofDefaults("Circuit"), isError: (`[`Response`](../../../org.http4k.core/-response/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { it.status.serverError }, onError: () -> `[`Response`](../../../org.http4k.core/-response/index.md)` = { Response(SERVICE_UNAVAILABLE.description("Circuit is open")) }): <ERROR CLASS>` |
