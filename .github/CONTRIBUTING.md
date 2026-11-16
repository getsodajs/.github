# Contributing

Thank you for helping with Soda.

## Setup

Soda is developed with [Bun](https://bun.sh) 1.4 or later.

```bash
bun install
bun run lint
bun run typecheck
bun run build
bun run test
```

## Changes

- Open an issue first for a new feature, so we can agree on the API before the code.
- One change per pull request, with tests for the behaviour it adds or fixes.
- Update `docs/` in the same pull request when the change is visible to users.
- Commit messages and pull request titles follow [Conventional Commits](https://www.conventionalcommits.org): `feat(http): ...`, `fix(di): ...`, `docs: ...`.
- The packages share one version and are released together from a tag; maintainers do the releases.
