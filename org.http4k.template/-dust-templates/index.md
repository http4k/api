[http4k](../../index.md) / [org.http4k.template](../index.md) / [DustTemplates](./index.md)

# DustTemplates

`class DustTemplates : `[`Templates`](../-templates/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-template-dust/src/main/kotlin/org/http4k/template/DustTemplates.kt#L9)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `DustTemplates(precachePoolSize: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0, dustPluginScripts: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`URL`](http://docs.oracle.com/javase/6/docs/api/java/net/URL.html)`> = emptyList())` |

### Functions

| Name | Summary |
|---|---|
| [Caching](-caching.md) | `fun Caching(baseTemplateDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md)<br>Load and caches templates from a file path |
| [CachingClasspath](-caching-classpath.md) | `fun CachingClasspath(baseClasspathPackage: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md)<br>Loads and caches templates from the compiled classpath |
| [HotReload](-hot-reload.md) | `fun HotReload(baseTemplateDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md)<br>Hot-reloads (no-caching) templates from a file path |
