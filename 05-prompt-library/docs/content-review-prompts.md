# AI-Assisted Content Review Prompts

**Project:** Nexus IT Operations Platform  
**Document Type:** Reusable Prompt Collection  
**Version:** 1.0  
**Date:** November 16, 2026

---

## 1. Purpose

This document provides reusable prompts for reviewing and improving technical documentation with AI assistance.

The prompts support editorial review, terminology checks, consistency analysis, readability improvements, and documentation quality assessment.

AI review results are suggestions. A human reviewer must evaluate findings before applying changes.

## 2. Grammar and Editorial Review

**Use case:** Identify grammar, spelling, and sentence-structure issues.

**Prompt:**

> Act as an experienced technical editor.
>
> Review the following technical documentation for:
>
> - Grammar and spelling.
> - Punctuation.
> - Sentence structure.
> - Unnecessary repetition.
> - Awkward phrasing.
> - Inconsistent capitalization.
>
> Preserve the original technical meaning.
>
> Do not introduce new product claims or remove important warnings.
>
> Return:
>
> 1. A revised version of the content.
> 2. A table of significant changes.
> 3. Any statements requiring technical clarification.
>
> Content:
>
> [Paste content here]

**Expected output:** An edited draft with a summary of significant changes.

## 3. Clarity and Readability Review

**Use case:** Improve content for a specific audience.

**Prompt:**

> Review this document for clarity and readability.
>
> Intended audience: [Insert audience]
>
> Document purpose: [Insert purpose]
>
> Identify sentences that are difficult to understand, overly complex, vague, or unnecessarily long.
>
> Recommend clearer alternatives while preserving technical accuracy.
>
> Check whether instructions are easy to follow and whether technical terms are explained appropriately.
>
> Return findings in a table containing the original wording, issue, and recommended revision.
>
> Do not invent missing technical details.
>
> Content:
>
> [Paste content here]

**Expected output:** Audience-focused editorial recommendations.

## 4. Terminology Consistency Review

**Use case:** Check whether approved product terminology is used consistently.

**Prompt:**

> Review the following document against the supplied terminology glossary.
>
> Identify:
>
> - Incorrect terminology.
> - Alternative terms used for the same concept.
> - Incorrect capitalization.
> - Undefined acronyms.
> - Inconsistent interface labels.
>
> Use the approved glossary as the reference.
>
> Do not replace terms with alternatives unless the glossary supports the change.
>
> Return a table with the current term, approved term, location, and recommended correction.
>
> Glossary:
>
> [Paste glossary here]
>
> Document:
>
> [Paste document here]

**Expected output:** A terminology consistency report.

## 5. Procedural Documentation Review

**Use case:** Review step-by-step instructions.

**Prompt:**

> Review the following procedure from the perspective of an end user.
>
> Check whether:
>
> - Prerequisites are clearly stated.
> - Steps appear in the correct logical order.
> - Each step describes a clear action.
> - Important warnings are included.
> - Expected outcomes are explained.
> - The procedure contains unsupported assumptions.
>
> Identify ambiguous instructions and suggest improvements.
>
> Do not invent interface elements or product behaviour.
>
> Return findings in a table with step number, issue, impact, and recommendation.
>
> Procedure:
>
> [Paste procedure here]

**Expected output:** A procedural review report.

## 6. Style Guide Compliance Review

**Use case:** Check whether documentation follows an approved writing standard.

**Prompt:**

> Review this document against the supplied documentation style guide.
>
> Assess:
>
> - Heading structure.
> - Sentence case.
> - Active voice.
> - Tone and language.
> - Numbered procedures.
> - Tables and lists.
> - Terminology.
> - Accessibility and readability.
>
> Identify deviations and suggest corrections.
>
> Separate style issues from technical accuracy concerns.
>
> Do not rewrite technical facts.
>
> Style guide:
>
> [Paste style guide here]
>
> Document:
>
> [Paste document here]

**Expected output:** A style compliance review.

## 7. Cross-Document Consistency Review

**Use case:** Identify contradictions across related documentation.

**Prompt:**

> Compare the following documents for consistency.
>
> Check product names, feature descriptions, role permissions, status values, terminology, and references.
>
> Identify conflicting statements, duplicated explanations, and differences in terminology.
>
> For each finding, identify the affected documents and recommend which source should be used as the authoritative reference.
>
> Do not decide between conflicting statements without sufficient source evidence.
>
> Documents:
>
> [Paste relevant documents here]

**Expected output:** A cross-document consistency report.

## 8. Quality Review Summary

**Use case:** Prepare a concise summary of review findings.

**Prompt:**

> Summarize the findings from the completed documentation review.
>
> Organize the findings into:
>
> - Critical accuracy issues.
> - Missing information.
> - Editorial improvements.
> - Terminology corrections.
> - Reference and formatting issues.
> - Items requiring SME confirmation.
>
> Include a recommended next action for each finding.
>
> Do not describe an issue as resolved unless the supplied evidence confirms the correction.

**Expected output:** A review summary suitable for documentation tracking.

## 9. Responsible Use Guidelines

- Provide only information authorized for AI processing.
- Use approved references when checking product-specific terminology.
- Treat AI findings as recommendations, not verified defects.
- Review proposed changes before applying them.
- Preserve technical meaning and important warnings.
- Escalate unresolved technical questions to qualified reviewers.

---

**Document Status:** Portfolio Demonstration  
**Purpose:** Reusable prompts for AI-assisted technical content review and quality improvement.
