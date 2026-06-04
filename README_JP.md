# 小児科学 Pediatrics-PMPH-10edition
<div align="center">

> *「21世紀 医学生ガイド」*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>
> 人民衛生出版社『小児科学』第10版に基づく臨床スキルハンドブック — 184 の小児科核心臨床スキル
<br>
<br>

教科書を丸ごと読む必要はありません<br>
質問を入力するだけで、教科書から解決策を即座に見つけられます

<br>

**他の言語 / Other Languages:**

[中文](README.md) · [English](README_EN.md) · [Français](README_FR.md) · [Русский](README_RU.md)

</div>

---

## プロジェクト概要

本プロジェクトは、小児科学、新生児医学、小児の発育と栄養、感染症対策、遺伝代謝疾患の診療、救急・集中治療などの中核領域を体系的に統合し、**184 の重要臨床スキル**を **15 カテゴリ**に分類して収録しています。

**対象読者**：小児科医、医学生、公衆衛生従事者、新生児医療チーム

**参考教科書**：人民衛生出版社『小児科学』第 10 版

## プロジェクト構造

```
Pediatrics-PMPH-10edition/
├── SKILL.md              # 核心設定 — 184 スキルレジストリ
├── README.md             # 本ドキュメント — プロジェクト概要と使用ガイド
├── <skill-name>/         # 各スキルの詳細定義
│   └── SKILL.md          #   スキル詳細（使用タイミング、手順、参考資料）
├── scripts/              # 実行可能スクリプト
├── config/               # 設定ファイル
└── tests/                # 検証とテスト
```

## スキルカテゴリ一覧

| カテゴリ | スキル数 | 説明 |
|----------|----------|------|
| 👶 新生医学・周産期医学 | 18 | 黄疸、RDS、溶血、出血、NEC、ROP、BPD |
| 📏 発育・発達と栄養 | 18 | 体格評価、離乳食、睡眠、微量栄養素 |
| 💉 予防接種と感染症対策 | 20 | 予防接種スケジュール、麻疹、手足口病、結核、川崎病 |
| 🫁 呼吸器疾患 | 12 | 肺炎、喘息、マイコプラズマ、気管支鏡、血液ガス分析 |
| ❤️ 心血管疾患 | 10 | 先天性心疾患分類、心不全、心筋炎、Duke基準 |
| 🫃 消化器・肝胆道疾患 | 12 | 腸重積、ヒルシュスプルング病、IBD、胆道閉鎖、GERD |
| 🫘 泌尿器・腎疾患 | 10 | 血尿、腎炎、ネフローゼ症候群、AKI、RTA |
| ⚖️ 内分泌・代謝疾患 | 13 | GHD、思春期早発症、甲状腺機能低下症、糖尿病、DKA |
| 🩸 血液・腫瘍疾患 | 9 | ITP、AIHA、血友病、サラセミア、LCH |
| 🧠 神経・精神行動障害 | 12 | てんかん、熱性けいれん、ADHD、GBS、重症筋無力症 |
| 🚑 救急・集中治療 | 10 | CPR、外傷、溺水、呼吸不全、脱水 |
| 🧬 遺伝・先天疾患 | 7 | 三段階予防、遺伝病分類、CHARGE、DMD/BMD |
| 🔬 検査・画像診断 | 11 | 髄液、PKU、CAH、くる病、MRI、超音波 |
| 📚 教科書・根拠に基づく医療 | 7 | 教科書権威性評価、改訂原則、文献紹介 |
| 🏋️ 総合的健康管理 | 9 | 運動、食事、免疫系、薬剤用量、身体診察 |

## クイックスタート

### インストール

CLI：
```bash
openclaw skills install pediatrics-pmph-10edition
```

### 使用方法

各スキルは以下の4つのセクションで構成されています：
1. **使用タイミング** — このスキルを適用する臨床状況
2. **実行手順** — 標準化された操作フロー
3. **注意事項** — 禁忌と警告
4. **参考文献** — 補足資料

**使用例：**
- 「『新生児低血糖の診断と層別治療』スキルに基づき、出生4時間、血糖値1.8 mmol/Lの正期産児の管理計画を立案してください。」
- 「『ネフローゼ症候群の診断と分類』スキルを用いて、大量蛋白尿、低アルブミン血症、浮腫を呈する5歳男児の診断手順を分析してください。」
- 「『国家予防接種計画』と『12ヶ月未満の必須ワクチン』スキルを参照し、生後2ヶ月の健康な乳児のための0–12ヶ月完全予防接種計画を立ててください。」

## ライセンス

本プロジェクトの内容は人民衛生出版社『小児科学』第10版に基づいて整理されており、学習参考のみを目的としています。

## Star History

<a href="https://www.star-history.com/#">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=&type=date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=&type=date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=&type=date" />
 </picture>
</a>
