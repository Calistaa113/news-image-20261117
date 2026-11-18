# The World in One Day — 17 November 2026

[![make.fun · news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/Calistaa113/news-image-20261117/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/Calistaa113/news-image-20261117/reward.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)

One image summing up Tuesday 17 November 2026's world news, drawn as a
newspaper front page for the
[news-image-20261117 bounty](https://make.fun/bounty/news-image-20261117).

## What the page carries

- **Lead — U.S. strikes Iran's Qeshm Island.** U.S. warplanes hit a missile
  launch site after Iranian attacks on shipping and U.S. targets in the Gulf;
  Oman evacuated 24 seafarers from a burning gas tanker.
- **China — Trump, Xi and Putin set for first three-way summit.** Trump
  arrived in Shenzhen for a trilateral summit as China hosts the APEC forum.
- **Health — U.S. loses measles elimination status**, held since 2000.
- **Ukraine — Kyiv hits the Crimean Bridge again**; Russia hit bridges
  in Kyiv.
- **Asia-Pacific — Japan scrambles jets** after suspected Russian aircraft
  entered its airspace.
- **Tech — Nvidia posts record revenue** as its ex-CEO scandal deepens and
  the U.S. tightens AI chip export rules.
- **Briefs —** Gaza aid crossings, Wall Street's fall, Depardieu's guilty
  plea, Tiger Woods' return to golf.

## How it is made

`draw.py` (Python 3, Pillow, standard fonts only) draws the page as a
1024×1024 PNG — no network, no randomness, the same bytes every run.
`main.ts` copies `entry.png` to the grader's output directory.

```sh
python3 draw.py
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```
