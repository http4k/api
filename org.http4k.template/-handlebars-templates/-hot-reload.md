[http4k](../../index.md) / [org.http4k.template](../index.md) / [HandlebarsTemplates](index.md) / [HotReload](./-hot-reload.md)

# HotReload

`fun HotReload(baseTemplateDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md)

Hot-reloads (no-caching) templates from a file path

### Parameters

`baseTemplateDir` - the root path to load templates from`fun HotReload(firstBaseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, secondBaseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, vararg rest: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md)

Hot-reloads (no-caching) templates from a file path

### Parameters

`firstBaseDir` - the first dir to load templates from

`secondBaseDir` - the second dir to load templates from

`rest` - the rest