# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Repo Is

This is a **trip planning repository**, not a software project. It uses Claude Code in non-interactive mode (`claude -p`) to research, plan, and generate decision-support documents for a summer 2026 trip. There is no code to build, lint, or test.

## Shared Context

**Always read `vision.md` first.** It defines the travelers, destinations, preferences, budget mindset, activities, and output format expectations. Every feature spec references it as shared context.

## Workflow

This repo uses [spec kit](https://github.com/) (`.specify/` directory and `.claude/commands/speckit.*`) to organize research into features. The spec kit commands (`/speckit.specify`, `/speckit.plan`, `/speckit.tasks`, `/speckit.implement`) are adapted here for research and document generation rather than software development.

### Mapping spec kit concepts to trip planning

| Spec Kit Concept | In This Repo |
|---|---|
| Feature | A research area (e.g., "Yellowstone hiking trails", "flights from Boston") |
| Spec | What to research, what questions to answer, what format to deliver |
| Plan | Research strategy — what sources to check, how to organize findings |
| Implementation | Performing the research (web searches, comparisons) and writing the output document |
| User stories | Information needs — "As a trip planner, I need to compare X so I can decide Y" |
| Acceptance criteria | The output doc contains specific, actionable information (links, prices, distances, pros/cons) |

### Non-interactive execution

Features are designed to be runnable independently via `claude -p`. Each feature spec should contain enough context (plus a reference to `vision.md`) that Claude can produce a complete output document without interactive clarification.

## Output Standards

All output documents must follow these rules from `vision.md`:

- **Decision support, not decisions.** Present 2-3 options with trade-offs, pros/cons, and a recommendation with reasoning. Never prescribe a single answer.
- **Day-by-day menus.** For itinerary features, group activity options by effort level (chill / standard / big day).
- **Actionable info.** Include links, booking URLs, trail names searchable in CalTopo/Gaia/AllTrails, prices, distances, and elevation gains.
- **Current information.** Use web search to find up-to-date info. It is 2026 — check for 2026-specific details (permit deadlines, reservation windows, road openings).

## Key Details to Remember

- Departing from **Arlington, MA** (fly round-trip BOS → BZN)
- **Chosen destination:** Greater Yellowstone Loop — **Tetons → Yellowstone → Beartooth/Shoshone NF → BZN**
- **~10 days** on the ground: 3 days Tetons, 3-4 days Yellowstone, 2-3 days Beartooth
- **Car camping** is the base mode; **backpacking in Beartooth Wilderness** is a strong option
- They are **fit and experienced** hikers (10+ mile days standard), but this is their **first time in grizzly country**
- She is a **V10 boulderer** — include bouldering spots and pad rental info
- They value **going deeper than typical tourists** — lesser-known trails and solitude over famous crowded overlooks
- **Spend smart**, not cheap — surface prices but don't filter out options by cost
