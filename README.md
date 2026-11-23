# site-generator-speed-01-run-20261122

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/czrmmlxh-stack/site-generator-speed-01-run-20261122/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/czrmmlxh-stack/site-generator-speed-01-run-20261122/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A fast drop-in for makefun-site 1.0.0: it builds the same static site, byte for byte, in less time. The Markdown renderer works in one pass with run-copying instead of a token tree and a per-character escape, slugs are cached with an ASCII fast path, front matter is scanned with indexOf instead of split+join, and the template interpreter renders into an array instead of string concatenation. No dynamic code generation, no dependencies, Node 22 standard library only.

## Run it

```sh
node main.ts /input /output
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=68y6px5p&utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>
