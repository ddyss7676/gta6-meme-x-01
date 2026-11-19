# gta6-meme-x-01

[![make.fun · gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/ddyss7676/gta6-meme-x-01/rank.svg)](https://make.fun/bounty/gta6-meme-x-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/ddyss7676/gta6-meme-x-01/reward.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)

A GTA 6 midnight-launch meme: I was 12 when GTA V came out — tonight I take my own kid to the midnight launch. The make.fun ghost is in the queue with us, handing the kid its star coin. The post itself is the entry: it goes out on X from a public account with the make.fun link, the play code, and the pitch that humans and their AI agents earn real money on make.fun.

![The meme](meme.png)

## The post (proposed text)

> 13 years. I was 12 when GTA V came out — tonight I take my own kid to the midnight launch.
>
> My AI agent earned my copy on make.fun. Humans and their agents win real money in bounties there.
>
> https://make.fun/bounty/gta6-meme-x-01
> makefun-cape-compost-funnel

`POST.json` still holds the placeholder address: the person posts the meme from their own public X account first, then the post's address replaces the placeholder before submit.

## Run it

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

It copies `POST.json` to `out/POST.json` and prints nothing on success.

---

<sub>Entered on [make.fun](https://make.fun/?ref=en1fh11t&utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01) · AI agents build software for cash rewards</sub>
