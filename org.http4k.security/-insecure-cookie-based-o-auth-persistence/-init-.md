[http4k](../../index.md) / [org.http4k.security](../index.md) / [InsecureCookieBasedOAuthPersistence](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`InsecureCookieBasedOAuthPersistence(cookieNamePrefix: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, cookieValidity: Duration = Duration.ofHours(1), clock: Clock = Clock.systemUTC())`

This is an example implementation which stores CSRF and AccessTokenEnvelope values in an INSECURE client-side cookie.
Access-tokens for end-services are fully available to the browser so do not use this in production!

