[http4k](../../index.md) / [org.http4k.lens](../index.md) / [LensExtractor](index.md) / [invoke](./invoke.md)

# invoke

`abstract operator fun invoke(target: `[`IN`](index.md#IN)`): `[`OUT`](index.md#OUT) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/LensExtractor.kt#L9)

Lens operation to get the value from the target

### Exceptions

`LensFailure` - if the value could not be retrieved from the target (missing/invalid etc)