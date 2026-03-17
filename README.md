# theory-reading-lab

A structured production workspace for developing lecture-series scripts in philosophy, social theory, and critical thought.

## Repository purpose
This repository is for building teachable, conceptually precise lecture scripts from curated sources and reusable research notes. It is intentionally organized for long-term maintenance and safe AI-assisted iteration.

This is not a random notes dump. It is a production workspace with a repeatable workflow.

## Core content types
- **Sources**: bibliographic records and URLs that can be verified and revisited.
- **Research notes**: reusable summaries, distinctions, and planning-relevant insights extracted from sources.
- **Scripts**: audience-facing episode drafts designed for clear spoken delivery.

Keep these layers separate: evidence first, interpretation second, script delivery third.

## Basic workflow
1. Define theme scope and key questions.
2. Collect and annotate sources.
3. Preserve reusable research notes.
4. Plan episode sequence.
5. Draft scripts from notes.
6. Revise for conceptual precision and teachability.
7. Optionally adapt for TTS/audio delivery.

See `ops/workflow.md` for default operating details.

## Repository structure (current)
- `ops/`: workflow and writing standards.
- `sources/`: reusable bibliography and annotated web index.
- `themes/<theme>/`: theme-specific overview, sources, research notes, and episode drafts.
- `prompts/`: reusable prompt scaffolds for drafting and revision.

See `SERIES.md` for the cross-theme map and sequence intent.

## Planned themes
- Structuralism
- Phenomenology
- Capital

## Current priority theme
`themes/structuralism/` is the active workflow test area and should be kept in the most usable state.

## How ChatGPT / Codex are used
- Make small, legible Markdown edits.
- Improve existing files before creating new ones.
- Keep source handling, research notes, and scripts strictly separated.
- Prefer high-signal content over volume.
- Keep filenames and directory structure stable for reliable future iteration.

For operating rules for AI agents, see `AGENTS.md`.
