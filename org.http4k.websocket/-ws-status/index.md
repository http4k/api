[http4k](../../index.md) / [org.http4k.websocket](../index.md) / [WsStatus](./index.md)

# WsStatus

`data class WsStatus` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/websocket/WsStatus.kt#L3)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `WsStatus(code: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [code](code.md) | `val code: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [description](description.md) | `val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [description](description.md) | `fun description(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`WsStatus`](./index.md) |
| [equals](equals.md) | `fun equals(other: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hashCode](hash-code.md) | `fun hashCode(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [ABNORMAL_CLOSE](-a-b-n-o-r-m-a-l_-c-l-o-s-e.md) | `val ABNORMAL_CLOSE: `[`WsStatus`](./index.md) |
| [BUGGYCLOSE](-b-u-g-g-y-c-l-o-s-e.md) | `val BUGGYCLOSE: `[`WsStatus`](./index.md) |
| [EXTENSION](-e-x-t-e-n-s-i-o-n.md) | `val EXTENSION: `[`WsStatus`](./index.md) |
| [FLASHPOLICY](-f-l-a-s-h-p-o-l-i-c-y.md) | `val FLASHPOLICY: `[`WsStatus`](./index.md) |
| [GOING_AWAY](-g-o-i-n-g_-a-w-a-y.md) | `val GOING_AWAY: `[`WsStatus`](./index.md) |
| [NEVER_CONNECTED](-n-e-v-e-r_-c-o-n-n-e-c-t-e-d.md) | `val NEVER_CONNECTED: `[`WsStatus`](./index.md) |
| [NOCODE](-n-o-c-o-d-e.md) | `val NOCODE: `[`WsStatus`](./index.md) |
| [NORMAL](-n-o-r-m-a-l.md) | `val NORMAL: `[`WsStatus`](./index.md) |
| [NO_UTF8](-n-o_-u-t-f8.md) | `val NO_UTF8: `[`WsStatus`](./index.md) |
| [POLICY_VALIDATION](-p-o-l-i-c-y_-v-a-l-i-d-a-t-i-o-n.md) | `val POLICY_VALIDATION: `[`WsStatus`](./index.md) |
| [PROTOCOL_ERROR](-p-r-o-t-o-c-o-l_-e-r-r-o-r.md) | `val PROTOCOL_ERROR: `[`WsStatus`](./index.md) |
| [REFUSE](-r-e-f-u-s-e.md) | `val REFUSE: `[`WsStatus`](./index.md) |
| [TLS_ERROR](-t-l-s_-e-r-r-o-r.md) | `val TLS_ERROR: `[`WsStatus`](./index.md) |
| [TOOBIG](-t-o-o-b-i-g.md) | `val TOOBIG: `[`WsStatus`](./index.md) |
| [UNEXPECTED_CONDITION](-u-n-e-x-p-e-c-t-e-d_-c-o-n-d-i-t-i-o-n.md) | `val UNEXPECTED_CONDITION: `[`WsStatus`](./index.md) |
