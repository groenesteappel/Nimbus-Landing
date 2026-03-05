# Contributing

Thanks for your interest in contributing to the Nimbus landing page!

## Branch Naming

Please use the following prefixes:

- `feature/` — new features or sections
- `fix/` — bug fixes
- `chore/` — maintenance, dependency updates

## Pull Requests

- Use [conventional commit](https://www.conventionalcommits.org/) format for PR titles
- Example: `feat(pricing): add annual billing toggle`
- Keep PRs focused — one change per PR

## Local Development

1. Fork the repository
2. Clone your fork
3. Run `npm install`
4. Run `npm run dev`
5. Open a PR when ready

## CI/CD

All PRs are checked automatically for branch naming and title conventions. The staging site redeploys periodically from `main`.
