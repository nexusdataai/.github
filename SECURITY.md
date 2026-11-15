# Security policy (nexusdataai)

## Supported versions

Security fixes are applied on the **actively maintained** default branches of each repository. Legacy **`nexus-backend`** / **`nexus-ui`** receive fixes only while extraction to **nexus-ontology**, **nexus-ai-engine**, and **nexus-simulator** is in progress — prefer reporting issues against the target extraction repo when known.

## Reporting a vulnerability

**Please do not open public GitHub issues for exploitable security problems.**

1. Email your report to your organization’s security contact (configure in GitHub org settings).
2. Include: affected repository, versions/commits, reproduction steps, and impact assessment.
3. Allow reasonable time for remediation before public disclosure.

If no dedicated mailbox is configured yet, open a **private** security advisory on the most relevant repository via GitHub **Security → Advisories** (repository admins).

## Safe harbor

We support good-faith security research that follows this policy and avoids privacy violations, service degradation, or data exfiltration beyond what is necessary to demonstrate the issue.

## Dependencies

Report third-party dependency issues through the repository that pins the dependency; maintainers will track upstream CVEs and release notes.