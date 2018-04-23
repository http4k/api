[http4k](../index.md) / [org.http4k.lens](index.md) / [Cookies](./-cookies.md)

# Cookies

`object Cookies : `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`Request`](../org.http4k.core/-request/index.md)`, `[`Cookie`](../org.http4k.core.cookie/-cookie/index.md)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/Cookies.kt#L9)

### Inherited Properties

| Name | Summary |
|---|---|
| [multi](-bi-di-lens-spec/multi.md) | `open val multi: `[`BiDiMultiLensSpec`](-bi-di-multi-lens-spec/index.md)`<`[`IN`](-bi-di-lens-spec/index.md#IN)`, `[`OUT`](-bi-di-lens-spec/index.md#OUT)`>` |

### Inherited Functions

| Name | Summary |
|---|---|
| [defaulted](-bi-di-lens-spec/defaulted.md) | `open fun defaulted(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, default: `[`OUT`](-bi-di-lens-spec/index.md#OUT)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiLens`](-bi-di-lens/index.md)`<`[`IN`](-bi-di-lens-spec/index.md#IN)`, `[`OUT`](-bi-di-lens-spec/index.md#OUT)`>`<br>Make a concrete Lens for this spec that falls back to the default value if no value is found in the target. |
| [map](-bi-di-lens-spec/map.md) | `fun <NEXT> map(nextIn: (`[`OUT`](-bi-di-lens-spec/index.md#OUT)`) -> `[`NEXT`](-bi-di-lens-spec/map.md#NEXT)`, nextOut: (`[`NEXT`](-bi-di-lens-spec/map.md#NEXT)`) -> `[`OUT`](-bi-di-lens-spec/index.md#OUT)`): `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](-bi-di-lens-spec/index.md#IN)`, `[`NEXT`](-bi-di-lens-spec/map.md#NEXT)`>`<br>Create another BiDiLensSpec which applies the bi-directional transformations to the result. Any resultant Lens can be used to extract or insert the final type from/into a target. |
| [optional](-bi-di-lens-spec/optional.md) | `open fun optional(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiLens`](-bi-di-lens/index.md)`<`[`IN`](-bi-di-lens-spec/index.md#IN)`, `[`OUT`](-bi-di-lens-spec/index.md#OUT)`?>`<br>Make a concrete Lens for this spec that looks for an optional value in the target. |
| [required](-bi-di-lens-spec/required.md) | `open fun required(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiLens`](-bi-di-lens/index.md)`<`[`IN`](-bi-di-lens-spec/index.md#IN)`, `[`OUT`](-bi-di-lens-spec/index.md#OUT)`>`<br>Make a concrete Lens for this spec that looks for a required value in the target. |

### Extension Functions

| Name | Summary |
|---|---|
| [boolean](boolean.md) | `fun <IN> `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](boolean.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.boolean(): `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](boolean.md#IN)`, `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [dateTime](date-time.md) | `fun <IN> `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](date-time.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.dateTime(formatter: DateTimeFormatter = ISO_LOCAL_DATE_TIME): `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](date-time.md#IN)`, LocalDateTime>` |
| [double](double.md) | `fun <IN> `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](double.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.double(): `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](double.md#IN)`, `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`>` |
| [float](float.md) | `fun <IN> `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](float.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.float(): `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](float.md#IN)`, `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)`>` |
| [int](int.md) | `fun <IN> `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](int.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.int(): `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](int.md#IN)`, `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>` |
| [localDate](local-date.md) | `fun <IN> `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](local-date.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.localDate(formatter: DateTimeFormatter = ISO_LOCAL_DATE): `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](local-date.md#IN)`, LocalDate>` |
| [long](long.md) | `fun <IN> `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](long.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.long(): `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](long.md#IN)`, `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`>` |
| [nonEmptyString](non-empty-string.md) | `fun <IN> `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](non-empty-string.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.nonEmptyString(): `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](non-empty-string.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [regex](regex.md) | `fun <IN> `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](regex.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.regex(pattern: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, group: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 1): `[`LensSpec`](-lens-spec/index.md)`<`[`IN`](regex.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [string](string.md) | `fun <IN> `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](string.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.string(): `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](string.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [uri](uri.md) | `fun <IN> `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](uri.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.uri(): `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](uri.md#IN)`, `[`Uri`](../org.http4k.core/-uri/index.md)`>` |
| [uuid](uuid.md) | `fun <IN> `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](uuid.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.uuid(): `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](uuid.md#IN)`, `[`UUID`](http://docs.oracle.com/javase/6/docs/api/java/util/UUID.html)`>` |
| [zonedDateTime](zoned-date-time.md) | `fun <IN> `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](zoned-date-time.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.zonedDateTime(formatter: DateTimeFormatter = ISO_ZONED_DATE_TIME): `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](zoned-date-time.md#IN)`, ZonedDateTime>` |
