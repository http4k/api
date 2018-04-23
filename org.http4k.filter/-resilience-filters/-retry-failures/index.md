[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ResilienceFilters](../index.md) / [RetryFailures](./index.md)

# RetryFailures

`object RetryFailures` [(source)](https://github.com/http4k/http4k/blob/master/http4k-resilience4j/src/main/kotlin/org/http4k/filter/ResilienceFilters.kt#L46)

Provide simple Retrying functionality. Returns the last response when retries expire.
By default, retries 3 times with a delay of 500ms between attempts, backing off at a 1.5x multiplier.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(retry: Retry = ofDefaults("Retrying"), isError: (`[`Response`](../../../org.http4k.core/-response/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { it.status.serverError }): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
