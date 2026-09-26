G-011 «Кнопка и Василий в Парке слов» — FINAL PRODUCTION PACKAGE

Entry point: index.html

Identity:
G-011 / gameVersion 1.0.0 / BANK-01 v1

Bank architecture:
- banks/manifest.js — runtime manifest
- banks/BANK-01.v1.js — approved BANK-01 runtime module
- JSON mirrors included for review/editing
- default bank: BANK-01
- selected bank: ?bank=BANK-01
- TEST: ?test=1&bank=BANK-01

Visual architecture:
- start screen keeps approved locked composition;
- all other scenic layers are environment/cats only;
- changing labels, instructions, cards, progress, feedback, zone-complete text/buttons and final results/actions are live DOM.

Publish as one static site over HTTP/HTTPS preserving this folder structure.
