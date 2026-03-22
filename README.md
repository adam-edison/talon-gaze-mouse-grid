# Gaze Mouse Grid

A gaze-based mouse targeting tool for [Talon](https://talonvoice.com/) that uses eye tracking and parrot sounds to quickly navigate and click anywhere on screen.

Built by [Ember & Tide](https://emberandtide.org/).
For your custom software development needs - big or small, [get in touch](https://emberandtide.org/contact).

## Why I built this

1. **Existing mouse grids are slow** — too many steps to narrow down to a target
2. **Eye trackers lose accuracy on large monitors** — especially in the corners on screens bigger than 27"
3. **The eye tracking cursor is distracting** — it jumps around while you're trying to read, triggering hover tooltips and other UI noise
4. **Voice commands wear out your voice** — I wanted a fully voiceless workflow using only parrot sounds

Gaze Mouse Grid solves all four: it starts the grid where you're already looking, reaches any corner fast, keeps eye tracking off until you need it, and the entire interaction is parrot sounds.

## Installation

```
cd ~/.talon/user
git clone https://github.com/developer-funky-goblin/talon-gaze-mouse-grid.git
```

## Requirements

- [Talon](https://talonvoice.com/) beta (requires a [subscription](https://www.patreon.com/lunixbochs) — needed for parrot sound integration)
- An eye tracker (e.g., [Tobii Eye Tracker 5](https://gaming.tobii.com/product/eye-tracker-5/))
- Eye tracking **"Always on"** must be enabled in Talon's eye tracking preferences (the grid needs continuous gaze data even when eye tracking mouse control is off)
- A parrot model with at least 3 sounds — train one with [parrot.py](https://github.com/chaosparrot/parrot.py) (defaults use `kuh`, `tih`, and `clop` but all sounds are customizable)

## How it works

1. Say **"gaze grid"** (or make the `kuh` sound) — the grid reads your gaze position, narrows to that region, takes a screenshot, and displays it as a zoomed-in grid overlay
2. Look at the cell containing your target, then make the `**tih`** sound — the grid narrows further into that cell and re-captures the screenshot
3. Repeat step 2 until your target is easy to hit
4. Make the `**clop**` sound — the grid closes, moves the mouse to the corresponding real-screen position, and clicks

You can close the grid without clicking by saying **"gaze grid close"** or making the `kuh` sound again.

## Command reference

### Voice commands (always available)

- **gaze grid** — open the grid
- **gaze grid close** — close the grid without clicking

### Parrot sounds (always available)

- **kuh** — toggle grid open/closed

### Parrot sounds (while grid is open)

- **tih** — narrow into the cell under your cursor
- **clop** — click at the target location and close the grid

## Configuration

All settings have sensible defaults. Override any setting by creating a `.talon` file with a `settings():` block. See `gaze_mouse_grid_settings.talon` for the full list with explanations.

### Customizing sounds

To use different parrot sounds, edit the `.talon` files and replace the sound names. For example, to use `pop` instead of `kuh` for toggling:

```talon
# in gaze_mouse_grid.talon
parrot(pop): user.gaze_grid_toggle()
```

Any sound your parrot model recognizes can be used.

## Known limitations

- **Talon menu dropdown** — the grid cannot reliably target items inside the Talon menu bar dropdown.

## Troubleshooting

- **Grid opens but cursor isn't near your target**
  - Increase `user.gaze_grid_settle_delay` (e.g., `"400ms"`) to give your eye tracker more time to update
- **Grid cells are too small/large**
  - Adjust `user.gaze_grid_size` — lower = fewer, larger cells; higher = more, smaller cells
- **Grid overlay is too small/large on screen**
  - Adjust `user.gaze_grid_display_ratio` — 0.3 = 30% of screen, 0.7 = 70%
- **Initial zoom is too tight/loose**
  - Adjust `user.gaze_grid_initial_narrow_factor` — 1 = no initial zoom, 3 = one-third of screen
- **Target disappears after narrowing**
  - Increase `user.gaze_grid_narrow_padding` — default is 1 (3x3 cell region), higher values show more surrounding cells per narrow

