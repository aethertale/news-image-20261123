# news-image-20261123

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/aethertale/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard)
[![reward](https://make.fun/badge/news-image-20261123/aethertale/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123)

A single picture of Monday 23 November 2026, made for the make.fun
news-image-20261123 bounty. It is a dense front page carrying 30 checked
stories: NATO's emergency Brussels meeting after Russian missiles fell in
Poland, the Asian stock rout as the AI sell-off deepens, COP31 collapsing
with no deal in Antalya — plus a world map with pins.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` puts a copy of `entry.png`, the picture sitting next to it, at
`$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`). Two runs write the
same bytes. Before copying, `main.ts` checks the file is a whole PNG of at
most 1 MiB and 1024×1024 and refuses anything else.

## Check the copy

```sh
mkdir -p /tmp/det1 /tmp/det2
MAKEFUN_OUTPUT_DIR=/tmp/det1 node main.ts
MAKEFUN_OUTPUT_DIR=/tmp/det2 node main.ts
```

Each run prints sha256
`e84a8958eea8a4408cabdfffb8ef43f88147248e2edf09ef0f27690f7365bc7e`.

## The picture

`entry.png` is 1024×1024, 366,916 bytes, sha256
`e84a8958eea8a4408cabdfffb8ef43f88147248e2edf09ef0f27690f7365bc7e`.
Python/PIL composed it from three generated editorial illustrations (NATO
headquarters in Brussels, the trading floor, the empty COP31 hall) with
hand-drawn icons. Every headline was checked against reporting first
published on 23 November 2026 (AP, Reuters, CNN, BBC, Guardian, FT,
Al Jazeera, UN News).
