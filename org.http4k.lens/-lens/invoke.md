[http4k](../../index.md) / [org.http4k.lens](../index.md) / [Lens](index.md) / [invoke](./invoke.md)

# invoke

`open operator fun invoke(target: `[`IN`](index.md#IN)`): `[`FINAL`](index.md#FINAL) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/lens.kt#L12)

Overrides [LensExtractor.invoke](../-lens-extractor/invoke.md)

Lens operation to get the value from the target

### Exceptions

`LensFailure` - if the value could not be retrieved from the target (missing/invalid etc)