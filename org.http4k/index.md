[http4k](../index.md) / [org.http4k](./index.md)

## Package org.http4k

### Extensions for External Classes

| Name | Summary |
|---|---|
| [java.lang.StringBuilder](java.lang.-string-builder/index.md) |  |
| [java.nio.ByteBuffer](java.nio.-byte-buffer/index.md) |  |
| [kotlin.String](kotlin.-string/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [ProcessFiles](-process-files.md) | `fun `[`ServerFilters`](../org.http4k.filter/-server-filters/index.md)`.ProcessFiles(fileConsumer: (`[`File`](../org.http4k.core/-multipart-entity/-file/index.md)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Filter`](../org.http4k.core/-filter/index.md)<br>Process files on upload using the passed consumer, which returns a reference. The form file is replaced in the form with this reference. |
