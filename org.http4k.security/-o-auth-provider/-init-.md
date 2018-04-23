[http4k](../../index.md) / [org.http4k.security](../index.md) / [OAuthProvider](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`OAuthProvider(providerConfig: `[`OAuthProviderConfig`](../-o-auth-provider-config/index.md)`, client: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, callbackUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, oAuthPersistence: `[`OAuthPersistence`](../-o-auth-persistence/index.md)`, modifyAuthState: (`[`Uri`](../../org.http4k.core/-uri/index.md)`) -> `[`Uri`](../../org.http4k.core/-uri/index.md)` = { it }, generateCrsf: `[`CsrfGenerator`](../-csrf-generator.md)` = SECURE_CSRF)`

Provides a configured set of objects for use with an OAuth2 provider.

