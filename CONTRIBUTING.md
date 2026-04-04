# Contributing to IP API

Thanks for your interest in contributing.

## Code of Conduct

All participants are expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Reporting Bugs

Before creating a bug report, check existing issues to avoid duplicates. Include:

- A clear, descriptive title
- Steps to reproduce the problem
- Expected vs actual behaviour
- Your environment (OS, Node.js version, etc.)

## Suggesting Features

Feature suggestions are welcome. Please include:

- A clear description of the proposed feature
- Why it would be useful
- Any alternatives you have considered

## Pull Requests

1. Fork the repo and branch from `main`
2. Make your changes
3. Test locally
4. Commit with clear messages following [Conventional Commits](https://www.conventionalcommits.org/)
5. Open a Pull Request

### Development Setup

```bash
git clone https://github.com/YOUR_USERNAME/ip-api.git
cd ip-api
npm install
npm run dev
```

### Commit Messages

```
<type>(<scope>): <description>
```

Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`

Examples:
```
feat(api): add city field to response
fix(geo): handle IPv6 addresses correctly
docs: update API usage examples
```

### Review Process

1. A maintainer will review your PR
2. Changes may be requested
3. Once approved, your PR will be merged
