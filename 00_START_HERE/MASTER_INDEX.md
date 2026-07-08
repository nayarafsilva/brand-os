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

Planned documents:

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

Planned documents:

• Vocabulary_Library.md
• Hook_Library.md
• Re_Hook_Library.md
• Storytelling_System.md
• Post_Structures.md
• CTA_Library.md
• Creation_Workflow.md
• Creation_Checklist.md

03_REVIEW_SYSTEM

Purpose:

Defines how quality is reviewed, scored, and approved.

Planned documents:

• Review_Loop.md
• Content_Scorecard.md
• Hallucination_Prevention.md
• Structure_Scan.md
• Approval_Checklist.md

04_EXAMPLES

Purpose:

Stores examples and pattern libraries.

Planned documents:

• Hook_Examples.md
• Story_Examples.md
• CTA_Examples.md
• Vocabulary_Examples.md
• Before_After_Rewrites.md
• Full_Post_Examples.md

05_OUTPUTS

Purpose:

Stores templates, reusable frameworks, and approved finished assets.

Planned folders:

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

• Treating folder order as importance order.
• Adding examples into every file until documents become bloated.
• Putting review guidance inside creation documents.
• Saving finished assets inside strategic folders.
• Leaving outdated material outside 99_ARCHIVE.
• Letting documents overlap instead of cross referencing.

# Anti Patterns

• Duplicate documents with similar purposes.
• Hidden files outside the folder system.
• Random folders created for convenience.
• Strategy rules inside examples.
• Review rules inside outputs.
• Archive material treated as current.
• Folder names that require explanation.

# Cross References

• START_HERE.md
• NON_NEGOTIABLE_RULES.md
• CHANGELOG.md
• 01_FOUNDATION/Brand_Philosophy.md
• 02_CREATION_SYSTEM/Creation_Workflow.md
• 03_REVIEW_SYSTEM/Approval_Checklist.md

# Quality Checklist

• All active top level folders are listed.
• Each folder has a clear purpose.
• Planned documents are named consistently.
• Folder responsibilities do not overlap.
• Archive rules are clear.
• Cross references are useful.
• The index can guide a new AI session without prior context.

# Future Improvements

• Add links to documents once all files exist.
• Add a repository status table after v1.0 is complete.
• Add ownership notes if collaborators are added.
• Add module level indexes if folders become large.