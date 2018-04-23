[http4k](../index.md) / [org.http4k.traffic](./index.md)

## Package org.http4k.traffic

### Types

| Name | Summary |
|---|---|
| [ReadWriteCache](-read-write-cache/index.md) | `interface ReadWriteCache : `[`Sink`](-sink/index.md)`, `[`Source`](-source/index.md)<br>Combined Read/Write storage models, optimised for retrieval. |
| [ReadWriteStream](-read-write-stream/index.md) | `interface ReadWriteStream : `[`Sink`](-sink/index.md)`, `[`Replay`](-replay/index.md)<br>Combined Read/Write storage models, optimised for replay. |
| [Replay](-replay/index.md) | `interface Replay`<br>Provides a stream of traffic for replaying purposes. |
| [Responder](-responder/index.md) | `object Responder`<br>Provides HTTP Handlers which respond using pre-stored Requests. |
| [Sink](-sink/index.md) | `interface Sink`<br>Consumes HTTP traffic for storage. |
| [Source](-source/index.md) | `interface Source`<br>Tries to retrieve a stored response for a given request. |
