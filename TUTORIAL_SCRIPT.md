# Gaze Mouse Grid — Tutorial Video Script

**~3 minutes total**

1. Record the voiceover first (script below)
2. Screen record clips to match each section
3. Drop clips into iMovie over the voiceover

---

## Voiceover Script

Read this straight through into a mic. Each section has a CLIP note describing what footage to record and drop in later.

---

### Intro

Hey, I'm Adam Edison. I've been a member of the Talon beta community since 2020. This community has saved me a lot of pain in my hands, and I wanted to start giving back — so I built this plugin called Gaze Mouse Grid. I hope you find it as useful as I have.

I built it because I kept running into four problems.

---

### Existing grids are slow

First, existing mouse grids are just slow. There are too many steps to get where you want to go.

CLIP: open standard mouse grid, slowly narrow to an icon, close it

---

### Eye trackers lose accuracy on large monitors

Second, eye trackers lose accuracy on monitors bigger than 27 inches — especially in the corners.

CLIP: enable eye tracking, try to click a far corner, show the miss

---

### Eye tracking cursor is distracting

Third, the eye tracking cursor is really distracting. It jumps around while you're trying to read, and it triggers hover tooltips and all kinds of UI noise. See how much better that is when it's off?

CLIP: switch to BoardGameArena game, keep eye tracking on, try to read — cursor jumps and hover help fires everywhere — then turn it off and read peacefully

---

### Voice commands wear out your voice

And fourth, voice commands wear out your voice. I wanted a workflow that's completely voiceless.

---

### This plugin solves all four

Gaze Mouse Grid solves all four of these. It opens the grid right where you're looking. It's fast and accurate even on large screens. Eye tracking stays off until you actually need it. And the entire interaction uses parrot sounds — no voice required.

CLIP: `kuh` open, `tih` narrow, `clop` click — one quick demo

---

### Requirements

To use this, you'll need Talon with an eye tracker, the "Always on" eye tracking setting enabled, and a trained parrot model. All the details are in the README.

CLIP: open Talon dropdown, show "Always on" eye tracking setting

---

### Large screen corners

Let's start with one of the hardest things — targeting something in a far corner of the screen. The grid jumps to where I'm looking, that red cell shows where my eyes landed, and I can hit a corner target in under two seconds.

CLIP: look at a far corner, `kuh` open, pause to show grid and red hint cell, `tih` narrow, `clop` click — then repeat with a different corner

---

### Basic usage

Let me walk through the full workflow step by step. I'm clicking a small UI icon. First I look at the target and open the grid — it zooms into where I was looking and shows a screenshot as the grid overlay. The red cell shows where my gaze landed. Now I look at the right cell and narrow — it zooms in even further. I can see the exact icon I want. Now I click, and the grid closes with the mouse landing right on the target.

CLIP: look at a small target (sidebar icon, collapse arrow, gutter icon, tab close button), `kuh` open, pause, look at correct cell, `tih` narrow, pause, `clop` click

---

### Dismissing

If you open the grid and change your mind, just make the same sound again to close it. No click happens.

CLIP: `kuh` open, `kuh` close

---

### Hovering

You can also use it to hover. Narrow to your target, then dismiss instead of clicking. The cursor moves to where you were aiming, but it doesn't click. Great for tooltips.

CLIP: `kuh` open, `tih` narrow, `kuh` dismiss, show cursor on target and tooltip appearing

---

### Multiple narrows and re-centering

You can narrow as many times as you need — all the way down to the pixel level. Once you're at the deepest zoom, narrowing doesn't zoom in any further. Instead, it re-centers the view on your selection — same zoom level, it just pans over. Then you just click whenever you're ready.

CLIP: `kuh` open, `tih` four or five times until showing pixels, `tih` one more time to re-center, `clop` click

---

### Settings

Everything is customizable. You just change the values directly in the settings file. Grid size, initial zoom, settle delay, display ratio, colors, line width — it's all in there. Check the README for full details.

CLIP: open `gaze_mouse_grid_settings.talon` in Cursor, slowly scroll through the settings

---

### Closing

And that's Gaze Mouse Grid! The link to the plugin and install instructions are in the description below. I'm also a software developer and cofounder of a company called Ember and Tide. If you need custom software development — big or small — I'd love to chat. That link is down there too.

---

## Post-Production

- [ ] Record voiceover (read script above into mic)
- [ ] Screen record clips for each CLIP note (Cmd+Shift+5, no mic)
- [ ] Import everything into iMovie
- [ ] Drop clips over the voiceover, trim to fit
- [ ] Cross dissolve between clips
- [ ] Upload to YouTube — title: "Gaze Mouse Grid — Tutorial"
- [ ] Fix auto-captions: "Talon," "parrot," "kuh," "tih," "clop"
- [ ] Add GitHub repo URL to description
- [ ] Add Ember and Tide URL to description
- [ ] Publish
