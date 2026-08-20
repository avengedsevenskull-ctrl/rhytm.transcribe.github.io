# Cadence — Rhythm Transcription Tool

A fork of [imkevinkuo/rhythm](https://imkevinkuo.github.io/rhythm.html) — a web app that transcribes tapped rhythms into musical notation.

## What is this

Cadence listens to your spacebar taps and figures out the rhythm. Tap along to a song, it tells you whether you were hitting quarter notes, eighth notes, triplets, etc.

## Why this fork exists

This fork was vibe coded with AI (OpenCode / Claude) as an experiment to see what happens when you throw an LLM at someone else's small project and try to make quality-of-life improvements. No claims that it's better — just different.

### What's been changed so far

- **Musical notation rendering** — replaced text-based note labels with proper SMuFL music glyphs (Bravura font) so notes look like actual sheet music
- **Metronome sound** — swapped the harsh wood block tick for a softer metronome click
- **GitHub Pages** — deployed on a fork so it's accessible at a URL

### What hasn't been fixed

- Stems don't quite attach to noteheads properly yet (Bravura font metrics are tricky)
- Everything else is still the original code

## Original project

Created by [imkevinkuo](https://github.com/imkevinkuo). No license specified — all rights reserved by the original author.

## Running locally

Just open `rhythm.html` in a browser. It's a single-page app with no build step.
