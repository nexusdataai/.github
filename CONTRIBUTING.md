# Contributing to Nexus Data AI repositories

Thank you for contributing to the NexusAI platform. This file is the **organization default**; individual repositories may add or override guidance in their own `CONTRIBUTING.md`.

## Where to start

1. **Product context** — [nexus-docs](https://github.com/nexusdataai/nexus-docs), especially the [Developer Guide](https://nexusdataai.github.io/nexus-docs/developer/).
2. **Pick the right repo** — see the repository map in [`profile/README.md`](profile/README.md).
3. **Open an issue** — for substantial changes, discuss in the target repo before large PRs.

## Development norms

- **Branches** — feature branches; integrate via pull request to the repo’s primary integration branch (`dev` or `main`, per repo).
- **Tests** — run the repo’s unit/integration tests before requesting review.
- **Security** — do not commit secrets, customer data, or production credentials. Use LocalStack or simulators for local AWS-shaped development where documented.

## Pull requests

- Keep PRs focused; link related issues.
- Update docs in **nexus-docs** when you change user-visible behavior or architecture.
- Follow existing code style (Python: ruff/mypy where configured; TypeScript: ESLint/tsc where configured).

## Code of conduct

Treat collaborators with respect. Harassment or discrimination is not tolerated in project spaces.

## Questions

If unsure which repository owns a change, start with **nexus-docs** or **nexus-ontology** maintainers via issues in those repos.