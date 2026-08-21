# UDST governance

This document describes how decisions are made for the Urban Data Science
Toolkit GitHub organization and its repositories.

## Ownership and administration

Paul Waddell owns the UDST GitHub organization. UrbanSim Inc. supports its
administration and the maintenance of its repositories.

GitHub ownership is distinct from copyright. Copyright in a contribution
remains with its copyright holder unless it has been assigned separately. Each
repository is distributed under its published license.

Funding or contributing to a project does not confer ownership of UDST,
administrative control of a repository, or authority to publish a release.

## Roles

### Organization owner

The organization owner controls:

- organization settings, repository creation and archival, and access;
- appointment and removal of maintainers;
- package-publishing credentials and release infrastructure;
- transfers of repositories; and
- resolution of governance disputes.

Owner access is reserved for people with continuing responsibility for UDST as
a whole. Routine repository maintenance does not require it.

### Repository maintainers

Maintainers may review and merge pull requests, triage issues, make releases,
and guide technical work within the documented scope of their assigned
repositories. Authority may be limited by repository, branch, or release
function.

Maintainers are appointed on the basis of sustained contribution, judgment,
responsiveness, and trust. They are expected to preserve contributor credit,
disclose material conflicts of interest, and apply the same technical standards
to funded and volunteer work.

### Contributors

Contributors participate through issues, discussions, documentation, code,
testing, and review. Contribution does not by itself confer maintainer or
administrative authority.

### Advisors and funders

Agencies, research sponsors, users, and other partners may recommend
priorities, fund work, and participate in roadmap discussions. Final decisions
about repository scope, architecture, contributions, releases, credentials,
and maintainer appointments remain with UDST maintainers and the organization
owner.

An advisory or pooled-funding group may govern its own budget and procurement.
It does not govern UDST unless a separate public agreement grants it specific,
limited authority.

## Technical decisions

Routine decisions are made in the relevant repository through issues and pull
requests. Reviews consider:

- correctness, tests, and reproducibility;
- compatibility with supported platforms and downstream users;
- security and supply-chain risk;
- consistency with the project's mission and reference architecture;
- documentation and migration costs; and
- the ability to maintain the change.

Removal of established APIs, major new subsystems, license changes, repository
transfers, and changes that materially expand maintenance obligations should be
discussed before implementation.

Changes that materially alter a project's mission or reference execution
architecture receive organization-level review. The current policy and project
designations are recorded in [Open-source projects and commercial
offerings](OPEN_SOURCE_AND_COMMERCIAL.md) and the [UDST project
directory](PROJECTS.md).

Funding does not guarantee acceptance. Funded work undergoes the same
technical, license, provenance, and maintenance review as other contributions.

## Releases

Only designated maintainers may publish official UDST releases. Package-index
and release credentials are granted separately from general repository access.
Each repository documents its supported versions and release process.

## Open-source and commercial work

UDST projects may be used independently and as foundations for commercial
services. UrbanSim Inc. is a separate company founded by Paul Waddell. Its
products and services are not UDST projects unless code is expressly released
in a UDST repository.

The boundary is described in [Open-source projects and commercial
offerings](OPEN_SOURCE_AND_COMMERCIAL.md).

## Continuity

Administrative and release access should be maintained so that the projects do
not depend on a single unavailable account. If a repository can no longer be
maintained responsibly, UDST may seek maintainers, change its status, archive
it, or arrange a transfer or fork.

Transfer of an official repository or organization-level control requires an
explicit decision by the organization owner. It does not occur automatically
because a sponsor funded work on a project.

## Amendments

Material changes to this policy should be proposed publicly before adoption.
Changes to administrative ownership, repository transfer, or licensing require
the organization owner's approval and must respect the rights of copyright
holders.
