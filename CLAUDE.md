# CLAUDE.md

Guidance for Claude Code (claude.ai/code) when working in this repository.

## What this repo is

A personal, **source-faithful notebook on building a startup.** Each note distills one talk, essay, or lecture into what's *actionable*. It currently covers all **20 lectures of Stanford CS183B — *How to Start a Startup*** (Sam Altman, 2014), each paired with hand-built SVG diagrams.

There is **no build system, package manager, or test suite** — the artifacts are Markdown notes and standalone SVG files rendered inline by GitHub.

## Layout

| Path | What |
|---|---|
| `NN-slug.md` | one note per source, numbered so reading order is preserved (`01-…` → `20-…`) |
| `assets/*.svg` | the diagrams, embedded into notes via `![alt](assets/x.svg)` |
| `README.md` | the index: notes table, the layered narrative, the diagram gallery |

## Note conventions

Every note follows the same shape — match it when adding one:

1. **Header blockquote** with `> Source:`, `> Transcript:` (URL), `> Captured:` (today's date, absolute), and a one-line framing that links related notes.
2. **Faithful to the source.** Quotes are *real* — never invent them. If a source doesn't cover something, say so rather than filling it in from general knowledge. Convert relative dates to absolute.
3. **Scannable:** short prose, tables for comparisons, real quotes in `>` blockquotes, **bold** for the load-bearing phrase.
4. **Relative Markdown links** to related notes, with a readable title — e.g. `[Teams & Execution](02-teams-and-execution.md)` (these render on GitHub; Obsidian-style `[[wiki-links]]` do not).
5. End with a **`## My action items`** checklist — questions to ask about *my own* startup.

## Diagram conventions

The SVGs share one visual identity — keep it consistent:

- **viewBox `0 0 1040 560`**, white background, a 6px orange top bar (`#F1592A`), a bold title + muted subtitle, system font stack (`-apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif`).
- **Palette:** primary orange `#F1592A` (tints `#F2855B`, `#F6A07A`, `#F8B597`, `#FBD2BE`, `#FDE7DC`, `#FFF8F5`); dark text `#1A1A1A`; muted `#5A6475` / `#8A94A6` / `#9AA3B2`; light fills `#F4F6F9` / `#EEF1F5`; borders `#D8DCE4` / `#E2E6ED`. Green for "do" (`#1A8A4A`), red for "don't" (`#C0392B`).
- SVG text has **no markdown** — write literal characters (no `*emphasis*`), and keep text inside its shape (watch for clipping/overflow).

**Always validate and eyeball a diagram before committing:**

```bash
xmllint --noout assets/your-diagram.svg                       # well-formed XML
qlmanage -t -s 1040 -o /tmp/svgcheck assets/your-diagram.svg  # render to PNG, then view it
```

Real bugs have shipped from skipping the visual check (clipped labels, miscounted dot grids, backward arrows, overflowing captions). Render and look.

## Adding a note — checklist

1. Write `NN-slug.md` following the note conventions; weave in relative links to related notes.
2. Build the 1–2 most distinctive diagrams for that source; validate + render-check each.
3. Update `README.md`: the **Notes table**, the **layered-narrative** line, and the **Diagrams gallery**.
4. Commit with a descriptive message; co-author trailer:
   `Co-Authored-By: Claude Opus 4.8 (1M context) <noreply@anthropic.com>`

## Future sources

Same treatment when added: Paul Graham's essays, *Zero to One*, *The Hard Thing About Hard Things*, *High Output Management*.
