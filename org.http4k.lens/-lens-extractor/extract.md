[http4k](../../index.md) / [org.http4k.lens](../index.md) / [LensExtractor](index.md) / [extract](./extract.md)

# extract

`open fun extract(target: `[`IN`](index.md#IN)`): `[`OUT`](index.md#OUT) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/LensExtractor.kt#L16)

Lens operation to get the value from the target. Synonym for invoke(IN)

### Exceptions

`LensFailure` - if the value could not be retrieved from the target (missing/invalid etc)