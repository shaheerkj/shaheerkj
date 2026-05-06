# Shaheer Khalid
**Security Engineer & backend engineer, moving into IAM** · CUI'27 · Islamabad, Pakistan

[![Blog](https://img.shields.io/badge/blog-blog.shaheerkj.me-blue?style=flat-square)](https://blog.shaheerkj.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-shaheerkj-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/shaheerkj)
[![Dev.to](https://img.shields.io/badge/dev.to-shaheerkj-black?style=flat-square&logo=devdotto)](https://dev.to/shaheerkj)

---

I started out building backends in Go and Java, got into DevSecOps through container security and CI/CD pipelines, and ended up most interested in the identity layer — how systems decide who gets access to what, and how badly that goes wrong when it's misconfigured.

Now I'm working on Entra ID tenant security, SCIM provisioning, Keycloak federation, and SAP BTP. I write long-form posts on identity protocols at my [blog](https://blog.shaheerkj.me) and use GitHub to document what I'm learning.

---

## Where I am right now

**IAM & Cloud Security** ← current focus
- Microsoft Entra ID, PIM, Conditional Access, Identity Governance
- Keycloak (OIDC/SAML), SCIM provisioning, OAuth 2.0
- Cloud posture assessment — Prowler, AZQr, Maester
- Terraform for Azure IAM, Microsoft Graph API (PowerShell)

**DevSecOps** ← background I bring to IAM work
- Docker (multi-stage builds, container hardening), CI/CD with GitHub Actions & Jenkins
- Trivy for container scanning, Git security (commit signing, branch protection)
- Linux administration, WAF deployment (ModSecurity), Azure networking

**Backend** ← where I come from
- Go (Gin, REST APIs, concurrency), Java (Spring Boot), Python
- PostgreSQL, MySQL, containerized deployments

---

## Projects

| Repo | What it is | Stack |
|---|---|---|
| [vulnerable-azure-lab](https://github.com/shaheerkj/vulnerable-azure-lab) | Intentionally misconfigured Azure infra — 12 real-world misconfigs across IAM, storage, networking & Key Vault. Practice target for Prowler & Defender for Cloud. | Terraform / HCL |
| [LatentGuard](https://github.com/shaheerkj/LatentGuard) | Dual-layer WAF with static rules + autoencoder anomaly detection + HDBSCAN clustering. | Python |
| [keycloak-iam-labs](https://github.com/shaheerkj/keycloak-iam-labs) | Hands-on lab guide for Keycloak — OIDC flows, SAML federation, SSO across multiple SPs. | — |
| [sap-authorization-model](https://github.com/shaheerkj/sap-authorization-model) | SAP role & profile misconfigs that lead to privilege escalation — attacker POV + defense. | — |
| [django-todo-cicd](https://github.com/shaheerkj/django-todo-cicd) | Django app deployed via Jenkins — full CI/CD pipeline with Docker. | Python / Jenkins |
| [greenlight](https://github.com/shaheerkj/greenlight) | RESTful JSON API for managing movies — full CRUD, pagination, concurrency control, multi-stage Docker. | Go / PostgreSQL |
| [AzPolicyFactory](https://github.com/shaheerkj/AzPolicyFactory) | IaC for deploying Azure Policy resources via Bicep — compliance baselines at scale. | Bicep |
| [awesome-iam](https://github.com/shaheerkj/awesome-iam) | Everything to break into IAM — concepts, protocols, tools, certs, 52-week plan. | — |

---

## Recent writing

> Long-form posts on identity protocols and cloud security at [blog.shaheerkj.me](https://blog.shaheerkj.me)

- [Understanding OAuth2.0 using Keycloak as an IdP](https://blog.shaheerkj.me/posts/OAuth2.0-labs-Keycloak/) — 24 min
- [OpenID Connect (OIDC) — a comprehensive deep dive](https://blog.shaheerkj.me/posts/OIDC-deep-dive/) — 32 min
- [PHS vs PTA vs ADFS — how enterprises actually authenticate](https://blog.shaheerkj.me/posts/phs-vs-pta-vs-adfs-how-enterprises-actually-authenticate/) — 12 min
- [Exploring CSPM tools — Prowler, Checkov, Maester, AZQr](https://blog.shaheerkj.me/posts/exploring-cloud-security-assessment-tools/) — 8 min

---

## Certifications

- **SC-300** — Microsoft Identity and Access Administrator Associate *(Dec 2025)*
- **AZ-104** — Microsoft Azure Administrator Associate *(Mar 2026)*
- **CC** — ISC2 Certified in Cybersecurity *(Jun 2025)*
