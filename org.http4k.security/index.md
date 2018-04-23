[http4k](../index.md) / [org.http4k.security](./index.md)

## Package org.http4k.security

### Types

| Name | Summary |
|---|---|
| [AccessTokenContainer](-access-token-container/index.md) | `data class AccessTokenContainer` |
| [CrossSiteRequestForgeryToken](-cross-site-request-forgery-token/index.md) | `data class CrossSiteRequestForgeryToken` |
| [InsecureCookieBasedOAuthPersistence](-insecure-cookie-based-o-auth-persistence/index.md) | `open class InsecureCookieBasedOAuthPersistence : `[`OAuthPersistence`](-o-auth-persistence/index.md)<br>This is an example implementation which stores CSRF and AccessTokenEnvelope values in an INSECURE client-side cookie. Access-tokens for end-services are fully available to the browser so do not use this in production! |
| [OAuthCallback](-o-auth-callback/index.md) | `class OAuthCallback : `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [OAuthPersistence](-o-auth-persistence/index.md) | `interface OAuthPersistence`<br>Provides persistence for OAuth lifecycle values: |
| [OAuthProvider](-o-auth-provider/index.md) | `class OAuthProvider`<br>Provides a configured set of objects for use with an OAuth2 provider. |
| [OAuthProviderConfig](-o-auth-provider-config/index.md) | `data class OAuthProviderConfig` |
| [OAuthRedirectionFilter](-o-auth-redirection-filter/index.md) | `class OAuthRedirectionFilter : `[`Filter`](../org.http4k.core/-filter/index.md) |

### Type Aliases

| Name | Summary |
|---|---|
| [CsrfGenerator](-csrf-generator.md) | `typealias CsrfGenerator = () -> `[`CrossSiteRequestForgeryToken`](-cross-site-request-forgery-token/index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [auth0](auth0.md) | `fun OAuthProvider.Companion.auth0(auth0Uri: `[`Uri`](../org.http4k.core/-uri/index.md)`, client: `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](-o-auth-persistence/index.md)`): `[`OAuthProvider`](-o-auth-provider/index.md)<br>Preconfigured OAuthProviders go here... |
| [dropbox](dropbox.md) | `fun OAuthProvider.Companion.dropbox(client: `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](-o-auth-persistence/index.md)`): `[`OAuthProvider`](-o-auth-provider/index.md) |
| [gitHub](git-hub.md) | `fun OAuthProvider.Companion.gitHub(client: `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](-o-auth-persistence/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = listOf("user")): `[`OAuthProvider`](-o-auth-provider/index.md) |
| [google](google.md) | `fun OAuthProvider.Companion.google(client: `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](-o-auth-persistence/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = listOf("openid")): `[`OAuthProvider`](-o-auth-provider/index.md) |
| [soundCloud](sound-cloud.md) | `fun OAuthProvider.Companion.soundCloud(client: `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](-o-auth-persistence/index.md)`): `[`OAuthProvider`](-o-auth-provider/index.md) |
