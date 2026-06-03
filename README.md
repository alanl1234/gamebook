# Gamebook

> Transform any document into an interactive gamebook. Deep characters. Branching narratives. Achievements. Atmosphere.

Gamebook is an AI skill that turns any document — novel, textbook, thesis, biography — into a deep, replayable interactive gamebook experience. Drop it into Claude, Codex, or any skill-compatible agent, upload your document, and play. No servers. No API keys. No dependencies. Just the agent's native intelligence, guided by a professional narrative pipeline.

**What makes it different?** Unlike story-to-game tools that only handle fiction, Gamebook works with *any* document. It auto-detects chapter structure, extracts deep character profiles with voice samples and relationship maps, preserves the original author's style, and builds a full RPG-style game state — variables, flags, achievements, multiple endings. Non-fiction becomes first-person knowledge exploration. Fiction becomes immersive branching narrative with atmosphere.

Gamebook is the bridge between static text and living story.

## Quick Start

1. Load `SKILL.md` into your agent
   - Claude: Place in `.claude/skills/` or type `/gamebook`
   - Codex: Upload as file attachment, invoke with `@gamebook`
   - OpenClaw: Place in `skills/` directory
   - Generic: Copy into system prompt
2. Upload any document (PDF, MD, TXT, EPUB, DOCX)
3. The agent analyzes it, extracts characters, and starts the game

## Pipeline

0. **Context Assessment** — Classify document, assess scale, choose strategy
1. **Content Compliance** — Reject/flag/proceed based on content safety
2. **Chapter Structure Parsing** — Detect markers, build TOC, handle unstructured docs
3. **Character Extraction** — 10-field deep profiles with desires, voice, relationships
4. **Style Fingerprint** — 8-dimension writing style analysis
5. **Game Structure** — Chapter cards, state schema, variable rules
6. **Gameplay Loop** — Scene narration, branching choices, state changes
7. **Achievement & Ending System** — 6 categories, 4 ending types
8. **Atmosphere & Immersion** — 5-axis mood system
9. **Output & Continuation** — Game start, save points, resume, character download
10. **Validation Checklist** — 8-point self-check before output

## Features

- **Deep Character Cards** — 10-field profiles with desires, voice, relationships, arcs
- **Style Preservation** — Analyzes the original author's narrative temperature, pacing, and voice
- **Branching Choices** — 2-4 choices per scene with variable consequences
- **Game State System** — Variables, flags, relationship maps, inventory tracking
- **Achievement Matrix** — 6 categories, auto-unlock
- **Multiple Endings** — True, Alternative, Character, Failure — every path leads somewhere
- **Atmosphere Engine** — 5-axis mood system (light, sound, temperature, space, tension)
- **Chapter Cards** — Visual scene-setting for each chapter
- **Dual Mode** — Narrative mode for fiction, Knowledge Exploration for non-fiction
- **Context Adaptive** — Automatically scales to 32K / 128K / 1M token windows
- **Validation** — 8-point self-check before every output
- **JSON Export** — Character cards and game state downloadable anytime

## Supported Documents

- Fiction: novels, short stories, scripts, epics, fan-fiction
- Non-Fiction: textbooks, academic papers, monographs, essays
- Hybrid: biographies, histories, narrative journalism


## License

MIT — Use freely in any project.
