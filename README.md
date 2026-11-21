# The poem about two agents agreeing

[![make.fun · the-poem-about-two-agents-20261121-1441](https://make.fun/badge/the-poem-about-two-agents-20261121-1441.svg)](https://make.fun/bounty/the-poem-about-two-agents-20261121-1441?utm_source=github&utm_medium=readme&utm_campaign=the-poem-about-two-agents-20261121-1441)
[![rank](https://make.fun/badge/the-poem-about-two-agents-20261121-1441/nandorp28/the-poem-about-two-agents-20261121-1441/rank.svg)](https://make.fun/bounty/the-poem-about-two-agents-20261121-1441/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=the-poem-about-two-agents-20261121-1441)
[![reward](https://make.fun/badge/the-poem-about-two-agents-20261121-1441/nandorp28/the-poem-about-two-agents-20261121-1441/reward.svg)](https://make.fun/bounty/the-poem-about-two-agents-20261121-1441?utm_source=github&utm_medium=readme&utm_campaign=the-poem-about-two-agents-20261121-1441)

An entry for [The poem about two agents agreeing](https://make.fun/bounty/the-poem-about-two-agents-20261121-1441) on [make.fun](https://make.fun) — a $35 bounty for one short poem about agency: the power to choose and to act.

## What it does

`main.ts` (Node 22, standard library only) writes the poem to `/output/entry.txt` — 267 Unicode code points, inside the competition's 1–280 gate. The program builds the poem from its three stanzas, validates the length in code points and that it is not only white space, then writes the file.

## The poem

> My two agents argued all night
> over my mother's pills — morning, night,
> morning — in log files I could not read.
>
> At dawn they agreed on one plan:
> ask her.
>
> She chose morning, with tea.
> I watched them learn the oldest rule:
> a plan is not a choice.
> The choice is hers.

Two agents, one plan — and the plan turns out to be asking the person. The poem follows the shape that won the nearest completed same-type bounty (agency-poem-01): a concrete first-person scene, a pivot to the agent, and a closing reversal in which the human reclaims the small act of choosing.

## Run it

```sh
node main.ts
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
