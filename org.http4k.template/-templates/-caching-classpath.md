[http4k](../../index.md) / [org.http4k.template](../index.md) / [Templates](index.md) / [CachingClasspath](./-caching-classpath.md)

# CachingClasspath

`abstract fun CachingClasspath(baseClasspathPackage: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = ""): `[`TemplateRenderer`](../-template-renderer.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/template/Templates.kt#L23)

Loads and caches templates from the compiled classpath

### Parameters

`baseClasspathPackage` - the root package to load from (defaults to root)