## Mutegate

**Open-source, self-hosted DLP gateway for AI agents.** It sits between your
agents and LLM providers — OpenAI, Anthropic, Groq, any OpenAI-compatible
endpoint — and stops secrets and personal data before a prompt leaves your
network.

Your agents talk to the cloud. Know what they say.

- **Blocks or redacts** API keys and tokens, private keys, emails, cards,
  IBANs and your own patterns — in the system prompt, tool-call arguments and
  tool results, not just the visible message
- **Incident feed** with masked samples only; raw sensitive content is never stored
- **Per-key policies** with a dry-run, budgets and rate limits, cost tracking
  per model, key and agent
- **One Go binary** on your own machine: point Claude Code, Codex, Cursor, the
  OpenAI and Anthropic SDKs or any agent at it by changing the base URL

![The incident feed](https://github.com/Mutegate/mutegate/raw/main/docs/screenshots/incidents.png)

### Repositories

| | |
|---|---|
| [**mutegate**](https://github.com/Mutegate/mutegate) | The gateway and its web console — start with the [quickstart](https://github.com/Mutegate/mutegate#quickstart) |
| [**cli**](https://github.com/Mutegate/cli) | `mutegate login`, then `mutegate run -- claude`: any tool through your gateway, nothing changed on the machine |
| [homebrew-tap](https://github.com/Mutegate/homebrew-tap) · [scoop-bucket](https://github.com/Mutegate/scoop-bucket) | The CLI for Homebrew and Scoop — [how to install](https://github.com/Mutegate/cli#install) |
| [site](https://github.com/Mutegate/site) | [mutegate.github.io/site](https://mutegate.github.io/site/) — what Mutegate is, and the guides for each agent and SDK |

Apache 2.0.
