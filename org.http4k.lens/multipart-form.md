[http4k](../index.md) / [org.http4k.lens](index.md) / [multipartForm](./multipart-form.md)

# multipartForm

`fun Body.Companion.multipartForm(validator: `[`Validator`](-validator/index.md)`, vararg parts: `[`Lens`](-lens/index.md)`<`[`MultipartForm`](-multipart-form/index.md)`, *>, defaultBoundary: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = MULTIPART_BOUNDARY, diskThreshold: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = MultipartFormBody.DEFAULT_DISK_THRESHOLD): `[`BiDiBodyLensSpec`](-bi-di-body-lens-spec/index.md)`<`[`MultipartForm`](-multipart-form/index.md)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-multipart/src/main/kotlin/org/http4k/lens/multipartForm.kt#L46)