[http4k](../../index.md) / [org.http4k.servirtium](../index.md) / [InteractionStorage](./index.md)

# InteractionStorage

`interface InteractionStorage : `[`Supplier`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Supplier.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>, `[`Consumer`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Consumer.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>`

Provides storage for the recorded Servirtium interaction data.

### Functions

| Name | Summary |
|---|---|
| [clean](clean.md) | `abstract fun clean(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [Disk](-disk.md) | `fun Disk(root: `[`File`](https://docs.oracle.com/javase/9/docs/api/java/io/File.html)`): `[`StorageProvider`](../-storage-provider.md) |
| [InMemory](-in-memory.md) | `fun InMemory(): `[`StorageProvider`](../-storage-provider.md) |
