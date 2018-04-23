[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BodyLens](index.md) / [invoke](./invoke.md)

# invoke

`open operator fun invoke(target: `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`): `[`FINAL`](index.md#FINAL) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/body.kt#L18)

Overrides [LensExtractor.invoke](../-lens-extractor/invoke.md)

Lens operation to get the value from the target

### Exceptions

`LensFailure` - if the value could not be retrieved from the target (missing/invalid etc)