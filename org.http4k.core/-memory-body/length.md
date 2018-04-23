[http4k](../../index.md) / [org.http4k.core](../index.md) / [MemoryBody](index.md) / [length](./length.md)

# length

`val length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/http.kt#L44)

Overrides [Body.length](../-body/length.md)

Important: As body's length is not always known (e.g. if streaming is activated in the server or client),
attempting to retrieve this property can result in an IllegalStateException.

### Exceptions

`IllegalStateException` -

### Getter Exceptions

`IllegalStateException` -

**Getter**

Important: As body's length is not always known (e.g. if streaming is activated in the server or client),
attempting to retrieve this property can result in an IllegalStateException.

