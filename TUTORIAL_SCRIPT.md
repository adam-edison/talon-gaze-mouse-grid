# Gaze Mouse Grid — Tutorial Video Script

**~3 minutes total**

Two-pass recording:
1. Screen record the demos silently (no mic)
2. Edit in iMovie, then record voiceover using the microphone button

---

## Pass 1: Screen Recording (no mic)

Cmd+Shift+5, Record Entire Screen. No mic needed — just do the demos.

### Shot 1: Slow mouse grid

* open standard mouse grid, slowly narrow to an icon, close it

### Shot 2: Eye tracker misses corner

* enable eye tracking, try to click a far corner, show the miss

### Shot 3: Eye tracking cursor is distracting

* switch to BoardGameArena game
* keep eye tracking on, try to read — cursor jumps, hover help fires everywhere
* turn it off, read peacefully

### Shot 4: Quick demo of the solution

* `kuh` open, `tih` narrow, `clop` click

### Shot 5: Show the "Always on" setting

* open Talon dropdown, show "Always on" eye tracking setting

### Shot 6: Corner target

* look at a far corner
* `kuh` — grid opens
* pause — let viewer see grid and red hint cell
* `tih` narrow
* `clop` click

### Shot 7: Different corner

* look at a different corner
* `kuh` — grid opens
* `tih` narrow
* `clop` click

### Shot 8: Basic usage — open

* look at a small UI icon (sidebar icon, collapse arrow, gutter icon, tab close button)
* `kuh` — grid opens
* pause — let viewer see the overlay and red hint cell

### Shot 9: Basic usage — narrow

* look at correct cell
* `tih` — narrows
* pause — let viewer see the zoomed view

### Shot 10: Basic usage — click

* `clop` — click

### Shot 11: Dismissing

* `kuh` open
* `kuh` close

### Shot 12: Hovering

* `kuh` open
* `tih` narrow
* `kuh` dismiss
* show cursor on target, tooltip appears

### Shot 13: Multiple narrows and re-centering

* `kuh` open
* `tih` four or five times until showing pixels
* `tih` one more time — re-centers
* `clop` click

### Shot 14: Settings file

* open `gaze_mouse_grid_settings.talon` in Cursor
* slowly scroll through the settings

**Stop recording.**

---

## Pass 2: Voiceover Script

Import into iMovie, cut and arrange the shots, then use the microphone button to record voiceover while watching playback.

### Over Shot 1

Hey, I'm Adam Edison. I've been a member of the Talon beta community since 2020. This community has saved me a lot of pain in my hands, and I wanted to start giving back — so I built this plugin called Gaze Mouse Grid. I hope you find it as useful as I have.

I built it because I kept running into four problems. First, existing mouse grids are just slow. There are too many steps to get where you want to go.

### Over Shot 2

Second, eye trackers lose accuracy on monitors bigger than 27 inches — especially in the corners.

### Over Shot 3

Third, the eye tracking cursor is really distracting. It jumps around while you're trying to read, and it triggers hover tooltips and all kinds of UI noise. See how much better that is when the cursor isn't bouncing around?

### Over Shot 4

And fourth, voice commands wear out your voice. I wanted a workflow that's completely voiceless.

Gaze Mouse Grid solves all four of these. It opens the grid right where you're looking. It's fast and accurate even on large screens. Eye tracking stays off until you actually need it. And the entire interaction uses parrot sounds — no voice required.

### Over Shot 5

To use this, you'll need Talon with an eye tracker, the "Always on" eye tracking setting enabled, and a trained parrot model. All the details are in the README.

### Over Shots 6–7

Let's start with one of the hardest things — targeting something in a far corner of the screen. The grid jumped to where I was looking, that red cell shows where my eyes landed, and I hit the corner target in under two seconds.

### Over Shots 8–10

Let me walk through the full workflow step by step. I'm clicking a small UI icon. First I look at the target and open the grid — it zooms into where I was looking and shows a screenshot as the grid overlay. The red cell shows where my gaze landed. Now I look at the right cell and narrow — it zooms in even further. I can see the exact icon I want. Now I click, and the grid closes with the mouse landing right on the target.

### Over Shot 11

If you open the grid and change your mind, just make the same sound again to close it. No click happens.

### Over Shot 12

You can also use it to hover. Narrow to your target, then dismiss instead of clicking. The cursor moves to where you were aiming, but it doesn't click. Great for tooltips.

### Over Shot 13

You can narrow as many times as you need — all the way down to the pixel level. Once you're at the deepest zoom, narrowing doesn't zoom in any further. Instead, it re-centers the view on your selection — same zoom level, it just pans over. Then you just click whenever you're ready.

### Over Shot 14

Everything is customizable. You just change the values directly in this settings file. Grid size, initial zoom, settle delay, display ratio, colors, line width — it's all in there. Check the README for full details.

### Closing (over any shot or title card)

And that's Gaze Mouse Grid! The link to the plugin and install instructions are in the description below. I'm also a software developer and cofounder of a company called Ember and Tide. If you need custom software development — big or small — I'd love to chat. That link is down there too.

---

## Post-Production

- [ ] Import screen recording into iMovie
- [ ] Cut dead air and mistakes, cross dissolve at joins
- [ ] Record voiceover using iMovie mic button (Pass 2 above)
- [ ] Upload to YouTube — title: "Gaze Mouse Grid — Tutorial"
- [ ] Fix auto-captions: "Talon," "parrot," "kuh," "tih," "clop"
- [ ] Add GitHub repo URL to description
- [ ] Add Ember and Tide URL to description
- [ ] Publish
