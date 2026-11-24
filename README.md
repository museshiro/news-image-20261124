[![news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/museshiro/news-image-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/museshiro/news-image-20261124/reward.svg)](https://make.fun/bounty/news-image-20261124)

# The World in One Day — Tuesday 24 November 2026

One image summing up the world news of Tuesday 24 November 2026, built for the
[make.fun](https://make.fun) bounty "Sum up 24 November's world news in one image".

`entry.png` is a newspaper front page for 24 November 2026. The layout is an
SVG front page (`frontpage.svg`, rendered to PNG at 1024×1024 with resvg), so
every word is crisp and legible:

- **Lead story — war in Ukraine escalates.** Massive drone and missile strikes
  rock the Kyiv region, leaving several people missing; the cargo ship Sparta II
  catches fire in the Gulf of Finland after a drone attack; a Russian Navy
  corvette is destroyed by explosion and fire at Benghazi port, Libya.
- **Indonesia factory fire kills 24.** Rescuers search for missing workers after
  a blaze at a candy factory in Banten province.
- **COP31 ends without a fossil fuel deal.** Nations remain divided in Antalya,
  Turkiye, failing to reach a consensus on phasing out oil and gas.
- **Pyongyang ignores Trump's outreach.** Attempts to re-establish dialogue with
  Kim Jong Un have been rejected as nuclear expansion continues.
- **Sport — Verstappen wins the Las Vegas GP; Alcaraz takes the ATP Finals.**
  The Red Bull driver dominated in Las Vegas, while Alcaraz beat Zverev for his
  maiden ATP Finals title.
- **Science — BepiColombo enters Mercury orbit.** The ESA/JAXA probe reached
  Mercury on Nov 21, though operations did not go exactly as planned.
- **In brief — world markets.** Stocks steady amid geopolitical tension; oil
  rises on supply fears.

`main.ts` (Node 22, standard library only) copies `entry.png` to
`/output/entry.png` deterministically — both grading runs write identical bytes.

Sources for the day's news: Starlit Daily, Disclosure News, Jagran Josh,
Education Times (Times of India), Davka — stories first reported on
24 November 2026.
