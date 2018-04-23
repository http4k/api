[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ServerFilters](../index.md) / [GZip](./index.md)

# GZip

`object GZip` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ServerFilters.kt#L171)

Basic GZip and Gunzip support of Request/Response. Does not currently support GZipping streams.
Only Gunzips requests which contain "transfer-encoding" header containing 'gzip'
Only Gzips responses when request contains "accept-encoding" header containing 'gzip'.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
