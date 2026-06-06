# Strudel

A personal repository for exploring [Strudel](https://strudel.cc/) — a browser-based live coding environment for algorithmic music.

## What is Strudel?

[Strudel](https://strudel.cc/) is a JavaScript port of [Tidal Cycles](https://tidalcycles.org/), the algorithmic pattern language created by Alex McLean. Initiated by Alex McLean and Felix Roos in 2022, Strudel brings Tidal's expressive pattern manipulation to the web — no Haskell, SuperCollider, or local setup required.

Write patterns in the [Strudel REPL](https://strudel.cc/), press play, and hear the results immediately.

```javascript
s("bd sd cp hh").bank("tr909")
```

Or stack synths, samples, and effects:

```javascript
stack(
  s("bd, [~ sd], hh*8"),
  note("c3 eb3 g3").s("sawtooth").lpf(800)
)
```

## Why Strudel?

- **Live code music** — compose and perform in real time with code
- **Algorithmic composition** — use Tidal's unique approach to pattern manipulation
- **Zero install** — runs entirely in the browser
- **Teaching** — low barrier to entry for learning music and code together
- **Integration** — connect via MIDI or OSC to use Strudel as a flexible sequencer

## Getting started

1. Open the [Strudel REPL](https://strudel.cc/)
2. Click the **Shuffle** icon in the top menu to browse example patterns
3. Edit a pattern and click **Refresh** to hear your changes
4. Follow the [interactive workshop](https://strudel.cc/workshop/getting-started/) to learn the basics

You don't need to know JavaScript or Tidal Cycles to get started — the workshop walks you through your first sounds step by step.

## Resources

| Resource | Link |
| --- | --- |
| Strudel REPL | [strudel.cc](https://strudel.cc/) |
| Getting started | [strudel.cc/learn/getting-started](https://strudel.cc/learn/getting-started/) |
| Workshop | [strudel.cc/workshop/getting-started](https://strudel.cc/workshop/getting-started/) |
| Technical manual | [strudel.cc/technical-manual](https://strudel.cc/technical-manual/) |
| Source code | [github.com/tidalcycles/strudel](https://github.com/tidalcycles/strudel) |
| Tidal Cycles | [tidalcycles.org](https://tidalcycles.org/) |

## About this repo

This repository collects Strudel patterns, experiments, and notes. The upstream project lives at [tidalcycles/strudel](https://github.com/tidalcycles/strudel) — this repo is for personal exploration and learning.

## License

Patterns and notes in this repository are shared freely. Strudel itself is open source; see the [official repository](https://github.com/tidalcycles/strudel) for license details.
