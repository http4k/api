[http4k](../index.md) / [org.http4k.format](./index.md)

## Package org.http4k.format

### Types

| Name | Summary |
|---|---|
| [Argo](-argo/index.md) | `object Argo : `[`Json`](-json/index.md)`<JsonRootNode, JsonNode>` |
| [AutoMarshallingJson](-auto-marshalling-json/index.md) | `abstract class AutoMarshallingJson` |
| [ConfigurableGson](-configurable-gson/index.md) | `open class ConfigurableGson : `[`JsonLibAutoMarshallingJson`](-json-lib-auto-marshalling-json/index.md)`<JsonElement>` |
| [ConfigurableJackson](-configurable-jackson/index.md) | `open class ConfigurableJackson : `[`JsonLibAutoMarshallingJson`](-json-lib-auto-marshalling-json/index.md)`<JsonNode>` |
| [ConfigurableMoshi](-configurable-moshi/index.md) | `open class ConfigurableMoshi : `[`AutoMarshallingJson`](-auto-marshalling-json/index.md) |
| [Gson](-gson.md) | `object Gson : `[`ConfigurableGson`](-configurable-gson/index.md) |
| [Jackson](-jackson.md) | `object Jackson : `[`ConfigurableJackson`](-configurable-jackson/index.md) |
| [Json](-json/index.md) | `interface Json<ROOT : `[`NODE`](-json/index.md#NODE)`, NODE>`<br>This is the contract for all JSON implementations |
| [JsonErrorResponseRenderer](-json-error-response-renderer/index.md) | `class JsonErrorResponseRenderer<ROOT : `[`NODE`](-json-error-response-renderer/index.md#NODE)`, out NODE>` |
| [JsonLibAutoMarshallingJson](-json-lib-auto-marshalling-json/index.md) | `abstract class JsonLibAutoMarshallingJson<ROOT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`AutoMarshallingJson`](-auto-marshalling-json/index.md)`, `[`Json`](-json/index.md)`<`[`ROOT`](-json-lib-auto-marshalling-json/index.md#ROOT)`, `[`ROOT`](-json-lib-auto-marshalling-json/index.md#ROOT)`>` |
| [JsonType](-json-type/index.md) | `enum class JsonType` |
| [Moshi](-moshi.md) | `object Moshi : `[`ConfigurableMoshi`](-configurable-moshi/index.md) |
| [Xml](-xml/index.md) | `object Xml` |

### Exceptions

| Name | Summary |
|---|---|
| [InvalidJsonException](-invalid-json-exception/index.md) | `class InvalidJsonException : `[`Exception`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html) |
