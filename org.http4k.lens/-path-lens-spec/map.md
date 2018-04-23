[http4k](../../index.md) / [org.http4k.lens](../index.md) / [PathLensSpec](index.md) / [map](./map.md)

# map

`fun <NEXT> map(nextIn: (`[`OUT`](index.md#OUT)`) -> `[`NEXT`](map.md#NEXT)`): `[`PathLensSpec`](index.md)`<`[`NEXT`](map.md#NEXT)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/path.kt#L53)

Create another PathLensSpec which applies the uni-directional transformation to the result. Any resultant Lens can only be
used to extract the final type from a target path segment.

