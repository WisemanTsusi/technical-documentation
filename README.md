# Technical Documentation & Architecture Reference

[![Documentation](https://img.shields.io/badge/docs-engineering-blue?logo=readthedocs&logoColor=white)](docs)
[![Architecture](https://img.shields.io/badge/architecture-C4-orange)](architecture)
[![API](https://img.shields.io/badge/API-OpenAPI-6BA539?logo=openapiinitiative&logoColor=white)](api)
[![License](https://img.shields.io/badge/license-MIT-1f6feb?logo=opensourceinitiative&logoColor=white)](LICENSE)

A reusable Git-based technical documentation framework for software engineering, solution architecture, API design, security, operations, and architectural governance.

## Included

- C4-style architecture views
- Architectural Decision Records (ADRs)
- OpenAPI API standards and example contract
- Security and threat-model templates
- Operational runbooks
- Service ownership documentation
- Engineering and documentation standards
- Reusable architecture/service templates
- Architecture review checklists
- GitHub Actions documentation CI
- Sanitized SaaS/cloud/distributed-system examples

## Repository map

| Directory | Purpose |
|---|---|
| `architecture/` | System context, container and deployment views |
| `adr/` | Architecture decisions and trade-offs |
| `api/` | API standards and OpenAPI |
| `security/` | Threat modelling and security reviews |
| `operations/` | Runbooks and operational readiness |
| `standards/` | Engineering/documentation conventions |
| `templates/` | Reusable documentation templates |
| `examples/` | Generic reference examples |

## Documentation principles

Documentation is treated as an engineering artifact: versioned, reviewed, linked to implementation, and updated with architectural changes.

The architecture structure follows the C4 approach of hierarchical system, container, component and code abstractions, with supporting views such as deployment diagrams. ADRs capture significant architectural decisions and their rationale, trade-offs and consequences.

The included API example targets OpenAPI 3.2.1, the current published specification version as of September 2026.

## CI

GitHub Actions validates repository structure, JSON syntax, and ADR numbering.

## Portfolio scope

This repository is generic and contains no proprietary Ceribro™ SaaS or Genius Geeks source code.

## License

MIT
