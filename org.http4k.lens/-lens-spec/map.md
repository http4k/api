[http4k](../../index.md) / [org.http4k.lens](../index.md) / [LensSpec](index.md) / [map](./map.md)

# map

`fun <NEXT> map(nextIn: (`[`OUT`](index.md#OUT)`) -> `[`NEXT`](map.md#NEXT)`): `[`LensSpec`](index.md)`<`[`IN`](index.md#IN)`, `[`NEXT`](map.md#NEXT)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/lensSpec.kt#L55)

Create another LensSpec which applies the uni-directional transformation to the result. Any resultant Lens can only be
used to extract the final type from a target.

