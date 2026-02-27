State Management — Roadmap + Free Resources
Phase 1 — Core React State (Foundation)
1. Local Component State

Learn:

useState

Functional updates

Derived state

Avoiding unnecessary state

Resources:

useState Docs
https://react.dev/reference/react/useState

Managing State
https://react.dev/learn/managing-state

2. Lifting State Up

Learn:

Sharing state between components

Parent-controlled state

Avoiding duplicated state

Resource:

Sharing State Between Components
https://react.dev/learn/sharing-state-between-components

Phase 2 — Side Effects & Async State
3. useEffect + Data Fetching

Learn:

Fetching API data

Dependency arrays

Cleanup functions

Avoiding infinite loops

Resources:

useEffect Docs
https://react.dev/reference/react/useEffect

Data Fetching in React
https://react.dev/learn/synchronizing-with-effects

Phase 3 — Context API (Global State Basics)
4. Context API

Learn:

createContext

useContext

Provider pattern

Avoiding prop drilling

When NOT to use Context

Resources:

useContext Docs
https://react.dev/reference/react/useContext

Passing Data Deeply
https://react.dev/learn/passing-data-deeply-with-context

Phase 4 — Reducer Pattern
5. useReducer

Learn:

Reducer function pattern

Action types

Dispatch

State transitions

Resources:

useReducer Docs
https://react.dev/reference/react/useReducer

Phase 5 — Server State vs Client State
6. Server State Management

Learn:

Difference between client state and server state

Caching API responses

Background refetching

Loading & error states

Tool:

TanStack Query (React Query)

Resources:

TanStack Query Docs
https://tanstack.com/query/latest

React Query Tutorial (YouTube search)
https://www.youtube.com/results?search_query=react+query+tutorial

Phase 6 — External State Libraries
7. Zustand (Recommended Lightweight)

Learn:

Creating stores

Global state without boilerplate

Selective re-renders

Resources:

Zustand Docs
https://zustand-demo.pmnd.rs/

Zustand GitHub
https://github.com/pmndrs/zustand

8. Redux (For Large Apps)

Learn:

Redux principles

Store

Actions

Reducers

Redux Toolkit

Resources:

Redux Docs
https://redux.js.org/

Redux Toolkit
https://redux-toolkit.js.org/

Phase 7 — Advanced Patterns
9. Derived State & Memoization

Learn:

useMemo

useCallback

Preventing unnecessary renders

Resource:

Optimizing Performance
https://react.dev/learn/optimizing-performance

10. State Normalization

Learn:

Flattening nested state

Avoiding deeply nested updates

Immutable updates

Resource:

Redux Normalization Guide
https://redux.js.org/usage/structuring-reducers/normalizing-state-shape

Phase 8 — Next.js State Strategy
11. State in Next.js

Learn:

Server Components vs Client Components

When state belongs on server

When state belongs in client

Auth session state

Resources:

Next.js Rendering Docs
https://nextjs.org/docs/app/building-your-application/rendering

Auth.js Docs
https://authjs.dev/

Execution Order

Master useState

Learn lifting state

Learn useEffect with API calls

Learn Context API

Learn useReducer

Learn TanStack Query (server state)

Learn Zustand

Study Redux (optional advanced)

Optimize with memoization

Design proper state boundaries in Next.js
