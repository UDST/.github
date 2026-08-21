# UDST governance

This document describes how decisions are made for the Urban Data Science
Toolkit GitHub organization and its repositories.

## Ownership and administration

Paul Waddell founded and owns UDST and retains final governance authority.
UrbanSim Inc. administers the GitHub organization and supports maintenance of
its repositories.

GitHub also uses **organization owner** as the name of an access role with full
administrative permissions. That role may be granted to additional people for
continuity or operational needs. Granting technical access does not by itself
transfer ownership or final governance authority.

GitHub ownership is distinct from copyright. Copyright in a contribution
remains with its copyright holder unless it has been assigned separately. Each
repository is distributed under its published license.

Funding or contributing to a project does not confer organization ownership,
administrative control of a repository, or authority to publish a release.

## Roles

### Organization owner access

People with GitHub organization-owner access can control:

- organization settings, repository creation and archival, and access;
- appointment and removal of maintainers;
- package-publishing credentials and release infrastructure;
- transfers of repositories; and
- resolution of governance disputes.

Owner access is reserved for people with continuing operational responsibility
for UDST as a whole. Routine repository maintenance does not require it.
Governance decisions remain subject to the authority described in this policy.

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
priorities, fund work, and participate in roadmap discussions. Designated
maintainers decide ordinary repository matters within the project's documented
scope. Decisions about organization policy, project mission, repository
transfer, credentials, and maintainer appointments remain subject to Paul
Waddell's final governance authority.

An advisory or pooled-funding group may govern its own budget and procurement.
It does not govern UDST unless a written agreement expressly grants it
specific, limited authority. Any such authority affecting public project
governance should be disclosed.

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
architecture receive organization-level review by Paul Waddell, or a formally
designated successor, in consultation with the maintainers of the affected
repositories. The current policy and project designations are recorded in
[Open-source projects and commercial offerings](OPEN_SOURCE_AND_COMMERCIAL.md)
and the [UDST project directory](PROJECTS.md).

Funding does not guarantee acceptance. Funded work undergoes the same
technical, license, provenance, and maintenance review as other contributions.

## Releases

Only designated maintainers may publish official UDST releases. Package-index
and release credentials are granted separately from general repository access.
Each repository documents its supported versions and release process.

## Open-source and commercial work

UDST projects may be used independently and as foundations for commercial
services. UrbanSim Inc. is a separate company founded by Paul Waddell. Its
commercial products and services are not governed as UDST projects. Code
expressly released in a UDST repository is governed by that repository's
license and policies.

The boundary is described in [Open-source projects and commercial
offerings](OPEN_SOURCE_AND_COMMERCIAL.md).

## Continuity

Recovery arrangements should be maintained for administrative and release
access. This does not require granting routine organization-owner access to
repository maintainers. If a repository can no longer be maintained
responsibly, UDST may seek maintainers, change its status, archive it, or
arrange an orderly transfer.

Transfer of an official repository or organization-level control requires an
explicit decision by Paul Waddell or a formally designated successor. It does
not occur automatically because a sponsor funded work on a project.

## Amendments

Material changes to this policy should be proposed publicly before adoption.
Changes to administrative ownership, repository transfer, or licensing require
Paul Waddell's approval, or that of a formally designated successor, and must
respect the rights of copyright holders.
