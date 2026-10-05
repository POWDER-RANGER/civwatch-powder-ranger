# CIVWATCH COMMUNITY

**Open-source community and documentation home for the CIVWATCH / CIVINTELLIGENCE ecosystem.**

This repository is the community-facing pointer, contribution, and positioning surface. It does **not** contain the unified application runtime.

> **System of record:** [CivilianIntelligence](https://github.com/POWDER-RANGER/CivilianIntelligence)

## Ecosystem map

| Repository | Role |
|---|---|
| [CivilianIntelligence](https://github.com/POWDER-RANGER/CivilianIntelligence) | Unified application, public-data ingest, Veil, integration spine |
| [civwatch-watchtower](https://github.com/POWDER-RANGER/civwatch-watchtower) | Map-first civic oversight |
| [civwatch-cell-titan](https://github.com/POWDER-RANGER/civwatch-cell-titan) | Defensive RF telemetry and evidence |
| [civwatch-app](https://github.com/POWDER-RANGER/civwatch-app) | Flutter operator client |
| [CIVWATCH](https://github.com/POWDER-RANGER/CIVWATCH) | Legacy backend/ML/ingest/operations source |
| [civwatch-v3](https://github.com/POWDER-RANGER/civwatch-v3) | Earlier RF dashboard/reference |
| [civwatch-ruby-gem](https://github.com/POWDER-RANGER/civwatch-ruby-gem) | Ruby integration/package scaffold |
| [civwatch-powder-ranger](https://github.com/POWDER-RANGER/civwatch-powder-ranger) | This community/docs repository |

## Platform focus

The unified product provides public-interest access to:

- civic source discovery
- government movement and public-record activity
- oversight and accountability material
- political finance and contracts
- privacy and surveillance transparency
- records-request workflows
- defensive RF observability
- geospatial civic oversight

## Contribution routing

- **Unified app, public data, integration:** CivilianIntelligence
- **Maps, features, reports:** Watchtower
- **RF, telemetry, evidence:** Cell Titan
- **Flutter client:** civwatch-app
- **Legacy migration:** CIVWATCH
- **Reference RF UI:** civwatch-v3
- **Ruby integration scaffold:** civwatch-ruby-gem
- **Community docs / positioning:** this repository

## Integration contract

The authoritative cross-repository contract lives in [CivilianIntelligence/docs/CROSS_REPO_INTEGRATION.md](https://github.com/POWDER-RANGER/CivilianIntelligence/blob/main/docs/CROSS_REPO_INTEGRATION.md).

It defines service ownership, health endpoints, authentication boundaries, evidence/provenance expectations, and release gates.

## Community principles

- Public-interest first.
- Neutral analysis over partisan spin.
- Primary sources and traceable evidence.
- Defensive use only.
- No individual targeting.

## Status note

The repositories are at different maturity levels. A capability present in a legacy or predecessor repository is **not automatically a unified production capability**. Acceptance follows the current CIVINTELLIGENCE contract and passing CI/security gates.

## Contributing

Code and bug reports should go to the repository that owns the functionality. Documentation, positioning, and community improvements are welcome here.

## License

MIT / ODbL where repository-specific data licensing requires it.

**Built for citizens, by citizens. Transparency is not optional.**


## Current ecosystem status

The ecosystem is now centered on **CivilianIntelligence** as the system of record. The public application has moved beyond the original integration spine into a user-facing collection of native civic intelligence desks.

### Available / active surface

- **Framework** — living civic source catalog.
- **Watchtower** — geospatial oversight and public-infrastructure observation, including the native ALPR infrastructure atlas.
- **Finance** — public federal spending/records and SEC filing research.
- **Privacy** — surveillance transparency and public-record pathways.
- **Toolkit** — FOIA, Privacy Act, and state-request workflows.
- **Cell Titan** — defensive RF observability and evidence.
- **VEIL** — executive public-record briefing.
- **Movement** — government movement, hearings, calendars, and related activity.
- **Oversight** — accountability and public-record research across Congress, FOIA, Federal Register, and related sources.

### Next focus: Reading Rooms & declassified libraries

The next major activation is the **Reading Room / Declassified Libraries** layer. This is a planned first-class CIVINTELLIGENCE surface for finding and navigating official federal electronic reading rooms while preserving source attribution and provenance.

Initial library targets:

1. CIA Electronic Reading Room / CREST
2. FBI Vault
3. State Department FOIA Virtual Reading Room
4. DHS FOIA Library
5. NSA Reading Room
6. DIA FOIA Electronic Reading Room

Additional agency libraries and archival collections will follow as their public interfaces, provenance requirements, and maintenance paths are established.

The intent is deliberately **not** to manufacture a parallel archive or hide the originating agency. CIVINTELLIGENCE should make the public record easier to find, understand, connect, and challenge while keeping the original source authoritative.

### In progress

- Reading Room / federal declassified-library activation
- Production deployment synchronization for newly merged public surfaces
- Unified evidence-first search across desks and normalized public records
- Cross-desk dossiers and provenance-preserving timelines
- Broader public-source ingestion and source health visibility

> **Status discipline:** active means actually exposed and usable; planned/in progress means the capability is being built. Legacy repositories remain valuable source material, but a feature is not considered unified production capability until it exists in CIVINTELLIGENCE and meets the current integration contract.
