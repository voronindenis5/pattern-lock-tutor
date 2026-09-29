---
name: pattern-lock-tutor
description: Learn or change motor sequences — pattern locks, shortcut chains, riffs — with transposition drills, interference drills, and spaced recall.
version: 1.0.0
author: Denis Voronin
license: MIT
tags: [muscle-memory, spaced-repetition, training, habits, motor-learning]
---

# Pattern Lock Tutor

**New pattern fluent in days, not weeks.**

Motor-sequence trainer for pattern locks, shortcut chains, keypad PINs,
riffs, controller combos. Attacks the three real failure modes: untrained
transpositions (every rotation is a separate skill — weakest drilled first),
old-habit interference (interleaved old-vs-new alternation drills with a
win-rate that predicts real-world blanking), and speed-before-accuracy
(95% accuracy gate before any tempo work). Expanding recall ladder
(10min→35d), readiness verdict across all three criteria.

## Quick Start
```bash
python3 scripts/pattern_tutor.py seq add phone-new 2,6,4,8,5
python3 scripts/pattern_tutor.py train phone-new
python3 scripts/pattern_tutor.py interfere phone-old phone-new
python3 scripts/pattern_tutor.py ready phone-new
```

Never train on your real unlock pattern — same shape, different specifics.
100% local, terminal-based, works over SSH.
