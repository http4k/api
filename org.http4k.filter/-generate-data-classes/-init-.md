[http4k](../../index.md) / [org.http4k.filter](../index.md) / [GenerateDataClasses](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`GenerateDataClasses(json: `[`Json`](../../org.http4k.format/-json/index.md)`<NODE>, out: `[`PrintStream`](https://docs.oracle.com/javase/9/docs/api/java/io/PrintStream.html)` = System.out, idGenerator: () -> `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = { abs(Random.nextInt()) })`

This Filter is used to generate Data class definitions from a Response containing JSON. The Filter will try and reduce
the number of class definitions by selecting the definition with the most fields (for cases where lists of items
have different fields).

