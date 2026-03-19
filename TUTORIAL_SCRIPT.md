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

Hey, I'm Adam Edison. I've been a member of the Talon beta community since 2020. This community has saved me a lot of pain in my hands, and I wanted to start giving back — so I built this plugin called Gaze Mouse Grid. I hope you find it as useful as I have.

I built it because I kept running into four problems.

### Existing grids are slow

First, existing mouse grids are just slow. There are too many steps to get where you want to go. Let me show you what I mean.

DO
* open standard mouse grid, slowly narrow to an icon, close it

### Eye trackers lose accuracy on large monitors

Second, eye trackers lose accuracy on monitors bigger than 27 inches — especially in the corners. Watch what happens when I try to click something way over here.

DO
* enable eye tracking, try to click a far corner, show the miss

### Eye tracking cursor is distracting

Third, the eye tracking cursor is really distracting. It jumps around while you're trying to read, and it triggers hover tooltips and all kinds of UI noise. I'll switch over to a board game so you can really see this.

DO
* switch to BoardGameArena game
* keep eye tracking on, try to read — cursor jumps, hover help fires everywhere
* turn it off, read peacefully

See how much better that is when the cursor isn't bouncing around?

### Voice commands wear out your voice

And fourth, voice commands wear out your voice. I wanted a workflow that's completely voiceless.

### This plugin solves all four

Gaze Mouse Grid solves all four of these. It opens the grid right where you're looking. It's fast and accurate even on large screens. Eye tracking stays off until you actually need it. And the entire interaction uses parrot sounds — no voice required.

Let me show you what that looks like. I'll open the grid, narrow in, and click.

DO
* `kuh` open, `tih` narrow, `clop` click

### Requirements

To use this, you'll need Talon with an eye tracker, the "Always on" eye tracking setting enabled, and a trained parrot model. Let me show you where that setting is.

DO
* show Talon dropdown with "Always on" setting

All the details are in the README.

---

## Segment 2: Large Screen Corners (~30s)

### Explain

Let's start with one of the hardest things — targeting something in a far corner of the screen. I'll look over at the corner, open the grid, narrow once, and click. Watch how fast this is.

### Demo

DO
* look at a far corner
* `kuh` — grid opens
* pause — let viewer see grid and red hint cell
* `tih` narrow
* `clop` click

That red cell showed where my eyes landed, and I hit the corner target in under two seconds. Let me do it one more time with a different corner.

### Demo again

DO
* look at a different corner
* `kuh` — grid opens
* `tih` narrow
* `clop` click

---

## Segment 3: Basic Usage (~50s)

### Explain

Let me walk through the full workflow step by step. I'm going to click a small UI icon. First I'll look at the target and open the grid — it'll zoom into where I was looking and show a screenshot as the grid overlay. Then I'll look at the right cell and narrow to zoom in further. Then I'll click, and the grid will close with the mouse landing right on the target.

### Demo

DO
* pick a small target — sidebar icon, collapse arrow, gutter icon, tab close button
* look at target
* `kuh` — grid opens
* pause — let viewer see
* look at correct cell
* `tih` — narrows
* pause — let viewer see
* `clop` — click

---

## Segment 4: More Workflows (~60s)

There's more you can do beyond a basic click.

### Explain dismissing

If you open the grid and change your mind, just make the same sound again to close it. No click happens.

### Demo dismissing

DO
* `kuh` open
* `kuh` close

### Explain hovering

You can also use it to hover. Narrow to your target, then dismiss instead of clicking. The cursor moves to where you were aiming, but it doesn't click. Great for tooltips.

### Demo hovering

DO
* `kuh` open
* `tih` narrow
* `kuh` dismiss
* show cursor on target, tooltip appears

### Explain multiple narrows and re-centering

You can also narrow as many times as you need — all the way down to the pixel level. And once you're at the deepest zoom, narrowing doesn't zoom in any further. Instead, it re-centers the view on your selection — same zoom level, it just pans over. Then you just click whenever you're ready.

### Demo multiple narrows

DO
* `kuh` open
* `tih` four or five times until showing pixels
* `tih` one more time — re-centers
* `clop` click

### Wrap up

And that's Gaze Mouse Grid!

The link to the plugin and install instructions are in the description below. I'm also a software developer and cofounder of a company called Ember and Tide. If you need custom software development — big or small — I'd love to chat. That link is down there too.

---

## Segment 5: Settings (~40s)

### Open the settings file

Everything in Gaze Mouse Grid is customizable.

DO
* open `gaze_mouse_grid_settings.talon` in Cursor

You just change the values directly in this file. Grid size controls how many cells — the default is 6 by 6, lower it for bigger cells. Initial narrow factor controls the first zoom — 2 is half the screen, 3 is a third. Settle delay is how long it waits for your eye tracker — bump it up if the grid opens in the wrong spot. Display ratio controls how big the overlay is — 0.5 is half your screen. And you can change the line color, hint color, and line width too.

Check the README for full details on all of these.

**Stop recording.**

---

## Post-Production

- [ ] Import into iMovie, cut dead air and mistakes, cross dissolve at joins
- [ ] Upload to YouTube — title: "Gaze Mouse Grid — Tutorial"
- [ ] Fix auto-captions: "Talon," "parrot," "kuh," "tih," "clop"
- [ ] Add GitHub repo URL to description
- [ ] Add Ember and Tide URL to description
- [ ] Publish
