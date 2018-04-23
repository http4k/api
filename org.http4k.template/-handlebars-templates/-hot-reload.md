[http4k](../../index.md) / [org.http4k.template](../index.md) / [HandlebarsTemplates](index.md) / [HotReload](./-hot-reload.md)

# HotReload

`fun HotReload(baseTemplateDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-template-handlebars/src/main/kotlin/org/http4k/template/HandlebarsTemplates.kt#L37)

Overrides [Templates.HotReload](../-templates/-hot-reload.md)

Hot-reloads (no-caching) templates from a file path

### Parameters

`baseTemplateDir` - the root path to load templates from`fun HotReload(firstBaseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, secondBaseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, vararg rest: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-template-handlebars/src/main/kotlin/org/http4k/template/HandlebarsTemplates.kt#L53)

Hot-reloads (no-caching) templates from a file path

### Parameters

`firstBaseDir` - the first dir to load templates from

`secondBaseDir` - the second dir to load templates from

`rest` - the rest