# Contributing to Jellystat

Thanks for helping out. This guide applies to every repository in the JellyStat organisation.

## Where things go

| You want to… | Go to |
|---|---|
| Report a bug or request a feature | [Jellystat issues](https://github.com/JellyStat/Jellystat/issues/new/choose) |
| Ask a question | [Jellystat discussions](https://github.com/JellyStat/Jellystat/discussions) |
| Change the web interface | [Jellystat-UI](https://github.com/JellyStat/Jellystat-UI) |
| Change the backend, database or background tasks | [JellyStat-API-Core](https://github.com/JellyStat/JellyStat-API-Core) |
| Improve install docs or Docker Compose | [Jellystat](https://github.com/JellyStat/Jellystat) |
| Translate the UI | [TRANSLATING.md](https://github.com/JellyStat/Jellystat-UI/blob/main/TRANSLATING.md) |

## Pull requests

1. For anything bigger than a small fix, open or comment on an issue first so we can agree on the approach.
2. Fork the repository and create a branch from `main`.
3. Keep each pull request to one change, and describe what it does and why.
4. Make sure the checks pass before asking for review:
   - **UI:** `npm test` (formatting, lint, types and Jest).
   - **API:** `dotnet build` and any tests for the area you changed.
5. If you change the UI, add a screenshot to the pull request.
6. Link the issue the pull request fixes, for example `Fixes JellyStat/Jellystat#123`.

## Commit messages

We use [Conventional Commits](https://www.conventionalcommits.org/), for example `fix(sessions): show paused streams` or `feat(i18n): add French`.

## Licence

By contributing, you agree that your contributions are licensed under the GNU General Public License v3.0, the same as the project.
