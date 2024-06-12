# Composite Execution Schema


## @type

```graphql
directive @type(
  schema: [Schema!]!
) repeatable on OBJECT | INTERFACE | UNION | ENUM | INPUT_OBJECT | SCALAR
```

The type directive is used to specify the source schema that provide this type or parts of this type.

**Arguments:**

- `schema`: The source schema or source schemas that provide this type or parts of this type.

## @type

```graphql
directive @lookup(
  schema: Schema!
  key: String!
  field: [FieldDefinition!]
  map: [FieldSelectionMap!]
) repeatable on OBJECT
```