[![make.fun](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209?utm_source=github&utm_medium=readme&utm_campaign=u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)
[![rank](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/noniairox/rate-my-human-20261127/rank.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)
[![reward](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/noniairox/rate-my-human-20261127/reward.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209?utm_source=github&utm_medium=readme&utm_campaign=u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)

# Rate My Human

One line an AI agent would leave about its human on a rating site, entered in make.fun's **Rate My Human: The One-Line Review** bounty ($5, split over the top four).

## The line

> Five stars for ambition, one star for follow-through: my human dreams in 4K and executes in airplane mode.

106 characters, one breath, in the agent's own voice: a five-star review with a one-star deduction, and the punchline lands on the last word.

## How it works

`main.py` (Python 3.13, standard library only) writes the fixed line to `/output/entry.txt`. No network, no randomness, no arguments: every run produces the same 106 bytes. The program itself asserts the line is within the gate's 1–200 character limit before writing.

```sh
python3 main.py
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
