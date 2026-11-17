# Alert Management Guide — Source Analysis

**Project:** Nexus IT Operations Platform  
**Document:** Alert Management User Guide  
**Audience:** IT Operations Analysts and other authorized users  
**Analysis Date:** November 17, 2026  
**Status:** Source Review Completed — Clarifications Required

---

## 1. Purpose

This document records the source requirements, documentation decisions, and information gaps identified before drafting the Nexus Alert Management User Guide.

It establishes traceability between approved product specifications and the planned user documentation.

## 2. Source Documents

| Source | Version | Purpose |
|---|---|---|
| Product Overview | 1.0 | Defines product purpose, audience, and features |
| Feature Specifications | 1.0 | Defines functional requirements and role permissions |
| Documentation Style Guide | 1.0 | Defines writing and formatting standards |
| Terminology Glossary | 1.0 | Defines approved product terminology |

## 3. Requirements Mapping

| Requirement ID | Requirement | Documentation Coverage |
|---|---|---|
| ALT-001 | View alerts | Explain access to the alert list |
| ALT-002 | View alert details | Explain alert descriptions, severity, and status |
| ALT-003 | Filter alerts | Explain filtering by severity and status, subject to clarification |
| ALT-004 | Acknowledge alerts | Explain alert acknowledgement and role permissions |
| ALT-005 | Track alert status | Explain Active, Acknowledged, and Resolved statuses |
| IAM-005 | Restrict access | Explain role-based access restrictions |

## 4. Role Permission Analysis

The Feature Specifications define the following alert permissions:

| Role | View Alerts | Acknowledge Alerts |
|---|---|---|
| Administrator | Yes | Yes |
| Operations Analyst | Yes | Yes |
| Viewer | Yes | No |

Documentation must not suggest that Viewers can acknowledge alerts.

## 5. Approved Terminology

| Term | Approved Meaning |
|---|---|
| Alert | A notification generated when a monitored condition requires attention |
| Severity | The level of urgency associated with an alert |
| Acknowledge | An action indicating that an alert has been reviewed |
| Active | Alert has been generated and requires review |
| Acknowledged | An authorized user has reviewed the alert |
| Resolved | The underlying condition has been addressed |

### Severity Levels

- Critical — Requires immediate investigation.
- High — Indicates a significant operational concern.
- Medium — Requires investigation and monitoring.
- Low — Informational or lower-priority condition.

## 6. Source Discrepancy

A difference was identified between the two product source documents.

| Source | Filtering Requirement |
|---|---|
| Product Overview | Filter by status and category |
| Feature Specifications, ALT-003 | Filter by severity and status |

**Action required:** Request clarification from the product team.

**Drafting decision:** Use severity and status because ALT-003 provides the specific functional requirement. Do not claim that category filtering is supported until confirmed.

## 7. Information Gaps

The available specifications do not define:

- Exact screen names or navigation labels.
- Actual alert-list layout.
- Available filter controls or their interface labels.
- How users open individual alert details.
- Whether acknowledgement requires confirmation.
- Whether acknowledgement records a timestamp or user name.
- How an alert becomes resolved.
- Whether users can manually resolve alerts.
- Whether alerts can be reassigned or escalated.

These details must not be invented.

## 8. Documentation Boundaries

The user guide may explain:

- The purpose of the alert list.
- The meaning of severity levels.
- The meaning of alert statuses.
- Filtering requirements at a conceptual level.
- The difference between viewing and acknowledging alerts.
- Role-based restrictions.

The user guide must not claim to provide verified interface instructions or tested application procedures.

## 9. Drafting Readiness

<escape>|</escape> Area | Assessment |
|---|---|
| Core alert functionality | Defined |
| Severity classifications | Defined |
| Alert status definitions | Defined |
| Role permissions | Defined |
| Filtering requirement | Clarification required |
| Exact interface instructions | Not supplied |
| Resolution workflow | Not supplied |

**Conclusion:** Sufficient source information is available to prepare a conceptual user guide. Interface-specific and unresolved workflow details must be identified as limitations or questions for product-team confirmation.

---

**Portfolio Note:** This analysis uses fictional Nexus product specifications. It demonstrates source review and requirements traceability, not validation of a functioning software product.
