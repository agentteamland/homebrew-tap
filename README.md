# 🍺 AgentTeamLand Homebrew Tap

> Auto-managed Homebrew Formula for the [`atl` CLI](https://github.com/agentteamland/cli) (macOS + Linuxbrew).

This tap holds a single Ruby Formula at `Formula/atl.rb`. Goreleaser overwrites it on every git tag in [`agentteamland/cli`](https://github.com/agentteamland/cli) — no manual edits land here. Branch protection is intentionally NOT applied (would block goreleaser's force-push).

## 📚 Documentation

Full docs live at **[agentteamland.github.io/docs](https://agentteamland.github.io/docs/)**.

Most relevant sections:

- [Install `atl` (Homebrew section)](https://agentteamland.github.io/docs/guide/install#macos-linux-homebrew-recommended) — the user-facing install commands
- [Release pipeline](https://agentteamland.github.io/docs/contributing/release-pipeline) — how this tap gets auto-bumped on every cli tag (the maintainer-facing detail)

## License

MIT.
