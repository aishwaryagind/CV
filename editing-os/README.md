# Editing OS

A lightweight system for taking video/content from idea to published, the same way every time.

## Pipeline

1. **Capture** – ideas go in `inbox.md`. Nothing else.
2. **Plan** – promote an idea to a project: copy `projects/_template/` to `projects/YYYY-MM-DD-slug/` and fill `brief.md`.
3. **Ingest** – import footage, name and organize it (see `folder-structure.md`).
4. **Assemble** – rough cut: story and pacing only, no polish.
5. **Refine** – fine cut, audio, color, graphics, captions.
6. **Review** – run `templates/review-checklist.md`, get feedback, one revision round max.
7. **Export & publish** – use `templates/export-presets.md`, then `publish.md` in the project.
8. **Archive & retro** – archive raw files, write 3 lines in `retro.md`.

## Rules

- One project = one folder = one brief.
- Every project has a status: `idea → planned → editing → review → published → archived`.
- Work in passes (structure → polish → audio → export). Don't polish during assembly.
- Timebox each pass; note the limit in the brief.
- Keep `tracker.md` current; it is the single source of truth for what's in flight.

## Files

| File | Purpose |
|---|---|
| `inbox.md` | Idea capture |
| `tracker.md` | Project status board |
| `folder-structure.md` | Where files live and how they're named |
| `projects/_template/` | Per-project brief, shot list, publish and retro files |
| `templates/review-checklist.md` | QC before export |
| `templates/export-presets.md` | Export settings per platform |
| `weekly-review.md` | Weekly maintenance routine |
