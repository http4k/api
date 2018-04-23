[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [DebuggingFilters](../index.md) / [PrintRequest](./index.md)

# PrintRequest

`object PrintRequest` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/DebuggingFilters.kt#L15)

Print details of the request before it is sent to the next service.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(out: `[`PrintStream`](http://docs.oracle.com/javase/6/docs/api/java/io/PrintStream.html)` = System.out, debugStream: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = defaultDebugStream): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
