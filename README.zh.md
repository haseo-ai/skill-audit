# oc-skill-audit

OpenClaw AgentSkill 多维度质量评分。

## 安装

```bash
openclaw skills install oc-skill-audit
```

## 特色

- **6个评分维度**：结构、触发、Style Guide、工作流、Sub-Agent 设计、简洁性
- **N/A 权重再分配**：对不需要所有维度的技能也公平评分
- **双语报告**：以用户语言 + 英语提供结果
- **时间戳历史**：重新审计时不覆盖之前的结果
- **多语言评分标准**：EN/KO/JA/ZH

## 快速开始

```bash
# 审计特定技能
openclaw skills install oc-skill-audit
"审计 summarize 技能"

# 审计多个技能
"审计 skills/ 文件夹中的所有技能"
```

## 评分维度

| 维度 | 权重 | 评估内容 |
|------|------|---------|
| A. 结构 | 20% | 前置元数据、文件布局、命名规范 |
| B. 触发 | 15% | 描述质量、关键词 |
| C. Style Guide | 20% | 保留/压缩标准 |
| D. 工作流 | 15% | Phase 0、验证、错误处理 |
| E. Sub-Agent 设计 | 15% | 模板、上下文注入 |
| F. 简洁性 | 15% | 长度、冗余、智能代理写作 |

## 链接

- **ClawHub**: https://clawhub.ai/haseo-ai/oc-skill-audit
- **GitHub**: https://github.com/haseo-ai/skill-audit
- **许可证**: MIT-0
