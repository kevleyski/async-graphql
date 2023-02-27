Define a Scalar

# Macro attributes

| Attribute        | description                                                                                                                                                            | Type   | Optional |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|----------|
| name             | Scalar name                                                                                                                                                            | string | Y        |
| name_type        | If `true`, the scalar name will be specified from [`async_graphql::TypeName`](https://docs.rs/async-graphql/latest/async_graphql/trait.TypeName.html) trait            | bool   | Y        |
| specified_by_url | Provide a specification URL for this scalar type, it must link to a human-readable specification of the data format, serialization and coercion rules for this scalar. | string | Y        |
| inaccessible     | Indicate that a scalar is not accessible from a supergraph when using Apollo Federation                                                                                | bool   | Y        |
| tag              | Arbitrary string metadata that will be propagated to the supergraph when using Apollo Federation. This attribute is repeatable                                         | string | Y        |