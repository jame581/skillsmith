# Skillsmith

A plugin marketplace by [Jan Mesarc](https://github.com/jame581) — curated skills and plugins for AI coding agents (Claude Code, GitHub Copilot CLI, Gemini CLI).

## Plugins

### [logseq-brain](https://github.com/jame581/LogseqBrain)

Persistent memory for Claude using a dedicated Logseq graph. Save and load project context, decisions, and progress across sessions and devices.

### [godot-prompter](https://github.com/jame581/GodotPrompter)

Agentic skills framework for Godot 4.x game development — 44 domain-specific skills for GDScript and C#, plus agents for architecture, development, and code review.

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

### Gemini CLI

```bash
gemini extensions install https://github.com/jame581/LogseqBrain
gemini extensions install https://github.com/jame581/GodotPrompter
```

## Legacy Marketplace

The [godot-prompter-marketplace](https://github.com/jame581/godot-prompter-marketplace) remains online for existing installs, but new users should prefer `skillsmith`.
