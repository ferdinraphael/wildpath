# Wildpath

**Wildpath** is a short browser creature RPG where your companion learns from difficult encounters and adapts to survive them.

Choose **Mossling**, **Cindercub**, or **Brookit**, cross Fernwake, battle wild creatures, learn the type matchups, and challenge the guardian waiting at the north ridge.

If the guardian defeats you, the journey does not simply reset.

**Your companion remembers.**

It can adapt to the type of attack that defeated it, making the next attempt different from the last.

## Play

**Play Wildpath:** https://ferdinraphael.github.io/wildpath/

No installation is required. The game runs directly in a modern desktop browser.

## How a run works

1. Choose one of three companions.
2. Explore Fernwake and encounter wild creatures in the tall grass.
3. Gain XP, level up, and experiment with damaging and status moves.
4. Learn which move types are effective or resisted.
5. Reach the north ridge and challenge a guardian whose type counters your starter.
6. If you lose, your companion can adapt before the rematch.
7. Defeat the guardian to complete the journey.

## Adaptation

Failure is part of progression in Wildpath.

After losing to the ridge guardian, your companion can develop resistance to the guardian's attack type:

- **Adaptation I** after the first qualifying defeat
- **Adaptation II** after the second

Adaptation then reaches its limit for that journey.

This release implements the idea in a deliberately small form, but it represents the central direction of Wildpath:

> **Creatures change because of what they experience.**

## Controls

- **Move:** WASD or arrow keys
- **Choose / confirm:** Enter or Space
- **Battle:** click a move or press 1–4

## What's included

- three starter companions
- Fernwake exploration
- tall-grass encounters
- type advantages and resistances
- damaging and status moves
- XP and level progression
- a guardian tailored to counter the chosen starter
- guardian battle tactics including defense and limited healing
- experience-driven adaptation
- completion and replay loop

## About this release

Wildpath is currently a small, complete browser game rather than a full-length RPG. The focus of this release is the exploration → battle → adaptation → rematch loop.

Future versions may explore the adaptation idea more deeply rather than simply expanding toward a conventional creature-collection RPG.

## Technology

Wildpath is built with **TypeScript** and the **HTML Canvas API**.

The public repository contains the bundled/minified browser build. Development source is maintained separately.
