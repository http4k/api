[http4k](../../index.md) / [org.http4k.jsonrpc](../index.md) / [ErrorMessage](./index.md)

# ErrorMessage

`open class ErrorMessage`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ErrorMessage(code: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, message: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [code](code.md) | `val code: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [message](message.md) | `val message: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [data](data.md) | `open fun <NODE> data(json: `[`Json`](../../org.http4k.format/-json/index.md)`<NODE>): NODE?` |
| [invoke](invoke.md) | `operator fun <NODE> invoke(json: `[`Json`](../../org.http4k.format/-json/index.md)`<NODE>): NODE` |

### Companion Object Properties

| Name | Summary |
|---|---|
| [InternalError](-internal-error.md) | `val InternalError: `[`ErrorMessage`](./index.md) |
| [InvalidParams](-invalid-params.md) | `val InvalidParams: `[`ErrorMessage`](./index.md) |
| [InvalidRequest](-invalid-request.md) | `val InvalidRequest: `[`ErrorMessage`](./index.md) |
| [MethodNotFound](-method-not-found.md) | `val MethodNotFound: `[`ErrorMessage`](./index.md) |
| [ParseError](-parse-error.md) | `val ParseError: `[`ErrorMessage`](./index.md) |
