# Vault Structure Guide

How this vault is organized, so new projects can be added consistently and anyone browsing can navigate it without guessing.

## Entry Points

- `README.md` — plain root README. 
- `0. README.md` — the vault hub; lists and links every learning project plus the Vault Structure Guide, using plain Markdown links so it renders correctly if opened directly on GitHub. The real starting point inside Obsidian.

## File Naming

- `0.1. README_<Project Name>.md` — a project's own README.
- `0.2. <Project Name>.md` — a project's overview/plan file (Why, Goal, Strategy, Timeline).
- `0. Personal Notes.md` — one shared, dated work log/journal across **all** projects (not project-prefixed).
- `<Project Name>_0. Understand the Problem.md` — each project's foundational/definitions file, numbered `0` within that project's own content.
- `<Project Name>_N. <Topic>.md` — a project's actual content files, numbered `1`, `2`, `3`… per that project's internal structure.

**Separators:** underscore (`_`) splits the **project name** from that project's **internal numbering/topic**; period + space (`N. `) splits numbering from the topic title — including in meta files themselves (e.g. `0.1. README_...`, not `0.1.README_...`).

## Meta Numbering vs. Content Numbering

- `0.`-series = vault/project-level meta (README, overview, shared notes) — global, not tied to one knowledge area.
  - `0.` (bare) = vault-wide files, shared by every project: `0. README.md` (the hub) and `0. Personal Notes.md` (the shared journal). Distinguished from each other by name only, not by sub-number.
  - `0.1.` = project README
  - `0.2.` = project overview/plan
- `1.`–`6.`-series (or similar) = actual content units within a project.
- Numbering order ≠ study order. The order files are actually worked through is tracked separately in the project's overview (e.g. "Study order: 4 → 5 → 6 → 1 → 2 → 3") rather than renumbering files to match.
- `Z.`-prefix = structural/meta documents about the vault itself (e.g. this guide) — sorted to the bottom, deliberately outside the `0.`–`6.` project numbering since it isn't part of any one project.

## Folders ("Forks")

- `<Framework Name> Fork/` (e.g. `Polya Fork/`) — an alternate lens on the **same** project content, reorganized under a different framework. Not project-prefixed, since the folder name already scopes it.
- Each fork folder gets its own `0. README.md` explaining how it maps back to the main structure.
- Files inside a fork use bare numbers (no project-name prefix), since the folder itself provides the scope.

## In-Note Formatting

- `**Created:**` / `**Done:**` date fields at the top of an overview file.
- `==highlight==` for key conclusions/takeaways.
- Obsidian `[[wikilinks]]` for internal navigation between notes — **note:** these do not render as clickable links on GitHub, so `README.md` (the GitHub-facing entry point) should avoid relying on them alone.
- Markdown links `[text](<path with spaces.md>)` (angle-bracket wrapped) specifically in README files, so they still render correctly on GitHub.

## Work Log Structure

In `0. Personal Notes.md`:
- One `# Note_YYYY-MM-DD, Day` header per day.
- Subsections: `## Topic:`, `## Logs`, `## Summary`, `## Next Action`.

## Adding a New Project

1. Create `0.2. <New Project Name>.md` — the overview/plan.
2. Create `0.1. README_<New Project Name>.md` — the project README, and link it back from the overview file.
3. Create `<New Project Name>_0. Understand the Problem.md`, then `_1.`, `_2.`, … for content.
4. Link the new project's README from the root `0. README.md`.
5. Log daily progress in the shared `0. Personal Notes.md`, under a `## Topic:` line referencing the project.