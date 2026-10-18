# AGENTS.md — 给 AI Agent 的工作指引

本文件面向自动化 AI Agent。人类读者请看 [README.md](README.md)。

## 这个仓库是什么

`academic-pre-review-committee` 是一个 **Agent Skill 发布包**，核心资产是 `SKILL.md`。把本目录放入 Agent 的技能目录即可获得「学术论文预审」能力。

## 可用的工作命令

```bash
head -15 SKILL.md
cat SKILL.md
```

## 约定（Do）

- 修改 `SKILL.md` 时保持 YAML frontmatter 字段兼容。
- 新增审稿人维度时同步更新评分表与汇总模板。

## 禁止（Don't）

- 不要改动 `LICENSE.md` 的版权主体（© 2026 注册老炮@MedXpert）。
- 不要在仓库内提交任何真实论文原文或作者隐私数据。

## 边界

本技能专注投稿前预审；不覆盖同行评审的正式发表流程。
