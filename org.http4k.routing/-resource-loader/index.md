[http4k](../../index.md) / [org.http4k.routing](../index.md) / [ResourceLoader](./index.md)

# ResourceLoader

`interface ResourceLoader` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/routing/ResourceLoader.kt#L6)

### Functions

| Name | Summary |
|---|---|
| [load](load.md) | `abstract fun load(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`URL`](http://docs.oracle.com/javase/6/docs/api/java/net/URL.html)`?` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [Classpath](-classpath.md) | `fun Classpath(basePackagePath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/"): `[`ResourceLoader`](./index.md) |
| [Directory](-directory.md) | `fun Directory(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ResourceLoader`](./index.md) |
