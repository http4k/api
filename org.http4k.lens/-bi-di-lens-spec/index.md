[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiLensSpec](./index.md)

# BiDiLensSpec

`open class BiDiLensSpec<IN, OUT> : `[`LensSpec`](../-lens-spec/index.md)`<`[`IN`](index.md#IN)`, `[`OUT`](index.md#OUT)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/lensSpec.kt#L126)

Represents a bi-directional extraction of an entity from a target, or an insertion into a target.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BiDiLensSpec(location: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, paramMeta: `[`ParamMeta`](../-param-meta/index.md)`, get: `[`LensGet`](../-lens-get/index.md)`<`[`IN`](index.md#IN)`, `[`OUT`](index.md#OUT)`>, set: `[`LensSet`](../-lens-set/index.md)`<`[`IN`](index.md#IN)`, `[`OUT`](index.md#OUT)`>)`<br>Represents a bi-directional extraction of an entity from a target, or an insertion into a target. |

### Properties

| Name | Summary |
|---|---|
| [multi](multi.md) | `open val multi: `[`BiDiMultiLensSpec`](../-bi-di-multi-lens-spec/index.md)`<`[`IN`](index.md#IN)`, `[`OUT`](index.md#OUT)`>` |

### Inherited Properties

| Name | Summary |
|---|---|
| [location](../-lens-spec/location.md) | `val location: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [paramMeta](../-lens-spec/param-meta.md) | `val paramMeta: `[`ParamMeta`](../-param-meta/index.md) |

### Functions

| Name | Summary |
|---|---|
| [defaulted](defaulted.md) | `open fun defaulted(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, default: `[`OUT`](index.md#OUT)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiLens`](../-bi-di-lens/index.md)`<`[`IN`](index.md#IN)`, `[`OUT`](index.md#OUT)`>`<br>Make a concrete Lens for this spec that falls back to the default value if no value is found in the target. |
| [map](map.md) | `fun <NEXT> map(nextIn: (`[`OUT`](index.md#OUT)`) -> `[`NEXT`](map.md#NEXT)`, nextOut: (`[`NEXT`](map.md#NEXT)`) -> `[`OUT`](index.md#OUT)`): `[`BiDiLensSpec`](./index.md)`<`[`IN`](index.md#IN)`, `[`NEXT`](map.md#NEXT)`>`<br>Create another BiDiLensSpec which applies the bi-directional transformations to the result. Any resultant Lens can be used to extract or insert the final type from/into a target. |
| [optional](optional.md) | `open fun optional(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiLens`](../-bi-di-lens/index.md)`<`[`IN`](index.md#IN)`, `[`OUT`](index.md#OUT)`?>`<br>Make a concrete Lens for this spec that looks for an optional value in the target. |
| [required](required.md) | `open fun required(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiLens`](../-bi-di-lens/index.md)`<`[`IN`](index.md#IN)`, `[`OUT`](index.md#OUT)`>`<br>Make a concrete Lens for this spec that looks for a required value in the target. |

### Inherited Functions

| Name | Summary |
|---|---|
| [map](../-lens-spec/map.md) | `fun <NEXT> map(nextIn: (`[`OUT`](../-lens-spec/index.md#OUT)`) -> `[`NEXT`](../-lens-spec/map.md#NEXT)`): `[`LensSpec`](../-lens-spec/index.md)`<`[`IN`](../-lens-spec/index.md#IN)`, `[`NEXT`](../-lens-spec/map.md#NEXT)`>`<br>Create another LensSpec which applies the uni-directional transformation to the result. Any resultant Lens can only be used to extract the final type from a target. |

### Extension Functions

| Name | Summary |
|---|---|
| [boolean](../boolean.md) | `fun <IN> `[`BiDiLensSpec`](./index.md)`<`[`IN`](../boolean.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.boolean(): `[`BiDiLensSpec`](./index.md)`<`[`IN`](../boolean.md#IN)`, `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [dateTime](../date-time.md) | `fun <IN> `[`BiDiLensSpec`](./index.md)`<`[`IN`](../date-time.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.dateTime(formatter: DateTimeFormatter = ISO_LOCAL_DATE_TIME): `[`BiDiLensSpec`](./index.md)`<`[`IN`](../date-time.md#IN)`, LocalDateTime>` |
| [double](../double.md) | `fun <IN> `[`BiDiLensSpec`](./index.md)`<`[`IN`](../double.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.double(): `[`BiDiLensSpec`](./index.md)`<`[`IN`](../double.md#IN)`, `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`>` |
| [float](../float.md) | `fun <IN> `[`BiDiLensSpec`](./index.md)`<`[`IN`](../float.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.float(): `[`BiDiLensSpec`](./index.md)`<`[`IN`](../float.md#IN)`, `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)`>` |
| [int](../int.md) | `fun <IN> `[`BiDiLensSpec`](./index.md)`<`[`IN`](../int.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.int(): `[`BiDiLensSpec`](./index.md)`<`[`IN`](../int.md#IN)`, `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>` |
| [localDate](../local-date.md) | `fun <IN> `[`BiDiLensSpec`](./index.md)`<`[`IN`](../local-date.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.localDate(formatter: DateTimeFormatter = ISO_LOCAL_DATE): `[`BiDiLensSpec`](./index.md)`<`[`IN`](../local-date.md#IN)`, LocalDate>` |
| [long](../long.md) | `fun <IN> `[`BiDiLensSpec`](./index.md)`<`[`IN`](../long.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.long(): `[`BiDiLensSpec`](./index.md)`<`[`IN`](../long.md#IN)`, `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`>` |
| [nonEmptyString](../non-empty-string.md) | `fun <IN> `[`BiDiLensSpec`](./index.md)`<`[`IN`](../non-empty-string.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.nonEmptyString(): `[`BiDiLensSpec`](./index.md)`<`[`IN`](../non-empty-string.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [regex](../regex.md) | `fun <IN> `[`BiDiLensSpec`](./index.md)`<`[`IN`](../regex.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.regex(pattern: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, group: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 1): `[`LensSpec`](../-lens-spec/index.md)`<`[`IN`](../regex.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [string](../string.md) | `fun <IN> `[`BiDiLensSpec`](./index.md)`<`[`IN`](../string.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.string(): `[`BiDiLensSpec`](./index.md)`<`[`IN`](../string.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [uri](../uri.md) | `fun <IN> `[`BiDiLensSpec`](./index.md)`<`[`IN`](../uri.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.uri(): `[`BiDiLensSpec`](./index.md)`<`[`IN`](../uri.md#IN)`, `[`Uri`](../../org.http4k.core/-uri/index.md)`>` |
| [uuid](../uuid.md) | `fun <IN> `[`BiDiLensSpec`](./index.md)`<`[`IN`](../uuid.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.uuid(): `[`BiDiLensSpec`](./index.md)`<`[`IN`](../uuid.md#IN)`, `[`UUID`](http://docs.oracle.com/javase/6/docs/api/java/util/UUID.html)`>` |
| [zonedDateTime](../zoned-date-time.md) | `fun <IN> `[`BiDiLensSpec`](./index.md)`<`[`IN`](../zoned-date-time.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.zonedDateTime(formatter: DateTimeFormatter = ISO_ZONED_DATE_TIME): `[`BiDiLensSpec`](./index.md)`<`[`IN`](../zoned-date-time.md#IN)`, ZonedDateTime>` |

### Inheritors

| Name | Summary |
|---|---|
| [Cookies](../-cookies.md) | `object Cookies : `[`BiDiLensSpec`](./index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`>` |
| [FormField](../-form-field.md) | `object FormField : `[`BiDiLensSpec`](./index.md)`<`[`WebForm`](../-web-form/index.md)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [Header](../-header/index.md) | `object Header : `[`BiDiLensSpec`](./index.md)`<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [MultipartFormField](../-multipart-form-field.md) | `object MultipartFormField : `[`BiDiLensSpec`](./index.md)`<`[`MultipartForm`](../-multipart-form/index.md)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [MultipartFormFile](../-multipart-form-file.md) | `object MultipartFormFile : `[`BiDiLensSpec`](./index.md)`<`[`MultipartForm`](../-multipart-form/index.md)`, `[`FormFile`](../../org.http4k.core/-form-file/index.md)`>` |
| [Query](../-query.md) | `object Query : `[`BiDiLensSpec`](./index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
