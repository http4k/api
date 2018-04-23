[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ServerFilters](../index.md) / [CatchAll](./index.md)

# CatchAll

`object CatchAll` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ServerFilters.kt#L139)

Last gasp filter which catches all exceptions and returns a formatted Internal Server Error.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(errorStatus: `[`Status`](../../../org.http4k.core/-status/index.md)` = INTERNAL_SERVER_ERROR): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
