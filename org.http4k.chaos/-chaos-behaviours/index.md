[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosBehaviours](./index.md)

# ChaosBehaviours

`object ChaosBehaviours` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosBehaviours.kt#L32)

### Types

| Name | Summary |
|---|---|
| [BlockThread](-block-thread/index.md) | `object BlockThread`<br>Blocks the current thread. |
| [EatMemory](-eat-memory/index.md) | `object EatMemory`<br>Allocates memory in a busy loop until an OOM occurs. |
| [KillProcess](-kill-process/index.md) | `object KillProcess`<br>System exits from the process. |
| [Latency](-latency/index.md) | `object Latency`<br>Blocks the thread for a random amount of time within the allocated range. |
| [NoBody](-no-body/index.md) | `object NoBody`<br>Strips the body from a response. |
| [None](-none/index.md) | `object None`<br>Does absolutely nothing. |
| [ReturnStatus](-return-status/index.md) | `object ReturnStatus`<br>Returns an empty response with the appropriate status. |
| [StackOverflow](-stack-overflow/index.md) | `object StackOverflow`<br>Allocates memory in a busy loop until an OOM occurs. |
| [ThrowException](-throw-exception/index.md) | `object ThrowException`<br>Throws the appropriate exception. |
| [Variable](-variable/index.md) | `class Variable : `[`ChaosBehaviour`](../-chaos-behaviour.md)<br>Provide a means of modifying a ChaosBehaviour at runtime. |