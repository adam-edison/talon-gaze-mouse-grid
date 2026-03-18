# Gaze Mouse Grid — Tutorial Video Script

**~3 minutes total**
Cmd+Shift+5 with mic on. One take per segment.

---

## Setup

- [ ] Cursor IDE fullscreen, `gaze_mouse_grid.py` open
- [ ] Cmd+Shift+5 > Options > select mic
- [ ] Record Entire Screen
- [ ] This script on second screen

---

## Segment 1: Why I Built This (~50s)

SAY: built this for four reasons

SAY: existing mouse grids are slow, too many steps
DO: open standard mouse grid, slowly narrow to an icon, close it

SAY: eye trackers lose accuracy on monitors bigger than 27"
SAY: especially in the corners
DO: enable eye tracking, try to click a far corner, show the miss

SAY: eye tracking cursor is distracting
SAY: jumps around while I'm trying to read
DO: keep eye tracking on, read code, let cursor jump around
DO: turn it off, read peacefully

SAY: voice commands wear out my voice
SAY: want a voiceless workflow

SAY: this plugin solves all four
SAY: starts grid where you're looking
SAY: fast and accurate on large screens
SAY: eye tracking stays off until you need it
SAY: entire interaction is parrot sounds
DO: `kuh` open, `tih` narrow, `clop` click

SAY: need Talon, eye tracker with "Always on", trained parrot model
SAY: check the README
DO: show Talon dropdown with "Always on" setting

**Stop recording.**

---

## Segment 2: Large Screen Corners (~30s)

SAY: targeting something in a far corner

DO: look at a far corner
DO: `kuh` — grid opens

SAY: grid jumped to where I was looking
SAY: red cell shows where it thinks my eyes landed

DO: pause — let viewer see grid and red hint cell

SAY: one narrow, one click
SAY: corner target in under two seconds

DO: `tih` narrow
DO: `clop` click

DO: repeat for a different corner

**Stop recording.**

---

## Segment 3: Basic Usage (~50s)

SAY: full workflow step by step
SAY: clicking a small UI icon

DO: pick a small target
DO: sidebar icon, collapse arrow, gutter icon, tab close button

SAY: open the grid

DO: look at target
DO: `kuh` — grid opens

SAY: zoomed into where I was looking
SAY: screenshot as grid overlay
SAY: red cell shows where gaze landed

DO: pause — let viewer see

SAY: narrow

DO: look at correct cell
DO: `tih` — narrows

SAY: zoomed in further
SAY: can see the exact icon

DO: pause — let viewer see

SAY: click, grid closes, lands on target

DO: `clop` — click

**Stop recording.**

---

## Segment 4: More Workflows (~60s)

SAY: more you can do beyond basic click

SAY: dismissing
SAY: same sound closes it, no click

DO: `kuh` open
DO: `kuh` close

SAY: hovering
SAY: narrow to target, dismiss instead of click
SAY: cursor moves but doesn't click

DO: `kuh` open
DO: `tih` narrow
DO: `kuh` dismiss
DO: show cursor on target, tooltip appears

SAY: multiple narrows
SAY: zoom as many times as needed
SAY: all the way to pixel level

DO: `kuh` open
DO: `tih` four or five times until showing pixels

SAY: at deepest zoom, narrowing re-centers the view
SAY: same zoom level, just pans to your selection

DO: `tih` one more time — re-centers

SAY: click when ready

DO: `clop` click

SAY: that's Gaze Mouse Grid

**Stop recording.**

---

## Segment 5: Settings (~40s)

SAY: everything is customizable

DO: open `gaze_mouse_grid_settings.talon` in Cursor

SAY: just change the values directly in this file

SAY: grid size — how many cells
SAY: default is 6, so 6 by 6
SAY: lower it for bigger cells, easier to target

SAY: initial narrow factor — how much it zooms on first open
SAY: 2 is half the screen, 3 is a third

SAY: settle delay — how long it waits for the eye tracker
SAY: increase this if the grid opens in the wrong spot

SAY: display ratio — how big the overlay is on screen
SAY: 0.5 is half, bump it up if you want a bigger view

SAY: line color, hint color — RRGGBBAA hex
SAY: line width — pixels

SAY: check the README for full details

**Stop recording.**

---

## Post-Production

- [ ] Trim each recording (QuickTime: Edit > Trim)
- [ ] Upload to YouTube
- [ ] Titles:
  - "Gaze Mouse Grid — Why I Built This"
  - "Gaze Mouse Grid — Large Screen Corners"
  - "Gaze Mouse Grid — Basic Usage"
  - "Gaze Mouse Grid — Dismiss, Hover, & Multiple Narrows"
  - "Gaze Mouse Grid — Settings"
- [ ] Create playlist, all 5 in order
- [ ] Fix auto-captions: "Talon," "parrot," "kuh," "tih," "clop"
- [ ] Add GitHub repo URL to each description
- [ ] Publish
