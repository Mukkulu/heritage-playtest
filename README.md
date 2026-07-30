# Heritage — combat prototype playtest

A browser-only playtest build of a match-3 combat prototype: gear defines what each gem colour
does, hard shapes leave specials you detonate later, and fusing two specials chains into bigger
combos. Six loadouts to try, five encounters plus endless waves.

Just open `index.html` (or the hosted page) and play — click or drag adjacent gems to swap.

This is a single self-contained playtest build with no server and no tracking beyond an optional
log submission you trigger yourself with the in-game button.

## Playtest logs

Submitted logs land in a Google Sheet:
https://docs.google.com/spreadsheets/d/13lscJ8V8d3RqQ7iIEujB5qYYtGAEeUwsmG_zFMi3ZfI/edit?gid=159350321

Each row's Log column has a full run report (loadout, colours, triggers, shapes formed, fusions
taken, encounter-by-encounter results). Runs from before 2026-07-30 have no `version` line and
can't be reliably tied to a specific commit — only later rows can.
