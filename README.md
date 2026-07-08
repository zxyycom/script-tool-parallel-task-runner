# parallel-task-runner

Parallel task scheduling for TypeScript script tooling.

## Use

Import from `src/index.ts`.

This repository provides task normalization, dependency graph validation, concurrency, mutex scheduling, and lifecycle hooks. It depends on an adjacent `../foundation` source checkout.

## Checks

- `bun run typecheck`
- `bun run lint`
- `bun run test`
