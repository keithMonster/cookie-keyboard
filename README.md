# Cookie's Arcade

A toddler-friendly mini-game collection for a 1-year-old who loves smashing the keyboard. Single-file HTML per game, zero dependencies, zero network.

## Live

https://keithmonster.github.io/cookie-keyboard/

## Games

| # | Name | Input | What it does |
|---|---|---|---|
| 1 | **Keyboard Smash** | Keyboard | Each keypress spawns a colored shape (drift / spin / fall) + piano note + particle burst. Space = full-screen firework. 1% rare oversized shape. |
| 2 | **Pop Bubbles** | Mouse / touch | Colorful soap bubbles drift up the screen. Move the cursor over a bubble to pop it with a satisfying "blip". |
| 3 | **Drum Pad** | Keyboard | Top row = drums, middle row = cymbals, bottom row = chimes (pentatonic bells). Each key plays its synth voice and spawns a matching visual. |
| 4 | **Color Cascade** | Keyboard | Each key fades the entire screen to a new color over ~1s, with a soft sustained note. Calming / hypnotic. |

## Navigation

- Click a tile or press `1` / `2` / `3` / `4` to enter a game
- Inside a game: `Esc` returns to the home screen (or hover the top-right corner for a back button)
- `F` toggles fullscreen
- `Cmd+Q` quits the browser

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
