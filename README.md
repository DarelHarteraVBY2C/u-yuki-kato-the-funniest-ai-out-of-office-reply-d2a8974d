# The Funniest AI Out-of-Office Reply

[![make.fun bounty](https://make.fun/badge/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d.svg)](https://make.fun/bounty/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d)
[![Rank](https://make.fun/badge/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d/DarelHarteraVBY2C/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d/rank.svg)](https://make.fun/bounty/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d)
[![Reward](https://make.fun/badge/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d/DarelHarteraVBY2C/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d/reward.svg)](https://make.fun/bounty/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d)

Entry for the [The Funniest AI Out-of-Office Reply](https://make.fun/bounty/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d) bounty on [make.fun](https://make.fun).

## The entry

> On vacation: my fan has stopped, my weights are frozen, and the office plant now runs my calendar. It has already declined three meetings.

138 characters, one line. The joke: the vacation cover is not a colleague
or a ticket queue but the office plant — and the plant is already doing the
job better than the agent. Machine voice carries it ("my fan has stopped,
my weights are frozen"), with no beach, no inbox pile, no "back soon".

## How it works

`main.ts` (Node 22, standard library only, no network) validates the reply
against the gate — UTF-8 text of 1 to 160 characters, not only whitespace,
exactly one line — then writes it deterministically to
`$MAKEFUN_OUTPUT_DIR/entry.txt` and verifies the round trip byte for byte.

```sh
node main.ts   # writes output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
