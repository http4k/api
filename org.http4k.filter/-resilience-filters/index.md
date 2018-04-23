[http4k](../../index.md) / [org.http4k.filter](../index.md) / [ResilienceFilters](./index.md)

# ResilienceFilters

`object ResilienceFilters` [(source)](https://github.com/http4k/http4k/blob/master/http4k-resilience4j/src/main/kotlin/org/http4k/filter/ResilienceFilters.kt#L16)

### Types

| Name | Summary |
|---|---|
| [Bulkheading](-bulkheading/index.md) | `object Bulkheading`<br>Provide simple Bulkhead functionality. By default, handles 25 parallel requests, with zero wait time. |
| [CircuitBreak](-circuit-break/index.md) | `object CircuitBreak`<br>Provide simple Circuit Breaker. Returns ServiceUnavailable when the circuit is open. By default, uses a % failure rate of 50% detection and an Circuit Open period of 1minute |
| [RateLimit](-rate-limit/index.md) | `object RateLimit`<br>Provide simple Bulkhead functionality. By default, handles 25 parallel requests, with zero wait time. |
| [RetryFailures](-retry-failures/index.md) | `object RetryFailures`<br>Provide simple Retrying functionality. Returns the last response when retries expire. By default, retries 3 times with a delay of 500ms between attempts, backing off at a 1.5x multiplier. |
