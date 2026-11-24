# VIDEOLAND — mohamedNadyS.github.io

My personal portfolio, built as a 1980s video rental store. Every page is a tape,
every interaction is something a VCR would do.

**Live:** <https://mohamedNadyS.github.io>

## The store

| Tape | Page | Its thing |
| --- | --- | --- |
| TAPE 001 | `index.html` | Booting terminal hero, member card, the collection index |
| TAPE 002 | `projects.html` | A working CRT TV — CH+/CH− buttons switch projects — plus a browsable VHS shelf |
| TAPE 003 | `skills.html` | An audio cassette with a J-card tracklist, Side A and Side B |
| TAPE 004 | `experience.html` | The rental-history ledger, member #0011, no late fees |
| TAPE 005 | `contact.html` | Talk to the clerk |

## The mechanics

- **Eject / insert page transitions** — nav clicks slide the tape out, the next
  page thunks it back in.
- **FFWD / REW scroll navigation** — a deliberate double-flick past the bottom or
  top edge fast-forwards or rewinds to the next tape, with rolling scanlines and
  an OSD badge. A wild scroll to the bottom just arms it, so nobody flips a page
  by accident.
- **2.5D tilt** on the VHS sleeves, TV channel-surf OSD, tape counters, and a
  warm amber rental-store palette. No frameworks, no build step.

## Stack

Hand-written HTML, CSS and vanilla JS. One file per page, fully self-contained;
the only external dependency is Google Fonts (IBM Plex Mono, Fraunces, Caveat).

## Running locally

Clone the repo and open `index.html` in a browser — that's it.
Keep all five `.html` files in the same folder so the routes resolve.

```bash
git clone https://github.com/mohamedNadyS/mohamedNadyS.github.io.git
cd mohamedNadyS.github.io
open index.html   # or just double-click it
```

Best experienced on a laptop with a mouse: the tilt, hover and channel buttons
want a cursor. Scroll page-turn works with both wheel and touch.

## Copyright

© 2026 Mohamed Nady Selim. All rights reserved. No license is granted to copy,
reuse or redistribute the code or design at this time.
