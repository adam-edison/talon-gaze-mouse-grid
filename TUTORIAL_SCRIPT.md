# Gaze Mouse Grid — Tutorial Video Script

**~3 minutes total**
Cmd+Shift+5 with mic on. Single recording, edit in iMovie.

---

## Setup

- [ ] Cursor IDE fullscreen, `gaze_mouse_grid.py` open
- [ ] Cmd+Shift+5 > Options > select mic
- [ ] Record Entire Screen
- [ ] This script on second screen

---

## Segment 1: Why I Built This (~50s)

### Intro

SAY
* hey, I'm Adam Edison
* I'm a software developer and cofounder of Ember and Tide
* I've been a member of the Talon beta community since 2020
* this community has saved me a lot of pain in my hands
* I wanted to start giving back, so I created this plugin
* I hope you find it as useful as I have

### Four problems this solves

SAY
* built this for four reasons

### Existing grids are slow

SAY
* existing mouse grids are slow, too many steps

DO
* open standard mouse grid, slowly narrow to an icon, close it

### Eye trackers lose accuracy on large monitors

SAY
* eye trackers lose accuracy on monitors bigger than 27"
* especially in the corners

DO
* enable eye tracking, try to click a far corner, show the miss

### Eye tracking cursor is distracting

SAY
* eye tracking cursor is distracting
* jumps around while I'm trying to read

DO
* switch to BoardGameArena game
* keep eye tracking on, try to read — cursor jumps, hover help fires everywhere
* turn it off, read peacefully — hover help only when you want it

### Voice commands wear out your voice

SAY
* voice commands wear out my voice
* want a voiceless workflow

### This plugin solves all four

SAY
* this plugin solves all four
* starts grid where you're looking
* fast and accurate on large screens
* eye tracking stays off until you need it
* entire interaction is parrot sounds

DO
* `kuh` open, `tih` narrow, `clop` click

### Requirements

SAY
* need Talon, eye tracker with "Always on", trained parrot model
* check the README

DO
* show Talon dropdown with "Always on" setting

---

## Segment 2: Large Screen Corners (~30s)

### Set up the demo

SAY
* targeting something in a far corner

### Open grid in a corner

DO
* look at a far corner
* `kuh` — grid opens

SAY
* grid jumped to where I was looking
* red cell shows where it thinks my eyes landed

DO
* pause — let viewer see grid and red hint cell

### Click the corner target

SAY
* one narrow, one click
* corner target in under two seconds

DO
* `tih` narrow
* `clop` click
* repeat for a different corner

---

## Segment 3: Basic Usage (~50s)

### Pick a target

SAY
* full workflow step by step
* clicking a small UI icon

DO
* pick a small target
* sidebar icon, collapse arrow, gutter icon, tab close button

### Open the grid

SAY
* open the grid

DO
* look at target
* `kuh` — grid opens

SAY
* zoomed into where I was looking
* screenshot as grid overlay
* red cell shows where gaze landed

DO
* pause — let viewer see

### Narrow

SAY
* narrow

DO
* look at correct cell
* `tih` — narrows

SAY
* zoomed in further
* can see the exact icon

DO
* pause — let viewer see

### Click

SAY
* click, grid closes, lands on target

DO
* `clop` — click

---

## Segment 4: More Workflows (~60s)

SAY
* more you can do beyond basic click

### Dismissing

SAY
* dismissing
* same sound closes it, no click

DO
* `kuh` open
* `kuh` close

### Hovering

SAY
* hovering
* narrow to target, dismiss instead of click
* cursor moves but doesn't click

DO
* `kuh` open
* `tih` narrow
* `kuh` dismiss
* show cursor on target, tooltip appears

### Multiple narrows

SAY
* multiple narrows
* zoom as many times as needed
* all the way to pixel level

DO
* `kuh` open
* `tih` four or five times until showing pixels

### Re-centering at pixel level

SAY
* at deepest zoom, narrowing re-centers the view
* same zoom level, just pans to your selection

DO
* `tih` one more time — re-centers

### Click when ready

SAY
* click when ready

DO
* `clop` click

### Wrap up

SAY
* that's Gaze Mouse Grid

---

## Segment 5: Settings (~40s)

### Open the settings file

SAY
* everything is customizable

DO
* open `gaze_mouse_grid_settings.talon` in Cursor

SAY
* just change the values directly in this file

### Grid size

SAY
* grid size — how many cells
* default is 6, so 6 by 6
* lower it for bigger cells, easier to target

### Initial narrow factor

SAY
* initial narrow factor — how much it zooms on first open
* 2 is half the screen, 3 is a third

### Settle delay

SAY
* settle delay — how long it waits for the eye tracker
* increase this if the grid opens in the wrong spot

### Display ratio

SAY
* display ratio — how big the overlay is on screen
* 0.5 is half, bump it up if you want a bigger view

### Colors and line width

SAY
* line color, hint color — RRGGBBAA hex
* line width — pixels

### Closing

SAY
* check the README for full details

**Stop recording.**

---

## Post-Production

- [ ] Import into iMovie, cut dead air and mistakes, cross dissolve at joins
- [ ] Upload to YouTube — title: "Gaze Mouse Grid — Tutorial"
- [ ] Fix auto-captions: "Talon," "parrot," "kuh," "tih," "clop"
- [ ] Add GitHub repo URL to description
- [ ] Publish
