[🇧🇷 Português](README.md) · **🇺🇸 English**

# 🎮 Workshop: My First Game in GDevelop

> A complete workshop script for children to create their first digital game — from zero to playable in 2 hours, without writing code.

**Author:** [Paula Peclat](https://github.com/paulapeclat) · [APedê Digital](https://paulapeclat.com.br)
**Ages:** 8 to 12 · **Duration:** 2h (or two 1h sessions) · **Tool:** [GDevelop](https://gdevelop.io) (free, runs in the browser)

---

## Why this workshop exists

From a media literacy perspective, playing is not enough: we want children to **produce** media and, by producing, understand the choices every designer makes. When a child decides the character's speed, what scores points and what makes you lose, they discover in practice that **every game is made of someone's decisions** — and they start looking at the games they consume with new eyes.

This material follows the **concrete-to-abstract** progression: direct manipulation of objects → events (if/then) → variables (score).

## Learning goals

By the end, each child will have:

- [ ] Created a working "collect the items" game
- [ ] Used the **event → condition → action** logic (the foundation of computational thinking)
- [ ] Created and modified a **variable** (the score)
- [ ] Made at least **3 design decisions of their own** (character, speed, rule)
- [ ] Reflected on who makes those decisions in the games they play

**Curriculum alignment:** in Brazil, this maps to BNCC General Competency 5 (digital culture) — understanding, using and **creating** digital technologies in a critical, meaningful and ethical way. It translates naturally to media literacy and computing standards elsewhere.

## Materials

- Computers with a browser (the [GDevelop web editor](https://editor.gdevelop.io) requires no installation)
- Optional: a free GDevelop account for cloud saving (children under 13 need consent — alternative: save the `.json` file locally)
- A projector for demonstrations

## Script

### Step 0 — Opening conversation (10 min)

Ask: *"Who played a game today? Who DECIDED how that game works?"*
Write the hypotheses on the board — we will come back to them at closing time.

### Step 1 — Getting to know the stage (15 min)

1. Open [editor.gdevelop.io](https://editor.gdevelop.io) → **New project** → empty project
2. Explore together: the **scene** (the stage), **objects** (the actors), **events** (the rules)
3. Create the first object: the player sprite (use GDevelop's free asset library — let each child choose their character: **design decision #1**)

### Step 2 — Bringing the character to life (20 min)

1. Select the player object → **Behaviors** → add **"Top-down movement"**
2. Test with the arrow keys (▶️ Preview)
3. Let each child adjust the **speed** (design decision #2). Trigger question: *"Is a very easy game fun? What about an impossible one?"*

### Step 3 — What falls from the sky (20 min)

1. Create the second object: the item to collect (fruit, star, coin — free choice)
2. First **event**: `Every 1 second → Create object item at a random position at the top`
3. Add the **"Gravity force"** behavior or a movement event to make the item fall

*Natural break here if the workshop runs as two sessions.*

### Step 4 — The rule of the game (20 min)

1. Create the **scene variable** `score = 0`
2. Event: `If player collides with item → delete item AND add 1 to score`
3. Add a **text** object that displays the score
4. Each child defines **what happens when an item touches the ground** (design decision #3): lose a point? game over? nothing?

### Step 5 — Making the game YOURS (20 min)

Free choice: change the background, add a collect sound, create a second item type worth more points, or add a "bad" item that subtracts points.

### Step 6 — Game festival + closing (15 min)

1. Rotation: each child plays another child's game
2. Closing circle, returning to the Step 0 board:
   - *"What did you decide in your game that turned out different from your classmate's?"*
   - *"If every game has a designer deciding the rules... what did the designers of YOUR favorite games decide to keep you playing longer?"*

That last question is the bridge from creation to **critical media reading** — do not skip the closing.

## Assessment

Process observation, not a test: did the child use event/condition/action? Did they make their own decisions and justify them? Did they take part in the final reflection? A per-student checklist does the job.

## Variations

- **Ages 6-8:** the teacher projects and drives; children collectively decide each parameter (an unplugged version of design agency)
- **Ages 12+:** add a game over screen, levels, or port the same game to [microStudio](https://microstudio.dev) and compare blocks × code
- **Unstable internet:** GDevelop has an offline desktop version

## License

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) — use, adapt and redistribute, with attribution and the same license. If you run it at your school, [tell me how it went](https://github.com/paulapeclat/primeiro-jogo-gdevelop/issues)! 💛
