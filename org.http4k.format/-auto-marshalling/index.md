[http4k](../../index.md) / [org.http4k.format](../index.md) / [AutoMarshalling](./index.md)

# AutoMarshalling

`abstract class AutoMarshalling`

Common base type for all format libraries which can convert directly from String -&gt; Classes

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Common base type for all format libraries which can convert directly from String -&gt; Classes`AutoMarshalling()` |

### Functions

| Name | Summary |
|---|---|
| [asA](as-a.md) | `abstract fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<T>): T`<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): T`<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asA(target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<T>): T` |
| [asFormatString](as-format-string.md) | `abstract fun asFormatString(input: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [asInputStream](as-input-stream.md) | `fun asInputStream(input: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html) |

### Inheritors

| Name | Summary |
|---|---|
| [AutoMarshallingJson](../-auto-marshalling-json/index.md) | `abstract class AutoMarshallingJson<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`AutoMarshalling`](./index.md)`, `[`Json`](../-json/index.md)`<NODE>` |
| [AutoMarshallingXml](../-auto-marshalling-xml/index.md) | `abstract class AutoMarshallingXml : `[`AutoMarshalling`](./index.md) |
| [ConfigurableJacksonYaml](../-configurable-jackson-yaml/index.md) | `open class ConfigurableJacksonYaml : `[`AutoMarshalling`](./index.md) |
| [ConfigurableKlaxon](../-configurable-klaxon/index.md) | `open class ConfigurableKlaxon : `[`AutoMarshalling`](./index.md) |
| [ConfigurableMoshi](../-configurable-moshi/index.md) | `open class ConfigurableMoshi : `[`AutoMarshalling`](./index.md) |
