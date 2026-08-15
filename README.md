# One Hundred Daisies

A self-contained browser game for memorising a 0–100 number peg list — the kind used in memory-palace and mnemonic work, where each number has a fixed word and picture. The goal is instant, two-way recall: number → picture and picture → number, so the pegs can be strung into image-stories to remember real numbers.

Everything lives in a single `index.html` file: 101 hand-drawn SVG icons and all the game logic, no dependencies, no build step, no internet needed once loaded.

## How to play

Open `index.html` in any browser. New to the system? **Start with The Code** — a one-screen reference (with memory hooks) of which consonant sounds map to each digit 0–9, plus a quick self-quiz. Every peg word is built from it.

**Daily Practice** is the front door. A 15-question round the game picks for you: pegs due for spaced review, plus a few you haven't met yet. Most days this is the only button you need.

Then four modes for when you want something specific:

1. **Study** — flip through the cards to learn each number, picture, and word.
2. **Name It** — a number or a picture, and you type the word from memory. No options to choose from. This is the mode that teaches, and the only one that can bloom a peg.
3. **Beat the Clock** — 60-second rapid recall, to turn "I can work it out" into "it's just there."
4. **Daisy Rain** — arcade mode. A word, number, or picture drifts down from the sky; tap its match before it lands. Every catch makes the next fall faster, and running out of hearts ends the run.

A **Practice set** dropdown focuses any run on all 101, a single tens-group, reviews due, or everything not yet bloomed. Within a tens-group the wrong answers are drawn from that same group, so you're forced to tell 74 from 76 rather than from 3.

The home screen shows a live mastery grid — tap any cell to peek at that card. Progress is saved in your browser between sessions.

## What it takes to bloom a peg

Multiple choice is easy to beat. Once you know the code, seeing 75 tells you the word starts with a K sound, and picking Koala out of four options needs no memory at all. So multiple choice can carry a peg to "solid" on the grid, and no further.

**A peg only blooms once you've typed its word correctly 3 times, across at least 2 different days.** Getting it wrong anywhere, in any mode, resets the count. Typing is checked forgivingly: case, spaces, punctuation and plurals are ignored, and one typo is allowed on words of 4 letters or more.

Name It also watches what you miss. Fumble a few pegs in Daisy Rain or Daily Practice, then open Name It, and it offers to drill exactly those.

## The art

Each peg is a single-weight ink line drawing on an aged-paper card, with a gold accent and a serif face. Because the icons are vector SVG, the same set can be reused at any size or format later — cards, dice, dominoes, or a floating memory-palace landscape.

## Note on saved progress

Progress uses your browser's local storage, so it persists per-device and per-browser. Playing on the same browser each time keeps your streaks and weak-spot history intact.
