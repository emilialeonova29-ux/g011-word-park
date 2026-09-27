G-011 «Кнопка и Василий в Парке слов» — REUSABLE MATCHING TEMPLATE / FINAL PRODUCTION

Entry point: index.html

Identity:
G-011 / gameVersion 1.0.0 / BANK-01 v1

Reusable architecture:
- template/matching-template.css — stable matching-game layout and shared UI language;
- visual-packs/word-park.css — Word Park palette/decor identity only;
- banks/manifest.js + BANK-01.v1.js — replaceable content bank mechanism;
- assets/characters/knopka-vasiliy-approved.png — approved Knopka/Vasiliy identity;
- all dynamic state is live DOM.

Stable template surfaces:
- start;
- normal gameplay;
- generic wrong/correct feedback;
- homonym matching board inside the same shell;
- zone-complete DOM overlay;
- final in the same UI system.

Bank architecture:
- banks/manifest.js — runtime manifest
- banks/BANK-01.v1.js — approved BANK-01 runtime module
- JSON mirrors included for review/editing
- default bank: BANK-01
- selected bank: ?bank=BANK-01
- TEST: ?test=1&bank=BANK-01

Visual-pack rule:
background/decor/frames/character asset may change by theme, but dynamic zone name,
instruction, cards, progress, feedback, overlay text/actions and final results/actions
remain in DOM and keep the same template layout.

Publish as one static site over HTTP/HTTPS preserving this folder structure.
