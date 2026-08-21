# UDST governance

This document describes governance of the Urban Data Science Toolkit GitHub organization and its repositories. It is intended to make decision-making, maintenance authority, and the role of outside funding clear.

## Stewardship and ownership

The UDST GitHub organization is owned and administered by Paul Waddell, who founded UrbanSim and has led its research and development across its academic, public-sector, open-source, and commercial phases.

Administrative ownership of the GitHub organization is distinct from copyright in individual contributions. Each repository remains governed by its published open-source license. Contributors retain the rights provided by that license and by applicable law.

No sponsor, customer, contractor, advisory group, or contributor acquires ownership of UDST, administrative control of its repositories, or release authority by funding work or participating in a project.

## Roles

### Organization owner

The organization owner is responsible for:

- organization settings, repository creation and archival, and access control;
- appointment and removal of maintainers;
- protection of credentials, package indexes, signing keys, and release infrastructure;
- resolution of governance disputes; and
- continuity and succession planning.

Organization-owner access is limited to people with an ongoing fiduciary or operational responsibility for UDST as a whole. It is not required for routine maintenance.

### Repository maintainers

Maintainers may triage issues, review and merge pull requests, manage releases, and guide the technical direction of repositories within their assigned scope. Appointment is based on sustained technical contribution, sound judgment, responsiveness, and trust. Maintainer authority may be limited by repository, branch, or release function.

Maintainers are expected to disclose material conflicts of interest, preserve contributor credit, and apply the same technical standards to funded and volunteer work.

### Contributors

Contributors participate through issues, discussions, documentation, code, testing, and review. Contribution does not by itself confer maintainer or administrative status. Submissions are evaluated under the contribution policy and the requirements of the affected repository.

### Advisors and funders

Public agencies, research sponsors, users, and other partners may recommend priorities, fund defined work, and participate in roadmap discussions. Their knowledge and investment are important to the projects. Final decisions about repository architecture, acceptance of contributions, releases, credentials, and maintainer appointments remain with UDST maintainers and the organization owner.

An advisory or pooled-funding body may govern its own budget and procurement. It does not govern UDST unless a separate written agreement expressly establishes a narrowly defined authority and that arrangement is disclosed publicly.

## Technical decisions

Routine decisions are made in the relevant repository through issues and pull requests. Maintainers consider:

- correctness, test coverage, and reproducibility;
- compatibility with supported Python versions, platforms, and downstream users;
- security and supply-chain risk;
- consistency with the repository's purpose and architecture;
- documentation and migration costs; and
- the ability to maintain the change after its initial funding ends.

Substantial changes should be discussed before implementation. Examples include removal of established APIs, major new subsystems, changes of license, migration to a new repository, or commitments that materially expand long-term maintenance obligations.

Funding a proposed change does not guarantee its acceptance. Funded contributions undergo the same technical, license, provenance, and maintenance review as other contributions.

## Releases and project status

Each repository documents its own supported versions and release process. Maintainers may designate a project as active, maintenance mode, experimental, or historical. Existing releases remain available under the licenses under which they were published; this does not require indefinite support for every release or API.

Only designated maintainers may publish official UDST releases. Access to package indexes and release credentials is granted separately from general repository write access.

## Open-source and commercial work

UDST projects may be used independently, in academic and public-sector work, and as foundations for commercial services. UrbanSim Inc. is a separate commercial company founded by Paul Waddell. Its products and services are not governed as UDST projects unless code is expressly released into a UDST repository.

The boundary between UDST and UrbanSim Inc. is described in [Open-source projects and commercial offerings](OPEN_SOURCE_AND_COMMERCIAL.md).

## Continuity

The organization owner will maintain a succession plan for administrative access and critical release credentials. If a repository can no longer be responsibly maintained, UDST may seek new maintainers, place it in maintenance mode, archive it, or arrange an orderly transfer or fork. Any transfer of an official repository or organization-level control requires an explicit decision by the organization owner; it does not occur automatically because a particular sponsor funded maintenance.

## Amendments

Material changes to this policy should be proposed publicly and allowed a reasonable review period. Changes to administrative ownership, repository transfer, or licensing require explicit approval from the organization owner and compliance with the rights of copyright holders.
