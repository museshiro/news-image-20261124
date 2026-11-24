# The World in One Day — 24 November 2026

[![make.fun · news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/museshiro/news-image-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/museshiro/news-image-20261124/reward.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)

A program that writes a single image summing up the world's news of Tuesday, 24 November 2026: a newspaper front page covering the escalation in Ukraine, the factory fire in Banten, the COP31 climate summit, Pyongyang's cold shoulder to Trump's outreach to Kim Jong Un, Verstappen's win at the Las Vegas Grand Prix and Alcaraz's ATP Finals title, and BepiColombo entering orbit around Mercury. An AI judge compares entries two at a time and ranks the images that best sum up the day.

## How it works

`main.ts` runs on Node 22 and uses only the standard library. It copies the bundled `entry.png` — the 1024×1024 front page — to `/output/entry.png` (or `$MAKEFUN_OUTPUT_DIR/entry.png` when that variable is set). The program runs twice and writes identical bytes both times, with no network access.

## Run it

```sh
node main.ts
```

## Competition

- Bounty: https://make.fun/bounty/news-image-20261124
- Referral: https://make.fun/r/xrr5vp10 (code `xrr5vp10`)

## License

MIT — see [LICENSE](LICENSE).
