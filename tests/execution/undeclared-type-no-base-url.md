---
error: true
---

# undeclared-type-no-base-url

```graphql @config
schema @server {
  query: Query
}

type Query {
  users: [User] @http(url: "http://jsonplaceholder.typicode.com/users")
}
```
