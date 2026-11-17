# AI-Assisted Release Notes Prompts

**Project:** Nexus IT Operations Platform  
**Document Type:** Reusable Prompt Collection  
**Version:** 1.0  
**Date:** November 17, 2026

---

## 1. Purpose

This document provides reusable prompts for preparing and reviewing software release notes with AI assistance.

The prompts help transform approved change information into concise, audience-focused release communications.

AI must not invent features, fixes, enhancements, or release dates.

## 2. New Feature Release Notes

**Use case:** Describe a newly introduced feature.

**Prompt:**

> Act as a technical writer preparing software release notes.
>
> Product: [Insert product name]
>
> Release version: [Insert version]
>
> New feature: [Insert approved feature description]
>
> Intended audience: [Insert audience]
>
> Prepare a concise release note explaining:
>
> - What is new.
> - What the feature does.
> - Who can use it.
> - Why it is useful.
>
> Use only the supplied approved information.
>
> Do not invent availability dates, technical behaviour, or feature capabilities.
>
> Return the content in clear, user-focused language.

**Expected output:** A concise new-feature announcement.

## 3. Bug Fix Release Notes

**Use case:** Describe an approved software correction.

**Prompt:**

> Prepare a release note describing the following software correction.
>
> Product: [Insert product name]
>
> Release version: [Insert version]
>
> Issue: [Describe the confirmed issue]
>
> Correction: [Describe the approved fix]
>
> User impact: [Describe the confirmed impact]
>
> Explain what was corrected and how the change affects users.
>
> Do not claim that additional issues were resolved.
>
> Do not invent technical root causes or implementation details.
>
> Return a concise release note.

**Expected output:** A clear description of the confirmed correction.

## 4. Enhancement Release Notes

**Use case:** Communicate an improvement to an existing feature.

**Prompt:**

> Draft a release note for the following product enhancement.
>
> Product: [Insert product name]
>
> Release version: [Insert version]
>
> Existing functionality: [Describe the previous behaviour]
>
> Enhancement: [Describe the approved improvement]
>
> User benefit: [Describe the confirmed benefit]
>
> Explain what has changed and why users may find it useful.
>
> Preserve the distinction between existing functionality and new improvements.
>
> Do not introduce unsupported claims.

**Expected output:** An audience-focused enhancement summary.

## 5. Release Notes from a Change Log

**Use case:** Convert an approved change log into release notes.

**Prompt:**

> Convert the following approved change log into structured software release notes.
>
> Product: [Insert product name]
>
> Release version: [Insert version]
>
> Intended audience: [Insert audience]
>
> Organize the changes into:
>
> - New Features
> - Enhancements
> - Bug Fixes
> - Known Issues
> - Important Notes
>
> Include only categories supported by the supplied information.
>
> Use clear, concise language.
>
> Do not invent changes or imply that an issue has been fixed unless the source confirms it.
>
> Change log:
>
> [Paste approved change log here]

**Expected output:** A structured release notes draft.

## 6. Release Notes Editorial Review

**Use case:** Review a release notes draft before publication.

**Prompt:**

> Review the following software release notes.
>
> Check:
>
> - Accuracy against the supplied change information.
> - Clarity and readability.
> - Consistent product terminology.
> - Appropriate audience focus.
> - Duplicate or unclear statements.
> - Unsupported feature or fix claims.
> - Version and date information.
>
> Suggest corrections without changing the technical meaning.
>
> Identify statements requiring confirmation.
>
> Draft:
>
> [Paste release notes here]
>
> Approved change information:
>
> [Paste source information here]

**Expected output:** An edited release notes draft and a list of review findings.

## 7. Release Notes Quality Checklist

Before publication, confirm:

- [ ] Product name is correct.
- [ ] Release version is confirmed.
- [ ] Release date is approved.
- [ ] New features match approved requirements.
- [ ] Enhancements are accurately described.
- [ ] Bug fixes are confirmed.
- [ ] Known issues are included where applicable.
- [ ] Terminology follows the documentation style guide.
- [ ] Content is appropriate for the intended audience.
- [ ] Required human review is complete.

## 8. Responsible Use

- Use approved change records as the source of truth.
- Do not invent release dates or feature availability.
- Do not describe planned features as released features.
- Do not claim an issue has been fixed without confirmation.
- Review all AI-generated release notes before publication.

---

**Document Status:** Portfolio Demonstration  
**Purpose:** Reusable prompts for AI-assisted software release communication.