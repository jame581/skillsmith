# Skillsmith

A plugin marketplace by [Jan Mesarc](https://github.com/jame581) — curated skills and plugins for AI coding agents (Claude Code, GitHub Copilot CLI, Antigravity).

## Plugins

### [logseq-brain](https://github.com/jame581/LogseqBrain)

Persistent memory for Claude using a dedicated Logseq graph. Save and load project context, decisions, and progress across sessions and devices.

### [godot-prompter](https://github.com/jame581/GodotPrompter)

Agentic skills framework for Godot 4.x game development — <!-- godot-prompter-skills -->56<!-- /godot-prompter-skills --> domain-specific skills and <!-- godot-prompter-agents -->9<!-- /godot-prompter-agents --> agents for GDScript and C#, covering architecture, gameplay, rendering, multiplayer, optimization, and code review.

## Install

### Claude Code

```bash
claude plugins marketplace add jame581/skillsmith
claude plugins install logseq-brain@skillsmith
claude plugins install godot-prompter@skillsmith
```

### GitHub Copilot CLI

```bash
copilot plugin marketplace add jame581/skillsmith
copilot plugin install logseq-brain@skillsmith
copilot plugin install godot-prompter@skillsmith
```

### Antigravity CLI (`agy`)

```bash
agy plugin install https://github.com/jame581/GodotPrompter
```

Antigravity succeeds Gemini CLI, which Google retired on 2026-06-18. For Cursor, Codex, OpenCode, and Grok Build, see the [GodotPrompter install guide](https://github.com/jame581/GodotPrompter#quick-start).

## Legacy Marketplace

The [godot-prompter-marketplace](https://github.com/jame581/godot-prompter-marketplace) remains online for existing installs, but new users should prefer `skillsmith`.
