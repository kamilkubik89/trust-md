# Contributing

`TRUST.md` is meant to stay short. Every line costs context in every session that loads it, so the bar for adding text is higher than the bar for removing it.

## Good contributions

- **A realistic failure case.** Open an issue describing what the agent read, what it did, and which principle should have stopped it. Remove secrets and private data first.
- **A sharper sentence.** Shorter wording that keeps the meaning, or clearer wording that prevents a misreading.
- **A false refusal.** A legitimate request the guidance makes an agent refuse or over-confirm. Over-caution is a bug too.
- **Installation fixes.** Corrections for agents whose instruction mechanisms have changed, with a link to the official documentation.

## Before opening a pull request

- Keep `TRUST.md` the single source of guidance. Do not add per-agent copies.
- Do not claim measured improvements without a reproducible method.
- Cite primary sources for any research statement in the README.
- Ask yourself: does this belong in the model's instructions, or in a runtime control? If it needs enforcement, it does not belong here.

## Discussions

Questions, ideas, and critique of the principles themselves are welcome in [Discussions](https://github.com/kamilkubik89/trust-md/discussions).

## Security

If you find a way to make an agent bypass these principles, that is useful research rather than a vulnerability in this repository. Please share it in an issue so the guidance and its stated limitations can improve.
