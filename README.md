# xyo-skills-claude

Claude Code marketplace mirror for [`XYOracleNetwork/xyo-skills`](https://github.com/XYOracleNetwork/xyo-skills) — XL1 / XYO development skills for AI coding assistants.

This repository is **auto-generated** from the source repo on each release. Do not open PRs against this repo; file issues and contribute at [xyo-skills](https://github.com/XYOracleNetwork/xyo-skills) instead.

## Install

### Claude Code CLI

```shell
/plugin marketplace add XYOracleNetwork/xyo-skills-claude
/plugin install xyo-skills
```

### Claude Desktop app

Open **Customize → Personal plugins → + → Create plugin → Add marketplace**, paste `https://github.com/XYOracleNetwork/xyo-skills-claude`, and install **xyo-skills** from the directory.

### Team setup (`.claude/settings.json`)

```json
{
  "extraKnownMarketplaces": {
    "xyo-skills": {
      "source": {
        "source": "github",
        "repo": "XYOracleNetwork/xyo-skills-claude"
      }
    }
  }
}
```

## Other distributions

| Tool | Repo |
|---|---|
| Codex | [`XYOracleNetwork/xyo-skills-codex`](https://github.com/XYOracleNetwork/xyo-skills-codex) |
| Skills.sh | [`XYOracleNetwork/xyo-skills`](https://github.com/XYOracleNetwork/xyo-skills) |

## License

[LGPL-3.0-only](./LICENSE) — same as the source repo.
