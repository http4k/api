[http4k](../index.md) / [org.http4k](index.md) / [ProcessFiles](./-process-files.md)

# ProcessFiles

`fun `[`ServerFilters`](../org.http4k.filter/-server-filters/index.md)`.ProcessFiles(fileConsumer: (`[`File`](../org.http4k.core/-multipart-entity/-file/index.md)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Filter`](../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-multipart/src/main/kotlin/org/http4k/ext.kt#L15)

Process files on upload using the passed consumer, which returns a reference.
The form file is replaced in the form with this reference.

