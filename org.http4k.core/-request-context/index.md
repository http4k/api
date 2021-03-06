[http4k](../../index.md) / [org.http4k.core](../index.md) / [RequestContext](./index.md)

# RequestContext

`class RequestContext`

### Properties

| Name | Summary |
|---|---|
| [id](id.md) | `val id: `[`UUID`](https://docs.oracle.com/javase/9/docs/api/java/util/UUID.html) |

### Functions

| Name | Summary |
|---|---|
| [get](get.md) | `operator fun <T> get(key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): T?` |
| [set](set.md) | `operator fun set(key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [lensForStore](lens-for-store.md) | `fun lensForStore(storeId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`LensInjectorExtractor`](../../org.http4k.lens/-lens-injector-extractor.md)`<`[`Request`](../-request/index.md)`, `[`UUID`](https://docs.oracle.com/javase/9/docs/api/java/util/UUID.html)`>` |
