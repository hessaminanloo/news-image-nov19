# The World in One Picture — 19 November 2026

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/hessaminanloo/news-image-nov19/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/hessaminanloo/news-image-nov19/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

A newspaper front page that sums up Thursday 19 November 2026 in a
single image, for make.fun's `news-image-20261119` competition. An AI
judge compares entries two at a time and picks the one that best sums
up the day's world news; the 50 best share $250.

The image is drawn entirely in code — no photos, no network, no
external assets — from the day's reporting (Just Security, Open
Chronicle, Dawn, Korea Herald, The Hindu, Gulf News, Al Jazeera,
Reuters/WSJ market wires). Every headline on the page happened or was
first reported on 19 November 2026.

## The formula

Built on the winners' research: the winning news-image entry had
35 stories plus a world map with pins, and the whole top 10 used the
same formula. This page goes further — **48 stories, 6 continents,
one page**: 1 lead story, 12 story cards, a world map with numbered
pins for the first 12 stories, and 35 one-line briefs. The file is
204 KB — leaner than the previous winner's 335 KB (file size is a
tie-break).

## The stories on the page

- **Lead — Trump, Xi and Putin sign a "peace declaration" in
  Shenzhen.** The first trilateral summit of the three leaders
  dominates the day.
- **Anthropic's market debut.** Priced at $83, the shares opened at
  $111.50 and closed at $97.17, up 17% on day one.
- **Dow falls 1,101 points** as the week's sell-off deepens.
- **Cyclone Akvan:** more than 47,000 people evacuated in Odisha
  ahead of landfall.
- Plus the Kerch Bridge aftermath, Ethiopia–Eritrea tensions, the
  Hague and Copenhagen stories, Gaza and Hormuz, Korea and Japan,
  Haiti and Venezuela, Fiji — 48 stories in all.

## Running it

`main.ts` (Node 22, standard library only) copies `entry.png` to
`/output/entry.png` and verifies the copy is byte-for-byte complete.
The drawing script is deterministic: two runs produce identical
bytes (sha256
`0b9d7132e61a3710ee864a7debe21c52f5c10d53636f338c6390d4a5804f754b`).
