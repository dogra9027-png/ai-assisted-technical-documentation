# AI-Assisted Drafting Process

**Project:** Nexus IT Operations Platform  
**Document Type:** Process Guide  
**Version:** 1.0  
**Date:** November 16, 2026

---

## 1. Purpose

This document describes the practical process used to develop technical documentation with generative AI assistance.

The process focuses on preparing structured prompts, supplying approved source information, reviewing generated content, and refining drafts to meet documentation requirements.

AI-generated content is considered a starting point. The technical writer remains responsible for the final document.

## 2. Preparing for AI-Assisted Drafting

Before using AI, establish the requirements for the document.

### 2.1 Identify the Document Type

Determine whether the requested output is:

- Product documentation.
- User guide.
- Administrator guide.
- Installation guide.
- Configuration guide.
- Troubleshooting guide.
- Training material.
- Release notes.

The document type determines the structure, level of detail, and writing style.

### 2.2 Identify the Audience

Define the intended reader and their expected technical knowledge.

For example:

| Audience | Documentation Focus |
|---|---|
| End users | Navigation and everyday tasks |
| System administrators | Configuration and access management |
| Operations analysts | Monitoring, alerts, and incident handling |
| Support teams | Troubleshooting and issue escalation |

### 2.3 Gather Source Material

Provide relevant approved information, such as:

- Product specifications.
- Feature requirements.
- Terminology glossary.
- Existing style guide.
- Relevant technical references.

Do not ask AI to invent missing product details.

If required information is unavailable, record it as an open question.

## 3. Prompt Structure

A useful documentation prompt should contain the following elements:

| Element | Purpose |
|---|---|
| Role | Defines the perspective AI should adopt |
| Context | Explains the product and documentation task |
| Audience | Identifies the intended reader |
| Source material | Establishes the approved information |
| Requirements | Defines the required content |
| Constraints | Identifies information that must not be invented |
| Output format | Specifies the expected structure |

## 4. Drafting Process

### Step 1: Request a Document Outline

Ask AI to propose a structure based on the document purpose, audience, and source information.

Review the outline before generating the full document.

### Step 2: Generate Section Content

Develop the document in manageable sections.

Provide the relevant source information and ask AI to produce clear, audience-appropriate content.

### Step 3: Review the Initial Draft

Check whether the draft:

- Covers the required topics.
- Uses approved product terminology.
- Follows the intended structure.
- Avoids unsupported technical claims.
- Addresses the reader's needs.

### Step 4: Refine the Content

Use follow-up prompts to improve:

- Clarity.
- Conciseness.
- Instructional flow.
- Heading organization.
- Tables and lists.
- Consistency.

### Step 5: Consolidate the Document

Combine the approved sections and review the document as a complete deliverable.

Check for duplicated content, inconsistent terminology, missing sections, and incorrect cross-references.

### Step 6: Complete Human Review

Compare the final draft with the approved source material and documentation standards.

Record unresolved questions rather than presenting assumptions as facts.

## 5. Example: Nexus Configuration Guide

The following example illustrates how a structured prompt can be used to develop an administrator guide.

**Prompt objective:** Create a configuration guide for system administrators.

**Source information:**

- Nexus is a fictional IT operations platform.
- Administrators manage user accounts and roles.
- The platform uses role-based access control.
- Monitoring and alert management are defined in the feature specifications.
- Exact technical configuration values have not been supplied.

**Drafting instructions:**

1. Organize the content into logical configuration sections.
2. Explain each configuration area in clear language.
3. Use the approved role names and terminology.
4. Do not invent commands, ports, server requirements, or configuration values.
5. Clearly identify conceptual procedures.
6. Include related documentation references.

**Expected output:** A structured administrator guide with configuration explanations, review considerations, and appropriate limitations.

## 6. Iterative Improvement

AI-assisted drafting is an iterative process.

| Iteration | Activity | Expected Result |
|---|---|---|
| 1 | Generate outline | Proposed document structure |
| 2 | Generate initial content | First draft |
| 3 | Review technical content | Identified gaps and inaccuracies |
| 4 | Refine language | Improved readability and consistency |
| 5 | Review complete document | Consolidated draft |
| 6 | Human validation | Reviewed portfolio deliverable |

## 7. Common Drafting Problems

| Problem | Recommended Approach |
|---|---|
| AI invents product functionality | Restrict output to supplied specifications |
| Content is too general | Provide audience and task-specific context |
| Instructions are too complex | Request shorter, sequential steps |
| Terminology is inconsistent | Supply the approved glossary |
| Sections contain repeated information | Request a consistency and duplication review |
| Technical details are missing | Record questions for SME confirmation |

## 8. Responsible Use

When using AI for documentation:

- Use only information authorized for the selected AI tool.
- Avoid confidential customer or company information unless explicitly approved.
- Do not treat generated content as verified technical guidance.
- Check facts against authoritative references.
- Preserve human review and approval.
- Disclose AI assistance when required by organizational policy.

## 9. Related Documents

- [AI Documentation Workflow](ai-documentation-workflow.md)
- [Human Validation Process](human-validation-process.md)
- [Technical Drafting Prompts](../05-prompt-library/technical-drafting-prompts.md)
- [Content Review Prompts](../05-prompt-library/content-review-prompts.md)
- [Documentation Style Guide](../02-style-guide/documentation-style-guide.md)

---

**Document Status:** Portfolio Demonstration  
**Key Principle:** Structured prompts improve the quality of initial drafts, but human judgment determines whether the final documentation is suitable for use.
