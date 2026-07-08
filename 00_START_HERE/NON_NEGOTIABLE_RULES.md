# NON NEGOTIABLE RULES

Repository: Nayara Brand OS
Folder: 00_START_HERE
Document: NON_NEGOTIABLE_RULES.md

Status: Approved

Owner: Nayara Fernandes

Dependencies:
• START_HERE.md

---

# Purpose

This document defines the permanent operating rules for the Nayara Brand OS. These rules protect consistency, quality, portability, and trust.

No document, folder, prompt, example, or output should enter the repository unless it follows these rules.

# How this document connects to the rest of the repository

This document is the repository's quality constitution. Every other file depends on it.

If any document conflicts with NON_NEGOTIABLE_RULES.md, this document wins.

If a new rule is proposed, it must be added here only after approval. Other files should reference the rule, not create competing standards.

# Core Principles

• Every Markdown file follows exactly the same template.
• No extra random sections.
• No missing sections.
• No drifting structure.
• Version control is handled through CHANGELOG.md.
• Every document goes through the same review loop.
• Knowledge comes before prompts.
• One folder is the atomic unit of approval.
• Work in progress stays outside the repository.
• Only approved documents enter the repository.
• The Brand OS is Nayara's personal brand system, not a Pluralsight guide.

# Decision Framework

Before any document is saved, decide:

1. Does it belong in the current folder?
2. Does it begin with the approved metadata block?
3. Does it follow the twelve mandatory sections in order?
4. Does it avoid extra body sections?
5. Does it complete the review workflow?
6. Does the folder pass the repository checklist?
7. Does it support Nayara's personal brand beyond her current role?
8. Does it avoid hallucinated claims and fake examples?

# Detailed Rules

Mandatory metadata block:

# Document Title

Repository: Nayara Brand OS
Folder: Folder name
Document: Exact file name

Status: Approved

Owner: Nayara Fernandes

Dependencies:
• START_HERE.md
• NON_NEGOTIABLE_RULES.md

Mandatory Markdown structure:

1. Purpose
2. How this document connects to the rest of the repository
3. Core Principles
4. Decision Framework
5. Detailed Rules
6. Good Examples
7. Bad Examples
8. Common Mistakes
9. Anti Patterns
10. Cross References
11. Quality Checklist
12. Future Improvements

Repository level checklist:

1. Repository Structure: PASS
2. Folder Naming: PASS
3. Metadata Validation: PASS
4. Template Validation: PASS
5. Cross References: PASS
6. Knowledge Hierarchy: PASS
7. Review Loop: PASS
8. Hallucination Prevention: PASS
9. Duplicate Content Scan: PASS
10. Repository Ready: PASS

Workflow:

1. Generate document.
2. Review against Brand OS rules.
3. Critique.
4. Rewrite.
5. Stress test.
6. Run structure scan.
7. Run cross reference scan.
8. Run duplicate content scan.
9. Run consistency scan.
10. Run hallucination check.
11. Mark as Approved.
12. Save into repository.

Edge cases:

Edge cases must be written inside Detailed Rules, not as a separate section.

Version notes must go in CHANGELOG.md, not inside every document.

If a document cannot pass the checklist, it must not be committed.

If a folder contains one failing document, the whole folder is not approved.

# Good Examples

Good example:

A folder contains four Markdown files. All four use the same metadata block and twelve sections. Cross references are checked. The folder is approved as one unit.

Why this works:

It keeps the repository clean and predictable.

Good example:

A document needs version notes. The notes are placed in CHANGELOG.md instead of adding a Version History section.

Why this works:

It preserves the mandatory structure.

Good example:

A file needs edge cases. They are included under Detailed Rules.

Why this works:

It avoids adding extra sections.

# Bad Examples

Bad example:

Adding a section called Edge Cases.

Why this fails:

Edge cases belong inside Detailed Rules.

Bad example:

Adding Version History inside every document.

Why this fails:

Version notes belong in CHANGELOG.md.

Bad example:

Saving a Draft status file to the repository.

Why this fails:

Only Approved files enter the repository.

Bad example:

Treating Pluralsight as the core brand.

Why this fails:

The repository is for Nayara's personal brand.

# Common Mistakes

• Creating useful but non compliant sections.
• Treating a good draft as approved.
• Forgetting the metadata block.
• Forgetting dependencies.
• Writing examples without saying why they work.
• Repeating the same rule across many documents.
• Moving to the next folder before the current folder passes.
• Making product context stronger than personal brand context.

# Anti Patterns

• Repository drift.
• Hidden drafts.
• Silent rule changes.
• Inconsistent templates.
• Prompt libraries without knowledge foundations.
• Hallucinated proof.
• Generic content standards.
• Employer dependent identity.
• Folder approval without scans.

# Cross References

• START_HERE.md
• MASTER_INDEX.md
• CHANGELOG.md
• 03_REVIEW_SYSTEM/Structure_Scan.md
• 03_REVIEW_SYSTEM/Approval_Checklist.md
• 03_REVIEW_SYSTEM/Hallucination_Prevention.md

# Quality Checklist

• Metadata standard is defined.
• Mandatory Markdown structure is defined.
• Repository level checklist is defined.
• Workflow is defined.
• Atomic folder approval is defined.
• No extra body sections are introduced.
• Brand hierarchy is protected.
• Version control location is clear.
• Edge case location is clear.

# Future Improvements

• Add automated validation scripts if the repository becomes large.
• Add a contributor guide if other people start editing the Brand OS.
• Add formal release rules when Nayara Brand OS v1.0 is complete.