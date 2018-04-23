[http4k](../../index.md) / [org.http4k.lens](../index.md) / [ContentNegotiation](./index.md)

# ContentNegotiation

`interface ContentNegotiation` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/body.kt#L98)

Modes for determining if a passed content type is acceptable.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `abstract operator fun invoke(expected: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`, actual: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [NonStrict](-non-strict.md) | `val NonStrict: `[`ContentNegotiation`](./index.md)<br>If present, the received Content-type header passed back MUST equal the expected Content-type, including directive |
| [None](-none.md) | `val None: `[`ContentNegotiation`](./index.md)<br>No validation is done on the received content type at all |
| [Strict](-strict.md) | `val Strict: `[`ContentNegotiation`](./index.md)<br>The received Content-type header passed back MUST equal the expected Content-type, including directive |
| [StrictNoDirective](-strict-no-directive.md) | `val StrictNoDirective: `[`ContentNegotiation`](./index.md)<br>The received Content-type header passed back MUST equal the expected Content-type, not including the directive |
