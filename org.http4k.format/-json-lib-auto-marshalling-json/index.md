[http4k](../../index.md) / [org.http4k.format](../index.md) / [JsonLibAutoMarshallingJson](./index.md)

# JsonLibAutoMarshallingJson

`abstract class JsonLibAutoMarshallingJson<ROOT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`AutoMarshallingJson`](../-auto-marshalling-json/index.md)`, `[`Json`](../-json/index.md)`<`[`ROOT`](index.md#ROOT)`, `[`ROOT`](index.md#ROOT)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/format/AutoMarshallingJson.kt#L15)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `JsonLibAutoMarshallingJson()` |

### Functions

| Name | Summary |
|---|---|
| [asA](as-a.md) | `abstract fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(j: `[`ROOT`](index.md#ROOT)`, c: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](as-a.md#T)`>): `[`T`](as-a.md#T)<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`ROOT`](index.md#ROOT)`.asA(c: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](as-a.md#T)`>): `[`T`](as-a.md#T) |
| [asJsonObject](as-json-object.md) | `abstract fun asJsonObject(a: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`ROOT`](index.md#ROOT)<br>`fun `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`.asJsonObject(): `[`ROOT`](index.md#ROOT) |
| [asJsonString](as-json-string.md) | `open fun asJsonString(a: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Inherited Functions

| Name | Summary |
|---|---|
| [array](../-json/array.md) | `open fun <T : `[`NODE`](../-json/index.md#NODE)`> array(value: `[`T`](../-json/array.md#T)`): `[`ROOT`](../-json/index.md#ROOT)<br>`open fun <T : `[`NODE`](../-json/index.md#NODE)`> array(value: `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`T`](../-json/array.md#T)`>): `[`ROOT`](../-json/index.md#ROOT) |
| [asA](../-auto-marshalling-json/as-a.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asA(c: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](../-auto-marshalling-json/as-a.md#T)`>): `[`T`](../-auto-marshalling-json/as-a.md#T) |
| [asCompactJsonString](../-json/as-compact-json-string.md) | `abstract fun `[`ROOT`](../-json/index.md#ROOT)`.asCompactJsonString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [asJsonArray](../-json/as-json-array.md) | `abstract fun <T : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`NODE`](../-json/index.md#NODE)`>> `[`T`](../-json/as-json-array.md#T)`.asJsonArray(): `[`ROOT`](../-json/index.md#ROOT) |
| [asJsonObject](../-json/as-json-object.md) | `abstract fun `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asJsonObject(): `[`ROOT`](../-json/index.md#ROOT)<br>`abstract fun <LIST : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`NODE`](../-json/index.md#NODE)`>>> `[`LIST`](../-json/as-json-object.md#LIST)`.asJsonObject(): `[`ROOT`](../-json/index.md#ROOT) |
| [asJsonValue](../-json/as-json-value.md) | `abstract fun `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?.asJsonValue(): `[`NODE`](../-json/index.md#NODE)<br>`abstract fun `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?.asJsonValue(): `[`NODE`](../-json/index.md#NODE)<br>`abstract fun `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`?.asJsonValue(): `[`NODE`](../-json/index.md#NODE)<br>`abstract fun `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?.asJsonValue(): `[`NODE`](../-json/index.md#NODE)<br>`abstract fun `[`BigDecimal`](http://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`?.asJsonValue(): `[`NODE`](../-json/index.md#NODE)<br>`abstract fun `[`BigInteger`](http://docs.oracle.com/javase/6/docs/api/java/math/BigInteger.html)`?.asJsonValue(): `[`NODE`](../-json/index.md#NODE)<br>`abstract fun `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?.asJsonValue(): `[`NODE`](../-json/index.md#NODE) |
| [asPrettyJsonString](../-json/as-pretty-json-string.md) | `abstract fun `[`ROOT`](../-json/index.md#ROOT)`.asPrettyJsonString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [body](../-json/body.md) | `open fun body(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = None): `[`BiDiBodyLensSpec`](../../org.http4k.lens/-bi-di-body-lens-spec/index.md)`<`[`ROOT`](../-json/index.md#ROOT)`>` |
| [boolean](../-json/boolean.md) | `open fun boolean(value: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`NODE`](../-json/index.md#NODE) |
| [compact](../-json/compact.md) | `open fun compact(node: `[`ROOT`](../-json/index.md#ROOT)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [compactify](../-json/compactify.md) | `open fun compactify(s: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [elements](../-json/elements.md) | `abstract fun elements(value: `[`NODE`](../-json/index.md#NODE)`): `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`NODE`](../-json/index.md#NODE)`>` |
| [fields](../-json/fields.md) | `abstract fun fields(node: `[`NODE`](../-json/index.md#NODE)`): `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`NODE`](../-json/index.md#NODE)`>>` |
| [json](../-json/json.md) | `open fun <IN> `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](../-json/json.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.json(): `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](../-json/json.md#IN)`, `[`ROOT`](../-json/index.md#ROOT)`>` |
| [lens](../-json/lens.md) | `open fun <IN> lens(spec: `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](../-json/lens.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](../-json/lens.md#IN)`, `[`ROOT`](../-json/index.md#ROOT)`>` |
| [nullNode](../-json/null-node.md) | `open fun nullNode(): `[`NODE`](../-json/index.md#NODE) |
| [number](../-json/number.md) | `open fun number(value: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`NODE`](../-json/index.md#NODE)<br>`open fun number(value: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`NODE`](../-json/index.md#NODE)<br>`open fun number(value: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`NODE`](../-json/index.md#NODE)<br>`open fun number(value: `[`BigDecimal`](http://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`): `[`NODE`](../-json/index.md#NODE)<br>`open fun number(value: `[`BigInteger`](http://docs.oracle.com/javase/6/docs/api/java/math/BigInteger.html)`): `[`NODE`](../-json/index.md#NODE) |
| [obj](../-json/obj.md) | `open fun obj(): `[`ROOT`](../-json/index.md#ROOT)<br>`open fun <T : `[`NODE`](../-json/index.md#NODE)`> obj(value: `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`T`](../-json/obj.md#T)`>>): `[`ROOT`](../-json/index.md#ROOT)<br>`open fun <T : `[`NODE`](../-json/index.md#NODE)`> obj(vararg fields: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`T`](../-json/obj.md#T)`>): `[`ROOT`](../-json/index.md#ROOT) |
| [parse](../-json/parse.md) | `open fun parse(s: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ROOT`](../-json/index.md#ROOT) |
| [prettify](../-json/prettify.md) | `open fun prettify(s: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [pretty](../-json/pretty.md) | `open fun pretty(node: `[`ROOT`](../-json/index.md#ROOT)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [string](../-json/string.md) | `open fun string(value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`NODE`](../-json/index.md#NODE) |
| [text](../-json/text.md) | `abstract fun text(value: `[`NODE`](../-json/index.md#NODE)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [typeOf](../-json/type-of.md) | `abstract fun typeOf(value: `[`NODE`](../-json/index.md#NODE)`): `[`JsonType`](../-json-type/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [hasBody](../../org.http4k.hamkrest/has-body.md) | `fun <ROOT : `[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`, NODE> `[`Json`](../-json/index.md)`<`[`ROOT`](../../org.http4k.hamkrest/has-body.md#ROOT)`, `[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`>.hasBody(expected: `[`ROOT`](../../org.http4k.hamkrest/has-body.md#ROOT)`): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <ROOT : `[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`, NODE> `[`Json`](../-json/index.md)`<`[`ROOT`](../../org.http4k.hamkrest/has-body.md#ROOT)`, `[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`>.hasBody(expected: Matcher<`[`ROOT`](../../org.http4k.hamkrest/has-body.md#ROOT)`>): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <ROOT : `[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`, NODE> `[`Json`](../-json/index.md)`<`[`ROOT`](../../org.http4k.hamkrest/has-body.md#ROOT)`, `[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`>.hasBody(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>` |

### Inheritors

| Name | Summary |
|---|---|
| [ConfigurableGson](../-configurable-gson/index.md) | `open class ConfigurableGson : `[`JsonLibAutoMarshallingJson`](./index.md)`<JsonElement>` |
| [ConfigurableJackson](../-configurable-jackson/index.md) | `open class ConfigurableJackson : `[`JsonLibAutoMarshallingJson`](./index.md)`<JsonNode>` |
