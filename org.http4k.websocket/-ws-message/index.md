[http4k](../../index.md) / [org.http4k.websocket](../index.md) / [WsMessage](./index.md)

# WsMessage

`data class WsMessage` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/websocket/websocket.kt#L32)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `WsMessage(value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)`<br>`WsMessage(value: `[`InputStream`](http://docs.oracle.com/javase/6/docs/api/java/io/InputStream.html)`)`<br>`WsMessage(body: `[`Body`](../../org.http4k.core/-body/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [body](body.md) | `val body: `[`Body`](../../org.http4k.core/-body/index.md) |

### Functions

| Name | Summary |
|---|---|
| [body](body.md) | `fun body(new: `[`Body`](../../org.http4k.core/-body/index.md)`): `[`WsMessage`](./index.md) |
| [bodyString](body-string.md) | `fun bodyString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Extension Functions

| Name | Summary |
|---|---|
| [binary](../../org.http4k.lens/binary.md) | `fun WsMessage.Companion.binary(): `[`BiDiWsMessageLensSpec`](../../org.http4k.lens/-bi-di-ws-message-lens-spec/index.md)`<`[`ByteBuffer`](http://docs.oracle.com/javase/6/docs/api/java/nio/ByteBuffer.html)`>` |
| [string](../../org.http4k.lens/string.md) | `fun WsMessage.Companion.string(): `[`BiDiWsMessageLensSpec`](../../org.http4k.lens/-bi-di-ws-message-lens-spec/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
