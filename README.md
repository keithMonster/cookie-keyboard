# Cookie Keyboard

A baby keyboard smasher for toddlers — every keypress spawns a colorful shape, plays a piano note, and speaks the color name aloud.

Single-file HTML, zero dependencies, zero network. Just open `index.html` in a browser, press any key, and play.

## Live

https://keithmonster.github.io/cookie-keyboard/

## How it works

- **Press any key** → random colored shape pops up (circle / square / star / heart / hexagon / moon / etc.)
- **Sound** → piano note synthesized via Web Audio API, mapped to a C-major scale
- **Cleanup** → at most 8 shapes on screen at once, oldest fades out

## Local

Just double-click `index.html` and press any key.

Press `F` to toggle fullscreen. `Cmd+Q` to quit (left intentionally unblocked so adults can exit).

## Inspirations

- [BabySmash](https://github.com/shanselman/babysmash) by Scott Hanselman
- [TinyFingers](https://tinyfingers.net/)
- [baby-bam-bam](https://github.com/bfritscher/baby-bam-bam)
