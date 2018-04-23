[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ResilienceFilters](../index.md) / [Bulkheading](index.md) / [invoke](./invoke.md)

# invoke

`operator fun invoke(bulkhead: Bulkhead = Bulkhead.ofDefaults("Bulkhead"), onError: () -> `[`Response`](../../../org.http4k.core/-response/index.md)` = { Response(TOO_MANY_REQUESTS.description("Bulkhead limit exceeded")) }): `[`Filter`](../../../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-resilience4j/src/main/kotlin/org/http4k/filter/ResilienceFilters.kt#L88)