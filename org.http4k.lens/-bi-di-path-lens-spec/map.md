[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiPathLensSpec](index.md) / [map](./map.md)

# map

`fun <NEXT> map(nextIn: (OUT) -> NEXT, nextOut: (NEXT) -> OUT): `[`BiDiPathLensSpec`](index.md)`<NEXT>`

Create another BiDiPathLensSpec which applies the bi-directional transformations to the result. Any resultant Lens can be
used to extract or insert the final type from/into a path segment.

