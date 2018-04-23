[http4k](../../index.md) / [org.http4k.format](../index.md) / [Json](./index.md)

# Json

`interface Json<ROOT : `[`NODE`](index.md#NODE)`, NODE>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/format/Json.kt#L22)

This is the contract for all JSON implementations

### Functions

| Name | Summary |
|---|---|
| [array](array.md) | `open fun <T : `[`NODE`](index.md#NODE)`> array(value: `[`T`](array.md#T)`): `[`ROOT`](index.md#ROOT)<br>`open fun <T : `[`NODE`](index.md#NODE)`> array(value: `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`T`](array.md#T)`>): `[`ROOT`](index.md#ROOT) |
| [asCompactJsonString](as-compact-json-string.md) | `abstract fun `[`ROOT`](index.md#ROOT)`.asCompactJsonString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [asJsonArray](as-json-array.md) | `abstract fun <T : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`NODE`](index.md#NODE)`>> `[`T`](as-json-array.md#T)`.asJsonArray(): `[`ROOT`](index.md#ROOT) |
| [asJsonObject](as-json-object.md) | `abstract fun `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asJsonObject(): `[`ROOT`](index.md#ROOT)<br>`abstract fun <LIST : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`NODE`](index.md#NODE)`>>> `[`LIST`](as-json-object.md#LIST)`.asJsonObject(): `[`ROOT`](index.md#ROOT) |
| [asJsonValue](as-json-value.md) | `abstract fun `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?.asJsonValue(): `[`NODE`](index.md#NODE)<br>`abstract fun `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?.asJsonValue(): `[`NODE`](index.md#NODE)<br>`abstract fun `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`?.asJsonValue(): `[`NODE`](index.md#NODE)<br>`abstract fun `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?.asJsonValue(): `[`NODE`](index.md#NODE)<br>`abstract fun `[`BigDecimal`](http://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`?.asJsonValue(): `[`NODE`](index.md#NODE)<br>`abstract fun `[`BigInteger`](http://docs.oracle.com/javase/6/docs/api/java/math/BigInteger.html)`?.asJsonValue(): `[`NODE`](index.md#NODE)<br>`abstract fun `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?.asJsonValue(): `[`NODE`](index.md#NODE) |
| [asPrettyJsonString](as-pretty-json-string.md) | `abstract fun `[`ROOT`](index.md#ROOT)`.asPrettyJsonString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [body](body.md) | `open fun body(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = None): `[`BiDiBodyLensSpec`](../../org.http4k.lens/-bi-di-body-lens-spec/index.md)`<`[`ROOT`](index.md#ROOT)`>` |
| [boolean](boolean.md) | `open fun boolean(value: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`NODE`](index.md#NODE) |
| [compact](compact.md) | `open fun compact(node: `[`ROOT`](index.md#ROOT)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [compactify](compactify.md) | `open fun compactify(s: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [elements](elements.md) | `abstract fun elements(value: `[`NODE`](index.md#NODE)`): `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`NODE`](index.md#NODE)`>` |
| [fields](fields.md) | `abstract fun fields(node: `[`NODE`](index.md#NODE)`): `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`NODE`](index.md#NODE)`>>` |
| [json](json.md) | `open fun <IN> `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](json.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.json(): `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](json.md#IN)`, `[`ROOT`](index.md#ROOT)`>` |
| [lens](lens.md) | `open fun <IN> lens(spec: `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](lens.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](lens.md#IN)`, `[`ROOT`](index.md#ROOT)`>` |
| [nullNode](null-node.md) | `open fun nullNode(): `[`NODE`](index.md#NODE) |
| [number](number.md) | `open fun number(value: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`NODE`](index.md#NODE)<br>`open fun number(value: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`NODE`](index.md#NODE)<br>`open fun number(value: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`NODE`](index.md#NODE)<br>`open fun number(value: `[`BigDecimal`](http://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`): `[`NODE`](index.md#NODE)<br>`open fun number(value: `[`BigInteger`](http://docs.oracle.com/javase/6/docs/api/java/math/BigInteger.html)`): `[`NODE`](index.md#NODE) |
| [obj](obj.md) | `open fun obj(): `[`ROOT`](index.md#ROOT)<br>`open fun <T : `[`NODE`](index.md#NODE)`> obj(value: `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`T`](obj.md#T)`>>): `[`ROOT`](index.md#ROOT)<br>`open fun <T : `[`NODE`](index.md#NODE)`> obj(vararg fields: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`T`](obj.md#T)`>): `[`ROOT`](index.md#ROOT) |
| [parse](parse.md) | `open fun parse(s: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ROOT`](index.md#ROOT) |
| [prettify](prettify.md) | `open fun prettify(s: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [pretty](pretty.md) | `open fun pretty(node: `[`ROOT`](index.md#ROOT)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [string](string.md) | `open fun string(value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`NODE`](index.md#NODE) |
| [text](text.md) | `abstract fun text(value: `[`NODE`](index.md#NODE)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [typeOf](type-of.md) | `abstract fun typeOf(value: `[`NODE`](index.md#NODE)`): `[`JsonType`](../-json-type/index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [json](json.md) | `open fun Body.Companion.json(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = None): `[`BiDiBodyLensSpec`](../../org.http4k.lens/-bi-di-body-lens-spec/index.md)`<`[`ROOT`](index.md#ROOT)`>`<br>`open fun WsMessage.Companion.json(): `[`BiDiWsMessageLensSpec`](../../org.http4k.lens/-bi-di-ws-message-lens-spec/index.md)`<`[`ROOT`](index.md#ROOT)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [hasBody](../../org.http4k.hamkrest/has-body.md) | `fun <ROOT : `[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`, NODE> `[`Json`](./index.md)`<`[`ROOT`](../../org.http4k.hamkrest/has-body.md#ROOT)`, `[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`>.hasBody(expected: `[`ROOT`](../../org.http4k.hamkrest/has-body.md#ROOT)`): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <ROOT : `[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`, NODE> `[`Json`](./index.md)`<`[`ROOT`](../../org.http4k.hamkrest/has-body.md#ROOT)`, `[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`>.hasBody(expected: Matcher<`[`ROOT`](../../org.http4k.hamkrest/has-body.md#ROOT)`>): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <ROOT : `[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`, NODE> `[`Json`](./index.md)`<`[`ROOT`](../../org.http4k.hamkrest/has-body.md#ROOT)`, `[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`>.hasBody(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>` |

### Inheritors

| Name | Summary |
|---|---|
| [Argo](../-argo/index.md) | `object Argo : `[`Json`](./index.md)`<JsonRootNode, JsonNode>` |
| [JsonLibAutoMarshallingJson](../-json-lib-auto-marshalling-json/index.md) | `abstract class JsonLibAutoMarshallingJson<ROOT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`AutoMarshallingJson`](../-auto-marshalling-json/index.md)`, `[`Json`](./index.md)`<`[`ROOT`](../-json-lib-auto-marshalling-json/index.md#ROOT)`, `[`ROOT`](../-json-lib-auto-marshalling-json/index.md#ROOT)`>` |
