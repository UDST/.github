# Open-source projects and commercial offerings

UDST and UrbanSim Inc. serve complementary roles in the urban modeling
ecosystem.

## UDST

The Urban Data Science Toolkit maintains open-source software for urban
simulation, workflow orchestration, network accessibility, discrete-choice
modeling, multimodal network analysis, and related urban data science.

UDST projects support:

- transparent and reproducible research;
- education and independent experimentation;
- self-managed implementations by public agencies, researchers, consultants,
  and developers;
- stable and documented methods, APIs, specifications, and data interfaces;
- maintenance and modernization of established capabilities; and
- community contributions that advance the defined purpose and sustainability
  of each project.

UDST projects are intended to be credible and useful software in their own
right. Technically capable users can install, inspect, adapt, extend, and
operate them directly under the license stated in each repository.

## UrbanSim Inc.

UrbanSim Inc. is a separate commercial company founded by Paul Waddell. It
develops products, technology, data, and professional services for
organizations that want an operational modeling program built on open and
proprietary components.

Its offerings may include:

- curated and maintained regional data;
- model specification, estimation, calibration, validation, and updating;
- specialized high-performance implementations;
- managed cloud computation and production operations;
- scenario and model lifecycle management;
- collaboration, mapping, visualization, and user interfaces;
- integration with client systems and other modeling platforms;
- security, monitoring, provenance, auditability, and production reliability;
- training, service levels, and continuing technical support; and
- proprietary or separately licensed technology developed by the company.

UrbanSim commercial products may incorporate UDST components alongside
additional data, workflows, implementations, infrastructure, interfaces, and
technology developed for production use.

## The boundary

UDST provides open methods, interfaces, specifications, and self-managed
implementations within defined project missions. UrbanSim Inc. builds
operational products and services through independently developed technology,
data, automation, infrastructure, integrated applications, and managed
delivery.

This structure supports a strong open-source ecosystem while allowing multiple
implementations and delivery models to coexist around common methods and
interfaces.

## Project scope and reference architecture

Each active UDST project documents its purpose, maintenance status, supported
interfaces, relationship to other UDST projects, and expectations for future
development. Its scope statement defines the capabilities it is intended to
maintain and develop.

Where execution architecture is material to a project's identity and
maintenance obligations, the project also documents its reference execution
model. A reference implementation may target portable CPU-based,
shared-memory, or in-process execution while documented interfaces permit
other implementations to interoperate.

A materially different execution model, such as accelerator-specific or
distributed execution, is an architectural scope change. It is considered
through organization-level governance rather than treated as an ordinary
implementation change.

Defining a reference architecture does not prevent independent or compatible
implementations. It establishes what the official repository undertakes to
install, test, document, release, and maintain.

## Project status

UDST projects may be designated as:

- **Active** — supports continuing development within its stated scope;
- **LTS / Compatibility** — emphasizes compatibility, reliability, and support
  for existing users;
- **Deprecated / Migration** — remains available while users and dependent
  projects move to maintained alternatives;
- **Seeking Maintainers** — remains available but needs additional sustained
  maintenance; or
- **Archived** — retained for history or reproducibility without an active
  development commitment.

Current designations are recorded in the [UDST project directory](PROJECTS.md).
Status describes a project's development posture; it does not promise that a
particular organization will fund or perform all future work.

## Stewardship and contributions

UDST operates as a federation of open-source projects. Repository maintainers
may guide roadmaps, review and merge pull requests, triage issues, make
releases, and direct technical development within an established project
scope.

Changes that materially expand a project's mission or redefine its reference
execution architecture receive organization-level review. Funding a proposed
change does not guarantee acceptance. Funded and volunteer contributions are
reviewed under the same standards for technical quality, provenance,
compatibility, maintainability, and fit with project scope.

Project stewardship, software licenses, copyright, organization
administration, sponsorship, and commercial relationships are distinct. A
contribution or funding relationship does not by itself confer ownership of
UDST or control of a repository.

## Open interfaces and alternative implementations

Where practical, UDST projects define clear interfaces among model
specifications, estimators, accessibility engines, workflows, run and result
formats, and data schemas. Researchers, agencies, companies, and developers
may use those interfaces to combine UDST components with other systems or
develop alternative implementations.

The existence of an interface does not obligate an official UDST repository to
adopt every implementation behind it. Maintainers consider the project's
scope, architecture, dependencies, maintenance requirements, and community
value when evaluating additions.

## Data and prepared models

UDST projects may define transparent schemas, public examples, model
structures, and reproducible self-managed workflows. Prepared regional data,
production preprocessing, operational model configurations, empirical
calibration, managed execution, visualization, and continuing model support
may be supplied separately by UrbanSim Inc. or other organizations.

## Attribution

UDST projects retain the licenses, copyright notices, attribution, and
contributor histories associated with their repositories. Use of a UDST
project does not imply endorsement by UDST, Paul Waddell, or UrbanSim Inc.
Inclusion in a public applications list does not imply a current commercial
relationship.

## Choosing an approach

Organizations with technical teams can use UDST projects directly to inspect,
adapt, extend, and operate urban modeling software. Organizations seeking
prepared data, operational models, managed computation, visualization,
production integrations, or continuing support can work with UrbanSim Inc. or
other service providers. Hybrid approaches are also possible.

