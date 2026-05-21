[English](README.md) | [한국어](README.ko.md) | [日本語](README.ja.md) | [中文](README.zh.md)

# oc-skill-audit

OpenClaw AgentSkillの多次元品質スコアリング。

## インストール

```bash
openclaw skills install oc-skill-audit
```

## 特徴

- **6つの評価ディメンション**: 構造、トリガー、Style Guide、ワークフロー、Sub-Agent設計、簡潔性
- **N/A ウェイト再配分**: 全ディメンションが不要なスキルにも公平なスコアリング
- **バイリンガルレポート**: ユーザー言語 + 英語で結果を提供
- **タイムスタンプ履歴**: 以前の結果を上書きせずに再監査可能
- **多言語ルーブリック**: EN/KO/JA/ZH

## クイックスタート

```bash
# 特定のスキルを監査
openclaw skills install oc-skill-audit
"summarize スキルを監査して"

# 複数のスキルを監査
"skills/ フォルダの全スキルを監査して"
```

## 評価ディメンション

| ディメンション | ウェイト | 評価内容 |
|---------------|---------|---------|
| A. 構造 | 20% | フロントマター、ファイルレイアウト、命名規則 |
| B. トリガー | 15% | 説明品質、キーワード |
| C. Style Guide | 20% | 保存/圧縮基準 |
| D. ワークフロー | 15% | Phase 0、バリデーション、エラー処理 |
| E. Sub-Agent設計 | 15% | テンプレート、コンテキスト注入 |
| F. 簡潔性 | 15% | 長さ、重複、エージェントスマートな記述 |

## リンク

- **ClawHub**: https://clawhub.ai/haseo-ai/oc-skill-audit
- **GitHub**: https://github.com/haseo-ai/skill-audit
- **ライセンス**: MIT-0
