[http4k](../../../index.md) / [org.http4k.core](../../index.md) / [RequestContext](../index.md) / [Companion](index.md) / [invoke](./invoke.md)

# invoke

`fun <R : `[`Request`](../../-request/index.md)`> invoke(value: `[`UUID`](http://docs.oracle.com/javase/6/docs/api/java/util/UUID.html)`, target: `[`R`](invoke.md#R)`): `[`R`](invoke.md#R) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/RequestContext.kt#L16)

Overrides [LensInjector.invoke](../../../org.http4k.lens/-lens-injector/invoke.md)

Lens operation to set the value into the target

`fun invoke(target: `[`Request`](../../-request/index.md)`): `[`UUID`](http://docs.oracle.com/javase/6/docs/api/java/util/UUID.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/RequestContext.kt#L18)

Overrides [LensExtractor.invoke](../../../org.http4k.lens/-lens-extractor/invoke.md)

Lens operation to get the value from the target

### Exceptions

`LensFailure` - if the value could not be retrieved from the target (missing/invalid etc)