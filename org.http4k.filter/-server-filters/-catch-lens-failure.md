[http4k](../../index.md) / [org.http4k.filter](../index.md) / [ServerFilters](index.md) / [CatchLensFailure](./-catch-lens-failure.md)

# CatchLensFailure

`object CatchLensFailure : `[`Filter`](../../org.http4k.core/-filter.md)

Converts Lens extraction failures into correct HTTP responses (Bad Requests/UnsupportedMediaType).
This is required when using lenses to automatically unmarshall inbound requests.
Note that LensFailures from unmarshalling upstream Response objects are NOT caught to avoid incorrect server behaviour.

`fun CatchLensFailure(failResponseFn: (`[`LensFailure`](../../org.http4k.lens/-lens-failure/index.md)`) -> `[`Response`](../../org.http4k.core/-response/index.md)` = {
        Response(BAD_REQUEST.description(it.failures.joinToString("; ")))
    }): <ERROR CLASS>`

Converts Lens extraction failures into correct HTTP responses (Bad Requests/UnsupportedMediaType).
This is required when using lenses to automatically unmarshall inbound requests.
Note that LensFailures from unmarshalling upstream Response objects are NOT caught to avoid incorrect server behaviour.

Pass the failResponseFn param to provide a custom response for the LensFailure case

