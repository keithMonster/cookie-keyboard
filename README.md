# Cookie's Arcade

A toddler-friendly mini-game collection for a 1-year-old who loves smashing the keyboard. Single-file HTML per game, zero dependencies, zero network.

## Live

https://keithmonster.github.io/cookie-arcade/

## Games

| # | Name | Input | What it does |
|---|---|---|---|
| 1 | **Keyboard Smash** | Keyboard | Each keypress spawns a colored shape (drift / spin / fall) + piano note + particle burst. Space = full-screen firework. 1% rare oversized shape. |
| 2 | **Pop Bubbles** | Mouse / touch | Colorful soap bubbles drift up the screen. Move the cursor over a bubble to pop it with a satisfying "blip". |
| 3 | **Drum Pad** | Keyboard | Top row = drums, middle row = cymbals, bottom row = chimes (pentatonic bells). Each key plays its synth voice and spawns a matching visual. |
| 4 | **Color Cascade** | Keyboard | Each key fades the entire screen to a new color over ~1s, with a soft sustained note. Calming / hypnotic. |

## Navigation

- Click / tap a tile, press `1` / `2` / `3` / `4` for an exact game, or any other key for a random game
- Inside a game: `Esc` (twice if in fullscreen — first exits fullscreen) or tap the top-right corner returns to home
- `F` toggles fullscreen
- `Cmd+Q` quits the browser

## On iPad

Open the live URL in Safari → tap **Share → Add to Home Screen**. The arcade installs as a standalone full-screen "app" with no Safari UI. All four games respond to touch:

- **Keyboard Smash** — tap anywhere, shape spawns at your finger
- **Pop Bubbles** — drag your finger across bubbles to pop them
- **Drum Pad** — tap the top third for drums, middle for cymbals, bottom for chimes
- **Color Cascade** — tap anywhere; multi-touch triggers multiple colors

## Local

Double-click `index.html` to play offline. Everything is generated in code — no audio files, no network, no dependencies.

## Inspirations

- [BabySmash](https://github.com/shanselman/babysmash) by Scott Hanselman
- [TinyFingers](https://tinyfingers.net/)
- [baby-bam-bam](https://github.com/bfritscher/baby-bam-bam)

## Structure

```
.
├── index.html              # arcade home (game picker)
└── games/
    ├── keyboard/index.html
    ├── bubbles/index.html
    ├── drums/index.html
    └── cascade/index.html
```

Each game is self-contained — no shared CSS / JS. Easy to fork a game off into its own toy.
