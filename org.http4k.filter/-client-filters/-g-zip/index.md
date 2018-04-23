[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ClientFilters](../index.md) / [GZip](./index.md)

# GZip

`object GZip` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ClientFilters.kt#L117)

Basic GZip and Gunzip support of Request/Response. Does not currently support GZipping streams.
Only Gunzip responses when the response contains "transfer-encoding" header containing 'gzip'

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
