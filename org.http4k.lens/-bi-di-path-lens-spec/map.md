[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiPathLensSpec](index.md) / [map](./map.md)

# map

`fun <NEXT> map(nextIn: (`[`OUT`](index.md#OUT)`) -> `[`NEXT`](map.md#NEXT)`, nextOut: (`[`NEXT`](map.md#NEXT)`) -> `[`OUT`](index.md#OUT)`): `[`BiDiPathLensSpec`](index.md)`<`[`NEXT`](map.md#NEXT)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/path.kt#L64)

Create another BiDiPathLensSpec which applies the bi-directional transformations to the result. Any resultant Lens can be
used to extract or insert the final type from/into a path segment.

