[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [TrafficFilters](../index.md) / [ServeCachedFrom](./index.md)

# ServeCachedFrom

`object ServeCachedFrom` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/TrafficFilters.kt#L12)

Responds to requests with a stored Response if possible, or falls back to the next Http Handler

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(source: `[`Source`](../../../org.http4k.traffic/-source/index.md)`): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
