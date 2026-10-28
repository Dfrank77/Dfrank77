# Darius Frank

IAM and cloud security engineer building open-source Entra ID security tooling.

**Portfolio:** [dfrank-iam.com](https://dfrank-iam.com)

## Open Source

Contributor to [Maester](https://github.com/maester365/maester), the open-source Entra/M365 security testing framework.

| PR | What it does | Status |
|---|---|---|
| [#2395](https://github.com/maester365/maester/pull/2395) | MT.1224: Microsoft-managed CA policies left in report-only | Merged |
| [#2403](https://github.com/maester365/maester/pull/2403) | MT.1210: PIM-eligible roles on agent users | Merged |
| [#2434](https://github.com/maester365/maester/pull/2434) | MT.1223: Application.ReadUpdate.All as high-risk agent permission | Merged |
| [#2436](https://github.com/maester365/maester/pull/2436) | MT.1206: server-side filter for agent sign-in activity | Merged |
| [#2496](https://github.com/maester365/maester/pull/2496) | MT.1022/MT.1023: license gap and risk-based CA coverage | Merged |
| [#2506](https://github.com/maester365/maester/pull/2506) | MT.1252: Exchange RBAC for Applications overlap with tenant-wide Graph grants | Merged |

## Entra ID Security Suite

| Tool | What it does |
|------|-------------|
| [entra-blast-radius](https://github.com/Dfrank77/entra-blast-radius) | Compute an identity's full reachable privilege set, ranked worst-first |
| [entra-attack-path-visualizer](https://github.com/Dfrank77/entra-attack-path-visualizer) | Detect privilege escalation paths through roles, groups, and PIM |
| [entra-zt-policy-engine](https://github.com/Dfrank77/entra-zt-policy-engine) | Audit Conditional Access against CIS benchmarks, deploy fixes via Terraform |
| [entra-workload-identity-scanner](https://github.com/Dfrank77/entra-workload-identity-scanner) | Audit app registrations and service principals for overprivilege and stale credentials |
| [entra-orchestrator](https://github.com/Dfrank77/entra-orchestrator) | Correlate findings across all scanners into one report |
| [entra-security-report](https://github.com/Dfrank77/entra-security-report) | Shared findings model and HTML renderer used by the suite |

All tools run against any Entra ID tenant via Microsoft Graph with delegated permissions. Each tool runs against a test tenant I seeded with Terraform to simulate realistic scale.

## Stack

Python, PowerShell, Pester, Microsoft Graph API, Terraform (azuread provider), aiohttp, NetworkX

## Links

- [dfrank-iam.com](https://dfrank-iam.com)
- [LinkedIn](https://www.linkedin.com/in/darius-frank-24a895192/)
