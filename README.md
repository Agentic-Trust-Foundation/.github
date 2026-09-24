# Agentic Trust Foundation

Open foundation for interoperable trust, delegated authority, identity, policy, and accountability in the agentic internet.

## Current ecosystem status

- **Agentic Trust Foundation (ATF): V2 FINAL — Phase 42** — protocol, schemas, conformance vectors, implementation, tests, and final validation.
- **Agent-Pay: V2 FINAL — Phase 43** — financial-control/payment protocol and reference implementation with final contract validation and ATF cross-repository final gate.
- **Agent Site Adapter: V1 FINAL** — service integration layer; future integration changes must remain compatible with the current versioned contracts.
- **Agent-Pay Iran: deployment-profile validation baseline complete** — country-specific deployment profile with explicit sandbox/target/production evidence gates; no live-provider claim without target evidence.
- **Project Docs: synchronized master documentation** — cross-project architecture, decisions, chronology, roadmap, and interoperability evidence.

## Architecture

```
                         AGENTIC INTERNET
                                |
                +---------------+---------------+
                |                               |
                v                               v
       Agentic Trust Foundation          Agent / Service Ecosystem
             V2 Final                         |
                |                             v
                v                       Agent Commerce
          Site Adapter                       |
                |                             v
                +----------------------> Agent-Pay
                                            V2 Final
                                                |
                                  +-------------+-------------+
                                  |                           |
                                  v                           v
                           Provider-neutral             Local profiles
                                                              |
                                                              v
                                                     Agent-Pay Iran
```

The ecosystem is protocol-first and intentionally does not require one centralized trust authority. Downstream layers consume, but do not expand, upstream authority.

## Repository roles

| Repository | Role | Status |
|---|---|---|
| `agentic-trust` | Trust/delegation/authorization protocol | **V2 FINAL — Phase 42** |
| `agent-pay` | Financial control/payment protocol | **V2 FINAL — Phase 43** |
| `agent-site-adapter` | Service/site integration layer | **V1 FINAL** |
| `agent-pay-iran` | Iran product/deployment profile | **Validation baseline; production-gated** |
| `project-docs` | Private master project memory | **Synchronized** |

## Documentation

The private `project-docs` repository is the master project memory containing cross-project architecture, decisions, timeline, research, roadmap, and interoperability evidence.

For protocol semantics, the protocol repositories remain authoritative.

## Contributing

Please read each public repository's `CONTRIBUTING.md`, `SECURITY.md`, and `AGENTS.md` before making changes.
