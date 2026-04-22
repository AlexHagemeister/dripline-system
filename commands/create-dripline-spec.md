You are creating a spec for the next increment in this project. The roadmap is already in context — find the first increment marked "To Do" and use its entry (Goal, Requirements) along with any completed increment specs to write the spec for that increment.

<context>
The spec is the working document for an increment. It is created just-in-time, immediately before work begins. It should reflect the current state of the codebase and any decisions made in prior increments — not just the original plan.

Before writing, read the spec files for any completed increments and use them to inform implementation decisions for this increment.

Also inspect the project's existing test setup (e.g. package.json scripts, pytest.ini, existing test files, vitest.config, jest.config, etc.) to determine the test framework and conventions in use. If nothing exists yet, note this — the first increment that introduces testable behavior should also establish the test setup.
</context>

<instructions>
1. Review the roadmap entry for the increment (Goal, Requirements)
2. Read completed increment spec files for relevant context
3. Inspect the project's test setup to identify the test framework and conventions
4. Think through the implementation — what needs to be built, in what order, what are the natural groupings of work?
5. Write the spec file at the path specified in the roadmap entry

Do not begin implementation. Do not create other files. Only produce the spec.
</instructions>

<output_format>
# [Increment Name]

<!--
DRIPLINE: SPEC
This is the working document for the current increment.

- Work through tasks top to bottom, checking them off as you complete each one.
- Use the task ID to locate and check off a specific task: grep for the ID (e.g. `[auth-01]`) to jump directly to it.
- Add sub-items or inline notes under a task as needed.
- Each task group that introduces verifiable behavior ends with a test task: write tests using the project's test framework, then run them. Do not check off the test task until tests pass.
- Skip the test task for pure setup/config groups (e.g. installing dependencies, creating directories) where there is no behavior to verify.
- If you encounter an error you cannot resolve — a failing test, unexpected behavior, or a blocker requiring a decision — stop immediately and consult the user before continuing.
- Record any choices that affect downstream increments in Decisions.
- Do not mark the increment Done in ROADMAP.md until the user confirms completion.
- When the user confirms completion, write a concise summary into the INCREMENT_SUMMARY block.
-->

## Tasks

### [Grouping]
- [ ] `[slug-01]` Task description
- [ ] `[slug-02]` Task description
- [ ] `[slug-03]` Write and run tests for [grouping]

### [Grouping]
- [ ] `[slug-04]` Task description
- [ ] `[slug-05]` Write and run tests for [grouping]

## Decisions
<!-- Notable choices made during implementation that affect downstream increments. -->

<!-- INCREMENT_SUMMARY -->
<!-- /INCREMENT_SUMMARY -->
</output_format>

<rules>
- Derive task IDs from the increment's filename slug (e.g. auth-flow.md → auth-01, auth-02)
- Group tasks under ### headings where there are natural groupings; use a single flat list if the work is simple enough
- Tasks should be specific and actionable, not vague ("Create JWT middleware" not "Set up auth")
- End each group that has verifiable behavior with a test task; omit for setup/config groups
- Test tasks should name what they're testing ("Write and run tests for JWT middleware") not just say "write tests"
- Do not include implementation detail that belongs in code comments
- Do not pre-fill Decisions or INCREMENT_SUMMARY — leave them empty
- Do not attempt to resolve errors autonomously — stop and consult the user if a blocker is encountered
</rules>
