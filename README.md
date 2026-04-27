# TOP MOW — Operation Ship It

A very stupid joke game starring **Brent Sperry**, COO of LexMed, on a Spartan zero-turn riding mower, mowing down the founder's terrible AI startup ideas while shipping good ones out the back.

## Play

Open `index.html` in any modern browser. No build step.

**Controls**
- Arrows / WASD — drive the mower
- Enter / Space — advance menus
- M — toggle music

## How it works

- The **Founder** paces the office and pitches bad ideas (they accumulate as gravestones with zombie hands)
- **Drive over bad ideas** to mow them — score goes up, scope creep drops
- **Drive constantly** — Brent's mower kicks **good ideas** out the back. They mature into shipped (green check)
- **DON'T mow your own immature good ideas** — that's a scope-creep penalty
- Game over when **scope creep** maxes or **fuel** runs out

## Tech

Single self-contained `index.html`. Vanilla JS, no dependencies. Canvas 2D with a hand-rolled bitmap pixel font, sprite system, particle effects, and a chiptune music loop via WebAudio.

The cover image (`cover.png`) is shown on the title screen.

## Credits

A LexMed.ai birthday-card-grade artifact. For internal laughs only.
