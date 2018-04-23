[http4k](../../index.md) / [org.http4k.lens](../index.md) / [WsMessageLensSpec](index.md) / [map](./map.md)

# map

`fun <NEXT> map(nextIn: (`[`OUT`](index.md#OUT)`) -> `[`NEXT`](map.md#NEXT)`): `[`WsMessageLensSpec`](index.md)`<`[`NEXT`](map.md#NEXT)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/wsMessageLens.kt#L21)

Create another WsMessageLensSpec which applies the uni-directional transformation to the result. Any resultant Lens can only be used to extract the final type from a WsMessage.

