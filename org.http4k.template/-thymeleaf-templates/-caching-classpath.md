[http4k](../../index.md) / [org.http4k.template](../index.md) / [ThymeleafTemplates](index.md) / [CachingClasspath](./-caching-classpath.md)

# CachingClasspath

`fun CachingClasspath(baseClasspathPackage: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-template-thymeleaf/src/main/kotlin/org/http4k/template/ThymeleafTemplates.kt#L14)

Overrides [Templates.CachingClasspath](../-templates/-caching-classpath.md)

Loads and caches templates from the compiled classpath

### Parameters

`baseClasspathPackage` - the root package to load from (defaults to root)