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


---

## Public platform status — October 2026

**CIVINTELLIGENCE is live on the public web and its REST/API surface is active.**

**Public site:** https://civintelligence.onrender.com

The web platform is now the working reference implementation for the CIVWATCH ecosystem: the core application, public-data surfaces, evidence/provenance model, specialized pillars, and integration boundaries are being exercised through the deployed CIVINTELLIGENCE service.

### Applications are next

With the web application and REST contracts now active, the remaining client work is primarily **productization and platform packaging**, not rebuilding the intelligence platform from scratch. Native applications for the major target platforms are planned and will be coming soon.

The application layer can consume the same stable contracts already used by the web experience:

- **Android**
- **iOS**
- **Windows**
- **Linux**
- additional platform clients as the shared API contract matures

The existing Flutter client and service boundaries give the ecosystem a head start. Mobile/desktop applications can progressively adopt the established authentication, API, provenance, map, evidence, and desk contracts rather than duplicating backend intelligence.

### How quickly this came together

The current milestone is notable because the ecosystem moved from a multi-repository architecture and integration plan to a functioning public platform in a short development window. The difficult architectural work — ownership boundaries, public-data ingestion, REST contracts, evidence/provenance rules, Watchtower/Cell Titan integration, and the user-facing desk model — is already substantially established.

That means the next step should be treated as **client delivery on top of an operating platform**. The web application is the reference surface; native clients become additional presentation and interaction layers over the same CIVINTELLIGENCE contracts.

> **Build once at the platform layer. Deliver many clients at the edge.**

### Ecosystem rule

CIVINTELLIGENCE remains the system of record. Specialized repositories retain clear ownership of their domains, while clients consume stable public/service contracts. Legacy and predecessor repositories remain valuable migration/reference material but are not silently represented as unified production capabilities.

**Status discipline:** live means exposed and usable; available means implemented and integrated; in progress means actively being built; planned means not yet shipped. No synthetic or unavailable source is represented as live evidence.
