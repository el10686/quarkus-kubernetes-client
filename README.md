# quarkus-kubernetes-client project

This project has been setup to demonstrate an error when using kubernetes-client
as Quarkus docs prescribe.

This project follows the step by step process of the official docs but using  
`@QuarkusTestResource(KubernetesMockServerTestResource.class)` which is deprecated, but the test is working.

## Running tests

```shell script
./mvnw clean test
```
