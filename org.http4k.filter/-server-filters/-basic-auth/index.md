[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ServerFilters](../index.md) / [BasicAuth](./index.md)

# BasicAuth

`object BasicAuth` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ServerFilters.kt#L86)

Simple Basic Auth credential checking.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(realm: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, authorize: (`[`Credentials`](../../../org.http4k.core/-credentials/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Filter`](../../../org.http4k.core/-filter/index.md)<br>`operator fun invoke(realm: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, user: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, password: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Filter`](../../../org.http4k.core/-filter/index.md)<br>`operator fun invoke(realm: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, credentials: `[`Credentials`](../../../org.http4k.core/-credentials/index.md)`): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
