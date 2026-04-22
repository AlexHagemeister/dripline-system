Using the increment plan already in context, create `docs/ROADMAP.md`.

<output_format>
# Roadmap

<!--
DRIPLINE: ROADMAP
This is the entry point for all development work on this project. The project is divided into increments — discrete, testable chunks of work, each representing a vertical slice that can be verified by interacting with the running software.

The flow:
Increments move through: To Do → In Progress → Done.
Each increment links to a spec in docs/specs/ which is the working spec for that increment.
Find the first increment marked "In Progress" and open its spec to continue work.
If nothing is In Progress, find the first "To Do" increment and open its spec. If the spec does not yet exist, inform the user and wait for instructions.

Only mark an increment In Progress if the spec exists AND the user has approved starting work.
Only mark an increment Done if the user has reviewed and explicitly confirmed completion.
Do not modify this file except to update increment statuses and append increment summaries.
-->

[One short paragraph describing the project and its core purpose. Pull from the design doc — this is context for the agent, not a summary for humans.]

---

## [Descriptive Increment Name]
Status: To Do
Spec: docs/specs/[descriptive-slug].md
Goal: [Condense from the plan. Maintain fidelity of important high-level details, but aim for 2-3 sentences.]
Requirements: [Hard constraints only, no rationale. Omit if none.]

---
</output_format>

<rules>
- Condense the verbose planning descriptions down to the tightest accurate summary
- Do not number the increments
- Do not include acceptance criteria, task breakdowns, or implementation detail
- Leave all spec files as stubs — do not create them
</rules>
