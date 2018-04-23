[http4k](../../index.md) / [org.http4k.template.dust](../index.md) / [Dust](./index.md)

# Dust

`class Dust` [(source)](https://github.com/http4k/http4k/blob/master/http4k-template-dust/src/main/kotlin/org/http4k/template/dust/Dust.kt#L110)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Dust(cacheTemplates: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, precachePoolSize: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, dustPluginScripts: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`URL`](http://docs.oracle.com/javase/6/docs/api/java/net/URL.html)`>, loader: `[`TemplateLoader`](../-template-loader.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [openTemplates](open-templates.md) | `fun openTemplates(): `[`TemplateExpansionService`](../-template-expansion-service.md) |
| [withTemplates](with-templates.md) | `fun <T> withTemplates(block: (`[`TemplateExpansion`](../-template-expansion/index.md)`) -> `[`T`](with-templates.md#T)`): `[`T`](with-templates.md#T) |
