<p align="center">
  <img src="https://img.shields.io/badge/potatoDesignSkill-v1.0.0-brightgreen?style=for-the-badge" alt="Version">
  <img src="https://img.shields.io/badge/UX%2FUI-design-blue?style=for-the-badge" alt="UX/UI Design">
  <img src="https://img.shields.io/badge/Codex-WorkBuddy-orange?style=for-the-badge" alt="Codex & WorkBuddy">
  <img src="https://img.shields.io/badge/%E4%B8%AD%E6%96%87-ok-green?style=for-the-badge" alt="中文">
</p>

<h1 align="center">🥔 potatoDesignSkill</h1>
<h3 align="center">动手写界面之前，先把"好用"想清楚</h3>

<p align="center">
  <strong>面向 Codex / WorkBuddy 的中文 UX/UI 设计专家：把"好看但难用"变成"一看就懂、一用就会"，输出的是开发 AI 能照着做的可执行设计规格。</strong>
</p>

---

## 💡 为什么需要 potatoDesignSkill？

小白用 AI 做产品，功能往往都做出来了，但用户一用就说"难用"。问题通常不在功能，而在界面：找不到入口、点了没反应、第一次打开一片空白。

**potatoDesignSkill 改变了这个流程。** 它把"好用"从凭感觉变成可执行的设计流程：

- **先定设计目标**：先问清给谁用、核心任务是什么，一句话说清"让谁在几分钟内完成什么事"，不猜用户
- **四状态必设计**：空状态、加载中、出错、成功——小白最容易漏的四个页面状态，全部要求写清楚
- **可用性逐项检查**：可发现性、反馈、心智模型、容错，每个核心流程过一遍，卡点变成"问题 → 最小修复"清单
- **视觉规范可落地**：主色不超过 5 个、正文对比度 ≥ 4.5:1、可点区域 ≥ 44px，全是能直接照做的数字

---

## 🎯 解决什么问题 / 使用场景

**适合谁**：和 AI 一起做产品、功能能做出来但界面"总差点意思"的人——尤其是刚接触产品设计的开发者和小白。

| 场景 | 怎么用 potatoDesignSkill |
|------|--------------------------|
| **新产品界面设计** | 告诉 AI"帮我设计 XX 的界面"，先访谈确认用户和核心任务，再输出主路径、页面清单和视觉规范 |
| **用户说"难用"** | 把现状描述给 AI，做可用性诊断，输出摩擦清单（问题 → 用户怎么卡住 → 最小修复） |
| **页面怎么排 / 配色方案** | 让 AI 按布局原则和色彩规范给出具体色值、字号、间距 |
| **开发前设计交接** | 每页给出"职责 + 元素顺序 + 关键规则 + 四状态"的可执行规格，开发 AI 照着做 |

**不适合**：写界面代码（用开发专家）、品牌营销与广告文案、数据库结构与算法设计。

---

## 🚀 快速开始

### 安装

把整个目录复制到 Skill 目录：

```bash
# Codex
cp -r potatoDesignSkill ~/.codex/skills/

# WorkBuddy
cp -r potatoDesignSkill ~/.workbuddy/skills/
```

### 使用提示词

```text
帮我设计一个宠物咖啡店预约小程序的界面，先确认用户和核心任务，再输出页面清单和视觉规范。
```

AI 会先确认"给谁用、核心任务是什么"，再按流程输出主路径、页面清单、视觉规范和摩擦检查清单。

### 验证提示词

```text
使用 $potatoDesignSkill 简单介绍你能帮我做什么，先不要开始设计。
```

---

## 🔒 隐私与安全

- **只基于你的描述工作**：需要参考竞品截图或设计时，只提炼设计意图，不复制其素材
- **示例均为虚构**：设计示例使用虚构品牌与场景，不使用真实企业的标志、字体、配色
- **原创方法论**：基于业界通用的设计方法（尼尔森可用性原则、认知负荷理论、Fitts 定律、格式塔原理、OKLCH 色彩等公共知识）独立编写，示例与图表均为原创

---

## 📚 更多

**Potato 系列全家桶（21 个）**：

| 层 | Skill |
|----|-------|
| 公共层 | potatoMemorySkill（记忆协议）、potatoPRDSkill（PRD 专家）、potatoAssistantSkill（陪跑助手）、potatoOrchestratorSkill（总调度） |
| 网页线 | potatoArchitectureSkill（架构设计）、potatoRequirementSkill（需求澄清）、potatoDesignSkill（UX/UI）、potatoWebSkill（网页开发）、potatoQASkill（测试验收）、potatoDatabaseSkill（数据建模）、potatoAuthSkill（登录认证）、potatoSecuritySkill（安全审计）、potatoPerformanceSkill（性能优化）、potatoPublishSkill（打包发布）、potatoOpsSkill（部署监控） |
| 小程序 | potatoMiniProgramSkill（开发）、potatoMiniProgramPublishSkill（上架教学） |
| App | potatoAppSkill（开发）、potatoAppPublishSkill（上架教学） |
| 桌面 | potatoDesktopSkill（开发）、potatoDesktopPublishSkill（发布教学） |

**License**: [MIT](LICENSE)

---

## English

**potatoDesignSkill** is a Chinese-language UX/UI design skill for Codex and WorkBuddy. It turns "make it usable" from a feeling into an executable process: define the design goal, map the page flow, set visual specs, and walk every core flow through usability checks (discoverability, feedback, mental models, error tolerance).

- **Four states always designed**: empty, loading, error, success — the states beginners most often miss
- **Executable specs for developers**: each page gets its purpose, element order, key rules, and states
- **Concrete visual rules**: ≤ 5 primary colors, body text contrast ≥ 4.5:1, tappable targets ≥ 44px
- **Friction checklist**: every blocker becomes "problem → user impact → minimal fix"

**Install**: `cp -r potatoDesignSkill ~/.codex/skills/` and `~/.workbuddy/skills/`

**Usage**: "帮我设计 XX 的界面" / "用户说难用，帮我看看". The skill interviews you first, then outputs a page list, visual spec, and a friction checklist.

**Privacy**: works only from your description; examples use fictional brands; methodology is based on public design knowledge (Nielsen heuristics, cognitive load, Fitts's law, Gestalt principles, OKLCH color).

**License**: MIT
