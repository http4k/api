[http4k](../index.md) / [org.http4k.filter](index.md) / [HandleUpstreamRequestFailed](./-handle-upstream-request-failed.md)

# HandleUpstreamRequestFailed

`fun `[`ServerFilters`](-server-filters/index.md)`.~~HandleUpstreamRequestFailed~~(exceptionToBody: `[`RemoteRequestFailed`](../org.http4k.cloudnative/-remote-request-failed/index.md)`.() -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = { localizedMessage }): `[`Filter`](../org.http4k.core/-filter.md)
**Deprecated:** Renamed


`fun `[`ClientFilters`](-client-filters/index.md)`.~~HandleUpstreamRequestFailed~~(responseWasSuccessful: `[`Response`](../org.http4k.core/-response/index.md)`.() -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { status.successful }, responseToMessage: `[`Response`](../org.http4k.core/-response/index.md)`.() -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = Response::bodyString): <ERROR CLASS>`
**Deprecated:** Renamed

