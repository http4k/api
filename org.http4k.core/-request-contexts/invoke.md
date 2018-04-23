[http4k](../../index.md) / [org.http4k.core](../index.md) / [RequestContexts](index.md) / [invoke](./invoke.md)

# invoke

`fun invoke(target: `[`Request`](../-request/index.md)`): `[`RequestContext`](../-request-context/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/RequestContexts.kt#L13)

Overrides [LensExtractor.invoke](../../org.http4k.lens/-lens-extractor/invoke.md)

Lens operation to get the value from the target

### Exceptions

`LensFailure` - if the value could not be retrieved from the target (missing/invalid etc)`fun <R : `[`Request`](../-request/index.md)`> invoke(value: `[`RequestContext`](../-request-context/index.md)`, target: `[`R`](invoke.md#R)`): `[`R`](invoke.md#R) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/RequestContexts.kt#L16)

Overrides [LensInjector.invoke](../../org.http4k.lens/-lens-injector/invoke.md)

Lens operation to set the value into the target

