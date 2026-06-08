# CREST Reference Library

The offline reference toolkit for every Colorado referee.

**Live URL:** [coloradoreferee.github.io/CREST_Reference](https://coloradoreferee.github.io/CREST_Reference)
**Developed by:** JAReferee LLC
**Licensed to:** Colorado Soccer Association

---

## What this is

CREST Reference Library is the in-pocket reference application for every referee operating under the Colorado Soccer Association's CREST program. All 17 Laws of the Game, the complete Guide to Referees, game day procedures, signals, age groups, Referee Abuse Prevention policy, and CSA contacts — in one application, on any device, completely offline.

It is designed for use on the touchline, in the parking lot before a match, or anywhere a referee needs a fast, authoritative reference without depending on connectivity.

---

## What it contains

The Reference Library bundles 31 reference modules covering:

| Category | Modules |
|---|---|
| Laws of the Game | All 17 IFAB Laws in full and condensed form, with decision trees |
| CSA Operations | Guide to Referees, age group standards, pre-game procedures, in-game procedures, post-game procedures |
| Signals & Mechanics | Complete signals guide, whistle patterns, 4 Moments of Soccer |
| Player Safety | Referee Abuse Prevention policy, RAP penalty matrix, code of conduct |
| Career Path | How to upgrade your grade, getting paid, Assignr platform guide |
| Contacts | CSA contact directory, parents of youth referees guide |

---

## Architecture

The application is a single-file HTML application with no server, no backend, and no external dependencies at runtime.

- Vanilla HTML, CSS, and JavaScript — no frameworks
- Embedded fonts (Bebas Neue, DM Sans) as base64 — fully offline
- All content embedded — works offline after first load
- Hosted via GitHub Pages from `main`
- Mobile first, scales cleanly to tablet and desktop

This is a deliberate constraint, not a limitation. The app must run on a referee's phone on a youth field with no connectivity, instantly, every time.

---

## The CREST Suite

| Tool | URL | Status |
|---|---|---|
| CREST Hub | [coloradoreferee.github.io](https://coloradoreferee.github.io) | Live |
| CREST Game Day | [coloradoreferee.github.io](https://coloradoreferee.github.io) (in hub) | Live |
| CREST Ref Coach | [coloradoreferee.github.io](https://coloradoreferee.github.io) (in hub) | Live |
| CREST Team | [coloradoreferee.github.io](https://coloradoreferee.github.io) (in hub, per-club) | Live |
| CREST Evaluator | [coloradoreferee.github.io/CREST_Evaluator](https://coloradoreferee.github.io/CREST_Evaluator) | Live — to merge into hub |
| CREST Academy | [coloradoreferee.github.io/CREST_Academy](https://coloradoreferee.github.io/CREST_Academy) | Live — to merge into hub |
| CREST Reference Library | this repo | Live — to merge into hub |

The three currently-separate CREST repos will be consolidated into the main hub repository ahead of the program's full handoff to CSA in January 2027.

---

## About C.R.E.S.T.

C.R.E.S.T. is the Colorado Soccer Association's referee development program. It integrates U.S. Soccer's referee certification framework with Colorado-specific operations and the Referee Abuse Prevention initiative. The program is developed and operated by CSA, with software provided by JAReferee LLC.

---

## Status

This software is under active development as part of the CREST program. Releases deploy automatically to GitHub Pages from the `main` branch.

---

## License & Use

This software is proprietary, owned by **JAReferee LLC**, and licensed to the **Colorado Soccer Association** for use within the CREST program. See `LICENSE.txt` and `NOTICE.md` for the full terms.

Reference content (including the Guide to Referees and CSA-specific procedures) is contributed by CSA and remains the property of CSA. IFAB Laws of the Game content remains the property of IFAB.

Use by parties other than CSA (acting within the scope of the CREST program) requires a separate written license agreement from JAReferee LLC.

**Public visibility of source does not imply public license.**

---

## Contact

**For CREST program questions:**
- Director of Referee Operations: **Deanna Duncan-Allen** — refeducation@coloradoreferees.com — 303.888.6863
- Head of Refereeing: **Esse Baharmast**
- Media: **Krissia Vasquez** — kvasquez@coloradosoccer.org

**For software licensing or development questions:**
- JAReferee LLC — https://jareferee.com — licensing@jareferee.com
- Principal: **Jeff Arthurholtz**

---

© 2026 JAReferee LLC. All rights reserved.
Licensed to the Colorado Soccer Association for use within the CREST program.
