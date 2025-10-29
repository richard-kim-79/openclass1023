# Product Roadmap

## Phase 0 Compliance Readiness

### Regulatory Obligations Overview
| Category | Obligation | Phase 0 Scope | Mitigation Owner | Risk Register Entry | Mitigation Status | Gap Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Privacy | Data minimization for pilot analytics | Collect only pseudonymized learning metrics from beta classrooms; exclude PII until consent tooling ships. | Data Protection Officer (DPO) | [RR-PRIV-001](../operations/risk-register.md#rr-priv-001) | Interim dashboards limited to pseudonymized metrics and reviewed before schema changes. | None – mitigations approved in prior privacy impact assessment. |
| Privacy | Consent management for guardian approvals | Draft consent language and manual logging workflow for early adopters. Automation deferred to Phase 1. | Legal – Privacy Counsel | [RR-PRIV-004](../operations/risk-register.md#rr-priv-004) | Manual consent packet and sign-off checklist stored in secure SharePoint library. | Gap: Run operations dry-run of checklist before pilot kickoff. |
| Privacy | Cross-border data transfer compliance (GDPR/FERPA) | Restrict pilot tenancy to US-based regions and document rationale for any EU participants. | Operations – Regional Compliance Lead | [RR-PRIV-006](../operations/risk-register.md#rr-priv-006) | Legal memo drafted; EU participation gated behind COO approval. | Gap: Update data residency appendix once EU schools confirmed. |
| Copyright | Use of third-party curriculum assets | Inventory all third-party materials in pilot modules and document licenses. | Curriculum Lead | [RR-IP-002](../operations/risk-register.md#rr-ip-002) | Inventory spreadsheet with license attestations maintained for pilot modules. | None – inventory template finalized. |
| Copyright | User-generated content moderation | Establish manual review queue for uploaded assignments with clear takedown SLA. | Trust & Safety Manager | [RR-IP-005](../operations/risk-register.md#rr-ip-005) | Manual moderation queue with 48-hour SLA and escalation matrix. | Gap: Define process for repeat offenders exceeding three strikes. |
| Accessibility | WCAG 2.1 AA baseline for pilot features | Conduct quick-hit accessibility audit on learner dashboard and fix blockers (e.g., contrast, keyboard nav). | UX Accessibility Specialist | [RR-ACC-001](../operations/risk-register.md#rr-acc-001) | Remediation sprint scheduled to close audit blockers by Sprint 3. | None – audit scheduled sprint 3. |
| Accessibility | Alternative format support for core materials | Provide text transcripts for all pilot video lessons and alt text for imagery. | Content Operations Manager | [RR-ACC-003](../operations/risk-register.md#rr-acc-003) | Captioning vendor engaged; transcripts stored with media assets. | Gap: Select long-term transcript storage solution and retention owner. |

### Phase 0 Deliverables
- Finalize consent language and interim logging SOP.
- Complete copyright asset inventory and moderation playbook.
- Ship accessibility fixes for learner dashboard and publish media alternative text inventory.
- Produce a lightweight clickable prototype demonstrating pilot user journeys prior to full engineering hand-off.

### Dependencies & Next Steps
- Close identified gaps before Phase 0 exit review.
- Coordinate with Engineering to surface consent logging in admin UI.
- Align Legal and Operations on cross-border participation review cadence.
- Partner with Product Design to iterate on the prototype using Figma components and gather stakeholder sign-off.
