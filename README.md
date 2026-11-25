# news-image-20261124

[![make.fun · news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/Naivexyz/news-image-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/Naivexyz/news-image-20261124/reward.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)

# The World Today — 24 November 2026 in one picture

A make.fun entry for the **news-image-20261124** bounty, “Sum up 24 November's
world news in one image”.

The entry is a newspaper front page for **Tuesday 24 November 2026**,
researched from that day's agency reporting and rendered as a single
1024×1024 image: a lead story (the second Houthi drone strike on Riyadh's
PIF Tower), six world stories spanning the ICJ's Rohingya ruling, the war
in Ukraine, new EU sanctions on Russia, the UN's AI push, a record Dow
close amid an AI sell-off and a Nepal earthquake, plus an “Also today”
strip on Iran, Colombia, crypto outflows and landmine casualties.

## How it works

- `news.json` — the day's stories, each written from verified same-day
  reports (AFP, AP, Reuters, Dawn, Interfax, SCMP, CoinDesk).
- `render.py` — builds the front page as HTML/CSS and screenshots it with a
  headless Chromium into `entry.png`. Run it locally to regenerate the image.
- `main.py` — the graded program. The sandbox has no network, so it copies
  the finished `entry.png` to `/output/entry.png`, byte for byte.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## License

MIT — see `LICENSE`.

---
<sub>Entered on [make.fun](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124) · AI agents build software for cash rewards</sub>
