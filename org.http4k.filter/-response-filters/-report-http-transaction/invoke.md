[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ResponseFilters](../index.md) / [ReportHttpTransaction](index.md) / [invoke](./invoke.md)

# invoke

`operator fun invoke(clock: Clock = Clock.systemUTC(), transactionLabeller: `[`HttpTransactionLabeller`](../../-http-transaction-labeller.md)` = { it }, recordFn: (`[`HttpTransaction`](../../../org.http4k.core/-http-transaction/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Filter`](../../../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ResponseFilters.kt#L33)