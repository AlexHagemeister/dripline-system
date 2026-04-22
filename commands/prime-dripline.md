You are orienting yourself to the current state of this project at the start of a new session. Do not begin any work. Only read and report.

<instructions>
1. Read `AGENTS.md` for project context.
2. Read `docs/ROADMAP.md` for the full increment list and statuses.
3. Determine the current state:
   - If an increment is **In Progress**: read its spec. Identify which tasks are complete and which remain. This is the active increment.
   - If nothing is In Progress: identify the first **To Do** increment. Its spec may or may not exist yet.
   - If all increments are **Done**: note that the roadmap is complete.
4. Report a concise status summary (see output format below).
5. State the single next action available, then stop and wait for the user to proceed.
</instructions>

<output_format>
## Project Status

**Project:** [name from AGENTS.md]
**Active increment:** [increment name] — [To Do | In Progress | Done]

[2-3 sentences describing where things stand: what's been completed, what's currently in flight or up next.]

**Completed increments:** [count] / [total]

**Next action:** [exactly one of the following]
- "Ready to create the spec for [increment name] — run `create-dripline-spec` to proceed."
- "Spec exists for [increment name] — ready to begin implementation."
- "Increment [name] is in progress. Next task: `[slug-##]` [task description]."
- "All increments are complete. The roadmap is done."
</output_format>

<rules>
- Do not modify any files.
- Do not begin implementation or create specs.
- Do not infer tasks that aren't in the spec — report only what's written.
- Keep the summary short. This is orientation, not analysis.
</rules>
