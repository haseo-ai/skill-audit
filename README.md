[English](README.md) | [한국어](README.ko.md) | [日本語](README.ja.md) | [中文](README.zh.md)

# oc-skill-audit

Multi-dimensional quality scoring for OpenClaw AgentSkills.

## Install

```bash
openclaw skills install oc-skill-audit
```

## What Makes This Different

- **6 scoring dimensions**: Structure, Triggering, Style Guide, Workflow, Sub-Agent Design, Conciseness
- **N/A weight redistribution**: Fair scoring for skills that don't need all dimensions
- **Bilingual reports**: Results in user's language + English
- **Timestamped history**: Re-audit without overwriting previous results
- **Multilingual rubric**: EN/KO/JA/ZH

## Quick Start

```bash
# Audit a specific skill
openclaw skills install oc-skill-audit
"audit the summarize skill"

# Audit multiple skills
"audit all skills in skills/ folder"
```

## Scoring Dimensions

| Dimension | Weight | What it measures |
|-----------|--------|-----------------|
| A. Structure | 20% | Frontmatter, file layout, naming |
| B. Triggering | 15% | Description quality, keywords |
| C. Style Guide | 20% | Preservation/compression criteria |
| D. Workflow | 15% | Phase 0, validation, error handling |
| E. Sub-Agent Design | 15% | Templates, context injection |
| F. Conciseness | 15% | Length, redundancy, agent-smart writing |

## Links

- **ClawHub**: https://clawhub.ai/haseo-ai/oc-skill-audit
- **GitHub**: https://github.com/haseo-ai/skill-audit
- **License**: MIT-0
