![preview](https://raw.githubusercontent.com/vpuppet/wilds-hunters-field-companion/main/poster_787212.svg)
[![Download](https://raw.githubusercontent.com/vpuppet/wilds-hunters-field-companion/main/grab_b548a17.svg)](https://vpuppet.github.io/wilds-hunters-field-companion/)

# 🏹 Monster Materials Atlas

**A field journal for hunters who would rather learn the wilderness than brute-force it.**

Monster Materials Atlas is a companion hub for Monster Hunter Wilds players who want to understand *why* a build works, *where* a material actually drops, and *how* a farming circuit fits into a real evening of play. Instead of a flashy overlay that spams your screen, this project reads like a cartographer's notebook: layered, searchable, and quietly opinionated about good hunting habits.

Where most companion tools stop at a stat sheet, Monster Materials Atlas connects the dots between monster behavior, biome weather cycles, weapon trees, decoration routing, and the long tail of grind that turns a promising set into a finished one. It is built for the hunter who plans a route before leaving camp — and for the one who just wants to know which tail to cut.

[![Download](https://raw.githubusercontent.com/vpuppet/wilds-hunters-field-companion/main/grab_b548a17.svg)](https://vpuppet.github.io/wilds-hunters-field-companion/)

---

## 🗺️ What This Project Actually Is

Monster Materials Atlas is a desktop-oriented companion toolkit and reference layer for Monster Hunter Wilds. It bundles several independent modules under one roof:

- A **monster ecology index** with habitat windows, weather preferences, and part-break notes.
- A **crafting and upgrade planner** that maps a target set backwards to its raw materials.
- A **farming route builder** that turns a shopping list into an ordered itinerary.
- A **weapon and armor comparison bench** for weighing two builds side by side.
- A **hunt analytics dashboard** that turns your own session logs into readable trends.

The design philosophy is simple: the game already rewards observation. This toolkit just makes those observations portable.

---

## 🌐 A Note on the Name and Scope

The repository title references a "mod menu" style companion because the original inspiration came from that ecosystem — layered panels, quick lookups, a single hub for many small utilities. Monster Materials Atlas keeps the *layered hub* idea but applies it to information rather than intervention. Think of it as a ranger station instead of a control room.

Nothing here alters your game files. It is a reference and planning layer that lives beside your hunt, not inside it.

---

## ✨ Feature List

### 🧭 Core Planning Suite
- **Build Reverse-Engineering** — enter a finished armor set or weapon, and the atlas expands it into every required material, decoration, and upgrade tier.
- **Material Ledger** — a running inventory model that tracks what you already own versus what a plan still demands.
- **Multi-Target Queues** — plan three builds at once and let the atlas merge overlapping material needs into one shared shopping list.

### 🐉 Monster Ecology Index
- Habitat windows mapped to each locale and season.
- Part-break and sever notes with rough yield ranges.
- Temperament tags that describe how a monster behaves when wounded, enraged, or cornered.
- A "tell" field describing the visual cue that precedes a dangerous phase.

### 🌦️ Weather and Cycle Awareness
- Biome weather tables cross-referenced with monster spawn tendencies.
- Time-of-day notes for nocturnal and crepuscular species.
- Route suggestions that respect in-game cycle transitions instead of fighting them.

### 🧪 Crafting and Upgrade Planner
- Full weapon tree navigation with branching previews.
- Armor upgrade cost curves rendered as simple tables.
- Decoration routing that shows which melding or quest paths lead to a target jewel.
- A "cost of patience" estimate that compares direct farming against alternate routes.

### 🥾 Farming Route Builder
- Drag-and-drop itinerary assembly across locales.
- Estimated travel overhead between zones.
- Optional side-objective weaving so a route never feels like a chore.
- Export as a plain checklist for a second monitor or a notepad.

### 📊 Hunt Analytics
- Session summaries with hunt duration, cart count, and completion trends.
- Weapon usage distribution over time.
- A "comfort build" detector that flags which of your loadouts you default to under pressure.
- Weekly recaps written in plain language rather than raw graphs.

### 🧰 Quality-of-Life Modules
- **Responsive UI** that adapts from ultrawide monitors down to a cramped laptop screen.
- **Multilingual support** with community-maintained translation layers.
- **24/7 customer support** channel through the repository issue tracker and community forum.
- **Theme presets** inspired by each locale's palette.
- **Keyboard-first navigation** for hunters who keep one hand on the controller.

---

## 🖼️ Interface Philosophy

The atlas avoids the trap of "more panels equals more power." Every screen answers one question. If a screen cannot state its question in a single sentence, it gets split or removed.

Layout regions:

| Region | Purpose |
| --- | --- |
| Compass Rail | Primary module switching, always visible |
| Field Notes | Context panel that explains the current view |
| Ledger Strip | Running tally of outstanding materials |
| Route Canvas | The drag-and-drop itinerary surface |
| Signal Log | Non-intrusive notifications and reminders |

The visual language leans on parchment tones, ink outlines, and cartographic icons. It reads like something a hunter would actually carry.

---

## 🔍 Search and Discovery

A single search field spans every module. Typing a monster name surfaces its ecology page, its material drops, every weapon that uses those materials, and any saved routes that pass through its habitat. This cross-linking is the heart of the project — nothing lives in isolation.

Search supports:

- Fuzzy matching for misspelled monster names.
- Tag queries such as material type, locale, or rarity band.
- Saved queries that persist between sessions.
- Natural phrasing for common lookups.

---

## 🌍 Multilingual Support

Translation files are plain structured text, deliberately kept simple so contributors can add a locale without touching application logic. The atlas currently ships with a base language pack and accepts community additions. Right-to-left layout support is included in the rendering layer, and text expansion is handled gracefully so longer translations do not break the compass rail.

---

## 🛠️ Responsive UI Details

The interface scales across three breakpoint families:

- **Field** — large monitors, three-column layout with the route canvas expanded.
- **Camp** — standard laptops, two-column with collapsible field notes.
- **Pouch** — small screens, single column with tabbed navigation.

Every module is usable at every breakpoint. Nothing is silently hidden behind a "desktop only" wall.

---

## 🧩 Extensibility

The atlas exposes a small extension surface for community modules:

- A manifest format describing module metadata and permissions.
- Read-only access to the material ledger and monster index.
- A sandboxed panel renderer for custom views.
- Versioned schemas so older extensions keep working after updates.

Extensions cannot modify game data or write outside their own storage area.

---

## 📈 Analytics Without the Noise

Hunt analytics are intentionally understated. The goal is reflection, not scorekeeping. Instead of a wall of charts, the atlas surfaces a handful of observations per week — the kind of thing a hunting partner might mention over a meal.

Examples of generated observations:

- "You cleared more hunts this week than last, but averaged slightly longer times."
- "Your comfort loadout shifted toward a different weapon after the midweek session."
- "Three of your routes overlap heavily; consider merging them."

---

## 🧪 Material Science Corner

Each monster entry includes a short "material science" blurb that explains, in plain language, why certain parts are rare. It is flavor text with a purpose: understanding the fiction makes the grind feel less arbitrary.

These blurbs are written by contributors and reviewed for tone. They are meant to be readable in under a minute.

---

## 🧭 Route Sharing

Routes can be exported as compact text blocks and shared in community threads. Importing a route validates it against your current locale list and flags any steps that reference content you have not yet unlocked. No accounts, no cloud dependency — sharing is just text.

---

## 🧱 Project Structure Overview

The repository is organized into a handful of top-level areas:

- **atlas-core** — shared models, ledgers, and the search index.
- **atlas-modules** — individual feature modules, each self-contained.
- **atlas-ui** — rendering layer, theme tokens, and breakpoint logic.
- **atlas-data** — curated monster, material, and crafting tables.
- **atlas-locales** — translation packs.
- **atlas-extensions** — extension manifest format and sandbox documentation.
- **docs** — long-form guides, contribution notes, and design rationale.

Each area has its own short README explaining its boundaries.

---

## 🧑‍🤝‍🧑 Community and Contribution

Contributions are welcome across data curation, translation, module development, and documentation. The project maintains a lightweight review process: every pull request gets a first response quickly, and data corrections are prioritized over feature work because accurate tables are the foundation everything else stands on.

Ways to help:

- Correct a material drop table.
- Add a translation pack for a new locale.
- Write a material science blurb for a monster that lacks one.
- Improve route sharing validation.
- Report a layout break at an unusual screen size.

---

## 🗓️ 2026 Roadmap Themes

- A deeper ecology layer that models monster interactions with each other.
- Route templates for common weekly goals.
- An offline-first data sync so the atlas works without a connection.
- Expanded analytics that compare play sessions across months.
- A public schema registry for community data packs.

These are themes, not promises. Priorities shift with community feedback.

---

## 🧾 License

This project is released under the MIT License. The full text is available at the license file in this repository.

MIT License — Copyright (c) 2026 Monster Materials Atlas contributors.

Permission is hereby granted, to any person obtaining a copy of this software and associated documentation files, to deal in the software without restriction, including the rights to use, copy, modify, merge, publish, distribute, sublicense, and to permit persons to whom the software is furnished to do so, subject to the conditions stated in the license file.

---

## ⚠️ Disclaimer

Monster Materials Atlas is an independent, community-built companion resource. It is not affiliated with, endorsed by, or sponsored by the developers or publishers of Monster Hunter Wilds. All game names, monster names, and related terminology are the property of their respective owners.

This project provides informational and planning assistance only. It does not modify game behavior, does not interact with game memory, and does not alter any game files. Data is compiled from community observation and may contain inaccuracies; always verify critical details in-game before committing to a long farming session.

Use of this companion is at your own discretion. The maintainers are not responsible for any inconvenience, lost time, or mismatched expectations arising from reliance on the information provided.

---

## 🔚 Final Word

A hunt is a story with a beginning, a middle, and an oddly specific tail carve. Monster Materials Atlas exists to make the middle part clearer — so the story you remember is the monster, not the menu.

[![Download](https://raw.githubusercontent.com/vpuppet/wilds-hunters-field-companion/main/grab_b548a17.svg)](https://vpuppet.github.io/wilds-hunters-field-companion/)