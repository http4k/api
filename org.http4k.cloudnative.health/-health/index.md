[http4k](../../index.md) / [org.http4k.cloudnative.health](../index.md) / [Health](./index.md)

# Health

`object Health`

Represents the set of operational endpoints to ensure that a particular app is working ok.
By default provides Readiness and Liveness endpoints, but extra routes can be passed, as
can a different renderer implementation for the ReadinessCheck results.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(vararg extraRoutes: `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)`, checks: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ReadinessCheck`](../-readiness-check/index.md)`> = emptyList(), renderer: `[`ReadinessCheckResultRenderer`](../-readiness-check-result-renderer/index.md)` = DefaultReadinessCheckResultRenderer): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
