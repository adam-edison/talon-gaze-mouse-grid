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

Hey, I'm Adam Edison. I've been in the Talon beta community since 2020. Talon has saved me a lot of pain in my hands, and I wanted to give back — so I built this plugin called Gaze Mouse Grid.

I built it because I kept running into four problems.

### Why I built this

First, existing mouse grids are slow. You say a number, wait for the grid to redraw, say another number, wait again. Every step has speech recognition delay on top of the redraw delay, and it adds up fast. If you're trying to hit a small target, you might need five or six rounds of that. And if you're using a grid as your primary mouse replacement, try doing that for twenty minutes — your voice is going to start getting tired.

CLIP: open standard mouse grid, slowly narrow to an icon, close it

Second, eye trackers lose accuracy on large monitors. Once you get past about 27 inches, the tracking starts to drift — especially in the corners. You look at a button, the tracker thinks you're an inch away, and you miss. It makes eye tracking unreliable for precise targeting on bigger screens.

CLIP: enable eye tracking, try to click a far corner, show the miss

Third, if you leave eye tracking on, the cursor follows your eyes everywhere. You're trying to read something and the cursor is jumping around the page, triggering hover tooltips, opening dropdown previews, highlighting menu items you didn't ask for. It's constant visual noise. You basically can't read with it on.

CLIP: switch to BoardGameArena game, keep eye tracking on, try to read — cursor jumps and hover help fires everywhere — then turn it off and read peacefully

And fourth, voice commands wear out your voice. If you're using Talon as your primary input all day, your voice is doing a lot of work. I wanted a mouse workflow that doesn't use voice at all.

Gaze Mouse Grid solves all four. It opens the grid where you're already looking, so you skip most of the narrowing steps. It's accurate on large screens because it reads your gaze position directly. Eye tracking stays off until you invoke the grid. And the whole interaction is parrot sounds — three quick sounds and the click happens.

CLIP: `kuh` open, `tih` narrow, `clop` click — one quick demo

### Requirements

You need a Talon beta subscription. That's what gives you parrot sound support, which the whole plugin is built on.

You need an eye tracker. I use the Tobii Eye Tracker 5, but anything Talon supports works.

In Talon's eye tracking preferences, set tracking to "Always on." The grid reads your gaze position when it opens, so it needs continuous gaze data even when eye tracking mouse control is off.

And you need a trained parrot model. I use three sounds — `kuh`, `tih`, and `clop` — but you can configure any sounds your model recognizes. The README links to parrot.py for training.

CLIP: open Talon dropdown, show "Always on" eye tracking setting

### How it works

Let me walk through the workflow.

I'm going to click a small UI icon. I look at the target and open the grid. It reads my gaze position, zooms into that region, takes a screenshot, and displays it as a grid overlay. The red cell shows where my eyes landed so I can orient myself.

I look at the cell containing my target and narrow. It zooms in further and I can see the exact icon. I make the click sound — the grid closes, moves the mouse to the corresponding screen position, and clicks.

And you don't have to be precise with the narrow step. The cell you pick becomes roughly the center of the next zoomed-in view, so if you're off by a cell or two it doesn't matter — your target will still be in frame.

CLIP: look at a small target (sidebar icon, collapse arrow, gutter icon, tab close button), `kuh` open, pause, look at correct cell, `tih` narrow, pause, `clop` click

If the target is big enough, you don't even need to narrow. You just open the grid and click immediately — two sounds, that's it. A standard mouse grid would still have you saying numbers and waiting for redraws. This is where the speed difference is most obvious.

CLIP: `kuh` open on a large target (big button, tab, menu item), `clop` click immediately — no narrow step

Here's a harder case — hitting a target in a far corner of the screen, where eye tracking is least accurate. The grid opens where I'm looking, I narrow once, click. Under two seconds.

CLIP: look at a far corner, `kuh` open, pause to show grid and red hint cell, `tih` narrow, `clop` click — then repeat with a different corner

You can narrow as many times as you need, all the way down to individual pixels. Once you hit the deepest zoom level, narrowing again re-centers the view on your current gaze position instead of zooming further. Same zoom, it just pans. Useful for fine-tuning your position before clicking.

CLIP: `kuh` open, `tih` four or five times until showing pixels, `tih` one more time to re-center, `clop` click

If you open the grid and change your mind, make the open sound again to dismiss it. No click.

CLIP: `kuh` open, `kuh` close

You can also use it for hovering. Narrow to your target, then dismiss instead of clicking. The cursor moves there but doesn't click. Useful for tooltips or anything where you need the cursor positioned without a click event.

CLIP: `kuh` open, `tih` narrow, `kuh` dismiss, show cursor on target and tooltip appearing

### Configuration

Everything is configurable through a settings file. Grid size, initial zoom level, gaze settle delay, display ratio, colors, line widths. Change a value and the grid picks it up. The README has the full list with explanations.

CLIP: open `gaze_mouse_grid_settings.talon` in Cursor, slowly scroll through the settings

### Closing

That's Gaze Mouse Grid. The plugin link and install instructions are in the description. I'm also a software developer and cofounder of Ember and Tide — if you need custom software development, big or small, there's a link for that below too.

---

## Post-Production

- Record voiceover (read script above into mic)
- Screen record clips for each CLIP note (Cmd+Shift+5, no mic)
- Import everything into iMovie
- Drop clips over the voiceover, trim to fit
- Cross dissolve between clips
- Upload to YouTube — title: "Gaze Mouse Grid — Tutorial"
- Fix auto-captions: "Talon," "parrot," "kuh," "tih," "clop"
- Add GitHub repo URL to description
- Add Ember and Tide URL to description
- Publish
