# History of UrbanSim and UDST

Paul Waddell created UrbanSim in the 1990s to model interactions among land
use, transportation, real-estate markets, households, employment, and public
policy. Research, software development, and planning applications have
continued for more than three decades.

Waddell has served continuously as principal investigator, co-principal
investigator, research lead, software architect, or organizational steward
across UrbanSim's academic, public-sector, open-source, and commercial phases.
Co-investigators, developers, students, planning agencies, research sponsors,
and independent users have also made substantial contributions.

## Research origins

UrbanSim's intellectual origins predate the University of Washington.
Waddell's dissertation research at the University of Texas at Dallas,
supervised by Brian J. L. Berry with John Kain serving as an informal advisor,
provided part of the foundation for the work. The initial conceptual design of
what became UrbanSim was developed during a consulting project for the Oahu
Metropolitan Planning Organization in the mid-1990s.

Waddell subsequently implemented the first working prototype for
Eugene–Springfield, Oregon, in 1998. The research program then expanded at the
University of Washington to behaviorally explicit models of households, firms,
real-estate markets, and development linked with transportation and
environmental planning.

Beginning in 1999, National Science Foundation awards supported reusable
modeling components, microsimulation architecture, public participation,
uncertainty analysis, artificial intelligence, and visualization. Related NSF
Biocomplexity projects connected urban development with land-cover change and
urban ecosystems. An EPA Science to Achieve Results grant supported integrated
land-use, transportation, and air-quality modeling. The Puget Sound Regional
Council was an early and sustained implementation partner.

Waddell described the early model system in his 2002 paper,
[*UrbanSim: Modeling Urban Development for Land Use, Transportation, and
Environmental Planning*](https://doi.org/10.1080/01944360208976274).

The research program later continued at the University of California,
Berkeley. Work there contributed to the current Python generation of UrbanSim,
new model and visualization methods, and the modular projects that became
UDST.

The software reflects this research history through behavioral models of
households and firms, explicit real-estate development, links to transportation
models, reproducible data preparation, and comparison of policy scenarios.

## Open-source development

UrbanSim was released as open-source software so that researchers and public
agencies could inspect, adapt, and extend the methods. As the software evolved,
common capabilities were separated into reusable projects:

- **UrbanSim** for land-use and urban-development simulation;
- **Orca** for data and model workflow orchestration;
- **Pandana** for high-performance network accessibility and shortest-path
  analysis;
- **ChoiceModels** for discrete-choice estimation and simulation; and
- **UrbanAccess** for multimodal transportation-network preparation and
  integration.

These and other projects formed the Urban Data Science Toolkit. Their histories
are related, but each has its own contributors, releases, licenses, and
downstream users.

## Academic and agency applications

UrbanSim has been applied in research and planning contexts in North America,
Latin America, Europe, Africa, Asia, and Australia. Applications range from
university research and prototypes to operational regional planning systems.
Participating institutions have included metropolitan planning organizations,
transportation agencies, housing authorities, national laboratories,
universities, and independent research teams.

Because implementations differ in maturity and institutional relationship,
UDST distinguishes operational deployments, research applications, prototypes,
and published reviews. Inclusion in the historical record does not imply
endorsement or a current customer relationship. A separate, sourced
applications record will document locations and institutions.

## UrbanSim Inc.

Paul Waddell founded UrbanSim Inc. to provide the data engineering,
implementation, hosting, calibration, visualization, training, and support
required for production use. The company has continued research and
development with public agencies and national laboratories while building
commercial products for operational urban modeling and scenario analysis.

UDST and UrbanSim Inc. are related but not interchangeable. UDST provides
independently usable open-source projects. UrbanSim Inc. provides commercial
products, services, managed infrastructure, and separately developed
technology. The distinction is set out in [Open-source projects and commercial
offerings](OPEN_SOURCE_AND_COMMERCIAL.md).

## Stewardship today

UDST is renewing maintenance of its core repositories, updating compatibility
and release practices, and documenting their research and application history.
Paul Waddell owns and stewards the UDST GitHub organization; UrbanSim Inc.
supports its administration and repository maintenance. Repository histories,
publications, releases, acknowledgments, and project documentation record the
work of the many technical contributors. UDST's approach is described in
[Credit and attribution](CREDIT_AND_ATTRIBUTION.md).

Research support and applications will be documented separately with sources.
Application records should distinguish operational deployments, research
applications, prototypes, and preliminary work.
