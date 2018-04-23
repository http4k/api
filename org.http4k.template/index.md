[http4k](../index.md) / [org.http4k.template](./index.md)

## Package org.http4k.template

### Types

| Name | Summary |
|---|---|
| [DustTemplates](-dust-templates/index.md) | `class DustTemplates : `[`Templates`](-templates/index.md) |
| [HandlebarsTemplates](-handlebars-templates/index.md) | `class HandlebarsTemplates : `[`Templates`](-templates/index.md)<br>Handlebars templating support. Use the function in the constructor to configure the instance. |
| [PebbleTemplates](-pebble-templates/index.md) | `class PebbleTemplates : `[`Templates`](-templates/index.md) |
| [Templates](-templates/index.md) | `interface Templates`<br>Supported template implementations for templating engine implementations |
| [ThymeleafTemplates](-thymeleaf-templates/index.md) | `class ThymeleafTemplates : `[`Templates`](-templates/index.md) |
| [ViewModel](-view-model/index.md) | `interface ViewModel` |

### Exceptions

| Name | Summary |
|---|---|
| [ViewNotFound](-view-not-found/index.md) | `data class ViewNotFound : `[`Exception`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html) |

### Type Aliases

| Name | Summary |
|---|---|
| [TemplateRenderer](-template-renderer.md) | `typealias TemplateRenderer = (`[`ViewModel`](-view-model/index.md)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.Function1](kotlin.-function1/index.md) |  |

### Companion Object Functions

| Name | Summary |
|---|---|
| [view](view.md) | `fun Body.Companion.view(renderer: `[`TemplateRenderer`](-template-renderer.md)`, contentType: `[`ContentType`](../org.http4k.core/-content-type/index.md)`): `[`BiDiBodyLens`](../org.http4k.lens/-bi-di-body-lens/index.md)`<`[`ViewModel`](-view-model/index.md)`>` |
