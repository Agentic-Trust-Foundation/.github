# Agentic Trust Foundation

Open foundation for interoperable trust, delegated authority, identity, policy, and accountability in the agentic internet.

## Current ecosystem status

- **Agentic Trust Foundation (ATF): V1 FINAL** — protocol, schemas, conformance suite, and reference implementation.
- **Agent-Pay: V1 FINAL** — financial-control/payment protocol and reference implementation; post-audit runtime hardening is verified.
- **Agent Site Adapter: V1 FINAL** — service integration layer with profile framework and Agent-Pay handoff.
- **Agent-Pay Iran: Phase 1–6 implementation/runtime baseline** — private country-specific product/deployment profile; production activation remains deployment-gated.
- **Project Docs: active master documentation** — cross-project architecture, decisions, chronology, roadmap, and interoperability evidence.

## Architecture

```text
                         AGENTIC INTERNET
                                |
                +---------------+---------------+
                |                               |
                v                               v
       Agentic Trust Foundation          Agent / Service Ecosystem
                |                               |
                v                               v
          Site Adapter                    Agent Commerce
                |                               |
                +---------------+---------------+
                                |
                                v
                           Agent-Pay
                                |
                    +-----------+-----------+
                    |                       |
                    v                       v
             Provider-neutral        Local profiles
                                        |
                                        v
                                Agent-Pay Iran
```

The ecosystem is protocol-first and intentionally does not require one centralized trust authority. Downstream layers consume, but do not expand, upstream authority.

## Repository roles

| Repository | Role | Status |
|---|---|---|
| `agentic-trust` | Trust/delegation/authorization protocol | V1 FINAL |
| `agent-pay` | Financial control/payment protocol | V1 FINAL |
| `agent-site-adapter` | Service/site integration layer | V1 FINAL |
| `agent-pay-iran` | Iran product/deployment profile | Phase 1–6 baseline |
| `project-docs` | Private master project memory | Active |

## Documentation

The private `project-docs` repository is the master project memory containing cross-project architecture, decisions, timeline, research, roadmap, and interoperability evidence.

For protocol semantics, the public protocol repositories remain authoritative.

## Contributing

Please read each public repository's `CONTRIBUTING.md`, `SECURITY.md`, and `AGENTS.md` before making changes.
