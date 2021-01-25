---
id: version-4.0.0-alpha.12-getting-started
title: Getting Started
original_id: getting-started
---

GraphQL Kotlin is a collection of libraries, built on top of [graphql-java](https://www.graphql-java.com/), that aim to simplify running GraphQL in Kotlin.

## Installation

Using a JVM dependency manager, simply link any `graphql-kotlin-*` library to your project.

<!--DOCUSAURUS_CODE_TABS-->
<!--Gradle Kotlin-->
```kotlin
implementation("com.expediagroup", "graphql-kotlin-spring-server", latestVersion)
```
<!--Maven-->
```xml
<dependency>
    <groupId>com.expediagroup</groupId>
    <artifactId>graphql-kotlin-spring-server</artifactId>
    <version>${latestVersion}</version>
</dependency>
```
<!--END_DOCUSAURUS_CODE_TABS-->

## Generating a Schema

You can use `graphql-kotlin-schema-generator` to generate a schema from Kotlin code and expose it with any server library.

See the docs in [Schema Generator Getting Started](./schema-generator/schema-generator-getting-started.md).

### Apollo Federation

Using `graphql-kotlin-federation`, you can generate an [Apollo Federation](https://www.apollographql.com/docs/apollo-server/federation/federation-spec/) compliant schema.

See the docs in [Apollo Federation](./federated/apollo-federation.md).

## Running a Server
`graphql-kotlin-server` is a combination of the schema generator, federation, and server libraries. If you are looking to run a GraphQL server, this is the place to start.

See the docs in [GraphQL Kotlin Server](./server/graphql-server.md).

## Creating a Client
`graphql-kotlin-plugins` can be used to generate a `graphql-kotlin-client` from an existing schema that is easy to use and type-safe.

See the docs in [Client Overview](./client/client-overview.md).

## Examples

The `examples` module is a collection of working code and examples on how to use all of the `graphql-kotlin` modules.

See the [example docs](./examples.md) for more info.

## Blogs and Videos

You can find more posts and recorded conference talks on GraphQL and `graphql-kotlin` on our [Blogs and Videos](./blogs-and-videos.md) page.

## Additional resources

* [GraphQL](https://graphql.org/)
* [graphql-java](https://www.graphql-java.com/documentation/)