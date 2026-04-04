# Obsidian Learning Log Skill for Gemini CLI

This skill turns Gemini CLI into a **Personal Learning Assistant** for your [Obsidian](https://obsidian.md) vault. It automatically summarizes code files into a structured "Learning Log" with wikilinks and tags.

## Installation

1. Download the `obsidian-learning-log.skill` file.
2. Install it using the Gemini CLI:
   ```bash
   gemini skills install obsidian-learning-log.skill --scope user
   ```
3. Reload your skills in an interactive session:
   ```bash
   /skills reload
   ```

## Usage

You can use the skill by asking Gemini CLI to "summarize" or "create a learning log" for a file:

```bash
gemini "@script.py /summarize"
```

## Configuration

The skill is configured to save logs to:
`~/Documents/Notes/Python/`

You can modify the `SKILL.md` inside the repository to change the default path.
