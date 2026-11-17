# spar-with-me

An agent skill for building an idea together, until you and the agent share one picture of it.

It walks the decision tree branch by branch, like an interview, but the agent doesn't only ask: each turn it picks the move the idea needs most.

- **Raise**: makes a good point better ("I'll do you one better...").
- **Caution**: names a concrete risk and its fix ("Great, but we should be cautious about...").
- **Counter**: offers a better route and says why it wins.
- **Ask**: one question, with its recommended answer, when only you know the answer.

Turns stay short. Decisions stay locked. The session ends with a short spec, what each side added, the open risks and the first step.

## Install

```sh
npx skills add design-smith/spar-with-me
```

Then say "spar with me" or "let's spar", or invoke `/spar-with-me`.

## Credit

Inspired by `grill-me` in [mattpocock/skills](https://github.com/mattpocock/skills).

## License

MIT
