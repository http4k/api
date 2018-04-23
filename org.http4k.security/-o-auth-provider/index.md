[http4k](../../index.md) / [org.http4k.security](../index.md) / [OAuthProvider](./index.md)

# OAuthProvider

`class OAuthProvider` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/OAuthProvider.kt#L13)

Provides a configured set of objects for use with an OAuth2 provider.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `OAuthProvider(providerConfig: `[`OAuthProviderConfig`](../-o-auth-provider-config/index.md)`, client: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, callbackUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, oAuthPersistence: `[`OAuthPersistence`](../-o-auth-persistence/index.md)`, modifyAuthState: (`[`Uri`](../../org.http4k.core/-uri/index.md)`) -> `[`Uri`](../../org.http4k.core/-uri/index.md)` = { it }, generateCrsf: `[`CsrfGenerator`](../-csrf-generator.md)` = SECURE_CSRF)`<br>Provides a configured set of objects for use with an OAuth2 provider. |

### Properties

| Name | Summary |
|---|---|
| [api](api.md) | `val api: `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |
| [authFilter](auth-filter.md) | `val authFilter: `[`Filter`](../../org.http4k.core/-filter/index.md) |
| [callback](callback.md) | `val callback: `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |

### Companion Object Extension Functions

| Name | Summary |
|---|---|
| [auth0](../auth0.md) | `fun OAuthProvider.Companion.auth0(auth0Uri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, client: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](../-o-auth-persistence/index.md)`): `[`OAuthProvider`](./index.md)<br>Preconfigured OAuthProviders go here... |
| [dropbox](../dropbox.md) | `fun OAuthProvider.Companion.dropbox(client: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](../-o-auth-persistence/index.md)`): `[`OAuthProvider`](./index.md) |
| [gitHub](../git-hub.md) | `fun OAuthProvider.Companion.gitHub(client: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](../-o-auth-persistence/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = listOf("user")): `[`OAuthProvider`](./index.md) |
| [google](../google.md) | `fun OAuthProvider.Companion.google(client: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](../-o-auth-persistence/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = listOf("openid")): `[`OAuthProvider`](./index.md) |
| [soundCloud](../sound-cloud.md) | `fun OAuthProvider.Companion.soundCloud(client: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](../-o-auth-persistence/index.md)`): `[`OAuthProvider`](./index.md) |
