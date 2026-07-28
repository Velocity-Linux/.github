# Contributing to Velocity OS

Thank you for your interest in contributing to Velocity OS. This document describes the development workflow, standards, and expectations for contributors and maintainers.

## Development Workflow

1. Fork the relevant repository and clone it locally.
2. Create a feature branch from `main` or the current stable branch.
3. Make your changes. Keep changes focused and minimal.
4. Run tests and benchmarks locally before submitting.
5. Commit with a clear, descriptive message following [Conventional Commits](https://www.conventionalcommits.org/).
6. Push your branch and open a pull request against `main`.
7. Address review feedback promptly.

## Branch Strategy

- `main`: Primary development branch. All contributions target `main`.
- `stable/YYYY.MM`: Stable release branches created from `main` at release time.
- Feature branches: Short-lived branches for individual features or fixes. Delete after merge.

Branch names should be descriptive: `scheduler/improve-deadline-fairness`, `docs/fix-install-guide`, or `fix/alsa-xrun-under-load`.

## Pull Request Process

1. Ensure your branch is up to date with `main` before opening a PR.
2. Fill out the pull request template completely.
3. Link the PR to any relevant issues.
4. Keep PRs small. Large changes should be broken into incremental, reviewable steps.
5. At least one maintainer approval is required before merge.
6. All CI checks must pass.
7. Performance-related changes must include benchmark evidence.

## Commit Messages

Follow [Conventional Commits](https://www.conventionalcommits.org/):

```
type(scope): short description

Longer description if needed.

Benchmark: ./scripts/bench.sh --before HEAD~1 --after HEAD
```

Types:
- `feat`: New feature
- `fix`: Bug fix
- `perf`: Performance improvement
- `refactor`: Code change that neither fixes a bug nor adds a feature
- `docs`: Documentation only
- `test`: Adding or updating tests
- `chore`: Maintenance, dependencies, tooling

## Coding Standards

- Write minimal, readable code. Prefer clarity over cleverness.
- Use the existing code style of the project. Do not reformat unrelated code.
- Document public APIs, configuration options, and non-obvious logic.
- Avoid adding new dependencies without prior discussion.
- Error handling must be explicit and meaningful.
- No telemetry, no phone-home, no usage reporting.

## Documentation

- Update relevant documentation with every user-visible change.
- Documentation changes should be included in the same PR as the code change.
- Use clear, concise language. Avoid jargon where possible.
- Code examples must be tested and accurate.

## Testing

- All new features must include tests.
- Bug fixes should include a test that would have caught the issue.
- Run the full test suite locally before submitting a PR.
- Tests must be deterministic and isolated.

## Performance Benchmarking Policy

- Performance-related PRs must include benchmark evidence.
- Use the project's standardized benchmarking tools and workloads.
- Report baseline and after-change results side-by-side.
- Include hardware details and environment configuration.
- Regressions must be justified with a clear benefit that outweighs the cost.
- Benchmarks must be reproducible. Provide commands and scripts.

## Code Review Process

1. Maintainers review PRs on a best-effort basis.
2. Reviewers may request changes, ask clarifying questions, or approve.
3. Authors should address all review comments before requesting re-review.
4. If a review stalls for more than 14 days, ping the maintainer team.
5. Disagreements on technical direction should be raised in the relevant issue or discussion.

## Repository Etiquette

- Do not open duplicate issues. Search existing issues before filing.
- Keep issue discussions on-topic.
- Do not push directly to `main` or `stable/*` branches.
- Use issues and discussions to propose large changes before writing code.
- Respect maintainer decisions. If you disagree, raise the concern through the governance process.

## Bug Reporting

Use the bug report issue template. Include:
- Velocity OS version and kernel version
- Hardware details
- Steps to reproduce
- Expected vs actual behavior
- Relevant logs

## Feature Proposals

Use the feature request issue template. Include:
- The problem being solved
- A proposed solution
- Alternatives considered
- Drawbacks and trade-offs

Large features should be discussed in GitHub Discussions before implementation begins.
