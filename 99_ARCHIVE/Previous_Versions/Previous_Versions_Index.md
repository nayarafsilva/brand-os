# Previous Versions Index

Repository: Nayara Brand OS
Folder: 99_ARCHIVE
Document: Previous_Versions_Index.md

Status: Approved

Owner: Nayara Fernandes

Dependencies:
• START_HERE.md
• NON_NEGOTIABLE_RULES.md
• MASTER_INDEX.md
• CHANGELOG.md
• Build_Notes.md

---

# Purpose

This document defines how previous versions of Nayara Brand OS files should be archived, labelled, and interpreted. It exists because GitHub cannot store empty folders, so this index makes the Previous_Versions folder active, documented, and usable.

# How this document connects to the rest of the repository

Previous_Versions_Index.md belongs inside 99_ARCHIVE because previous versions are historical references only. They should never override approved current files.

This document works with Build_Notes.md and CHANGELOG.md. CHANGELOG.md records approved changes. Build_Notes.md records relevant build context. Previous_Versions_Index.md governs old file storage.

# Core Principles

• Previous versions are historical records.
• Current approved files are the source of truth.
• Archived files must be clearly labelled.
• Old versions should not be reused without review.
• Nothing in this folder should be treated as active guidance unless it has been promoted back into the approved repository structure.

# Decision Framework

Before archiving a previous version, ask:

1. Is the old version worth preserving?
2. Could it confuse future users?
3. Is it clearly labelled as historical?
4. Is the current approved version available elsewhere?
5. Does CHANGELOG.md need an entry?
6. Should the old version be deleted instead of archived?

# Detailed Rules

Previous version naming pattern:

Original file name plus context label.

Recommended examples:

• Brand_Positioning_previous_build.md
• Hook_Library_pre_review.md
• Creation_Workflow_old_structure.md

Rules:

Do not archive vague files.

Do not archive unlabelled drafts.

Do not archive confidential material.

Do not use archived files as dependencies for active documents.

Do not allow previous versions to duplicate current guidance without a reason.

Current status:

No previous versions are currently approved for storage in this folder.

Edge cases:

If an older version contains one useful idea, extract and review the idea before adding it to an active file.

If an older version is confusing, do not preserve it.

If a previous version is kept only for traceability, label it clearly and reference the relevant CHANGELOG.md entry.

# Good Examples

Good example:

An old Foundation draft is archived as Brand_Philosophy_old_phase_structure.md and clearly marked as historical inside the file.

Why this works:

The name explains why it exists and prevents confusion.

Good example:

A previous hook bank is not archived because better examples already exist in 04_EXAMPLES.

Why this works:

The archive does not become cluttered.

# Bad Examples

Bad example:

Saving a file called draft.md.

Why this fails:

It is unclear, untraceable, and easy to misuse.

Bad example:

Using an archived file as the active source for a new post.

Why this fails:

Archived material is historical, not authoritative.

# Common Mistakes

• Archiving too much.
• Keeping old files without labels.
• Treating archived files as active guidance.
• Forgetting to update CHANGELOG.md.
• Preserving weak drafts because they took time to create.
• Leaving confidential details inside archived material.

# Anti Patterns

• Archive hoarding.
• Unlabelled drafts.
• Previous versions used as current standards.
• Duplicate guidance across archive and active folders.
• Archived files with no reason to exist.
• Confidential or unsupported content stored for convenience.

# Cross References

• Build_Notes.md
• CHANGELOG.md
• NON_NEGOTIABLE_RULES.md
• 03_REVIEW_SYSTEM/Approval_Checklist.md
• 03_REVIEW_SYSTEM/Structure_Scan.md

# Quality Checklist

• Previous version rules are clear.
• Current approved files remain source of truth.
• Naming rules are defined.
• Current status is stated.
• Edge cases are inside Detailed Rules.
• The document follows the mandatory template.

# Future Improvements

• Add a table of archived files if previous versions are added.
• Add deletion criteria for obsolete archived files.
• Add a restoration process if historical content is promoted back into active use.
