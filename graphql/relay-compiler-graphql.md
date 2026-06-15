# Relay Compiler GraphQL API

The Relay Compiler is Meta's ahead-of-time GraphQL compiler that generates optimized runtime artifacts and type-safe code for Relay applications. It processes GraphQL fragments in JavaScript/TypeScript source code, aggregates data requirements, optimizes queries, and generates TypeScript or Flow types. The compiler enforces GraphQL best practices including connection patterns, pagination fragments, and data masking.

## Relay Compiler

**Documentation:** https://relay.dev

**References:**

- Documentation: https://relay.dev/docs/
- GettingStarted: https://relay.dev/docs/getting-started/
- APIReference: https://relay.dev/docs/api-reference/graphql-and-directives/

## Relay Runtime

The Relay Runtime provides the client-side execution environment for Relay applications. It includes the normalized in-memory store, network layer, and React hooks including usePreloadedQuery, useFragment, usePaginationFragment, useRefetchableFragment, useMutation, and useSubscription for declarative data-fetching in React components.

**Documentation:** https://relay.dev/docs/api-reference/

**References:**

- Documentation: https://relay.dev/docs/api-reference/
