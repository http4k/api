[http4k](../../index.md) / [org.http4k.format](../index.md) / [Xml](./index.md)

# Xml

`object Xml` [(source)](https://github.com/http4k/http4k/blob/master/http4k-format-xml/src/main/kotlin/org/http4k/format/Xml.kt#L25)

### Functions

| Name | Summary |
|---|---|
| [asA](as-a.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asA(): `[`T`](as-a.md#T) |
| [asXmlDocument](as-xml-document.md) | `fun `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asXmlDocument(): `[`Document`](https://kotlinlang.org/api/latest/jvm/stdlib/org.w3c.dom/-document/index.html) |
| [asXmlString](as-xml-string.md) | `fun `[`Document`](https://kotlinlang.org/api/latest/jvm/stdlib/org.w3c.dom/-document/index.html)`.asXmlString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [asXmlToJsonElement](as-xml-to-json-element.md) | `fun `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asXmlToJsonElement(): JsonElement` |
| [xml](xml.md) | `fun <IN> `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](xml.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.xml(): `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](xml.md#IN)`, `[`Document`](https://kotlinlang.org/api/latest/jvm/stdlib/org.w3c.dom/-document/index.html)`>` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [auto](auto.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> Body.Companion.auto(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = None): `[`BodyLensSpec`](../../org.http4k.lens/-body-lens-spec/index.md)`<`[`T`](auto.md#T)`>` |
| [xml](xml.md) | `fun Body.Companion.xml(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = ContentNegotiation.None): `[`BiDiBodyLensSpec`](../../org.http4k.lens/-bi-di-body-lens-spec/index.md)`<`[`Document`](https://kotlinlang.org/api/latest/jvm/stdlib/org.w3c.dom/-document/index.html)`>` |
