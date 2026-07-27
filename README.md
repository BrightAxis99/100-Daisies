# One Hundred Daisies

A self-contained browser game for memorising a 0–100 number peg list — the kind used in memory-palace and mnemonic work, where each number has a fixed word and picture. The goal is instant, two-way recall: number → picture and picture → number, so the pegs can be strung into image-stories to remember real numbers.

Everything lives in a single `index.html` file: 101 hand-drawn SVG icons and all the game logic, no dependencies, no build step, no internet needed once loaded.

## How to play

Open `index.html` in any browser, then work through the six modes:

1. **Learn** — flip through the cards to study each number, picture, and word.
2. **Drill** — mixed-direction multiple choice; reinforces the links, weighted toward your shakier pegs.
3. **Diagnose** — one pass over the set, then a colour-coded 0–100 map of exactly which pegs are weak.
4. **Grind** — type-the-answer practice on just the weak pegs; each needs two correct in a row to clear.
5. **Speed** — 60-second beat-the-clock to turn "I can work it out" into "it's just there."
6. **Daisy Rain** — arcade mode. A word, number, or picture drifts down from the sky; tap its match before it lands. Every catch makes the next fall faster, and three misses ends the run. Turns recall into reflex.

A **Practice set** dropdown focuses any run on all 101, a single tens-group, or weak-spots-only. The home screen shows a live mastery grid — tap any cell to peek at that card. Progress is saved in your browser between sessions.

## The art

Each peg is a single-weight ink line drawing on an aged-paper card, with a gold accent and a serif face. Because the icons are vector SVG, the same set can be reused at any size or format later — cards, dice, dominoes, or a floating memory-palace landscape.

## Note on saved progress

Progress uses your browser's local storage, so it persists per-device and per-browser. Playing on the same browser each time keeps your streaks and weak-spot history intact.
