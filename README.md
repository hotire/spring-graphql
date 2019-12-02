# GraphQL

![GraphQL](/doc/img/logo.png)

## Getting started
- reference : https://www.graphql-java.com/tutorials/getting-started-with-spring-boot/

### dependencies

```
dependencies {
    implementation 'com.graphql-java:graphql-java:11.0' // NEW
    implementation 'com.graphql-java:graphql-java-spring-boot-starter-webmvc:1.0' // NEW
    implementation 'com.google.guava:guava:26.0-jre' // NEW
    implementation 'org.springframework.boot:spring-boot-starter-web'
    testImplementation 'org.springframework.boot:spring-boot-starter-test'
}
```

### Schema

[schema.graphqls](https://github.com/hotire/spring-graphql/blob/master/src/main/resources/schema.graphqls)

### GraphQLProvider

[GraphQLProvider](https://github.com/hotire/spring-graphql/blob/master/src/main/java/com/github/hotire/graphql/GraphQLProvider.java)

 