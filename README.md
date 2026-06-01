# Prompt Architect - AI绘画提示词建筑师

![GitHub Repo stars](https://img.shields.io/github/stars/tanghua-git/skill-ai-prompt-architect?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/tanghua-git/skill-ai-prompt-architect?style=flat-square)
![GitHub](https://img.shields.io/badge/license-MIT-blue?style=flat-square)
![Topics](https://img.shields.io/badge/tags-ai--prompt%20%7C%20prompt--engineering%20%7C%20midjourney-brightgreen?style=flat-square)

> **AI绘画提示词设计助手** — 基于 345 篇结构化知识蒸馏，通过 8 个专业智能体协作生成高质量 AI 绘画提示词。
>
> An AI prompt architect for AI art generation. Multi-agent collaboration for high-quality prompt engineering, powered by 345 articles of distilled knowledge across Midjourney, Nano Banana, Gemini, and more.

---

## 🌟 Features

| Capability | Description |
|-----------|-------------|
| **8 Specialized Agents** 🤖 | Concept Designer, Art Director, Colorist, Photographer, Lighting Artist, Material Specialist, Composition Designer, Narrative Designer |
| **345 Knowledge Articles** 📚 | Distilled from 200+ IMA knowledge base articles + 115 supplemented sources |
| **11 Reference Documents** 📖 | Professional guides covering style, photography, lighting, materials, composition, color, and narrative |
| **Multi-Platform Support** 🎨 | Midjourney / Nano Banana Pro / Gemini / 即梦AI / DALL·E / Stable Diffusion / Doubao / Tongyi |
| **55 Style System** 🖌️ | Comprehensive style categories with detailed prompt templates |
| **238 Prompt Examples** 💡 | Curated examples covering 31 templates and 28 methodologies |
| **Agent Workflow** 🔄 | Concept → Art Direction → Color → Photography → Lighting → Materials → Composition → Narrative → Quality Review |

---

## 📦 Installation

### As an OpenClaw Skill

```bash
# Clone the repo
git clone https://github.com/tanghua-git/skill-ai-prompt-architect.git \
  ~/.openclaw/skills/ai-prompt-architect

# Or install directly via OpenClaw:
openclaw skill install tanghua-git/skill-ai-prompt-architect
```

---

## 🚀 Usage

### Basic Prompt Generation

> **Input:** "赛博朋克风格，未来东京雨夜，女主角站在霓虹灯下的天桥上"
>
> **Output:** A complete prompt with lighting, composition, color palette, mood, camera parameters, and quality modifiers

### Multi-Agent Workflow

```
User Input
    ↓
🧠 概念设计师 (Concept Designer)
  - 3 directions: literal / unexpected / abstract
    ↓
🎭 艺术指导 (Art Director)
  - Sets tone, ensures consistency across all agents
    ↓
🎨 色彩师 (Colorist)
  - Color palette design (complementary / analogous / monochromatic)
    ↓
📷 摄影师 (Photographer)
  - Lens selection, focal length, depth of field, camera angle
    ↓
💡 光影师 (Lighting Artist)
  - Lighting setup, mood lighting, shadow design
    ↓
🧱 材质师 (Material Specialist)
  - Texture and material descriptions
    ↓
📐 构图师 (Composition Designer)
  - Frame layout, rule of thirds, leading lines
    ↓
📖 叙事设计师 (Narrative Designer)
  - Visual storytelling, emotional impact
    ↓
✅ 评测反馈 (Review & Feedback)
  - Quality check, platform-specific optimization
    ↓
Final Prompt Output
```

---

## 🧠 Knowledge Base Structure

| Category | Content |
|----------|---------|
| **Style System** | 55 style categories with detailed descriptions and examples |
| **Composition & Camera** | Composition rules, lens types, camera angles, depth of field |
| **Lighting & Atmosphere** | Lighting setups, mood lighting, atmospheric effects |
| **Materials & Textures** | Material descriptions, surface qualities, tactile prompts |
| **Color Theory** | Color palettes, harmony rules, emotional color mapping |
| **Platform Optimization** | Midjourney V8/V7, Nano Banana, Gemini, DALL·E specific parameters |
| **Prompt Construction** | Formula templates, weighting, parameters, quality modifiers |
| **Visual Narrative** | Storytelling through images, narrative arcs in single frames |

---

## 📁 Repository Structure

```
skill-ai-prompt-architect/
├── SKILL.md                         # Main skill file (v2.1 Darwin-optimized)
├── README.md                        # This file
└── references/
    ├── art-direction.md             # Art direction framework
    ├── color-theory.md              # Color theory & palette design
    ├── composition-guide.md         # Composition rules & techniques
    ├── concept-generation.md        # Concept generation methodology
    ├── lighting-atmosphere.md       # Lighting & atmosphere design
    ├── materials-adjectives.md      # Material & texture descriptions
    ├── photography-guide.md         # Camera & lens guide
    ├── prompt-construction.md       # Prompt formula & templates
    ├── review-checklist.md          # Quality review framework
    ├── style-categories.md          # 55 style categories
    └── visual-narrative.md          # Visual storytelling guide
```

---

## 📊 Quality Score (Darwin Skill 2.0)

| Dimension | Score | Note |
|-----------|-------|------|
| Frontmatter | ✅ 10/10 | Clear triggers and boundaries |
| Workflow Clarity | ✅ 10/10 | Agent orchestration with clear I/O |
| Failure Mode Encoding | ✅ 10/10 | 9 three-level fallback templates added |
| Checkpoint Design | ⏳ Pending | Planned for next iteration |
| Actionable Specificity | ✅ 10/10 | Concrete templates, examples, parameters |
| Resource Integration | ✅ 10/10 | All reference paths correct |
| Architecture | ✅ 10/10 | Clean orchestration pattern |
| Empirical Testing | ✅ 9/10 | Validated with test prompts |
| Anti-pattern Blacklist | ✅ Pending | Being supplemented |

*Darwin v2.1 optimized — dimension 3 (failure mode encoding) updated with 9 situational fallback templates.*

---

## 🔗 Related Projects

- [skill-instructional-design](https://github.com/tanghua-git/skill-instructional-design) — K-12 Instructional Design Assistant
- [OpenClaw](https://github.com/openclaw/openclaw) — AI agent platform
- [Darwin Skill](https://github.com/alchaincyf/darwin-skill) — Skill optimization framework

---

## 📄 License

MIT © 2026 Tanghua (唐华)

---

## 🤝 Contributing

Ideas, suggestions, or found a cool new style category? [Open an issue](https://github.com/tanghua-git/skill-ai-prompt-architect/issues) or submit a PR.

If this skill helps your AI art workflow, give it a ⭐!

---

*Built with ❤️ for AI art creators. 好的提示词，是画龙点睛的关键。*
