# Orbites

A rhythm game in space. Your planet circles its star on three orbits, one lap every two bars. Jump orbits right on the beat to catch shooting stars and dodge comets. Play the 1200 tracks from the Rythme plugin, or your own music.

*Version française : [README.md](README.md)*

## How to play

- **↑ or J/K**: jump to the outer orbit · **↓ or F/D**: to the inner orbit. A **click** works too: top of the screen for outwards, bottom for inwards.
- On every note, a **shooting star** waits on the next orbit, with an arrow showing which way to jump; jump when its **circle closes**.
- A **comet** comes along your orbit: staying, or jumping the wrong way, means hitting it (the note is missed).
- A **golden trail** follows the star: hold the key until its end, or the combo breaks.
- **Gamepad**: d-pad up or down, Y/B outwards, A/X inwards.

## Accuracy and points

Notes are judged by how far they are from the right moment: **Perfect** (about ±45 ms), **Good** (±90 ms), **OK** (±140 ms), otherwise a miss.

A note's points rise by 1 % per note of combo, up to double at 100 notes in a row; a miss resets the combo. At the end, accuracy gives a grade: **S** from 95 %, **A** at 90 %, **B** at 80 %, **C** at 70 %, **D** below.

## Songs and difficulty

The **Songs** tab has the 1200 Rythme tracks, in four difficulties (Easy, Normal, Hard, Expert). Each level's difficulty is computed from its notes (density, busy passages), from 1 to 10 stars.

## My music

In **My music**, create a level from an imported **audio file** or a track from your **NeoMusic** library: the game finds its tempo and strong beats and turns them into a level, at the chosen **difficulty** (1 to 10 stars).

## Settings

- Music **volume**.
- **Hit sound**: the sound played on each note you hit, one of 10 (Soft, Clap, Wood, Kick, Crystal, Pop, Hi-hat, Snare, Pluck, Tock) or none. Losing a combo of 10 or more plays a « combo break » sound.
- **Offset** (−300 to +300 ms): it adjusts itself after each game based on your average lateness or earliness; you can also change it by hand.

## Data and sync

Your scores and grades per level and your settings are stored by NeoDex, backed up and synced between your PCs when sync is on.

## Install

In NeoDex: **NeoStore → Discover → Orbites → Install**.

Building a plugin: see the [NeoDex SDK](https://github.com/NDesumeur/neodex-sdk).
