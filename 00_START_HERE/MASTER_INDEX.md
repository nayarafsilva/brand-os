# MASTER INDEX

Repository: Nayara Brand OS
Folder: 00_START_HERE
Document: MASTER_INDEX.md

Status: Approved

Owner: Nayara Fernandes

Dependencies:
• START_HERE.md
• NON_NEGOTIABLE_RULES.md

---

# Purpose

This document is the navigation map for the Nayara Brand OS. It shows where each type of knowledge belongs and which folder should be consulted for different tasks.

It prevents file hunting, duplicated guidance, and unclear ownership of information.

# How this document connects to the rest of the repository

This document should be read after START_HERE.md and NON_NEGOTIABLE_RULES.md.

START_HERE.md explains how to use the repository.

NON_NEGOTIABLE_RULES.md defines the standards.

MASTER_INDEX.md shows where everything lives.

# Core Principles

• Every folder has one clear responsibility.
• Every document has one primary job.
• Strategic documents come before execution documents.
• Examples are centralised when the repository grows.
• Archive material never overrides approved material.
• Folder names should make navigation obvious.
• The repository must be easy for Claude, ChatGPT, and future tools to parse.

# Decision Framework

To decide where information belongs, ask:

1. Is it about how the repository operates?
2. Is it about the brand foundation?
3. Is it about creating content?
4. Is it about reviewing quality?
5. Is it an example or pattern?
6. Is it a reusable output?
7. Is it historical material?

The answer determines the folder.

# Detailed Rules

Repository structure:

00_START_HERE

Purpose:

Repository guidance, operating rules, navigation, and change tracking.

Documents:

• START_HERE.md
• NON_NEGOTIABLE_RULES.md
• MASTER_INDEX.md
• CHANGELOG.md

01_FOUNDATION

Purpose:

Defines the strategic foundation of Nayara's personal brand.

Documents:

• Brand_Philosophy.md
• Brand_Positioning.md
• Brand_Identity.md
• Audience_Psychology.md
• Voice_Communication_System.md
• Editorial_Principles.md
• Knowledge_Boundaries.md

02_CREATION_SYSTEM

Purpose:

Defines how content is created.

Documents:

• Vocabulary_Library.md
• Hook_Library.md
• Re_Hook_Library.md
• Storytelling_System.md
• Post_Structures.md
• CTA_Library.md
• LinkedIn_Content_Cheat_Sheet.md
• Creation_Workflow.md
• Creation_Checklist.md

03_REVIEW_SYSTEM

Purpose:

Defines how quality is reviewed, scored, and approved.

Documents:

• Review_Loop.md
• Content_Scorecard.md
• Hallucination_Prevention.md
• Structure_Scan.md
• Approval_Checklist.md

04_EXAMPLES

Purpose:

Stores examples and pattern libraries.

Documents:

• Hook_Examples.md
• Story_Examples.md
• CTA_Examples.md
• Vocabulary_Examples.md
• Before_After_Rewrites.md
• Full_Post_Examples.md

05_OUTPUTS

Purpose:

Stores templates, reusable frameworks, and approved finished assets.

Folders:

• Templates
• Approved_Posts
• Carousels
• Frameworks

99_ARCHIVE

Purpose:

Stores previous versions, build notes, and historical context.

Rules:

Archived material must never override approved documents.

Edge cases:

If a document seems to fit two folders, place it in the folder where it will be used most often.

If a topic becomes too large, create a dedicated document only after approval.

If examples grow too large inside a file, move them to 04_EXAMPLES and cross reference them.

# Good Examples

Good example:

Audience psychology belongs in 01_FOUNDATION because it defines who Nayara is speaking to.

Why this works:

Audience decisions shape all later content.

Good example:

LinkedIn_Content_Cheat_Sheet.md belongs in 02_CREATION_SYSTEM because it turns positioning, audience, pillars, structure, and proof rules into LinkedIn execution.

Why this works:

It gives LinkedIn content a detailed operating system without mixing examples into foundation documents.

Good example:

Hook examples belong in 04_EXAMPLES once the library becomes large.

Why this works:

It keeps Hook_Library.md focused on rules and decision making.

Good example:

A final LinkedIn post template belongs in 05_OUTPUTS.

Why this works:

It is a reusable asset, not a strategy document.

# Bad Examples

Bad example:

Putting audience fears inside Hook_Library.md.

Why this fails:

Audience psychology belongs in Foundation.

Bad example:

Putting review scores inside Brand_Positioning.md.

Why this fails:

Quality scoring belongs in Review System.

Bad example:

Putting old drafts in 01_FOUNDATION.

Why this fails:

Old drafts belong in Archive.

# Common Mistakes

• Treating the index as a content plan.
• Adding files before deciding their role.
• Creating overlapping folders.
• Letting outputs contaminate strategy.
• Letting examples become scattered.
• Forgetting that 99_ARCHIVE is historical, not active guidance.
• Confusing current build sequence with final repository structure.

# Anti Patterns

• Folder sprawl.
• Duplicate source of truth.
• Unclear file ownership.
• Temporary folders becoming permanent.
• Mixing strategy, examples, and outputs in one place.
• Creating a structure that future AI assistants cannot follow.
• Saving files because they exist rather than because they are useful.

# Cross References

Use these files together with this document:

1. START_HERE.md for repository usage.
2. NON_NEGOTIABLE_RULES.md for approval standards.
3. CHANGELOG.md for repository change history.
4. 02_CREATION_SYSTEM/LinkedIn_Content_Cheat_Sheet.md for LinkedIn content execution.

# Quality Checklist

Before adding or moving a file, confirm:

1. The file has one primary purpose.
2. The file belongs to the selected folder.
3. The file does not duplicate another document.
4. The file supports the approved repository structure.
5. The file follows the mandatory Markdown template.
6. The file is approved before being committed.
7. The file has clear dependencies.
8. The folder remains coherent after the file is added.
9. The index does not need to change unless the architecture changes.
10. The repository remains easy to navigate.

# Future Improvements

Future improvements may include:

1. Adding short descriptions for every document once all folders are populated.
2. Adding a visual repository map.
3. Adding folder level README files if needed.
4. Adding maintenance rules for archived material.
5. Adding a release checklist for Nayara Brand OS v1.0.
