[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ClientFilters](../index.md) / [BasicAuth](./index.md)

# BasicAuth

`object BasicAuth` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ClientFilters.kt#L52)

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(provider: () -> `[`Credentials`](../../../org.http4k.core/-credentials/index.md)`): `[`Filter`](../../../org.http4k.core/-filter/index.md)<br>`operator fun invoke(user: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, password: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Filter`](../../../org.http4k.core/-filter/index.md)<br>`operator fun invoke(credentials: `[`Credentials`](../../../org.http4k.core/-credentials/index.md)`): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
