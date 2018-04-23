[http4k](../index.md) / [org.http4k.core](./index.md)

## Package org.http4k.core

### Types

| Name | Summary |
|---|---|
| [Body](-body/index.md) | `interface Body : `[`Closeable`](http://docs.oracle.com/javase/6/docs/api/java/io/Closeable.html)<br>If this Body is NOT being returned to the caller (via a Server implementation or otherwise), close() should be called. |
| [BodyMode](-body-mode/index.md) | `sealed class BodyMode : (`[`InputStream`](http://docs.oracle.com/javase/6/docs/api/java/io/InputStream.html)`) -> `[`Body`](-body/index.md) |
| [ContentType](-content-type/index.md) | `data class ContentType` |
| [Credentials](-credentials/index.md) | `data class Credentials` |
| [Event](-event/index.md) | `interface Event` |
| [EventCategory](-event-category/index.md) | `data class EventCategory` |
| [Filter](-filter/index.md) | `interface Filter : (`[`HttpHandler`](-http-handler.md)`) -> `[`HttpHandler`](-http-handler.md) |
| [FormFile](-form-file/index.md) | `data class FormFile : `[`Closeable`](http://docs.oracle.com/javase/6/docs/api/java/io/Closeable.html) |
| [HttpMessage](-http-message/index.md) | `interface HttpMessage : `[`Closeable`](http://docs.oracle.com/javase/6/docs/api/java/io/Closeable.html) |
| [HttpTransaction](-http-transaction/index.md) | `data class HttpTransaction` |
| [MemoryBody](-memory-body/index.md) | `data class MemoryBody : `[`Body`](-body/index.md)<br>Represents a body that is backed by an in-memory ByteBuffer. Closing this has no effect. |
| [MemoryRequest](-memory-request/index.md) | `data class MemoryRequest : `[`Request`](-request/index.md) |
| [MemoryResponse](-memory-response/index.md) | `data class MemoryResponse : `[`Response`](-response/index.md) |
| [Method](-method/index.md) | `enum class Method` |
| [MimeTypes](-mime-types/index.md) | `data class MimeTypes` |
| [MultipartEntity](-multipart-entity/index.md) | `sealed class MultipartEntity : `[`Closeable`](http://docs.oracle.com/javase/6/docs/api/java/io/Closeable.html) |
| [MultipartFormBody](-multipart-form-body/index.md) | `data class MultipartFormBody : `[`Body`](-body/index.md)`, `[`Closeable`](http://docs.oracle.com/javase/6/docs/api/java/io/Closeable.html)<br>Represents a Multi-part that is backed by a stream, which should be closed after handling the content. The gotchas which apply to StreamBody also apply here.. |
| [Request](-request/index.md) | `interface Request : `[`HttpMessage`](-http-message/index.md) |
| [RequestContext](-request-context/index.md) | `class RequestContext` |
| [RequestContexts](-request-contexts/index.md) | `class RequestContexts : `[`Store`](-store/index.md)`<`[`RequestContext`](-request-context/index.md)`>`<br>In-memory RequestContext store. |
| [Response](-response/index.md) | `interface Response : `[`HttpMessage`](-http-message/index.md) |
| [Status](-status/index.md) | `data class Status` |
| [Store](-store/index.md) | `interface Store<OUT> : `[`LensInjector`](../org.http4k.lens/-lens-injector/index.md)`<`[`OUT`](-store/index.md#OUT)`, `[`Request`](-request/index.md)`>, `[`LensExtractor`](../org.http4k.lens/-lens-extractor/index.md)`<`[`Request`](-request/index.md)`, `[`OUT`](-store/index.md#OUT)`>` |
| [StreamBody](-stream-body/index.md) | `class StreamBody : `[`Body`](-body/index.md)<br>Represents a body that is backed by a (lazy) InputStream. Operating with StreamBody has a number of potential gotchas: |
| [Uri](-uri/index.md) | `data class Uri` |
| [UriTemplate](-uri-template/index.md) | `data class UriTemplate` |

### Type Aliases

| Name | Summary |
|---|---|
| [Events](-events.md) | `typealias Events = (`[`Event`](-event/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [Headers](-headers.md) | `typealias Headers = `[`Parameters`](-parameters.md) |
| [HttpHandler](-http-handler.md) | `typealias HttpHandler = (`[`Request`](-request/index.md)`) -> `[`Response`](-response/index.md) |
| [Parameters](-parameters.md) | `typealias Parameters = `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<Parameter>` |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.String](kotlin.-string/index.md) |  |
| [kotlin.collections.List](kotlin.collections.-list/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [maxAge](max-age.md) | `fun `[`Response`](-response/index.md)`.maxAge(duration: Duration): `[`Response`](-response/index.md) |
| [multipartIterator](multipart-iterator.md) | `fun `[`HttpMessage`](-http-message/index.md)`.multipartIterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`MultipartEntity`](-multipart-entity/index.md)`>` |
| [mustRevalidate](must-revalidate.md) | `fun `[`Response`](-response/index.md)`.mustRevalidate(): `[`Response`](-response/index.md) |
| [noCache](no-cache.md) | `fun `[`Response`](-response/index.md)`.noCache(): `[`Response`](-response/index.md) |
| [noStore](no-store.md) | `fun `[`Response`](-response/index.md)`.noStore(): `[`Response`](-response/index.md) |
| [onlyIfCached](only-if-cached.md) | `fun `[`Response`](-response/index.md)`.onlyIfCached(): `[`Response`](-response/index.md) |
| [private](private.md) | `fun `[`Response`](-response/index.md)`.private(): `[`Response`](-response/index.md) |
| [public](public.md) | `fun `[`Response`](-response/index.md)`.public(): `[`Response`](-response/index.md) |
| [queries](queries.md) | `fun `[`Uri`](-uri/index.md)`.queries(): `[`Parameters`](-parameters.md) |
| [query](query.md) | `fun `[`Uri`](-uri/index.md)`.query(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Uri`](-uri/index.md) |
| [staleIfError](stale-if-error.md) | `fun `[`Response`](-response/index.md)`.staleIfError(duration: Duration): `[`Response`](-response/index.md) |
| [staleWhileRevalidate](stale-while-revalidate.md) | `fun `[`Response`](-response/index.md)`.staleWhileRevalidate(duration: Duration): `[`Response`](-response/index.md) |
| [then](then.md) | `fun `[`Filter`](-filter/index.md)`.then(next: `[`Filter`](-filter/index.md)`): `[`Filter`](-filter/index.md)<br>`fun `[`Filter`](-filter/index.md)`.then(next: `[`HttpHandler`](-http-handler.md)`): `[`HttpHandler`](-http-handler.md)<br>`fun `[`Filter`](-filter/index.md)`.then(routingHttpHandler: `[`RoutingHttpHandler`](../org.http4k.routing/-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](../org.http4k.routing/-routing-http-handler/index.md) |
| [toCurl](to-curl.md) | `fun `[`Request`](-request/index.md)`.toCurl(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [with](with.md) | `fun <T> `[`T`](with.md#T)`.with(vararg modifiers: (`[`T`](with.md#T)`) -> `[`T`](with.md#T)`): `[`T`](with.md#T) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [NoOp](-no-op.md) | `val Filter.Companion.NoOp: `[`Filter`](-filter/index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [parse](parse.md) | `fun Request.Companion.parse(request: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](-request/index.md)<br>`fun Response.Companion.parse(response: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Response`](-response/index.md) |
