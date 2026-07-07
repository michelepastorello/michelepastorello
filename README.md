# Michele Pastorello

Open tools that make AI work **measurable and governable** for people who work solo or small.

If you run your work with AI agents — as a solo professional or a small team — you have the same governance problems a large company has: what did the agents do, what did it cost, what are they allowed to touch. You just don't have a platform team. I build small, honest tools for that gap.

## Now

**Current cycle:** shipping and maintaining [Headroom](https://github.com/michelepastorello/headroom), and shaping the tooling around AI usage limits and agent operations.

## Projects

| Project                                                             | What it does                                                                                                              | License         | Status    |
| :------------------------------------------------------------------ | :------------------------------------------------------------------------------------------------------------------------ | :-------------- | :-------- |
| [`headroom`](https://github.com/michelepastorello/headroom)         | macOS menu-bar gauge for your AI coding limits (Codex & Claude Code): live percentage, reset times, floating HUD, alerts. | MIT (open-core) | ✅ Active |
| [`homebrew-tap`](https://github.com/michelepastorello/homebrew-tap) | Homebrew formulae for my tools. `brew install michelepastorello/tap/headroom`                                             | —               | ✅ Active |

## How I build

- **Process first, tools second.** Every tool starts from a real process I already run — never from a tool idea looking for a problem.
- **Governable by default.** Agent actions should be inspectable, logged and measurable.
- **Your data, open formats.** SQLite, CSV, Markdown. Export is always possible; lock-in is a bug.
- **No hype.** The README tells you what the tool does, not what it disrupts. Ships when it works. Where there is telemetry, it is declared and opt-in.
- **Run in production first.** I publish only what I use daily on my own stack.

---

Swift · TypeScript/Astro · Python · Node · and a VPS full of systemd units
