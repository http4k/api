[http4k](../../index.md) / [org.http4k.core](../index.md) / [Body](index.md) / [length](./length.md)

# length

`abstract val length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/http.kt#L27)

Important: As body's length is not always known (e.g. if streaming is activated in the server or client),
attempting to retrieve this property can result in an IllegalStateException.

### Exceptions

`IllegalStateException` - 