# Agentic Trust Foundation

**Trust, Delegation & Access Layer for the Agentic Internet.**

Open protocols and reference implementations for trust, delegated authority, authorization, policy, provenance, accountability, and agentic commerce infrastructure.

**Canonical project definition:** the Agentic Trust Foundation defines the trust/authority layer for AI agents acting on behalf of users and organizations. Agent-Pay is the financial control/execution layer built on that authority. The ecosystem is not a bank, payment processor, blockchain, LLM framework, API gateway, or replacement for OAuth/MCP/A2A.

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

## Canonical project context

Start with the public project definition in the agentic-trust repository: PROJECT.md, WHY.md, AI-CONTEXT.md, GLOSSARY.md, and STATUS.md. These documents distinguish project intent from implementation evidence and external production/adoption evidence.

## Documentation

The private `project-docs` repository is the master project memory containing cross-project architecture, decisions, timeline, research, and roadmaps.

## Contributing

Please read each public repository's CONTRIBUTING.md, SECURITY.md, and AGENTS.md before making changes.
