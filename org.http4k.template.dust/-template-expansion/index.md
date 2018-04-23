[http4k](../../index.md) / [org.http4k.template.dust](../index.md) / [TemplateExpansion](./index.md)

# TemplateExpansion

`interface TemplateExpansion` [(source)](https://github.com/http4k/http4k/blob/master/http4k-template-dust/src/main/kotlin/org/http4k/template/dust/Dust.kt#L17)

### Functions

| Name | Summary |
|---|---|
| [expandTemplate](expand-template.md) | `abstract fun expandTemplate(templateName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, params: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, onMissingTemplate: (templateName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)` = ::missingTemplateIllegalArgument): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [TemplateExpansionService](../-template-expansion-service.md) | `interface TemplateExpansionService : `[`AutoCloseable`](http://docs.oracle.com/javase/6/docs/api/java/lang/AutoCloseable.html)`, `[`TemplateExpansion`](./index.md) |
