[http4k](../../index.md) / [org.http4k.webdriver](../index.md) / [Page](./index.md)

# Page

`data class Page` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-webdriver/src/main/kotlin/org/http4k/webdriver/Page.kt#L9)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Page(status: `[`Status`](../../org.http4k.core/-status/index.md)`, navigate: `[`Navigate`](../-navigate.md)`, handle: `[`UUID`](http://docs.oracle.com/javase/6/docs/api/java/util/UUID.html)`, url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, contents: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, previous: `[`Page`](./index.md)`? = null, next: `[`Page`](./index.md)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [contents](contents.md) | `val contents: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [handle](handle.md) | `val handle: `[`UUID`](http://docs.oracle.com/javase/6/docs/api/java/util/UUID.html) |
| [next](next.md) | `val next: `[`Page`](./index.md)`?` |
| [previous](previous.md) | `val previous: `[`Page`](./index.md)`?` |
| [status](status.md) | `val status: `[`Status`](../../org.http4k.core/-status/index.md) |
| [title](title.md) | `val title: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [url](url.md) | `val url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [findElement](find-element.md) | `fun findElement(by: By): WebElement?` |
| [findElements](find-elements.md) | `fun findElements(by: By): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<WebElement>` |
| [firstElement](first-element.md) | `fun firstElement(): `[`JSoupWebElement`](../-j-soup-web-element/index.md)`?` |
