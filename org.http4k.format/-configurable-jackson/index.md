[http4k](../../index.md) / [org.http4k.format](../index.md) / [ConfigurableJackson](./index.md)

# ConfigurableJackson

`open class ConfigurableJackson : `[`JsonLibAutoMarshallingJson`](../-json-lib-auto-marshalling-json/index.md)`<JsonNode>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-format-jackson/src/main/kotlin/org/http4k/format/Jackson.kt#L27)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ConfigurableJackson(mapper: ObjectMapper)` |

### Functions

| Name | Summary |
|---|---|
| [asA](as-a.md) | `open fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(s: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, c: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](as-a.md#T)`>): `[`T`](as-a.md#T)<br>`open fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(j: JsonNode, c: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](as-a.md#T)`>): `[`T`](as-a.md#T)<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asA(): `[`T`](as-a.md#T)<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> JsonNode.asA(): `[`T`](as-a.md#T) |
| [asCompactJsonString](as-compact-json-string.md) | `open fun JsonNode.asCompactJsonString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [asJsonArray](as-json-array.md) | `open fun <T : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<JsonNode>> `[`T`](as-json-array.md#T)`.asJsonArray(): JsonNode` |
| [asJsonObject](as-json-object.md) | `open fun `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asJsonObject(): JsonNode`<br>`open fun <LIST : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, JsonNode>>> `[`LIST`](as-json-object.md#LIST)`.asJsonObject(): JsonNode`<br>`open fun asJsonObject(a: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): JsonNode` |
| [asJsonValue](as-json-value.md) | `open fun `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?.asJsonValue(): JsonNode`<br>`open fun `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?.asJsonValue(): JsonNode`<br>`open fun `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`?.asJsonValue(): JsonNode`<br>`open fun `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?.asJsonValue(): JsonNode`<br>`open fun `[`BigDecimal`](http://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`?.asJsonValue(): JsonNode`<br>`open fun `[`BigInteger`](http://docs.oracle.com/javase/6/docs/api/java/math/BigInteger.html)`?.asJsonValue(): JsonNode`<br>`open fun `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?.asJsonValue(): JsonNode` |
| [asPrettyJsonString](as-pretty-json-string.md) | `open fun JsonNode.asPrettyJsonString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [elements](elements.md) | `open fun elements(value: JsonNode): `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<JsonNode>` |
| [fields](fields.md) | `open fun fields(node: JsonNode): `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, JsonNode>>` |
| [text](text.md) | `open fun text(value: JsonNode): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [typeOf](type-of.md) | `open fun typeOf(value: JsonNode): `[`JsonType`](../-json-type/index.md) |

### Inherited Functions

| Name | Summary |
|---|---|
| [asA](../-json-lib-auto-marshalling-json/as-a.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`ROOT`](../-json-lib-auto-marshalling-json/index.md#ROOT)`.asA(c: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](../-json-lib-auto-marshalling-json/as-a.md#T)`>): `[`T`](../-json-lib-auto-marshalling-json/as-a.md#T) |
| [asJsonObject](../-json-lib-auto-marshalling-json/as-json-object.md) | `fun `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`.asJsonObject(): `[`ROOT`](../-json-lib-auto-marshalling-json/index.md#ROOT) |
| [asJsonString](../-json-lib-auto-marshalling-json/as-json-string.md) | `open fun asJsonString(a: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [auto](auto.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> Body.Companion.auto(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = ContentNegotiation.None): `[`BiDiBodyLensSpec`](../../org.http4k.lens/-bi-di-body-lens-spec/index.md)`<`[`T`](auto.md#T)`>`<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> WsMessage.Companion.auto(): `[`BiDiWsMessageLensSpec`](../../org.http4k.lens/-bi-di-ws-message-lens-spec/index.md)`<`[`T`](auto.md#T)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [hasBody](../../org.http4k.hamkrest/has-body.md) | `fun <ROOT : `[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`, NODE> `[`Json`](../-json/index.md)`<`[`ROOT`](../../org.http4k.hamkrest/has-body.md#ROOT)`, `[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`>.hasBody(expected: `[`ROOT`](../../org.http4k.hamkrest/has-body.md#ROOT)`): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <ROOT : `[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`, NODE> `[`Json`](../-json/index.md)`<`[`ROOT`](../../org.http4k.hamkrest/has-body.md#ROOT)`, `[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`>.hasBody(expected: Matcher<`[`ROOT`](../../org.http4k.hamkrest/has-body.md#ROOT)`>): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <ROOT : `[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`, NODE> `[`Json`](../-json/index.md)`<`[`ROOT`](../../org.http4k.hamkrest/has-body.md#ROOT)`, `[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`>.hasBody(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>` |

### Inheritors

| Name | Summary |
|---|---|
| [Jackson](../-jackson.md) | `object Jackson : `[`ConfigurableJackson`](./index.md) |
