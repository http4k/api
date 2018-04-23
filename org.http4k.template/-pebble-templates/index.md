[http4k](../../index.md) / [org.http4k.template](../index.md) / [PebbleTemplates](./index.md)

# PebbleTemplates

`class PebbleTemplates : `[`Templates`](../-templates/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-template-pebble/src/main/kotlin/org/http4k/template/PebbleTemplates.kt#L10)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `PebbleTemplates(configure: (Builder) -> Builder = { it }, classLoader: `[`ClassLoader`](http://docs.oracle.com/javase/6/docs/api/java/lang/ClassLoader.html)` = ClassLoader.getSystemClassLoader())` |

### Functions

| Name | Summary |
|---|---|
| [Caching](-caching.md) | `fun Caching(baseTemplateDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md)<br>Load and caches templates from a file path |
| [CachingClasspath](-caching-classpath.md) | `fun CachingClasspath(baseClasspathPackage: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md)<br>Loads and caches templates from the compiled classpath |
| [HotReload](-hot-reload.md) | `fun HotReload(baseTemplateDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md)<br>Hot-reloads (no-caching) templates from a file path |
