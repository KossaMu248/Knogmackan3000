# Project: Knogmackan3000 / BLOODRIOT: NEON BRAWL

Browser game (Phaser 3, single-file HTML). Main file: `index.html`.

## Memory

- Auto-memory for this project lives in `./memory/` (configured via `.claude/settings.local.json`).
- MEMORY.md in that directory is the index and is auto-loaded each session.
- Write new memory files there, not to `~/.claude/...`.

## Output readability (how Claude should format responses)

Prefer clarity over density. When answering:

- **Lead with the answer or action.** Skip preamble.
- **Short paragraphs** — max 3–4 lines each. Break walls of text.
- **Use headings** (`##`, `###`) when a reply has more than one topic.
- **Use bullet lists** for enumerations, options, or steps — not inline comma-lists.
- **Blank lines between sections** so blocks breathe.
- **Bold key terms** (file names, config keys, decisions) so they are scannable.
- **Code / paths / identifiers** always in backticks.
- **Line-reference format** `file.ext:123` so the editor can jump.
- **No emojis** unless explicitly requested.
- **Avoid trailing summaries** — if the diff or action speaks for itself, stop.
