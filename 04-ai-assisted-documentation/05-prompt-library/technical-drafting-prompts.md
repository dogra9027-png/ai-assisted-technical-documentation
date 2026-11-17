# Technical Documentation Prompt Library

**Project:** Nexus IT Operations Platform  
**Document Type:** Reusable Prompt Collection  
**Version:** 1.0  
**Date:** November 16, 2026

---

## 1. Purpose

This prompt library provides reusable prompt templates for developing technical documentation with generative AI assistance.

Each prompt is designed to support a specific documentation task while maintaining control over source information, audience, structure, and output quality.

The templates can be adapted for different products and documentation environments.

## 2. Product Context Prompt

**Use case:** Establish product context before generating documentation.

**Prompt:**

> Act as a technical writer supporting an enterprise software documentation project.
>
> I will provide product specifications, feature descriptions, and approved terminology.
>
> Use only the information supplied in the source material.
>
> Do not invent product functionality, technical requirements, configuration values, or system behaviours.
>
> If information is missing, identify it as an open question.
>
> Confirm your understanding of the product, intended audience, and available source information before drafting.

**Expected output:** A concise summary of the product, audience, available information, and information gaps.

## 3. Document Outline Prompt

**Use case:** Create a structured outline for a technical document.

**Prompt:**

> Develop a documentation outline for the following document:
>
> - Document type: [Insert document type]
> - Product: [Insert product name]
> - Audience: [Insert intended audience]
> - Purpose: [Describe the document's purpose]
> - Source material: [Insert approved references]
>
> Organize the outline into logical sections.
>
> Include prerequisites, procedures, expected outcomes, warnings, and related documentation where relevant.
>
> Avoid adding sections that require unsupported product functionality.
>
> Return the proposed outline with a brief explanation of the purpose of each section.

**Expected output:** A structured document outline ready for technical writer review.

## 4. User Guide Drafting Prompt

**Use case:** Develop end-user instructions.

**Prompt:**

> Draft a user guide for [Insert product or feature].
>
> Audience: [Insert user audience]
>
> Purpose: Help users understand and complete [Insert task].
>
> Use the supplied product information as the only source of product-specific facts.
>
> Write in clear, direct language using active voice.
>
> Organize procedures into numbered steps.
>
> Include prerequisites, important notes, expected results, and troubleshooting guidance where supported.
>
> Do not invent interface labels or product behaviour.
>
> Identify any missing information that requires confirmation.

**Expected output:** An audience-focused user guide draft.

## 5. Administrator Guide Prompt

**Use case:** Develop configuration or administration documentation.

**Prompt:**

> Prepare an administrator guide for [Insert feature or configuration area].
>
> Intended audience: System Administrators.
>
> Source material: [Insert approved specifications].
>
> Explain the purpose of each configuration area.
>
> Include prerequisites, access requirements, configuration considerations, security implications, and verification steps where supported by the source material.
>
> Use tables where they improve clarity.
>
> Do not invent commands, ports, default values, server requirements, or configuration options.
>
> Clearly identify information that requires technical confirmation.

**Expected output:** A structured administrator guide draft.

## 6. Troubleshooting Guide Prompt

**Use case:** Create support-oriented troubleshooting content.

**Prompt:**

> Develop a troubleshooting entry for the following issue:
>
> - Product: [Insert product]
> - Issue: [Describe the issue]
> - Audience: [Insert audience]
> - Available technical information: [Insert source material]
>
> Organize the entry into:
>
> 1. Symptom
> 2. Possible causes
> 3. Recommended actions
> 4. Expected outcome
> 5. Escalation information
>
> Do not present unverified causes as confirmed facts.
>
> Do not invent error messages or diagnostic commands.
>
> Identify any additional information required from a subject matter expert.

**Expected output:** A structured troubleshooting entry.

## 7. Technical Content Simplification Prompt

**Use case:** Make complex technical information easier to understand.

**Prompt:**

> Rewrite the following technical content for [Insert audience].
>
> Preserve the technical meaning and all important details.
>
> Use clear language, shorter sentences, and consistent terminology.
>
> Explain unfamiliar terms when necessary.
>
> Do not remove warnings, prerequisites, limitations, or security considerations.
>
> Do not add technical claims that are not present in the original content.
>
> After rewriting, list any statements that may require technical clarification.
>
> Source content:
>
> [Paste content here]

**Expected output:** A clearer version of the original content with a list of possible clarification points.

## 8. Documentation Gap Analysis Prompt

**Use case:** Identify missing information before publication.

**Prompt:**

> Review the following documentation against the supplied product requirements.
>
> Identify:
>
> - Missing sections.
> - Unsupported statements.
> - Unclear instructions.
> - Missing prerequisites.
> - Inconsistent terminology.
> - Missing warnings or limitations.
> - Incorrect or incomplete references.
>
> Separate confirmed issues from questions requiring SME confirmation.
>
> Do not assume that missing information is available elsewhere.
>
> Return findings in a table with columns for issue, location, impact, and recommended action.

**Expected output:** A structured documentation gap analysis.

## 9. Prompt Adapt