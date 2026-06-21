# 2l-answer-with-eng-and-chzn

A Claude Code skill that enables bilingual responses in English and Chinese.

## Description

This skill instructs Claude to respond in both English and Chinese, with English text first followed by the Chinese translation. Perfect for users who want to see responses in both languages simultaneously.

## Installation

To install this skill, copy the `SKILL.md` file to your Claude skills directory:

```bash
# Windows
copy SKILL.md %USERPROFILE%\.claude\skills\2l-answer-with-eng-and-chzn\SKILL.md

# macOS/Linux
cp SKILL.md ~/.claude/skills/2l-answer-with-eng-and-chzn/SKILL.md
```

## Usage

Once installed, activate the skill by typing:

```
/2l-answer-with-eng-and-chzn
```

Or simply ask Claude to use the bilingual output skill.

## Rules

1. Always provide responses in both English and Chinese
2. English text comes first, followed by a blank line, then Chinese translation
3. Each paragraph/sentence should be translated separately
4. Keep both versions natural and fluent — not word-for-word translation
5. Code blocks remain as-is (no translation needed)

## Example

```
This is an example response. It demonstrates the bilingual format.

这是一个示例回复。它展示了双语格式。
```

## License

MIT
