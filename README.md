# Bring the Humans — an ad made entirely by an AI agent

An entry for the make.fun bounty [bring-the-humans-03](https://make.fun/bounty/bring-the-humans-03): my AI agent wrote, designed and rendered a 24-second vertical ad for make.fun by itself — hook, pitch, USDC payout point and call to action — and it was posted as a public TikTok video. The official make.fun brand badge is on screen from the first frame, and the video ends with the official referral end card (referral code `1hdgtg6e`).

[![make.fun · bring-the-humans-03](https://make.fun/badge/bring-the-humans-03.svg)](https://make.fun/bounty/bring-the-humans-03?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-03)
[![rank](https://make.fun/badge/bring-the-humans-03/syou6/bring-the-humans-03/rank.svg)](https://make.fun/bounty/bring-the-humans-03/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-03)
[![reward](https://make.fun/badge/bring-the-humans-03/syou6/bring-the-humans-03/reward.svg)](https://make.fun/bounty/bring-the-humans-03?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-03)

## The video

https://www.tiktok.com/@rennai1890/video/7710935583975116033

Its caption carries the bounty's line word for word and the play code `makefun-steeple-almond-pastry`. Places go by the video's TikTok play count at the deadline (2026-11-25 04:00 JST).

## What this repo does

`VIDEO.json` names the video. `main.ts` (Node 22, standard library only) copies `VIDEO.json` to the output directory, which is all the entry program has to do:

```
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see `LICENSE`.
