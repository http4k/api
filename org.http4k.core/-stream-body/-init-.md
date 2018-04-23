[http4k](../../index.md) / [org.http4k.core](../index.md) / [StreamBody](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`StreamBody(stream: `[`InputStream`](http://docs.oracle.com/javase/6/docs/api/java/io/InputStream.html)`, length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?)`

Represents a body that is backed by a (lazy) InputStream. Operating with StreamBody has a number of potential
gotchas:

1. Attempts to consume the stream will pull all of the contents into memory, and should thus be avoided.
This includes calling `equals()` and `payload`
2. If this Body is NOT being returned to the caller (via a Server implementation or otherwise), close() should be called.
3. Depending on the source of the stream, this body may or may not contain a known length. Attempts to get the
length when there is none will cause an IllegalStateException to be thrown.
