[http4k](../../index.md) / [org.http4k.webdriver](../index.md) / [Http4kWebDriver](./index.md)

# Http4kWebDriver

`class Http4kWebDriver : WebDriver`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Http4kWebDriver(initialHandler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [status](status.md) | `val status: `[`Status`](../../org.http4k.core/-status/index.md)`?` |

### Functions

| Name | Summary |
|---|---|
| [close](close.md) | `fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [findElement](find-element.md) | `fun findElement(by: By): WebElement?` |
| [findElements](find-elements.md) | `fun findElements(by: By): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<WebElement>?` |
| [get](get.md) | `fun get(url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun get(uri: `[`Uri`](../../org.http4k.core/-uri/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [getCurrentUrl](get-current-url.md) | `fun getCurrentUrl(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getPageSource](get-page-source.md) | `fun getPageSource(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getTitle](get-title.md) | `fun getTitle(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getWindowHandle](get-window-handle.md) | `fun getWindowHandle(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getWindowHandles](get-window-handles.md) | `fun getWindowHandles(): `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [manage](manage.md) | `fun manage(): Options` |
| [navigate](navigate.md) | `fun navigate(): `[`Http4KNavigation`](../-http4-k-navigation/index.md) |
| [quit](quit.md) | `fun quit(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [switchTo](switch-to.md) | `fun switchTo(): TargetLocator` |

### Extension Functions

| Name | Summary |
|---|---|
| [invoke](../invoke.md) | DSL-helper so we can use this webdriver in a lambda-with-receiver context`operator fun `[`Http4kWebDriver`](./index.md)`.invoke(fn: `[`Http4kWebDriver`](./index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Http4kWebDriver`](./index.md) |
