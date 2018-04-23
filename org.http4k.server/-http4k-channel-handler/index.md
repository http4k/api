[http4k](../../index.md) / [org.http4k.server](../index.md) / [Http4kChannelHandler](./index.md)

# Http4kChannelHandler

`class Http4kChannelHandler : SimpleChannelInboundHandler<FullHttpRequest>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-server-netty/src/main/kotlin/org/http4k/server/Netty.kt#L39)

Exposed to allow for insertion into a customised Netty server instance

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Http4kChannelHandler(handler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`)`<br>Exposed to allow for insertion into a customised Netty server instance |

### Functions

| Name | Summary |
|---|---|
| [channelRead0](channel-read0.md) | `fun channelRead0(ctx: ChannelHandlerContext, request: FullHttpRequest): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
