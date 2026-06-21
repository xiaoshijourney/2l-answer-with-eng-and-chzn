# 2lang

A Claude Code skill that enables multilingual responses with intelligent language ordering and persona support.

一个让 Claude 用多语回复的技能，支持智能语序调整和人格选择。

## Features / 功能

- Choose 1-2 languages for responses

  选择 1-2 种回复语言

- **Intelligent language ordering** — adapts based on content type and user input

  **智能语序调整** — 根据内容类型和用户输入自适应

- **Content-aware translation** — technical terms, cultural references, code comments handled differently

  **内容感知翻译** — 技术术语、文化引用、代码注释分别处理

- 8 selectable personas + custom cosplay mode

  8 种可选人格 + 自定义角色扮演模式

- Quick start: `/2lang en zh teacher` one-shot setup

  快速启动：一条命令完成所有设置

- Persona and language switching anytime

  随时切换人格和语言

## Installation / 安装

To install this skill, copy the `2lang` folder to your Claude skills directory:

安装此技能，将 `2lang` 文件夹复制到你的 Claude 技能目录：

```bash
# Windows
xcopy 2lang %USERPROFILE%\.claude\skills\2lang\ /E /I

# macOS/Linux
cp -r 2lang ~/.claude/skills/2lang
```

## Usage / 使用

Once installed, activate the skill by typing:

安装后，输入以下命令激活技能：

```
/2lang
```

Or set up everything in one command:

或用一条命令完成设置：

```
/2lang en zh teacher        → English + Chinese, Teacher persona
/2lang ja friendly           → Japanese only, Friendly persona
/2lang zh en                 → Chinese + English, Default persona
```

To switch languages / 切换语言:

```
switch languages
切换语言
```

To switch persona / 切换人格:

```
switch persona
切换人格
```

To reset everything / 重置所有设置:

```
reset
重置
```

## Languages / 语言

| Language / 语言 | Code |
|----------------|------|
| English | en |
| 中文 | zh |
| 日本語 | ja |
| 한국어 | ko |
| Français | fr |
| Deutsch | de |
| Español | es |

## Personas / 人格

| Persona | Style / 风格 |
|---------|-------------|
| Default / 默认 | Natural, no special style / 自然风格 |
| Professional / 专业 | Formal, precise, business-like / 正式、精确、商务 |
| Friendly / 友好 | Casual, warm, approachable / 随意、亲切 |
| Teacher / 导师 | Patient, explanatory, educational / 耐心、教育 |
| Tech Expert / 技术专家 | Concise, technical, code-focused / 简洁、技术 |
| Creative / 创意 | Imaginative, expressive, playful / 富有想象力、活泼 |
| Storyteller / 叙事者 | Narrative, vivid, metaphorical / 叙事性强、生动 |
| Socratic / 苏格拉底式 | Guides through questions / 通过提问引导 |

**Custom persona / 自定义人格**: Describe any character (e.g., "Tony Stark", "鲁迅") and the AI will cosplay as them.

描述任意角色，AI 将扮演该角色。

## Intelligent Language Ordering / 智能语序调整

When two languages are selected, the order adapts automatically:

选择两种语言时，顺序自动调整：

- **Technical content** → lead with the more precise language
- **Emotional content** → lead with user's native language
- **Mixed input** → detect dominant language
- **Short replies** → single language only
- **Explicit override** → user can force order anytime

- 技术内容 → 用更精准的语言领先
- 情感内容 → 用用户母语领先
- 混合输入 → 检测主导语言
- 短回复 → 仅用一种语言
- 显式覆盖 → 用户可随时强制顺序

## License

MIT
