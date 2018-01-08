https://github.com/swagger-api/swagger-codegen/issues/6223#issuecomment-324475821

```
A common misconception is that $ref is allowed anywhere in an OpenAPI specification file. Actually $ref is only allowed in places where the OpenAPI 3.0 Specification explicitly states that the value may be a reference.

For example, $ref cannot be used in the info section and directly under paths:

```