[http4k](../../../index.md) / [org.http4k.routing.experimental](../../index.md) / [ResourceLoaders](../index.md) / [Classpath](./index.md)

# Classpath

`object Classpath`

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(basePackagePath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/", mimeTypes: `[`MimeTypes`](../../../org.http4k.core/-mime-types/index.md)` = MimeTypes(), constantLastModified: `[`Instant`](https://docs.oracle.com/javase/9/docs/api/java/time/Instant.html)`? = Instant.now().truncatedTo(SECONDS), lastModifiedFinder: (path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`Instant`](https://docs.oracle.com/javase/9/docs/api/java/time/Instant.html)`? = { constantLastModified }): `[`Router`](../../../org.http4k.routing/-router/index.md) |
