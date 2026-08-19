# Organization links for UDST repository READMEs

This page contains proposed short inserts for the core repositories. They are deliberately concise: the organization profile should carry the institutional account, while repository READMEs should remain focused on the software.

## Standard project context

Place near the end of each README, before the license section:

```markdown
## Project context

This project is part of the [Urban Data Science Toolkit](https://github.com/UDST). See the UDST [history](https://github.com/UDST/.github/blob/main/HISTORY.md), [governance](https://github.com/UDST/.github/blob/main/GOVERNANCE.md), and [research support](https://github.com/UDST/.github/blob/main/FUNDING.md).

UDST provides open-source research software. [UrbanSim Inc.](https://www.urbansim.com/) provides separate commercial products, implementation services, managed data, and support. [Learn about the distinction](https://github.com/UDST/.github/blob/main/OPEN_SOURCE_AND_COMMERCIAL.md).
```

## UrbanSim

Add this sentence to the opening project description:

```markdown
UrbanSim was created by Paul Waddell and has been developed through more than three decades of research, public-sector application, software engineering, and community contribution.
```

## Orca

Use the standard project-context block. Orca should be described as a general open-source workflow library; the README need not frame it as a limited edition of a commercial product.

## ChoiceModels

Use the standard project-context block. The README should describe the established open-source estimation and simulation APIs. It should not promise that experimental, accelerated, managed, or separately developed modeling systems will be added to this repository.

## Pandana

Use the standard project-context block. The README should describe Pandana's current network-accessibility, aggregation, nearest-POI, and shortest-path APIs. It should not characterize a separately developed Pandana2 implementation as the automatic successor until its ownership, release plan, compatibility scope, and relationship to Pandana are formally documented.

## UrbanAccess

Use the standard project-context block. If the project is in maintenance mode, state that plainly near the installation instructions and link to the currently supported Python and dependency versions.

## Repository governance note

For repositories receiving substantial outside funding, add:

```markdown
Roadmap suggestions and funded contributions are welcome. Funding a change does not confer ownership or administrative control of the repository and does not guarantee merge. Contributions are reviewed for technical fit, compatibility, provenance, and continuing maintenance cost under [UDST governance](https://github.com/UDST/.github/blob/main/GOVERNANCE.md).
```

This note should be used only where the distinction is materially useful. It does not need to appear in every repository.

