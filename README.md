# Practice Table

A browser trainer for blackjack basic strategy and Hi-Lo card counting.

**Live:** https://arif9325.github.io/practice-table/

## Features

**Basic strategy**
- Flashcard drills: mixed hands, hard totals, soft totals, pairs, surrender, tricky spots
- My mistakes: hands you miss come back until you get them right
- Play it out: every hit or split leads to the next decision until the hand is finished
- Play full hands from a shoe, and a 60-second sprint
- Add up to 6 other players to the table between rounds

**Card counting (Hi-Lo)**
- Card values, cancel groups, running count stream, deck countdown, true count conversion
- Deviations: Illustrious 18, Fab 4 surrenders and insurance, tested on both sides of each index
- Live table: a full table plays itself; stop at any moment and give the running and true count
- Full shoe: play, count, bet on a ramp and deviate, with count checks between rounds

**Rules you can change**
H17 / S17, double after split, late surrender, 1–8 decks, penetration. The strategy charts rebuild from these settings.

Every decision is checked, and mistakes come with an explanation of the correct play.

## Tech

One self-contained HTML file with vanilla JavaScript and CSS. No build step and no dependencies. Progress is saved in the browser with `localStorage`.

## Run locally

Open `index.html` in a browser.
