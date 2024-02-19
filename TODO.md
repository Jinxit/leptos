- core examples
    - [x] counter
    - [x] counters
    - [x] fetch
    - [x] todomvc 
    - [ ] parent\_child
    - [ ] router
    - [ ] slots 
    - [ ] hackernews
    - [ ] counter\_isomorphic
    - [ ] todo\_app\_sqlite
- ErrorBoundary
- ssr examples
- reactivity 
    - Effects need to be stored (and not mem::forget)
    - Signal wrappers
    - SignalDispose implementations on all Copy types
    - untracked access warnings
- callbacks
    - unsync StoredValue
        - use this to store Effects
- SSR
    - escaping HTML correctly (attributes + text nodes)
- router
    - nested routes
- \_meta package (and use in hackernews)
- integrations
- update tests
- hackernews example
  - TODOs
  - Suspense/Transition/Await components
  - nicer routing components
  - async routing (waiting for data to load before navigation)
  - `<A>` component
  - figure out rebuilding issues: list (needs new signal IDs) vs. regular rebuild