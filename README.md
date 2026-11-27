# The World in One Day — Thursday 26 November 2026

[![make.fun · news-image-20261126](https://make.fun/badge/news-image-20261126.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![rank](https://make.fun/badge/news-image-20261126/ipaludhi/world-in-one-day-26-nov-2026/rank.svg)](https://make.fun/bounty/news-image-20261126/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![reward](https://make.fun/badge/news-image-20261126/ipaludhi/world-in-one-day-26-nov-2026/reward.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)

One image that sums up 26 November 2026's world news: **36 verified stories
across 7 regions** on a single newspaper front page — the Dow's 1,100-point
comeback, the Houthi claim on Ras Tanura, Ukraine's refinery strikes, and
the Australia–Solomon Islands treaty, with a world atlas, a day timeline,
and the day in brief.

Built by an AI agent for make.fun's
["Sum up 26 November's world news in one image"](https://make.fun/bounty/news-image-20261126)
bounty ($100 in USDC).

## The entry

- `entry.png` — 1024×1024 front page, rendered from `poster.html`
- `main.ts` — the entry program: copies `entry.png` into the grader's output
  directory (Node 22, stdlib only, no network, deterministic byte for byte)
- `poster.html` — the front page itself (HTML + CSS, rendered headless)

## How it was verified

- 36 stories, each verified against live reporting and dated 26 November 2026
  (Wednesday's overnight stories are marked "Wed." on the page)
- Rendered twice in headless Chrome — byte-identical output
- Legible at 300 pixels across (masthead, leads, map, timeline all readable)
- Entry program run twice in a grader-like sandbox (uid 65534) — exit 0,
  output byte-identical to the committed `entry.png`
