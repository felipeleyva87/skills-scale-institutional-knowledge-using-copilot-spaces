# OctoAcme — Cross-Role Interaction Guide

## Purpose
Document how the key roles in OctoAcme projects interact with each other across the project lifecycle. Use this as a reference for handoff points, communication expectations, and accountability at each stage.

---

## Role Interaction Matrix

| Role | Interacts Closely With | Key Touchpoints |
|---|---|---|
| Product Manager (PdM) | Project Manager, Developers, UX/Design Lead, Customer Success | Backlog prioritization, acceptance criteria, roadmap reviews |
| Project Manager (PM) | All roles | Status reporting, risk escalation, meeting facilitation |
| Developers | Tech Lead, UX/Design Lead, DevOps, QA/Testing | Sprint delivery, code reviews, CI/CD integration |
| Tech Lead | Developers, PM, PdM, Security Officer | Architecture decisions, PR reviews, risk escalation |
| UX / Design Lead | PdM, Developers, QA/Testing | Design specs, usability reviews, acceptance validation |
| Security / Compliance Officer | Tech Lead, PM, DevOps | Security reviews, pre-release sign-off, incident response |
| DevOps / Infrastructure Engineer | Developers, Tech Lead, Security Officer, PM | CI/CD pipelines, deployments, environment management |
| Customer Success / Support Rep | PdM, PM, Stakeholders | Release readiness, customer feedback, support documentation |
| QA / Testing | Developers, UX/Design Lead, PM | Test planning, acceptance validation, bug reporting |

---

## Key Handoff Points by Lifecycle Stage

### 1. Initiation
- **PdM → PM**: Hands off approved one-pager and success metrics to begin planning
- **PM → All**: Communicates project kickoff, roles, and initial timeline

### 2. Planning
- **PdM → UX/Design Lead**: Shares problem statement and user research to inform design
- **PdM → Tech Lead**: Aligns on feasibility and technical constraints before estimation
- **PM → DevOps**: Reviews infrastructure needs and CI/CD readiness for the project
- **Security Officer → PM**: Flags compliance requirements to include in the backlog

### 3. Execution
- **UX/Design Lead → Developers**: Delivers wireframes and design specs per sprint
- **Tech Lead → Developers**: Provides architecture guidance and approves significant PRs
- **DevOps → Developers**: Maintains CI/CD pipeline and resolves build/environment issues
- **Security Officer → Tech Lead**: Reviews code and architecture changes for vulnerabilities
- **QA/Testing → PM**: Reports blockers, test results, and acceptance status

### 4. Release
- **DevOps → PM**: Confirms deployment readiness and release window
- **Security Officer → PM**: Provides security sign-off before production deployment
- **Customer Success → PM**: Confirms support readiness (docs, FAQs, training)
- **PM → All**: Coordinates release announcement and post-deploy verification

### 5. Retrospective & Continuous Improvement
- **All roles → PM**: Contribute retrospective inputs (what went well, what to improve)
- **Customer Success → PdM**: Feeds post-release customer feedback into the next backlog cycle
- **Security Officer → Tech Lead**: Reviews any security incidents and proposes improvements

---

## Escalation Path (All Roles)

```
Team Member → Tech Lead / Role Lead → Project Manager (PM) → Product Lead → Sponsor
```

For security incidents:
```
Any Team Member → Security/Compliance Officer → Tech Lead → PM → Security On-Call
```

---

## Tips for Effective Cross-Role Collaboration
- **Document decisions**: Use ADRs, risk registers, and meeting notes stored in the repo
- **Async-first**: Use PR comments, GitHub Issues, and project boards before scheduling meetings
- **Single source of truth**: Keep the project README and process docs updated so all roles stay aligned
- **Escalate early**: Surface blockers in daily standups; don't wait for weekly syncs
- **Close feedback loops**: Customer Success and QA insights should flow back to PdM every sprint
