# Contributing to Rumba

Contributions are welcome. This document explains how to participate.

## Understand the License

Rumba is developed by [Kogito UG (haftungsbeschränkt)](https://kogito.dev), a
company based in Germany. We license this software under the
[Functional Source License (FSL)](https://fsl.software/), a non-compete license
that converts to Apache 2.0 or MIT after two years.

This means:

- You can use, modify, and redistribute the code
- You cannot use it to compete with Rumba
- After two years, each version becomes permissive open source

We chose FSL because it allows open development while protecting our ability to
sustain the project commercially. It is not strictly open source, but it will
be.

## Before You Contribute

External contributions are not central to our development process. The core
team works on features based on project roadmap and user feedback.

If you want to contribute a feature:

1. Open an issue or discussion first
2. Describe what you want to build and why
3. Wait for feedback before starting work

This prevents wasted effort on changes we cannot accept.

## Communication

- **GitHub Issues** - Bug reports and feature requests
- **GitHub Discussions** - Questions, ideas, and general conversation

## Submitting Bug Reports

Before reporting:

1. Search existing issues to avoid duplicates
2. Check if the issue persists in the latest version

When reporting:

- Describe expected vs actual behavior
- Provide steps to reproduce
- Include relevant logs, screenshots, or configuration
- Specify your environment (OS, Rumba version, etc.)

## Submitting Changes

If we agreed your change is something we would accept:

1. Fork the repository
2. Create a feature branch from `main`
3. Make your changes
4. Write clear commit messages using [Conventional Commits](https://www.conventionalcommits.org/)
5. Submit a pull request

### Commit Message Format

```text
type: short description

Longer explanation if needed.
```

Types: `feat`, `fix`, `docs`, `chore`, `refactor`, `test`

Examples:

- `feat: add SAML 2.0 identity provider support`
- `fix: correct token expiration calculation`
- `docs: update API authentication guide`

## Contribution License

By submitting a contribution, you grant us the right to redistribute your work
under the same license terms. We do not require a Contributor License Agreement
(CLA).

See [Why you probably shouldn't add a CLA to your open source project](https://ben.balter.com/2018/01/02/why-you-probably-shouldnt-add-a-cla-to-your-open-source-project/)
for background on this approach.

## Response Times

The team reviews contributions when time permits. Expect responses within a
week for most submissions. Complex changes may take longer.

## Code Style

Follow existing patterns in the codebase. For Rust code:

- Run `cargo fmt` before committing
- Ensure `cargo clippy` passes without warnings
- Add tests for new functionality

## Types of Contributions

We accept:

- Bug fixes with clear reproduction steps
- Documentation improvements
- Test coverage improvements
- Performance optimizations with benchmarks
- Features that align with project goals

We may decline:

- Features outside project scope
- Changes that add significant maintenance burden
- Contributions without prior discussion (for non-trivial changes)

## Questions

For questions about contributing, open a
[GitHub Discussion](https://github.com/orgs/rumba-id/discussions).
