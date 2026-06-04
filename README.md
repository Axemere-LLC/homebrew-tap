# Axemere Homebrew Tap

The official [Homebrew](https://brew.sh) tap for the **Axemere AI Gateway** by
[Axemere LLC](https://axemere.ai).

> ⚙️ **This repository is generated automatically** by our release pipeline
> (goreleaser). Please **do not edit files here or open pull requests** — changes are
> overwritten on the next release. Questions? See https://axemere.ai/docs.

---

## Install

```sh
brew tap Axemere-LLC/tap
brew install mvgc-gateway      # the gateway
brew install mvgc-console      # optional: the local console
```

For configuration and first-run setup, follow the macOS guide — it's the single
source of truth: **https://axemere.ai/docs/guides/it-setup/macos**

## What is the Axemere Gateway?

An HTTP proxy between your applications and your AI providers: your provider keys
live in the gateway instead of your code, with real-time cost tracking, per-project
spend limits, usage attribution, policy controls, and a verifiable audit ledger.

Three ways to run it:

- **Free Gateway** — self-hosted, run anywhere, no account or request limits.
  → https://axemere.ai/docs/free-gateway
- **Self-Hosted Gateway** — your infra, connected to the Axemere Control Plane and
  Cloud Console. → https://axemere.ai/docs/guides/it-setup
- **Managed Gateway** — Axemere runs it in the cloud, no infra to operate.
  → https://axemere.ai/docs/guides/managed-gateway

## Links

- Product & docs — https://axemere.ai
- macOS install guide — https://axemere.ai/docs/guides/it-setup/macos
- Release artifacts — https://github.com/Axemere-LLC/mvgc-releases
