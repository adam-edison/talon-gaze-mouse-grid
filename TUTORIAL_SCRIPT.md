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

SAY `drowse`

### Eye trackers lose accuracy on large monitors

Second, eye trackers lose accuracy on monitors bigger than 27 inches — especially in the corners. Watch what happens when I try to click something way over here.

DO
* enable eye tracking, try to click a far corner, show the miss

SAY `drowse`

### Eye tracking cursor is distracting

Third, the eye tracking cursor is really distracting. It jumps around while you're trying to read, and it triggers hover tooltips and all kinds of UI noise. I'll switch over to a board game so you can really see this.

DO
* switch to BoardGameArena game
* keep eye tracking on, try to read — cursor jumps, hover help fires everywhere
* turn it off, read peacefully

SAY `drowse`

See how much better that is when the cursor isn't bouncing around?

### Voice commands wear out your voice

And fourth, voice commands wear out your voice. I wanted a workflow that's completely voiceless.

### This plugin solves all four

Gaze Mouse Grid solves all four of these. It opens the grid right where you're looking. It's fast and accurate even on large screens. Eye tracking stays off until you actually need it. And the entire interaction uses parrot sounds — no voice required.

Let me show you what that looks like. I'll open the grid, narrow in, and click.

DO
* `kuh` open, `tih` narrow, `clop` click

SAY `drowse`

### Requirements

To use this, you'll need Talon with an eye tracker, the "Always on" eye tracking setting enabled, and a trained parrot model. Let me show you where that setting is.

DO
* show Talon dropdown with "Always on" setting

SAY `drowse`

All the details are in the README.

---

## Segment 2: Large Screen Corners (~30s)

### Explain

Let's start with one of the hardest things — targeting something in a far corner of the screen. I'm going to look at that corner over there, open the grid, narrow once, and click. Watch how fast this is.

### Demo

DO
* look at a far corner
* `kuh` — grid opens
* pause — let viewer see grid and red hint cell
* `tih` narrow
* `clop` click

SAY `drowse`

That red cell showed where my eyes landed, and I hit the corner target in under two seconds. Let me do it one more time — I'll look at a different corner this time.

### Demo again

DO
* look at a different corner
* `kuh` — grid opens
* `tih` narrow
* `clop` click

SAY `drowse`

---

## Segment 3: Basic Usage (~50s)

### Explain

Let me walk through the full workflow step by step. I'm going to click that small icon right there. First I'll look at it and open the grid.

### Open the grid

DO
* look at target
* `kuh` — grid opens

SAY `drowse`

It zoomed right into where I was looking. You can see the screenshot underneath the grid overlay, and the red cell shows where my gaze landed. Now I'll look at the cell with my target in it and narrow.

### Narrow

DO
* look at correct cell
* `tih` — narrows

SAY `drowse`

It zoomed in even further. I can see the exact icon I want. Now I'll click, and the grid will close with the mouse landing right on the target.

### Click

DO
* `clop` — click

SAY `drowse`

There it is — landed right on it.

---

## Segment 4: More Workflows (~60s)

There's more you can do beyond a basic click.

### Explain dismissing

If you open the grid and change your mind, just make the same sound again to close it. No click happens. I'll open the grid and then immediately close it.

### Demo dismissing

DO
* `kuh` open
* `kuh` close

SAY `drowse`

### Explain hovering

You can also use it to hover. I'll narrow to a target, then dismiss instead of clicking. The cursor will move to where I was aiming, but it won't click — great for triggering tooltips.

### Demo hovering

DO
* `kuh` open
* `tih` narrow
* `kuh` dismiss
* show cursor on target, tooltip appears

SAY `drowse`

### Explain multiple narrows and re-centering

You can also narrow as many times as you need — all the way down to the pixel level. I'll open the grid and narrow a bunch of times so you can see it zoom all the way in. Once I'm at the deepest zoom, narrowing doesn't zoom in any further — instead it re-centers the view on my selection. Same zoom level, it just pans over. Then I'll click whenever I'm ready.

### Demo multiple narrows

DO
* `kuh` open
* `tih` four or five times until showing pixels
* `tih` one more time — re-centers
* `clop` click

SAY `drowse`

### Wrap up

And that's Gaze Mouse Grid!

The link to the plugin and install instructions are in the description below. I'm also a software developer and cofounder of a company called Ember and Tide. If you need custom software development — big or small — I'd love to chat. That link is down there too.

---

## Segment 5: Settings (~40s)

### Open the settings file

Everything in Gaze Mouse Grid is customizable.

DO
* open `gaze_mouse_grid_settings.talon` in Cursor

SAY `drowse`

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
