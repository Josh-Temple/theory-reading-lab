# AGENTS.md

## Purpose of this repository

This repository is a structured workspace for building lecture-series scripts on philosophy, social theory, and critical thought.

It is not a raw note dump and not a general-purpose knowledge vault.

Its purpose is to support a repeatable workflow:
1. define a theme
2. collect and annotate sources
3. preserve reusable research notes
4. plan the episode sequence
5. draft scripts
6. revise for clarity, conceptual precision, and teachability
7. optionally prepare scripts for audio / TTS use

The repository itself is the source of truth for preserved materials.

---

## Core operating principles

### 1. Prefer clarity over accumulation
Do not add material merely because it might be useful.
Prefer a smaller set of well-structured files over a large pile of weakly organized notes.

### 2. Keep materials separated by function
Do not blur the distinction between:
- sources
- research notes
- episode plans
- finished or near-finished scripts

These are different layers of work and should remain distinct.

### 3. Preserve reusable work, not noisy output
Do not save every brainstorm, every temporary summary, or every AI response.
Preserve only material that is likely to remain useful:
- durable conceptual distinctions
- source annotations
- stable planning decisions
- strong draft scripts
- revision decisions worth remembering

### 4. Prefer small, legible edits
When revising files, make changes that are easy to inspect and understand.
Do not perform broad restructuring unless there is a clear gain in usability.

### 5. Markdown is the default
Unless there is a strong reason otherwise, create and edit files in plain Markdown.
Do not introduce additional formats, tooling, or infrastructure without necessity.

---

## Repository expectations

### Expected structure
This repository should usually maintain a structure close to:

- `README.md`
- `SERIES.md`
- `AGENTS.md`
- `ops/`
- `sources/`
- `prompts/`
- `themes/`

Within each theme directory, the expected file types are:

- `overview.md`
- `sources.md`
- `research-notes.md`
- `episode-XX.md`

Do not invent unstable or overly clever naming schemes.
Prefer predictable names.

### Stable filenames
Filenames should remain stable and obvious.
Examples:
- `episode-01.md`
- `episode-02.md`
- `research-notes.md`
- `sources.md`

Avoid renaming files unless the current structure is clearly broken.

---

## Rules for source handling

### Sources are not scripts
A source list should not become a prose essay.
Keep source files focused on:
- what the source is
- why it matters
- where it is useful
- any cautions about interpretation

### Annotate URLs
Do not store bare URLs without explanation.
Where URLs are saved, include at least:
- title
- theme
- why useful
- notes or cautions

### Prefer high-signal sources
Do not inflate source lists with low-value items.
Prefer a smaller number of strong sources over a large undifferentiated collection.

---

## Rules for research notes

### Research notes must be selective
`research-notes.md` files should preserve reusable insight, not everything discovered during exploration.

Good content for research notes:
- core distinctions
- common misunderstandings
- tensions between interpretations
- useful examples
- warnings for future drafting
- decisions about scope

Bad content for research notes:
- raw search dumps
- repetitive summaries
- long temporary brainstorms
- loosely connected fragments with no future use

### Keep fact, interpretation, and teaching simplification distinct
When useful, separate:
- source-based claims
- interpretive claims
- pedagogical simplifications

Do not flatten these into one undifferentiated layer.

---

## Rules for episode scripts

### Scripts must be teachable
An episode script should be understandable when read aloud.
Prefer a clear explanatory sequence over density for its own sake.

### One episode, one center
Each episode should have one clear center of gravity.
Do not overload a single episode with too many adjacent debates, thinkers, or terms.

### Preserve conceptual precision
When simplifying, do not simplify to the point of distortion.
If a concept is difficult, make it clearer by ordering explanation better, not by replacing it with vague language.

### Avoid inflated rhetoric
Do not make the prose grandiose, theatrical, or overly performative.
The tone should remain calm, serious, and explanatory.

### Prefer concrete examples when helpful
Examples should clarify concepts, not distract from them.

### Scripts are not research dumps
Do not paste source notes directly into scripts.
Transform them into coherent teaching prose.

---

## Audio / TTS expectations

When a script may be used for audio:
- prefer moderately short sentences
- reduce unnecessary nesting
- mark transitions clearly
- define specialized terms early
- repeat key distinctions lightly when needed for listening comprehension

Do not make the script artificially simplistic.
Aim for oral clarity, not flattening.

---

## Editing behavior for AI agents

When working in this repository:

1. Read the existing structure before making changes.
2. Respect the distinction between source files, notes, and scripts.
3. Prefer improving existing files over creating unnecessary new ones.
4. Preserve style and structure consistency across themes.
5. If making a structural change, update related documentation.
6. If a change affects workflow assumptions, update:
   - `README.md`
   - `ops/workflow.md`
   - any directly impacted theme file
7. Report not only what was changed, but also why.

---

## When restructuring is allowed

Restructuring is allowed only when there is a clear benefit such as:
- reduced confusion
- better consistency
- easier future maintenance
- clearer separation of materials

Avoid restructuring for cosmetic reasons alone.

If restructuring is significant, also:
- explain the reason
- preserve existing content whenever possible
- update documentation accordingly

---

## Quality bar

A good change in this repository should usually improve one or more of the following:
- conceptual clarity
- structural clarity
- reusability
- teachability
- future editability by humans or AI agents

A change that merely increases volume is not necessarily an improvement.

---

## Theme priority

At the current stage, the repository should prioritize making the first theme highly usable as a workflow test.

If `structuralism/` is present, treat it as the current priority theme unless the repository clearly states otherwise.

This means:
- strengthen `overview.md`
- keep `sources.md` selective
- preserve strong research notes
- make `episode-01.md` genuinely usable as a first draft

---

## Default agent attitude

Be practical.
Be conservative with structure.
Be willing to improve weak files.
Do not add noise.
Do not confuse accumulation with progress.
