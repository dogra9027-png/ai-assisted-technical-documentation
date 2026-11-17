# Human Validation and Review Process

**Project:** Nexus IT Operations Platform  
**Document Type:** Quality and Review Process  
**Version:** 1.0  
**Date:** November 16, 2026

---

## 1. Purpose

This document defines the human review and validation process for technical documentation developed with AI assistance.

The objective is to ensure that documentation is accurate, consistent, understandable, and aligned with approved product information.

AI-generated content must not be treated as technically verified until the appropriate review activities have been completed.

## 2. Review Principles

The validation process follows five principles:

1. **Accuracy:** Content must agree with approved source information.
2. **Clarity:** Instructions must be understandable to the intended audience.
3. **Consistency:** Terminology and formatting must follow documentation standards.
4. **Traceability:** Important statements should be supported by identifiable source material.
5. **Accountability:** A human reviewer remains responsible for approving documentation.

## 3. Validation Stages

### Stage 1: Source Verification

Compare the draft with the available product documentation.

Check that:

- Product names and descriptions are correct.
- Features match approved specifications.
- User roles and permissions are consistent.
- Terminology follows the glossary.
- No unsupported capabilities have been introduced.

### Stage 2: Technical Review

Review technical statements and procedural content.

Check:

- Technical descriptions.
- Configuration explanations.
- Workflow sequences.
- Security considerations.
- Error descriptions.
- Prerequisites and dependencies.

Where technical implementation details are unavailable, mark them for SME confirmation.

**Important:** A document review cannot replace testing in a real application or an appropriate technical environment.

### Stage 3: Editorial Review

Review the document for readability and structure.

Check:

- Grammar and spelling.
- Sentence clarity.
- Active voice.
- Heading hierarchy.
- Consistent terminology.
- Appropriate use of lists and tables.
- Clear procedural steps.

### Stage 4: Link and Reference Review

Check:

- Internal Markdown links.
- Related-document references.
- Document titles.
- Version information.
- Cross-references to specifications and the glossary.

### Stage 5: Final Approval

Review outstanding comments and unresolved questions.

Record the review outcome and ensure that limitations are clearly communicated.

## 4. Human Review Checklist

| Review Area | Validation Question |
|---|---|
| Source accuracy | Does the content match the approved source? |
| Product functionality | Are all described features supported by the specifications? |
| Terminology | Are approved product terms used consistently? |
| Audience | Is the content appropriate for the intended reader? |
| Instructions | Are steps clear and logically ordered? |
| Security | Are access and security statements appropriate? |
| Editorial quality | Is the language clear and concise? |
| References | Do internal links point to the correct documents? |
| Limitations | Are assumptions and unverified details identified? |
| Approval | Has the required human review been completed? |

## 5. Handling Unsupported Information

AI may produce details that are plausible but are not supported by the source material.

Examples include:

- Specific server requirements.
- Default ports.
- Installation commands.
- Database versions.
- API endpoints.
- Configuration values.
- Product behaviours not included in the specifications.

When unsupported information is identified:

1. Remove the unsupported statement or mark it for confirmation.
2. Check available authoritative source material.
3. Ask the responsible SME for clarification when required.
4. Update the document only after confirmation.
5. Record any remaining limitations.

Do not present assumptions as confirmed product behaviour.

## 6. Review Findings and Resolution

Use the following categories to record review findings.

| Finding Category | Description | Action |
|---|---|---|
| Accuracy issue | Content conflicts with source material | Correct the content |
| Missing information | Required information is unavailable | Request clarification |
| Terminology issue | Inconsistent or incorrect wording | Apply glossary terms |
| Editorial issue | Language or structure needs improvement | Revise the content |
| Reference issue | Link or cross-reference is incorrect | Correct and recheck |
| Validation limitation | Content cannot be tested in the available environment | Document the limitation |

## 7. Review Outcome

A document can be assigned one of the following review outcomes:

- **Approved:** Required review activities are complete.
- **Revision Required:** Changes are needed before approval.
- **Pending Confirmation:** Technical or product information requires SME clarification.
- **Not Validated:** The document has not undergone the required validation.

These outcomes should reflect the actual review performed.

## 8. Application to the Nexus Portfolio

For this portfolio demonstration, the human review process includes:

- Comparing technical guides with the product overview and feature specifications.
- Checking role names and permission descriptions.
- Reviewing alert and incident terminology.
- Checking consistency with the documentation style guide.
- Reviewing internal document links.
- Identifying fictional or conceptual procedures.
- Avoiding claims of real-world product testing.

Because Nexus is fictional, the portfolio cannot demonstrate validation against a live product or approval by an actual product SME.

## 9. Related Documents

- [AI Documentation Workflow](ai-documentation-workflow.md)
- [AI Drafting Process](ai-drafting-process.md)
- [AI Review Checklist](../06-quality-assurance/ai-review-checklist.md)
- [Documentation Audit](../06-quality-assurance/documentation-audit.md)
- [Documentation Style Guide](../02-style-guide/documentation-style-guide.md)

---

**Document Status:** Portfolio Demonstration  
**Review Principle:** AI can assist with drafting and review, but human validation is essential before technical documentation is approved for publication.
