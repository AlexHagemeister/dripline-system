## Learned User Preferences

- Prefers "increment" (not "sprint") for the unit of work in dripline-system; "sprint" is considered too Scrum-specific.
- Prefers "spec" (not "task list" or "plan") as the name for the document associated with each increment.
- Command files use the `dripline-` filename prefix to distinguish them from other Cursor commands in the palette.
- Wants terminology to be consistent across all files and prompts before moving on to new features.
- Favors concise, grammar-correct prose (e.g., "an increment" not "a increment").
- Prefers discussing ambiguities and making decisions in chat before writing them to files.

## Learned Workspace Facts

- Workspace: `dripline-system` — a structured, AI-assisted development workflow built around just-in-time context delivery.
- Unit of work: **increment** (scope-bounded, not time-bounded); summary block in specs: `INCREMENT_SUMMARY`.
- Per-increment document: **spec**, stored at `docs/specs/[slug].md`; referenced in ROADMAP as `Spec: docs/specs/[slug].md`.
- Document layout: `AGENTS.md` at repo root, `ROADMAP.md` at `docs/ROADMAP.md`, specs at `docs/specs/`.
- Command files live in `commands/` with `dripline-` prefix (e.g., `create-dripline-spec.md`, `plan-dripline-roadmap.md`).
- Outstanding design gap: `create-dripline-spec.md` does not yet enforce "read INCREMENT_SUMMARY only, not full spec files" when creating a new increment; a running `docs/DECISIONS.md` log is the proposed solution.
- System is in active development; open-sourcing is a future goal.
