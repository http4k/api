[http4k](../../index.md) / [org.http4k.traffic](../index.md) / [Sink](index.md) / [DiskStream](./-disk-stream.md)

# DiskStream

`fun DiskStream(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = ".", shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }, id: () -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = { System.nanoTime().toString() + UUID.randomUUID().toString() }): <ERROR CLASS>`

Serialises HTTP traffic to the FS in order.

