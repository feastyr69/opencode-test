# AGENTS.md

Commands and conventions for working with this repository.

## Commands

- `pnpm install`
- `pnpm build` — build all packages
- `pnpm test` — run all tests
- `pnpm test <file>` — run a single test file
- `pnpm lint` — run ESLint
- `pnpm typecheck` — run TypeScript type checks

## Architecture

- Monorepo managed with pnpm workspaces.
- `packages/*` contains all source code.
- Entry points are defined in each package's `package.json`.

## Notes

- This repository is empty. The user is testing OpenCode's AGENTS.md generation on an empty repository.
- Do not assume any commands or architecture exist until files are added.
