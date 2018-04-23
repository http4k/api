[http4k](../../index.md) / [org.http4k.core](../index.md) / [Status](./index.md)

# Status

`data class Status` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/Status.kt#L3)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Status(code: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [clientError](client-error.md) | `val clientError: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [code](code.md) | `val code: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [description](description.md) | `val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [informational](informational.md) | `val informational: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [redirection](redirection.md) | `val redirection: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [serverError](server-error.md) | `val serverError: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [successful](successful.md) | `val successful: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Functions

| Name | Summary |
|---|---|
| [description](description.md) | `fun description(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Status`](./index.md) |
| [equals](equals.md) | `fun equals(other: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hashCode](hash-code.md) | `fun hashCode(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [ACCEPTED](-a-c-c-e-p-t-e-d.md) | `val ACCEPTED: `[`Status`](./index.md) |
| [BAD_GATEWAY](-b-a-d_-g-a-t-e-w-a-y.md) | `val BAD_GATEWAY: `[`Status`](./index.md) |
| [BAD_REQUEST](-b-a-d_-r-e-q-u-e-s-t.md) | `val BAD_REQUEST: `[`Status`](./index.md) |
| [CLIENT_TIMEOUT](-c-l-i-e-n-t_-t-i-m-e-o-u-t.md) | `val CLIENT_TIMEOUT: `[`Status`](./index.md) |
| [CONFLICT](-c-o-n-f-l-i-c-t.md) | `val CONFLICT: `[`Status`](./index.md) |
| [CONNECTION_REFUSED](-c-o-n-n-e-c-t-i-o-n_-r-e-f-u-s-e-d.md) | `val CONNECTION_REFUSED: `[`Status`](./index.md) |
| [CONTINUE](-c-o-n-t-i-n-u-e.md) | `val CONTINUE: `[`Status`](./index.md) |
| [CREATED](-c-r-e-a-t-e-d.md) | `val CREATED: `[`Status`](./index.md) |
| [EXPECTATION_FAILED](-e-x-p-e-c-t-a-t-i-o-n_-f-a-i-l-e-d.md) | `val EXPECTATION_FAILED: `[`Status`](./index.md) |
| [FORBIDDEN](-f-o-r-b-i-d-d-e-n.md) | `val FORBIDDEN: `[`Status`](./index.md) |
| [FOUND](-f-o-u-n-d.md) | `val FOUND: `[`Status`](./index.md) |
| [GATEWAY_TIMEOUT](-g-a-t-e-w-a-y_-t-i-m-e-o-u-t.md) | `val GATEWAY_TIMEOUT: `[`Status`](./index.md) |
| [GONE](-g-o-n-e.md) | `val GONE: `[`Status`](./index.md) |
| [HTTP_VERSION_NOT_SUPPORTED](-h-t-t-p_-v-e-r-s-i-o-n_-n-o-t_-s-u-p-p-o-r-t-e-d.md) | `val HTTP_VERSION_NOT_SUPPORTED: `[`Status`](./index.md) |
| [INTERNAL_SERVER_ERROR](-i-n-t-e-r-n-a-l_-s-e-r-v-e-r_-e-r-r-o-r.md) | `val INTERNAL_SERVER_ERROR: `[`Status`](./index.md) |
| [I_M_A_TEAPOT](-i_-m_-a_-t-e-a-p-o-t.md) | `val I_M_A_TEAPOT: `[`Status`](./index.md) |
| [LENGTH_REQUIRED](-l-e-n-g-t-h_-r-e-q-u-i-r-e-d.md) | `val LENGTH_REQUIRED: `[`Status`](./index.md) |
| [METHOD_NOT_ALLOWED](-m-e-t-h-o-d_-n-o-t_-a-l-l-o-w-e-d.md) | `val METHOD_NOT_ALLOWED: `[`Status`](./index.md) |
| [MOVED_PERMANENTLY](-m-o-v-e-d_-p-e-r-m-a-n-e-n-t-l-y.md) | `val MOVED_PERMANENTLY: `[`Status`](./index.md) |
| [MULTIPLE_CHOICES](-m-u-l-t-i-p-l-e_-c-h-o-i-c-e-s.md) | `val MULTIPLE_CHOICES: `[`Status`](./index.md) |
| [NON_AUTHORITATIVE_INFORMATION](-n-o-n_-a-u-t-h-o-r-i-t-a-t-i-v-e_-i-n-f-o-r-m-a-t-i-o-n.md) | `val NON_AUTHORITATIVE_INFORMATION: `[`Status`](./index.md) |
| [NOT_ACCEPTABLE](-n-o-t_-a-c-c-e-p-t-a-b-l-e.md) | `val NOT_ACCEPTABLE: `[`Status`](./index.md) |
| [NOT_FOUND](-n-o-t_-f-o-u-n-d.md) | `val NOT_FOUND: `[`Status`](./index.md) |
| [NOT_IMPLEMENTED](-n-o-t_-i-m-p-l-e-m-e-n-t-e-d.md) | `val NOT_IMPLEMENTED: `[`Status`](./index.md) |
| [NOT_MODIFIED](-n-o-t_-m-o-d-i-f-i-e-d.md) | `val NOT_MODIFIED: `[`Status`](./index.md) |
| [NO_CONTENT](-n-o_-c-o-n-t-e-n-t.md) | `val NO_CONTENT: `[`Status`](./index.md) |
| [OK](-o-k.md) | `val OK: `[`Status`](./index.md) |
| [PARTIAL_CONTENT](-p-a-r-t-i-a-l_-c-o-n-t-e-n-t.md) | `val PARTIAL_CONTENT: `[`Status`](./index.md) |
| [PAYMENT_REQUIRED](-p-a-y-m-e-n-t_-r-e-q-u-i-r-e-d.md) | `val PAYMENT_REQUIRED: `[`Status`](./index.md) |
| [PRECONDITION_FAILED](-p-r-e-c-o-n-d-i-t-i-o-n_-f-a-i-l-e-d.md) | `val PRECONDITION_FAILED: `[`Status`](./index.md) |
| [PROXY_AUTHENTICATION_REQUIRED](-p-r-o-x-y_-a-u-t-h-e-n-t-i-c-a-t-i-o-n_-r-e-q-u-i-r-e-d.md) | `val PROXY_AUTHENTICATION_REQUIRED: `[`Status`](./index.md) |
| [REQUESTED_RANGE_NOT_SATISFIABLE](-r-e-q-u-e-s-t-e-d_-r-a-n-g-e_-n-o-t_-s-a-t-i-s-f-i-a-b-l-e.md) | `val REQUESTED_RANGE_NOT_SATISFIABLE: `[`Status`](./index.md) |
| [REQUEST_ENTITY_TOO_LARGE](-r-e-q-u-e-s-t_-e-n-t-i-t-y_-t-o-o_-l-a-r-g-e.md) | `val REQUEST_ENTITY_TOO_LARGE: `[`Status`](./index.md) |
| [REQUEST_TIMEOUT](-r-e-q-u-e-s-t_-t-i-m-e-o-u-t.md) | `val REQUEST_TIMEOUT: `[`Status`](./index.md) |
| [REQUEST_URI_TOO_LONG](-r-e-q-u-e-s-t_-u-r-i_-t-o-o_-l-o-n-g.md) | `val REQUEST_URI_TOO_LONG: `[`Status`](./index.md) |
| [RESET_CONTENT](-r-e-s-e-t_-c-o-n-t-e-n-t.md) | `val RESET_CONTENT: `[`Status`](./index.md) |
| [SEE_OTHER](-s-e-e_-o-t-h-e-r.md) | `val SEE_OTHER: `[`Status`](./index.md) |
| [SERVICE_UNAVAILABLE](-s-e-r-v-i-c-e_-u-n-a-v-a-i-l-a-b-l-e.md) | `val SERVICE_UNAVAILABLE: `[`Status`](./index.md) |
| [SWITCHING_PROTOCOLS](-s-w-i-t-c-h-i-n-g_-p-r-o-t-o-c-o-l-s.md) | `val SWITCHING_PROTOCOLS: `[`Status`](./index.md) |
| [TEMPORARY_REDIRECT](-t-e-m-p-o-r-a-r-y_-r-e-d-i-r-e-c-t.md) | `val TEMPORARY_REDIRECT: `[`Status`](./index.md) |
| [TOO_MANY_REQUESTS](-t-o-o_-m-a-n-y_-r-e-q-u-e-s-t-s.md) | `val TOO_MANY_REQUESTS: `[`Status`](./index.md) |
| [UNAUTHORIZED](-u-n-a-u-t-h-o-r-i-z-e-d.md) | `val UNAUTHORIZED: `[`Status`](./index.md) |
| [UNSATISFIABLE_PARAMETERS](-u-n-s-a-t-i-s-f-i-a-b-l-e_-p-a-r-a-m-e-t-e-r-s.md) | `val UNSATISFIABLE_PARAMETERS: `[`Status`](./index.md) |
| [UNSUPPORTED_MEDIA_TYPE](-u-n-s-u-p-p-o-r-t-e-d_-m-e-d-i-a_-t-y-p-e.md) | `val UNSUPPORTED_MEDIA_TYPE: `[`Status`](./index.md) |
| [USE_PROXY](-u-s-e_-p-r-o-x-y.md) | `val USE_PROXY: `[`Status`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [describeClientError](../../org.http4k.client/describe-client-error.md) | `fun `[`Status`](./index.md)`.describeClientError(e: `[`Exception`](http://docs.oracle.com/javase/6/docs/api/java/lang/Exception.html)`): `[`Status`](./index.md) |
