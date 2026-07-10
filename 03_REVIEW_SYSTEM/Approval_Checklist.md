# Approval Checklist

Repository: Nayara Brand OS
Folder: 03_REVIEW_SYSTEM
Document: Approval_Checklist.md

Status: Approved

Owner: Nayara Fernandes

Dependencies:
• START_HERE.md
• NON_NEGOTIABLE_RULES.md
• MASTER_INDEX.md
• Review_Loop.md
• Content_Scorecard.md
• Hallucination_Prevention.md
• Structure_Scan.md

---

# Purpose

This document defines the final approval gate for Brand OS folders, documents, and public outputs. It ensures that nothing is treated as approved unless it passes the agreed standards.

# How this document connects to the rest of the repository

Approval_Checklist.md is the final gate in the Review System. It should be used after Review_Loop.md, Content_Scorecard.md, Hallucination_Prevention.md, and Structure_Scan.md.

# Core Principles

• Approval is earned, not assumed.
• A folder is the atomic unit of approval.
• Every document inside a folder must pass before the folder is approved.
• Repository files must follow the Nayara Brand OS Repository Standards.
• Public content must protect brand trust, voice, and evidence safety.
• If one required check fails, approval fails.

# Decision Framework

Before approving, ask:

1. Has the full review loop been completed?
2. Has the structure scan passed?
3. Has the hallucination check passed?
4. Has the content scorecard passed where relevant?
5. Are cross references accurate?
6. Is the folder or output strategically aligned?
7. Is it safe to commit, publish, or reuse?

# Detailed Rules

Repository approval checklist:

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

Content approval checklist:

1. Strategic Alignment: PASS
2. Audience Relevance: PASS
3. Voice Fit: PASS
4. Evidence Safety: PASS
5. Structure: PASS
6. Usefulness: PASS
7. CTA Fit: PASS or Not Required
8. Publication Ready: PASS

Rules:

If any required repository check fails, do not commit the folder.

If any required content check fails, do not approve the output.

If a claim is unsafe, revise or remove it.

If a document violates the mandatory structure, revise before approval.

Edge cases:

If the output is internal and not public, evidence safety still applies.

If a folder is mostly approved but one file fails, the folder is not approved.

If the user asks to move fast, complete the approval checklist internally but do not skip it.

# Good Examples

Good example:

A folder with eight files is approved only after all eight files pass the metadata, structure, cross reference, and hallucination checks.

Why this works:

It preserves the folder as the atomic unit of approval.

Good example:

A post with a strong idea is held back because evidence safety fails.

Why this works:

It protects trust.

# Bad Examples

Bad example:

Approving a folder because most files pass.

Why this fails:

Folder approval requires every file to pass.

Bad example:

Approving content because the user likes the tone, even though the claim is unsupported.

Why this fails:

Preference does not override evidence safety.

# Common Mistakes

• Treating approval as a final glance.
• Approving documents individually when the folder is incomplete.
• Forgetting duplicate content checks.
• Skipping cross references.
• Marking work Approved before the final checklist.
• Treating internal content as exempt from hallucination checks.

# Anti Patterns

• Partial folder approval.
• Approval without scan evidence.
• Approval by vibe.
• Approval despite unsupported claims.
• Approval despite template drift.
• Publishing before review.

# Cross References

• Review_Loop.md
• Content_Scorecard.md
• Hallucination_Prevention.md
• Structure_Scan.md
• NON_NEGOTIABLE_RULES.md
• CHANGELOG.md

# Quality Checklist

• Repository approval checks are defined.
• Content approval checks are defined.
• Failure rules are clear.
• Folder level approval is enforced.
• Edge cases are inside Detailed Rules.
• The document follows the mandatory template.

# Future Improvements

• Add automated approval reports.
• Add a release approval checklist for Nayara Brand OS v1.0.
• Add separate approval checklists for posts, carousels, newsletters, and repository modules.
