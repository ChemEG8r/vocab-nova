# Vocab Nova

VJ's Chapter 10 space-vocabulary practice app, quizzable by section:

- **Section 1 — The solar system** (8 words): solar system, astronomical
  unit, Sun, planet, moon, asteroid, meteoroid, comet
- **Section 2 — The Sun** (7 words, this week's test): photosphere,
  chromosphere, corona, solar wind, sunspots, prominence, solar flare
- **Section 3 — Light & energy** (3 words): electromagnetic radiation,
  visible light, spectrum

Every word is asked **two ways** each round: multiple choice (term →
definition or definition → term, with same-section distractors) and typed
recall (definition → type the term, with Damerau-Levenshtein typo
tolerance). Each answer comes with a one-line memory hook, and the study
screen lists all words with corrected, test-ready definitions.

Scores sync across devices via Cloudflare Workers KV
(`functions/api/scores.js`, binding `SCORES`); history shows exactly which
words were missed and tallies trouble words.

Live: https://vocab-nova.pages.dev
