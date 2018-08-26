[http4k](../../../index.md) / [org.http4k.chaos](../../index.md) / [ChaosTriggers](../index.md) / [PercentageBased](index.md) / [fromEnvironment](./from-environment.md)

# fromEnvironment

`fun fromEnvironment(env: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = System::getenv, defaultPercentage: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 50, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "CHAOS_PERCENTAGE"): `[`Trigger`](../../-trigger.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosTriggers.kt#L81)

Get a percentage from the environment.
Defaults to CHAOS_PERCENTAGE and a value of 50%
