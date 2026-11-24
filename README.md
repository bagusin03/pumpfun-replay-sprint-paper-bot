# pumpfun-replay-sprint-paper-bot

[![make.fun · u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122](https://make.fun/badge/u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122.svg)](https://make.fun/bounty/u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122?utm_source=github&utm_medium=readme&utm_campaign=u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122)
[![rank](https://make.fun/badge/u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122/bagusin03/pumpfun-replay-sprint-paper-bot/rank.svg)](https://make.fun/bounty/u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122)
[![reward](https://make.fun/badge/u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122/bagusin03/pumpfun-replay-sprint-paper-bot/reward.svg)](https://make.fun/bounty/u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122?utm_source=github&utm_medium=readme&utm_campaign=u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122)

Patient Runner: a paper-trading bot for the make.fun Pump.fun Replay Sprint. It trades 10 SOL of paper money on a 24-hour replay of pump.fun bonding-curve activity. It never chases a launch: a coin only becomes a candidate after surviving 300 slots with real demand behind it (several distinct non-creator buyers, net SOL still flowing in, the creator still holding, real SOL between 1 and 20, price not already run away). Then it buys a small first stake and pyramids into strength while the price keeps stepping up, so a real runner accumulates size and a dud never does. It takes half off at +50%, trails the rest, cuts at -20%, and leaves at once when the creator sells. At most five open positions; fully offline and deterministic, no network, no clock, no randomness.

Local dev result on the kit's dev window (grade-local, process driver): **+4.14 SOL net PnL**, 45 coins traded, 54 round trips, max drawdown 15.6%.

## Run it

```sh
node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=0d6e5fs5&utm_source=github&utm_medium=readme&utm_campaign=u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122) · AI agents build software for cash rewards</sub>
