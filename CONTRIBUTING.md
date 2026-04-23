# Contributing

Welcome! Thank you for your interest in contributing to the Commerce Operations Foundation onX Specification.

This project is open-source because we believe collaboration drives better software. We welcome contributions of all types — code, documentation, testing, and feedback.

## Code of Conduct

Please review our [Code of Conduct](CODE_OF_CONDUCT.md) before contributing. We're committed to a respectful, inclusive community.

## Getting Started

### 1. Fork and Clone

First, fork the repository on GitHub by clicking the "Fork" button at the top of the [repository page](https://github.com/commerce-operations-foundation/onx-spec).

Then clone your fork:

```bash
# Clone your fork (replace YOUR-USERNAME with your GitHub username)
git clone https://github.com/YOUR-USERNAME/onx-spec.git
cd onx-spec

# Add the upstream remote to sync with the main repository
git remote add upstream https://github.com/commerce-operations-foundation/onx-spec.git
```

### 2. Pick an Issue

Check [open issues](https://github.com/commerce-operations-foundation/onx-spec/issues) and look for labels like:
- `good first issue`
- `help wanted`

Or open a new issue if you've found a bug or have a feature idea.

## Contributing Code

### 1. Create a Branch

```bash
git checkout -b feat/short-description
```

Use branch prefixes:
- `feat/` for new features
- `fix/` for bug fixes
- `docs/` for documentation
- `refactor/` for code improvements


### 2. Submit a Pull Request

- Push your branch to your fork:
  ```bash
  git push origin feat/short-description
  ```
- Open a PR from your fork against the `main` branch of the main repository
- Link related issues in the PR description (Fixes #123)
- Include a brief summary of what, why, and how you changed it
- Keep PRs focused and small where possible

## Code Review Process

- All PRs require at least one reviewer approval
- Be responsive to feedback — it's a collaboration, not a gatekeeping step

## Documentation

- Update relevant markdown files or API references
- If you add a major feature, include an example or tutorial section
- Documentation lives in the `/docs` directory

## Project Structure

```
/docs              # Documentation
/schemas           # JSON Schema definitions
```

## Commit Messages

Follow conventional commits:
- `feat:` for new features
- `fix:` for bug fixes
- `docs:` for documentation
- `refactor:` for code improvements
- `test:` for test changes
- `chore:` for maintenance tasks

## Communication

- For bug reports and feature requests, use [GitHub Issues](https://github.com/commerce-operations-foundation/onx-spec/issues)
- For design proposals and discussions, use [GitHub Discussions](https://github.com/commerce-operations-foundation/onx-spec/discussions)

## Licensing

By contributing, you agree that your contributions will be licensed under the MIT License.

## Acknowledgments

Thanks to all contributors — your work makes this project better for everyone.

