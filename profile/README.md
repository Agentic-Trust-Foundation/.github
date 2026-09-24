# Agentic Trust Foundation

Open protocols and reference implementations for trust, delegated authority, authorization, policy, provenance, accountability, and agentic commerce infrastructure.

## Current status

- **ATF — V2 FINAL (Phase 42)**
- **Agent-Pay — V2 FINAL (Phase 43)**
- **Agent Site Adapter — V1 FINAL**
- **Agent-Pay Iran — deployment-profile validation baseline; production activation remains evidence-gated**
- **Project Docs — synchronized master documentation**

## Projects

### Agentic Trust Foundation
Protocol and reference implementation for agent identity, delegation, authorization, capability, trust, consent, revocation, provenance, auditability, and human control.

### Agent-Pay
Financial control and payment execution layer built on delegated authority from ATF.

### Agent Site Adapter
Public integration layer for websites and services that want to expose authenticated, capability-aware interfaces to agents. Adapter installation is not, by itself, a trust assertion.

### Agent-Pay Iran
Private product/deployment profile for applying Agent-Pay to the Iranian operational and financial environment.

## Project architecture

```
ATF V2 Final
 |
 +--> Site Adapter --> Websites / Services
 |
 +--> Agent-Pay V2 Final --> Local / Provider Profiles
                              |
                              +--> Agent-Pay Iran
```

The ecosystem is protocol-first and intentionally avoids requiring one centralized trust authority.

## Repositories

- agentic-trust
- agent-pay
- agent-site-adapter

Private project planning and country-specific product work are maintained separately.

## Documentation

The private `project-docs` repository is the master project memory containing cross-project architecture, decisions, timeline, research, and roadmaps.

## Contributing

Please read each public repository's CONTRIBUTING.md, SECURITY.md, and AGENTS.md before making changes.
