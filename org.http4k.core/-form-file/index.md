[http4k](../../index.md) / [org.http4k.core](../index.md) / [FormFile](./index.md)

# FormFile

`data class FormFile : `[`Closeable`](http://docs.oracle.com/javase/6/docs/api/java/io/Closeable.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-multipart/src/main/kotlin/org/http4k/core/FormFile.kt#L6)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `FormFile(filename: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, contentType: `[`ContentType`](../-content-type/index.md)`, content: `[`InputStream`](http://docs.oracle.com/javase/6/docs/api/java/io/InputStream.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [content](content.md) | `val content: `[`InputStream`](http://docs.oracle.com/javase/6/docs/api/java/io/InputStream.html) |
| [contentType](content-type.md) | `val contentType: `[`ContentType`](../-content-type/index.md) |
| [filename](filename.md) | `val filename: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [close](close.md) | `fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [equals](equals.md) | `fun equals(other: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hashCode](hash-code.md) | `fun hashCode(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
