[http4k](../index.md) / [org.http4k.filter](index.md) / [AwsAuth](./-aws-auth.md)

# AwsAuth

`fun `[`ClientFilters`](-client-filters/index.md)`.AwsAuth(scope: `[`AwsCredentialScope`](../org.http4k.aws/-aws-credential-scope/index.md)`, credentials: `[`AwsCredentials`](../org.http4k.aws/-aws-credentials/index.md)`, clock: Clock = Clock.systemDefaultZone(), payloadMode: `[`Mode`](-payload/-mode/index.md)` = Payload.Mode.Signed): `[`Filter`](../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-aws/src/main/kotlin/org/http4k/filter/awsExtensions.kt#L19)