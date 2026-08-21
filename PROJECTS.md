# UDST project directory

This directory records the current mission and maintenance posture of the core
Urban Data Science Toolkit projects. Detailed APIs, supported versions, and
contribution requirements remain documented in each repository.

## Core projects

### UrbanSim

**Status:** Active  
**Repository:** [UDST/urbansim](https://github.com/UDST/urbansim)

UrbanSim provides methods and reusable model components for building
self-managed simulations of urban development, household and employment
location, real-estate markets, and related regional change.

Its reference implementation is a portable, self-managed Python library
designed primarily for conventional CPU-based execution. Its model components,
specifications, and interfaces can also interoperate with other execution
engines.

### Orca

**Status:** Active  
**Repository:** [UDST/orca](https://github.com/UDST/orca)

Orca provides lightweight Python orchestration for data-intensive analytical
and simulation workflows. Its reference architecture targets
dependency-managed analytical computation within a Python process.

### ChoiceModels

**Status:** Active  
**Repository:** [UDST/choicemodels](https://github.com/UDST/choicemodels)

ChoiceModels provides reusable tools for specifying, estimating, sampling, and
simulating discrete-choice models within larger analytical workflows.

Its portable Python reference implementations target conventional CPU-based
execution. Estimator interfaces allow other execution engines to interoperate
with the library.

### Pandana

**Status:** LTS / Compatibility  
**Repository:** [UDST/pandana](https://github.com/UDST/pandana)

Pandana provides the established UDST network-accessibility and shortest-path
API for existing applications and users. It retains its established CPU and
native-code execution architecture as part of its compatibility mission.

Maintenance focuses on supported Python and scientific-Python releases,
installation and binary packaging, correctness and security, preservation of
established APIs, and documentation for existing applications.

### UrbanAccess

**Status:** Active  
**Repository:** [UDST/urbanaccess](https://github.com/UDST/urbanaccess)

UrbanAccess provides tools for constructing and preparing integrated transit
and pedestrian networks from open transportation data for accessibility
analysis. Its scope centers on reproducible multimodal network-data preparation
and integration with maintained ecosystem libraries.

## Migration projects

### OSMnet

**Status:** Deprecated / Migration  
**Repository:** [UDST/osmnet](https://github.com/UDST/osmnet)

OSMnet provides legacy OpenStreetMap network-acquisition functionality used by
existing Pandana and UrbanAccess workflows while those projects migrate to
maintained OSM ecosystem libraries. It will remain available until dependent
UDST projects have documented and released their replacement workflows.

## Other repositories

UDST also retains examples, templates, historical implementations, research
artifacts, and experimental repositories. Their presence in the organization
does not by itself indicate active maintenance. Each repository's README and
archival status should be consulted before it is adopted as a dependency.

Projects may be added to this directory or have their status revised through
UDST's organization-level governance process.

## Related policy

- [Open-source projects and commercial offerings](OPEN_SOURCE_AND_COMMERCIAL.md)
- [Contribution guidelines](CONTRIBUTING.md)

