# Coding Focus Music (Python / TunePad Prototype)

> A creative-coding prototype that uses **music generated in code** to help young students regain focus during class. Built in **TunePad** and exported to GitHub for assessment.

---

## Table of Contents
- General Info
- Technologies / Environment
- Features
- Project Structure
- Setup
- Usage
- Linked Content
- Project Status
- Room for Improvement
- Acknowledgements
- Contact

---

## General Info
This project was developed across Weeks 7–12 to explore how **coded music** can support attention and calm in young learners (ages 5–10). The idea was to combine **creativity, education and technology** so teachers can play looping, predictable, research-informed music in class.

The repository contains:
- final TunePad-based songs (see `src/songs/`)
- exported / rewritten Python-style versions for reference
- reflection journal (see `docs/reflection.md`)
- space for earlier/alternate versions (see `versions/`)
- assets (screenshots from TunePad)

This follows the unit requirement: **“upload source code, assets, README, and make it publicly accessible.”**

---

## Technologies / Environment
- Python syntax via **TunePad** (Horn et al., 2020)
- TunePad musical functions: `playNote()`, `playSound()`, `rest()`, `with lowpass(...)`, `with pan(...)`, `with gain(...)`, `with transpose(...)`
- Runs best inside the **TunePad online environment**
- GitHub used as shared, public storage (per unit brief)

> ⚠️ Note: the code in `src/songs/*.py` uses TunePad-specific functions. These are **not** part of standard Python. To run/play the music, open the linked TunePad projects or re-import this code into TunePad.

---

## Features
- **Song 1 – Calm Focus Loop**  
  Soft drum groove, ambient keys, gentle bass, lowpass movement to keep it calm but not boring.
- **Song 2 – Focus Flow**  
  Kick–snare pattern, arpeggiated chords (D minor → G major → B minor → A major), dreamy pads, soft hats.
- **Song 3 – Mind Garden**  
  Marimba-style melody, bass pulse, slowly opening piano chords, stereo movement.

Additional features:
- Research-informed loops (Schellenberg, 2005; Roden, Kreutz & Bongard, 2012)
- Repetition with variation to maintain attention
- Code is **commented** so the marker can follow the musical structure

---

## Project Structure

```text
src/               → source code
src/main.py        → entry point / song selector
src/songs/         → 3 coded songs
docs/reflection.md → full reflection journal (Weeks 7–12)
versions/          → earlier TunePad tests / backups
assets/            → screenshots from TunePad
README.md          → this file
requirements.txt   → environment notes
