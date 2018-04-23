[http4k](../../index.md) / [org.http4k.template](../index.md) / [Templates](./index.md)

# Templates

`interface Templates` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/template/Templates.kt#L16)

Supported template implementations for templating engine implementations

### Functions

| Name | Summary |
|---|---|
| [Caching](-caching.md) | `abstract fun Caching(baseTemplateDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "./"): `[`TemplateRenderer`](../-template-renderer.md)<br>Load and caches templates from a file path |
| [CachingClasspath](-caching-classpath.md) | `abstract fun CachingClasspath(baseClasspathPackage: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = ""): `[`TemplateRenderer`](../-template-renderer.md)<br>Loads and caches templates from the compiled classpath |
| [HotReload](-hot-reload.md) | `abstract fun HotReload(baseTemplateDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "./"): `[`TemplateRenderer`](../-template-renderer.md)<br>Hot-reloads (no-caching) templates from a file path |

### Inheritors

| Name | Summary |
|---|---|
| [DustTemplates](../-dust-templates/index.md) | `class DustTemplates : `[`Templates`](./index.md) |
| [HandlebarsTemplates](../-handlebars-templates/index.md) | `class HandlebarsTemplates : `[`Templates`](./index.md)<br>Handlebars templating support. Use the function in the constructor to configure the instance. |
| [PebbleTemplates](../-pebble-templates/index.md) | `class PebbleTemplates : `[`Templates`](./index.md) |
| [ThymeleafTemplates](../-thymeleaf-templates/index.md) | `class ThymeleafTemplates : `[`Templates`](./index.md) |
