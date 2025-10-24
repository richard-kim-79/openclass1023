# Phase 0 Risk Register Extract

| Risk ID | Category | Description | Owner | Mitigation Status | Residual Gap |
| --- | --- | --- | --- | --- | --- |
| [RR-PRIV-001](#rr-priv-001) | Privacy | Excess analytics data capture during pilot violates data minimization commitments. | Data Protection Officer | Interim dashboards limited to pseudonymized learner metrics; review checkpoints before any schema changes. | None – controls verified in March 2024 audit. |
| [RR-PRIV-004](#rr-priv-004) | Privacy | Guardian consent capture lacks auditable trail prior to tooling rollout. | Privacy Counsel | Manual consent packet with sign-off checklist stored in secure SharePoint folder. | Checklist template drafted; requires ops dry-run before pilot kickoff. |
| [RR-PRIV-006](#rr-priv-006) | Privacy | Cross-border transfers could trigger GDPR/FERPA conflicts if EU schools join pilot. | Regional Compliance Lead | Pilot scope restricted to US regions; legal memo prepared for any EU expansion. | Need updated data residency appendix once participating schools finalize. |
| [RR-IP-002](#rr-ip-002) | Copyright | Third-party curriculum materials may be used without validated licenses. | Curriculum Lead | Inventory spreadsheet with license attestations maintained for pilot modules. | None – inventory approved by Legal April 2024. |
| [RR-IP-005](#rr-ip-005) | Copyright | User-generated uploads could introduce infringing content without timely takedown. | Trust & Safety Manager | Manual moderation queue with 48-hour SLA and escalation matrix. | Define process for repeat offenders exceeding three strikes. |
| [RR-ACC-001](#rr-acc-001) | Accessibility | Learner dashboard fails WCAG 2.1 AA baseline causing blockers for assistive tech users. | UX Accessibility Specialist | Accessibility tiger team fixing issues flagged in March 2024 audit. | None – remediation sprint scheduled for Sprint 3 sign-off. |
| [RR-ACC-003](#rr-acc-003) | Accessibility | Lack of alternative formats for rich media assets in pilot classrooms. | Content Operations Manager | Captioning vendor engaged; transcripts stored alongside media. | Select long-term storage solution and retention owner. |

> _Note:_ Status values reflect Phase 0 readiness reviews as of April 2024. Update mitigation notes after each weekly compliance stand-up.

## Risk Entry Details

### RR-PRIV-001
- **Control Validation:** Pseudonymization confirmed during March 2024 data minimization audit.
- **Next Review:** Reconfirm schema scope before enabling new analytics dimensions.

### RR-PRIV-004
- **Control Validation:** Consent packets template stored in `/Compliance/Pilot-Phase0/Consent` library.
- **Next Review:** Operations to conduct dry-run of checklist with two pilot schools by 2024-04-24.

### RR-PRIV-006
- **Control Validation:** Legal memo documenting US-only pilot scope archived in compliance SharePoint.
- **Next Review:** Update data residency appendix once final pilot roster approved (target 2024-04-18).

### RR-IP-002
- **Control Validation:** License attestations tracked in `Curriculum-Licenses.xlsx` with Legal sign-off dated 2024-04-05.
- **Next Review:** Refresh inventory before any new module is onboarded to the pilot.

### RR-IP-005
- **Control Validation:** Manual moderation workflow documented in `T&S Playbook v2` with 48-hour SLA.
- **Next Review:** Define escalation process for users exceeding three takedown violations by 2024-04-22.

### RR-ACC-001
- **Control Validation:** Accessibility tiger team scheduled Sprint 3 remediation, with daily check-ins during sprint.
- **Next Review:** Validate WCAG 2.1 AA compliance via spot audit after Sprint 3 release.

### RR-ACC-003
- **Control Validation:** Captioning vendor engaged; transcripts stored alongside media in SharePoint `Media/Transcripts`.
- **Next Review:** Identify system-of-record for long-term transcript retention and assign owner by 2024-04-29.
