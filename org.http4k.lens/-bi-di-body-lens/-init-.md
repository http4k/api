[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiBodyLens](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`BiDiBodyLens(metas: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Meta`](../-meta/index.md)`>, contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`, get: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`FINAL`](index.md#FINAL)`, setLens: (`[`FINAL`](index.md#FINAL)`, `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`)`

A BiDiBodyLens provides the bi-directional extraction of an entity from a target body, or the insertion of an entity
into a target body.

