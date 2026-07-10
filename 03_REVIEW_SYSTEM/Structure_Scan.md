# Structure Scan

Repository: Nayara Brand OS
Folder: 03_REVIEW_SYSTEM
Document: Structure_Scan.md

Status: Approved

Owner: Nayara Fernandes

Dependencies:
• START_HERE.md
• NON_NEGOTIABLE_RULES.md
• MASTER_INDEX.md
• Review_Loop.md

---

# Purpose

This document defines how to verify that every Markdown file follows the Nayara Brand OS Repository Standards before it is approved or committed.

# How this document connects to the rest of the repository

Structure_Scan.md enforces the metadata block, mandatory twelve section structure, folder naming, and repository consistency rules defined in NON_NEGOTIABLE_RULES.md.

# Core Principles

• Structure is part of quality.
• A useful document can still fail if it breaks the standard.
• Every Markdown file must follow the same pattern.
• No extra body sections are allowed.
• No missing body sections are allowed.
• Consistency makes the repository easier for AI tools to read.

# Decision Framework

Before approving a Markdown file, check:

1. Does it start with the approved metadata block?
2. Is the folder name correct?
3. Is the document name correct?
4. Is Status set to Approved?
5. Are dependencies listed?
6. Are the twelve mandatory sections present in order?
7. Are there any extra body sections?
8. Do cross references make sense?

# Detailed Rules

Mandatory body sections:

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

Metadata requirements:

• Document title.
• Repository name.
• Folder name.
• Exact file name.
• Status: Approved.
• Owner: Nayara Fernandes.
• Dependencies.

Rules:

Do not approve files with missing sections.

Do not approve files with extra body sections.

Do not approve files with Draft status.

Do not approve files with incorrect folder names.

Do not approve files with empty dependencies unless explicitly justified.

Edge cases:

If a file is a folder placeholder, do not create it as an approved Markdown document.

If a support file feels different, it must still follow the same template.

If a section seems unnecessary, keep it and explain the limited relevance inside that section.

# Good Examples

Good example:

A changelog follows the same twelve section structure even though it is a support file.

Why this works:

It preserves repository consistency.

Good example:

A document places edge cases inside Detailed Rules.

Why this works:

It avoids adding an extra section.

# Bad Examples

Bad example:

A document includes a separate Version History section.

Why this fails:

Version notes belong in CHANGELOG.md.

Bad example:

A document is useful but missing Anti Patterns.

Why this fails:

It does not follow the mandatory structure.

# Common Mistakes

• Forgetting dependencies.
• Adding useful but forbidden sections.
• Leaving old Draft labels.
• Using inconsistent document titles.
• Placing edge cases as their own section.
• Treating support files as exceptions.

# Anti Patterns

• Template drift.
• Metadata drift.
• Folder naming drift.
• Partial compliance.
• Unscanned files.
• Exceptions without approval.

# Cross References

• NON_NEGOTIABLE_RULES.md
• Review_Loop.md
• Approval_Checklist.md
• CHANGELOG.md

# Quality Checklist

• Metadata rules are clear.
• Section order is defined.
• Extra sections are prohibited.
• Support files are included in the standard.
• Edge cases are inside Detailed Rules.
• The document follows the mandatory template.

# Future Improvements

• Add automated scan scripts.
• Add a repository wide validation checklist.
• Add examples of compliant and non compliant files.
