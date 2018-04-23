[http4k](../../index.md) / [org.http4k.serverless.lambda](../index.md) / [LambdaFunction](./index.md)

# LambdaFunction

`class LambdaFunction` [(source)](https://github.com/http4k/http4k/blob/master/http4k-serverless-lambda/src/main/kotlin/org/http4k/serverless/lambda/LambdaFunction.kt#L16)

This is the main entry point for the lambda. It uses the local environment
to instantiate the Http4k handler which can be used for further invocations.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `LambdaFunction(env: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = System.getenv())`<br>This is the main entry point for the lambda. It uses the local environment to instantiate the Http4k handler which can be used for further invocations. |

### Functions

| Name | Summary |
|---|---|
| [handle](handle.md) | `fun handle(request: ApiGatewayProxyRequest): ApiGatewayProxyResponse` |
