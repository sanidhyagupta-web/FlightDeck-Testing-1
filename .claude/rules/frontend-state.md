---
paths:
  - "frontend/**/store/**/*.ts" # No frontend code exists in this repository yet. Scoped under frontend/ so it won't fire on an unrelated store/ directory elsewhere in the repo.
---

# State Management Patterns

<!-- CUSTOMIZE: Replace with your state management conventions (RTK Query, Zustand, TanStack Query, etc.) -->

## Service/API Layer
<!-- CUSTOMIZE: Your API service pattern -->
- How API services are defined and injected
- Base query/client configuration

## Cache Management
<!-- CUSTOMIZE: Your caching/invalidation strategy -->
- How to define cache tags on queries
- How to invalidate caches on mutations

## State Slices
<!-- CUSTOMIZE: Your local state patterns -->
- How to define state slices/stores
- Naming conventions
