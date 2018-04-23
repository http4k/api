[http4k](../../index.md) / [org.http4k.lens](../index.md) / [Path](./index.md)

# Path

`object Path : `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/path.kt#L82)

### Functions

| Name | Summary |
|---|---|
| [fixed](fixed.md) | `fun fixed(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`PathLens`](../-path-lens/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |

### Inherited Functions

| Name | Summary |
|---|---|
| [map](../-bi-di-path-lens-spec/map.md) | `fun <NEXT> map(nextIn: (`[`OUT`](../-bi-di-path-lens-spec/index.md#OUT)`) -> `[`NEXT`](../-bi-di-path-lens-spec/map.md#NEXT)`, nextOut: (`[`NEXT`](../-bi-di-path-lens-spec/map.md#NEXT)`) -> `[`OUT`](../-bi-di-path-lens-spec/index.md#OUT)`): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`NEXT`](../-bi-di-path-lens-spec/map.md#NEXT)`>`<br>Create another BiDiPathLensSpec which applies the bi-directional transformations to the result. Any resultant Lens can be used to extract or insert the final type from/into a path segment. |
| [of](../-bi-di-path-lens-spec/of.md) | `open fun of(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiPathLens`](../-bi-di-path-lens/index.md)`<`[`OUT`](../-bi-di-path-lens-spec/index.md#OUT)`>`<br>Create a lens for this Spec |

### Extension Functions

| Name | Summary |
|---|---|
| [boolean](../boolean.md) | `fun `[`Path`](./index.md)`.boolean(): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [dateTime](../date-time.md) | `fun `[`Path`](./index.md)`.dateTime(formatter: DateTimeFormatter = ISO_LOCAL_DATE_TIME): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<LocalDateTime>` |
| [double](../double.md) | `fun `[`Path`](./index.md)`.double(): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`>` |
| [float](../float.md) | `fun `[`Path`](./index.md)`.float(): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)`>` |
| [int](../int.md) | `fun `[`Path`](./index.md)`.int(): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>` |
| [localDate](../local-date.md) | `fun `[`Path`](./index.md)`.localDate(formatter: DateTimeFormatter = ISO_LOCAL_DATE): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<LocalDate>` |
| [long](../long.md) | `fun `[`Path`](./index.md)`.long(): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`>` |
| [nonEmptyString](../non-empty-string.md) | `fun `[`Path`](./index.md)`.nonEmptyString(): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [regex](../regex.md) | `fun `[`Path`](./index.md)`.regex(pattern: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, group: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 1): `[`PathLensSpec`](../-path-lens-spec/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [string](../string.md) | `fun `[`Path`](./index.md)`.string(): `[`Path`](./index.md) |
| [uuid](../uuid.md) | `fun `[`Path`](./index.md)`.uuid(): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`UUID`](http://docs.oracle.com/javase/6/docs/api/java/util/UUID.html)`>` |
| [zonedDateTime](../zoned-date-time.md) | `fun `[`Path`](./index.md)`.zonedDateTime(formatter: DateTimeFormatter = ISO_ZONED_DATE_TIME): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<ZonedDateTime>` |
