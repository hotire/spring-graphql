# GraphQL

![GraphQL](https://ko.wikipedia.org/wiki/%EA%B7%B8%EB%9E%98%ED%94%84QL#/media/%ED%8C%8C%EC%9D%BC:GraphQL_Logo.svg)

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

```
type Query {
  bookById(id: ID): Book 
}

type Book {
  id: ID
  name: String
  pageCount: Int
  author: Author
}

type Author {
  id: ID
  firstName: String
  lastName: String
}

```


### GraphQLProvider

[googlelink]: https://github.com/hotire/spring-graphql/blob/master/src/main/java/com/github/hotire/graphql/GraphQLProvider.java "GraphQLProvider"

```
@Component
public class GraphQLProvider {
...
}
```
 