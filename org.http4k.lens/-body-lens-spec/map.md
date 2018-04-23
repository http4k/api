[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BodyLensSpec](index.md) / [map](./map.md)

# map

`fun <NEXT> map(nextIn: (`[`OUT`](index.md#OUT)`) -> `[`NEXT`](map.md#NEXT)`): `[`BodyLensSpec`](index.md)`<`[`NEXT`](map.md#NEXT)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/body.kt#L56)

Create another BodyLensSpec which applies the uni-directional transformation to the result. Any resultant Lens can only be
used to extract the final type from a Body.

