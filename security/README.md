# Security Documentation

## Threat-model baseline
Review authentication, authorization, tenant isolation, privilege escalation, injection, sensitive data exposure, insecure integrations, secrets, dependencies, audit leakage, denial-of-service and supply-chain risk.

## Trust boundaries

```text
External Client -> HTTPS -> API Boundary -> Application -> Database / External Providers
```

Each boundary should have explicit authentication, authorization, validation and monitoring requirements.

## Security review questions
- Who can call this capability?
- Which tenant owns the data?
- What prevents cross-tenant access?
- What data is sensitive?
- Where are secrets stored?
- What is logged?
- How are privileged actions audited?
- What happens when dependencies fail?
