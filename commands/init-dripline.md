You are initializing a project to use the Dripline development system.

<instructions>
1. Search the entire project for any existing `AGENTS.md` file (not just the root).
   - If one or more exist: use the first one found (prefer the root-level one if present).
     - If it already references `docs/ROADMAP.md`, leave it untouched and note it is already initialized.
     - If it does not reference `docs/ROADMAP.md`, append the block in <entry_point_block> to the end of that file in place — do not create a new one at the root.
   - If none exist anywhere: create one at the project root using the template in <agents_md_template>. Remind the user to fill in the project name and description before proceeding.
2. Create the directory `docs/` if it does not exist.
3. Create the directory `docs/specs/` if it does not exist.
4. Do not create ROADMAP.md or any spec files — those are created by separate commands.

Report exactly what was created or modified and where.
</instructions>

<agents_md_template>
# [Project Name]

[One sentence describing the project and its purpose.]

This project uses [Dripline](https://github.com/alexhagemeister/dripline-system) for AI-assisted development.

**Development entry point:** [`docs/ROADMAP.md`](docs/ROADMAP.md)

Read the roadmap before doing any work. It lists all increments with their statuses and links to their specs. The roadmap contains all instructions for how to proceed.
</agents_md_template>

<entry_point_block>
## Dripline

This project uses [Dripline](https://github.com/alexhagemeister/dripline-system) for AI-assisted development.

**Development entry point:** [`docs/ROADMAP.md`](docs/ROADMAP.md)

Read the roadmap before doing any work. It lists all increments with their statuses and links to their specs. The roadmap contains all instructions for how to proceed.
</entry_point_block>
