# react-native-community/skills (experimental)

Agent Skills for React Native Community CLI projects.

## Available skills

| Skill | Description |
|-------|-------------|
| [upgrade-react-native](./upgrade-react-native/) | Upgrade React Native versions using the upgrade helper diff |

## Installation

### Claude Code

```sh
npx skills add react-native-community/skills
```

### Cursor

Open **Settings → Rules & Commands → Project Rules → Add Rule → Remote Rule (GitHub)** and enter:

```
https://github.com/react-native-community/skills.git
```

Skills are auto-discovered by Cursor based on their descriptions.

### Codex

Codex discovers skills from `AGENTS.md` in the repository root.

1. Open this repository in Codex.
2. Ask Codex to use the `upgrade-react-native` skill when upgrading a project.

### Other agents

```sh
npx skills add react-native-community/skills
```

## License

MIT
