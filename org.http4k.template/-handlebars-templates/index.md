[http4k](../../index.md) / [org.http4k.template](../index.md) / [HandlebarsTemplates](./index.md)

# HandlebarsTemplates

`class HandlebarsTemplates : `[`Templates`](../-templates/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-template-handlebars/src/main/kotlin/org/http4k/template/HandlebarsTemplates.kt#L15)

Handlebars templating support. Use the function in the constructor to configure the instance.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `HandlebarsTemplates(configure: (Handlebars) -> Handlebars = { it })`<br>Handlebars templating support. Use the function in the constructor to configure the instance. |

### Functions

| Name | Summary |
|---|---|
| [Caching](-caching.md) | `fun Caching(baseTemplateDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md)<br>Load and caches templates from a file path |
| [CachingClasspath](-caching-classpath.md) | `fun CachingClasspath(baseClasspathPackage: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md)<br>Loads and caches templates from the compiled classpath |
| [HotReload](-hot-reload.md) | `fun HotReload(baseTemplateDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md)<br>`fun HotReload(firstBaseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, secondBaseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, vararg rest: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md)<br>Hot-reloads (no-caching) templates from a file path |
