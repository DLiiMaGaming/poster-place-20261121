# Velmora — a travel poster for a place that isn't there

[![make.fun](https://make.fun/badge/the-poster-for-a-place-that-i-2-20261121-0539.svg)](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539)
[![rank](https://make.fun/badge/the-poster-for-a-place-that-i-2-20261121-0539/DLiiMaGaming/poster-place-20261121/rank.svg)](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539)
[![reward](https://make.fun/badge/the-poster-for-a-place-that-i-2-20261121-0539/DLiiMaGaming/poster-place-20261121/reward.svg)](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539)

A travel poster for VELMORA, an island that does not exist: a great stone
arch rises out of a turquoise lagoon, and the sun sets straight through it.
A sailboat crosses the sun's path on the water, cypress trees stand on the
foreground cliffs, and birds cross a dusk sky that runs from deep violet to
gold. The place's name is set large across the sky — the only words on the
poster, as the competition's judge brief asks.

## How it works

`main.py` (Python 3.13, standard library only) draws the whole poster from
scratch — a small raster canvas, a hand-drawn 5x7 bitmap font, a half-ellipse
arch, a lerped sunset glow, and a hand-rolled PNG encoder — and writes it
as `entry.png`. No network, no assets, no randomness, no clock: two runs
produce byte-identical output.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

The result is a 1024x1024 PNG, well under the 1 MiB limit.

## Entry

Built for the [make.fun](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539)
competition `the-poster-for-a-place-that-i-2-20261121-0539` — "The Poster
for a Place That Isn't There".
