# academic-pre-review-committee

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE.md)
[![Agent Skill](https://img.shields.io/badge/Agent%20Skill-SKILL.md-blue.svg)](SKILL.md)
[![Peer Review](https://img.shields.io/badge/peer-review-committee-brightgreen.svg)](SKILL.md)
[![Academic](https://img.shields.io/badge/academic-publishing-2ea44f.svg)](SKILL.md)

SynomosAI 四支柱体系：**身份（Identity）· 溯源（Traceability）· 治理（Governance）· 共生（Symbiosis）**——当 AI 进入商业，可信是唯一的硬通货。

> 本仓库属于 [SynomosAI](https://github.com/SynomosAI) 生态技能包的一员。生态全景见 [`synomosai-skills`](https://github.com/SynomosAI/synomosai-skills)，理论站位见 [`traceability-audit`](https://github.com/SynomosAI/traceability-audit)。

**关键词 / Keywords**：学术论文预审 · 同行评审 · 多审稿人 · desk reject · peer review · academic publishing · pre-screening

## 🚀 快速开始 / Quick Start

本仓是一个 **Agent Skill 发布包**（遵循 SKILL.md 规范），不是可运行的 SDK。

```bash
# 1. 克隆本仓
git clone https://github.com/SynomosAI/academic-pre-review-committee.git
cd academic-pre-review-committee

# 2. 查看技能主文件（五位审稿人角色 / 预审流程 / 评分维度）
cat SKILL.md
```

```bash
# 3. 查看技能元信息
head -15 SKILL.md

# 4. 把技能目录放入你的 Agent 技能目录
#    cp -r . ~/.workbuddy/skills/academic-pre-review-committee/
```

## 仓库内容

学术预审委员会

本技能模拟一份期刊投稿前的**多审稿人预审委员会**，由五位角色组成：理论贡献审稿人（是否有新理论视角）、方法论审稿人（方法是否严谨可复现）、文献对话审稿人（是否与现有文献有效对话）、逻辑链条审稿人（论证是否自洽）、主编预筛（整体匹配度、desk reject 判定）。每位审稿人独立给出评分与建议，最终汇总为预审结论（建议接收 / 大修 / 小修 / desk reject）。

## 元信息

- **技能名**：`academic-pre-review-committee`
- **版本**：1.0.0
- **署名**：SynomosAI
- **许可**：MIT（详见仓库 LICENSE）

## 使用方式

1. 克隆本仓库或将该技能目录放入你的 Agent 技能目录（如 `~/.workbuddy/skills/`）；
2. 在 Agent 中按 `SKILL.md` 的描述触发对应能力；
3. 需要审计/合规证据的场景，参考 `SKILL.md` 内模板产出工件。

## 五位审稿人角色概览

```text
1. 理论贡献审稿人   → 是否提出新理论视角 / 概念框架
2. 方法论审稿人     → 方法严谨性 / 可复现性 / 数据合理性
3. 文献对话审稿人   → 是否与现有文献有效对话 / 定位清晰
4. 逻辑链条审稿人   → 论证自洽 / 前提-结论一致 / 无跳跃
5. 主编预筛        → 整体匹配度 / desk reject 判定
```

## 仓库结构 / Repository layout

```text
academic-pre-review-committee/
├── README.md              # 本文件
├── README.en.md           # 英文版说明
├── SKILL.md               # 技能主文件（审稿人角色 / 预审流程 / 评分维度）
├── LICENSE.md             # MIT License
├── llms.txt               # 给 AI 的最小索引
├── llms-full.txt          # 给 AI 的完整文本
├── AGENTS.md              # 给 AI Agent 的工作指引
├── SECURITY.md            # 安全策略
└── .github/CODEOWNERS      # 代码所有者
```

## License / 许可

本项目以 **MIT** 许可发布，详见仓库根目录 [LICENSE.md](LICENSE.md)。版权：© 2026 注册老炮@MedXpert。

---

## 免责声明

本仓库内容为 SynomosAI 的**理论站位与工具化探索**，不代表任何已获认证、已商业化交付或已服务特定客户的声明；文中涉及的学术出版规范与评审标准信息为公开资料转述，正式引用前请**独立核实**。API、授权码与形象大使等为路线图（roadmap）事项，尚未上线。
