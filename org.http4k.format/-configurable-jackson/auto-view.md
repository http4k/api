[http4k](../../index.md) / [org.http4k.format](../index.md) / [ConfigurableJackson](index.md) / [autoView](./auto-view.md)

# autoView

`inline fun <reified T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, reified V : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> Body.Companion.autoView(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = None): `[`BiDiBodyLensSpec`](../../org.http4k.lens/-bi-di-body-lens-spec/index.md)`<`[`T`](auto-view.md#T)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-format-jackson/src/main/kotlin/org/http4k/format/internalJackson.kt#L94)
`inline fun <reified T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, reified V : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> WsMessage.Companion.autoView(): `[`BiDiWsMessageLensSpec`](../../org.http4k.lens/-bi-di-ws-message-lens-spec/index.md)`<`[`T`](auto-view.md#T)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-format-jackson/src/main/kotlin/org/http4k/format/internalJackson.kt#L98)