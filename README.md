# GraphQL Fundamentals

Welcome to my GraphQL fundamentals repository. This collection of topics covers the basic concepts of GraphQL. Whether you're new to GraphQL or looking to reinforce your understanding, you'll find valuable information here.

## Table of Contents

- [What is GraphQL?](#what-is-graphql)
- [Query Basics](#query-basics)
- [Making a GraphQL Server (with Apollo)](#making-a-graphql-server-with-apollo)
- [Schema & Types](#schema--types)
- [Resolver Functions](#resolver-functions)
- [Query Variables](#query-variables)
- [Related Data](#related-data)
- [Mutations (Adding & Deleting Data)](#mutations-adding--deleting-data)
- [Update Mutation](#update-mutation)

## What is GraphQL?

GraphQL is a query language for your API, and a runtime for executing those queries by a server. It provides a more efficient, powerful, and flexible alternative to the traditional REST API. GraphQL allows clients to request only the data they need, reducing over-fetching and under-fetching of data.

## Query Basics

In GraphQL, queries are used to request specific data from a GraphQL server. You can specify exactly what data you need, and the server will respond with that data in a structured JSON format. GraphQL queries are more flexible than traditional REST endpoints, as clients can request multiple related pieces of data in a single query.

## Making a GraphQL Server (with Apollo)

Apollo is a popular library for building GraphQL servers in JavaScript. With Apollo, you can set up a GraphQL server quickly and easily. It simplifies tasks like schema definition, data fetching, and more, making it a powerful tool for developing GraphQL APIs.

## Schema & Types

The GraphQL schema defines the structure of your API, including the types of data that can be queried and the relationships between them. GraphQL uses a schema definition language (SDL) to define these types. Types can represent objects, scalars, enums, and more, providing a clear contract between clients and servers.

## Resolver Functions

Resolver functions in GraphQL are responsible for fetching the actual data for a query. They specify how to retrieve data from your data sources, such as databases or APIs. Resolver functions are associated with specific fields in your schema and are a crucial part of making your GraphQL API functional.

## Query Variables

Query variables in GraphQL allow you to parameterize your queries. Instead of hardcoding values directly into a query, you can use variables to pass dynamic values. This enhances reusability and flexibility in your queries.

## Related Data

In GraphQL, you can retrieve related data efficiently. By specifying nested fields in your queries, you can retrieve data and its related information in a single request. This feature helps reduce the "N+1" query problem often seen in RESTful APIs.

## Mutations (Adding & Deleting Data)

GraphQL mutations are used for modifying data on the server. You can use mutations to add, update, or delete records. Mutations are similar to queries but are used to perform write operations instead.

## Update Mutation

Update mutations in GraphQL allow you to modify existing data on the server. They provide a structured way to update specific fields of a record, making it easy to perform partial updates to your data.

## Resources

Find additional resources, tutorials, and documentation to continue your journey into GraphQL fundamentals.

Feel free to explore the contents of this repository and use the examples as references for your GraphQL projects. Happy learning!




Course: https://www.youtube.com/watch?v=5199E50O7SI&ab_channel=freeCodeCamp.org
Repo: https://github.com/iamshaunjp/graphql-crash-course/tree/main
