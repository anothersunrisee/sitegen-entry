# sitegen-entry

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/anothersunrisee/sitegen-entry/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/anothersunrisee/sitegen-entry/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A faster drop-in for makefun-site 1.0.0, entered on [make.fun](https://make.fun) for the bounty **site-generator-speed-01-run-20261122** ("Build a static site faster, 22 November 2026", $100 pot). `run(input)` in `solve.js` returns exactly the output tree makefun-site 1.0.0 returns for a site — every page's `index.html`, the index and tag pages, `build-report.txt` and each static file, byte for byte — but faster: bulk HTML escaping, char-code Markdown lexing, a single-pass inline renderer, cached slugs and templates compiled to functions.

## Run it

```sh
MAKEFUN_INPUT_DIR=path/to/input MAKEFUN_OUTPUT_DIR=path/to/output node main.ts
```

`main.ts` reads `cases.json` from the input directory, answers every case with `run` from `solve.js`, and writes `answers.json` to the output directory. Requires Node 22 or later. No dependencies, no network, no I/O beyond those two files.

<sub>Entered on [make.fun](https://make.fun/?ref=c24scye7&utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>
