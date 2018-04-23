[http4k](../../../../index.md) / [org.http4k.filter](../../../index.md) / [CachingFilters](../../index.md) / [Response](../index.md) / [NoCache](index.md) / [invoke](./invoke.md)

# invoke

`operator fun invoke(predicate: (`[`Response`](../../../../org.http4k.core/-response/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { it.status.code < 400 }): `[`Filter`](../../../../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/CachingFilters.kt#L73)