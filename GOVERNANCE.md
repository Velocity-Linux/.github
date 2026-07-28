# Governance

## Overview

Velocity OS is developed and maintained by a distributed community of contributors. This document describes the organizational structure, decision-making process, and governance model.

## Core Team

The Core Team is responsible for the overall direction, release management, and strategic decisions of Velocity OS. Core Team members are maintainers with sustained, high-quality contributions across the project.

## Maintainers

Maintainers have write access to repositories within their area of responsibility. They review contributions, triage issues, and ensure the health of their subsystems.

See [MAINTAINERS.md](MAINTAINERS.md) for responsibilities and expectations.

## Contributors

Contributors are anyone who submits code, documentation, bug reports, or other improvements. All contributions are welcome regardless of affiliation or experience level.

## Decision Making

- **Routine decisions**: Maintainers make day-to-day decisions within their area.
- **Cross-cutting changes**: Changes affecting multiple subsystems require discussion in the relevant issue or discussion thread.
- **Major changes**: Significant architectural or design changes require an RFC (see below).
- **Release decisions**: The Core Team approves releases.

Decisions are made based on technical merit, alignment with project goals, and community consensus. Bikeshedding should be avoided; maintainers may close discussions that are not progressing.

## Release Approval

1. A release manager proposes a release cut from `main`.
2. The Core Team reviews the release candidate for regressions and completeness.
3. Benchmarks and test results must be current and passing.
4. The Core Team approves the release.
5. The release manager tags, signs, and publishes the release.

## RFC Process

Significant changes to Velocity OS should follow the Request for Comments (RFC) process:

1. Open an RFC issue in the appropriate repository using the RFC label.
2. Describe the motivation, proposed changes, alternatives, and trade-offs.
3. The community and maintainers discuss the proposal for at least 14 days.
4. A maintainer summarizes the discussion and moves the RFC to a vote.
5. The Core Team votes. Simple majority approves.
6. Approved RFCs are implemented incrementally.

## Deprecation Process

1. A deprecation notice is added to the affected documentation and code.
2. The deprecation is announced in the next release notes.
3. A timeline for removal is specified.
4. Maintainers provide migration guidance where applicable.
5. After the deprecation period, the deprecated feature is removed.

## Becoming a Maintainer

Contributors may be nominated for maintainer access by existing maintainers. Criteria include:

- Sustained, high-quality contributions over at least 3 months
- Demonstrated understanding of the project's standards and goals
- Consistent and constructive code review participation
- Alignment with the project's values

The Core Team reviews nominations and votes. A simple majority is required.

Maintainer access may be revoked for inactivity, repeated policy violations, or consistent disregard for project standards. See [MAINTAINERS.md](MAINTAINERS.md) for the inactivity policy.

## Dispute Resolution

Disputes between maintainers or community members should be escalated to the Core Team. The Core Team acts as the final arbiter.

## Amendments

This document may be amended by a two-thirds majority vote of the Core Team. Proposed amendments must be discussed publicly for at least 7 days before voting.
