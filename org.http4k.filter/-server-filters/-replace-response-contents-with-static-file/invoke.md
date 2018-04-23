[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ServerFilters](../index.md) / [ReplaceResponseContentsWithStaticFile](index.md) / [invoke](./invoke.md)

# invoke

`operator fun invoke(loader: `[`ResourceLoader`](../../../org.http4k.routing/-resource-loader/index.md)` = Classpath(), toResourceName: (`[`Response`](../../../org.http4k.core/-response/index.md)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = { if (it.status.successful) null else it.status.code.toString() }): `[`Filter`](../../../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ServerFilters.kt#L208)