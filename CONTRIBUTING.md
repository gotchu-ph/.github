# Contributing Guide

We are building a high-velocity, high-quality product. Your contributions drive our success. This guide outlines our standards for collaboration and code quality to ensure we move fast without breaking things.

## Workflow & Collaboration

### 1. Align First
Time is our most valuable resource. Avoid wasted effort by ensuring your work is aligned with our roadmap.
*   **Discuss:** Open a discussion for questions or architectural proposals.
*   **Track:** **Create an Issue** for every bug or feature before writing code. We value clear specs and design intent.

### 2. Fork & Branch
*   Fork the repository.
*   Create a feature branch for your changes. keep it focused and synced with `main`.

## Engineering Standards

We enforce strict engineering standards to maintain a pristine codebase and enable automated releases.

### Karma Commit Style
We use **Karma / Conventional Commits**. This is not optional. It powers our automated versioning and changelog generation.

**Structure:** `type(scope): subject`

**Allowed Types:**
*   `feat`: New features (triggers minor version bump)
*   `fix`: Bug fixes (triggers patch version bump)
*   `docs`: Documentation only
*   `style`: Formatting, missing semi-colons, etc; no code change
*   `refactor`: Code change that neither fixes a bug nor adds a feature
*   `perf`: Performance improvements
*   `test`: Adding or correcting tests
*   `chore`: Build process, dependency updates

**Example:**
> `feat(auth): implement OIDC provider integration`

### Signed Commits (Security)
Identity and security are non-negotiable. **All commits must be cryptographically signed.**
*   Configure GPG or SSH signing.
*   Unverified commits will be rejected by branch protection rules.
*   [GitHub Signing Guide](https://docs.github.com/en/authentication/managing-commit-signature-verification/about-commit-signature-verification)

## Pull Request Protocol

1.  **Self-Review:** Ensure your code meets standards and passes all local tests.
2.  **Documentation:** Update relevant docs, API specs, and environment variables.
3.  **Title:** PR titles must also follow the Karma format.

By contributing, you agree to our [Code of Conduct](CODE_OF_CONDUCT.md) and pledge to foster a professional, inclusive environment.
