<!-- Amity Solutions Corporation - Internal Engineering Hub -->

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://static.amity.tools/images/company/amity-solutions-primary.svg"/>
    <img src="https://static.amity.tools/images/company/amity-solutions-primary.svg" alt="Amity Solutions Corporation" width="100%" style="background-color: white; padding: 16px 64px; border-radius: 12px;"/>
  </picture>
</p>

<br/>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&pause=1000&color=A855F7&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=120&lines=%E2%9C%A8+Building+the+future+of+Enterprise+AI;%F0%9F%8C%8C+Exploring+the+AI+universe+together;%F0%9F%9B%B8+Agentic+AI+%7C+GenAI+%7C+Voice+AI;%F0%9F%92%AB+From+Bangkok+to+the+cosmos" alt="Typing SVG" />
  <br/><br/><br/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/🔒_Access-Internal%20Only-red?style=for-the-badge" alt="Internal Only"/>
  &nbsp;
  <img src="https://img.shields.io/badge/🧑‍💻_Team-Engineering-blueviolet?style=for-the-badge" alt="Engineering"/>
  &nbsp;
  <img src="https://img.shields.io/badge/🟢_Status-Active-success?style=for-the-badge" alt="Active"/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</p>

---

## 🌌 Overview

This is the **internal GitHub organization** for Amity Solutions engineering teams. All repositories here contain proprietary source code, infrastructure configurations, internal tools, and documentation that power our AI products and services.

> ⚠️ **Confidential** — All code and documentation in this org is proprietary. Do not share externally.

<p align="center">
  <img src="https://i.imgur.com/dBaSKWF.gif" height="20" width="100%"/>
</p>

## 🏗️ Repository Structure

| Category | Description |
|----------|-------------|
| `platform-*` | Core platform services and APIs |
| `bots-*` | Amity Bots & Bots Plus AI agent systems |
| `voice-*` | Speech recognition & voicebot services |
| `bi-*` | Business Intelligence & analytics pipelines |
| `infra-*` | Infrastructure-as-code, Terraform, K8s configs |
| `sdk-*` | Internal SDKs and shared libraries |
| `docs-*` | Internal documentation and runbooks |
| `tools-*` | Developer tooling and automation scripts |

<p align="center">
  <img src="https://i.imgur.com/dBaSKWF.gif" height="20" width="100%"/>
</p>

## 🚀 Getting Started

### For New Team Members

1. **Request access** — Ask your team lead to add you to the appropriate GitHub teams
2. **Set up your environment** — Follow the onboarding guide in [`docs-onboarding`](../docs-onboarding)
3. **Read the contributing guide** — Each repo has a `CONTRIBUTING.md` with team-specific conventions
4. **Join Slack channels** — `#eng-general`, `#eng-platform`, `#eng-ai`, `#eng-infra`

### Prerequisites

```bash
# Required tooling
node >= 20.x
python >= 3.11
docker >= 24.x
kubectl >= 1.28
terraform >= 1.6
```

---

## 🧠 Product Teams & Ownership

| Team | Scope | Slack Channel |
|------|-------|---------------|
| **Platform** | Core APIs, auth, shared services | `#eng-platform` |
| **AI/ML** | LLM integration, model training, NLP | `#eng-ai` |
| **Bots** | Chatbot engine, agent orchestration | `#eng-bots` |
| **Voice** | Speech-to-text, Thai NLP, voicebot | `#eng-voice` |
| **BI & Analytics** | Data pipelines, dashboards, insights | `#eng-bi` |
| **Infrastructure** | Cloud, CI/CD, observability, SRE | `#eng-infra` |
| **Frontend** | Web apps, admin dashboards, SDKs | `#eng-frontend` |

---

## � Development Workflow

```
┌──────────┐     ┌──────────┐     ┌──────────┐     ┌──────────┐
│  Feature  │────▶│   PR +   │────▶│  Staging  │────▶│   Prod   │
│  Branch   │     │  Review  │     │  Deploy   │     │  Release │
└──────────┘     └──────────┘     └──────────┘     └──────────┘
```

- **Branching** — `feature/*`, `fix/*`, `hotfix/*` off `main`
- **Code Review** — Minimum 2 approvals required
- **CI/CD** — All repos use GitHub Actions; check `.github/workflows/`
- **Environments** — `dev` → `staging` → `production`

---

## 📐 Engineering Standards

| Area | Standard |
|------|----------|
| Code Style | ESLint + Prettier (TS/JS), Black + Ruff (Python) |
| Testing | Unit + Integration required; min 80% coverage |
| Documentation | ADRs for architecture decisions, OpenAPI for APIs |
| Security | Dependabot enabled, secrets scanning active |
| Commits | Conventional Commits (`feat:`, `fix:`, `chore:`) |
| Containers | Multi-stage builds, non-root, distroless base images |

---

## 🛡️ Security & Compliance

- 🔐 **Secrets** — Use AWS Secrets Manager or Vault. Never commit secrets.
- � **Scanning** — Automated SAST/DAST on every PR
- 🛑 **Access** — Principle of least privilege for all service accounts
- � **Auditing** — All production access is logged and reviewed
- 🚨 **Incidents** — Follow runbook in `docs-incident-response`

---

## � Internal Resources

| Resource | Link |
|----------|------|
| 📖 Engineering Wiki | [Confluence](https://amity.atlassian.net/wiki) |
| 📋 Project Boards | [Jira](https://amity.atlassian.net/jira) |
| � Monitoring | [Grafana Dashboard](https://grafana.internal.amity.co) |
| 🚨 Alerts | [PagerDuty](https://amity.pagerduty.com) |
| � Secrets | [AWS Secrets Manager](https://console.aws.amazon.com) |
| 🏗️ CI/CD | [GitHub Actions](https://github.com/orgs/amity-solutions-corp/actions) |
| 💬 Team Chat | [Slack Workspace](https://amity-eng.slack.com) |

---

## 🆘 Support & Escalation

| Issue | Contact |
|-------|---------|
| Access / Permissions | `#eng-help` on Slack |
| CI/CD Failures | `#eng-infra` on Slack |
| Production Incidents | Page on-call via PagerDuty |
| Security Concerns | `security@amitysolutions.com` |

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1117,100:1a1b4b&height=2" width="100%"/>
</p>

<p align="center">
  <sub>🔒 Internal use only — Amity Solutions Corporation Engineering</sub><br/>
  <sub>© 2026 Amity Solutions. All rights reserved.</sub>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:1a1b4b,50:161b22,100:0d1117&section=footer&animation=twinkling" width="100%"/>
</p>
