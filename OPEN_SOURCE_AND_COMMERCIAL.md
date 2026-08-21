# Open-source projects and commercial offerings

UDST maintains open-source software for urban simulation, workflow
orchestration, network accessibility, discrete-choice modeling, and multimodal
network analysis. UrbanSim Inc. is a separate company that develops commercial
products and provides implementation services.

## UDST projects

UDST software supports research, teaching, independent development, and
self-managed use by public agencies, researchers, consultants, and developers.
Each repository is governed by its published license. Users may install,
inspect, adapt, and operate the software under that license.

The projects maintain documented methods, APIs, specifications, data
interfaces, and reference implementations. Their scope also includes the work
needed to keep those capabilities usable: packaging, compatibility, testing,
security, documentation, and correction of defects.

## UrbanSim Inc.

UrbanSim Inc. was founded by Paul Waddell. It works with organizations that
need an operational modeling program rather than a self-managed software
library. Its work can include prepared regional data, model implementation and
calibration, managed computation, scenario management, visualization,
integration with client systems, training, and continuing support.

The company's products may use UDST components together with separate data,
software, infrastructure, and operating procedures. Some of this technology is
proprietary or separately licensed.

## Project scope

Each core UDST project has a stated mission and maintenance status. Where it
matters, the project also identifies its reference execution architecture.
These statements define what the official repository undertakes to install,
test, document, release, and maintain.

A reference implementation may target CPU-based, shared-memory, or in-process
execution while exposing interfaces that other implementations can use. A move
to a materially different execution model, such as accelerator-specific or
distributed execution, is a change of project architecture and receives
organization-level review.

This does not prevent anyone from developing another implementation under the
terms of the applicable licenses. Nor does an available interface require an
official UDST repository to adopt every implementation that uses it.

Current missions and status are recorded in the [UDST project
directory](PROJECTS.md).

## Project status

UDST uses the following designations:

- **Active:** continuing development within the stated scope;
- **LTS / Compatibility:** maintenance centered on reliability, compatibility,
  and existing users;
- **Deprecated / Migration:** retained while users and dependent projects move
  to maintained alternatives;
- **Seeking Maintainers:** available, but in need of sustained maintenance; and
- **Archived:** retained for history or reproducibility without an active
  development commitment.

A status designation describes the project's maintenance posture. It is not a
promise that one organization will fund or perform all future work.

## Decisions and contributions

Repository maintainers review ordinary changes within the project's stated
scope. Changes that materially alter its mission or reference architecture
receive organization-level review.

Reviews consider technical quality, provenance, compatibility, maintenance
cost, and fit with project scope. These standards apply to both funded and
volunteer contributions. Funding work does not guarantee that a proposal will
be accepted, and it does not confer ownership of UDST or control of a
repository.

Software licenses, copyright, repository administration, maintainer authority,
sponsorship, and commercial relationships are separate matters.

## Interfaces and other implementations

UDST projects can define interfaces for model specifications, estimators,
accessibility engines, workflows, run and result formats, and data schemas.
Researchers, agencies, companies, and developers may use those interfaces to
connect UDST software to other systems or to build other implementations.

Maintainers decide whether a proposed implementation belongs in an official
repository based on the project's scope, architecture, dependencies, and
long-term maintenance requirements.

## Data, models, and services

UDST repositories can include public examples, schemas, model structures, and
reproducible workflows. Prepared regional data, production preprocessing,
operational model configurations, empirical calibration, managed execution,
visualization, and continuing support may be supplied separately by UrbanSim
Inc. or by other organizations.

## Attribution

UDST repositories retain their licenses, copyright notices, attribution, and
contributor histories. Use of a UDST project does not imply endorsement by
UDST, Paul Waddell, or UrbanSim Inc. Listing a public application does not imply
a current commercial relationship.

## Choosing an approach

Organizations with suitable technical staff can use UDST software directly.
Organizations that need prepared data, implementation, managed operation, or
continuing support can obtain those services from UrbanSim Inc. or another
provider. The two approaches can also be combined.
