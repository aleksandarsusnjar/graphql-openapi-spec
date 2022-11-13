# graphql-openapi-spec

This project aims to contain a generic OpenAPI specification for GraphQL APIs, potentially multiple versions of it.

This specification is not required to use GraphQL APIs. GraphQL does a great job of providing its own schema specification and documentation itself, through a concept called "introspection". When and why do we need an OpenAPI specification, then? There are multiple reasons for this.

1. **Established legacy processes.** We sometimes face manual and/or automated governance processes left over from a distant past. These may require developers to supply Swagger or OpenAPI specifications before they can expose their APIs. 
2. **Describing GraphQL.** People often assume scary things about GraphQL before they learn about it, including that it is more different than it is. They sometimes fear that their clients will have hard time accessing GraphQL but are perfectly comfortable with APIs that can be specified via OpenAPI specs. This specification here can be used to show them, in a language they understand, that GraphQL is friendly and may just be very similar to what they were thinking of themselves


