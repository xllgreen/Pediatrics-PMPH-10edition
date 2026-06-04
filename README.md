# 儿科学 Pediatrics-PMPH-10edition
<div align="center">

> *「21世纪医学生指南」*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>
> 基于人民卫生出版社《儿科学》第10版的临床技能手册 — 184 项儿科核心临床技能
<br>
<img src="https://github.com/xllgreen/Surgery-PMPH-10edition-/blob/main/assets/Pediatrics.png" width="260px">
<br>

何必苦苦读一本书<br>
只需输入一个问题，自动从课本中找到解决方案

<br>

**其他语言 / Other Languages:**

[English](README_EN.md) · [日本語](README_JP.md) · [Français](README_FR.md) · [Русский](README_RU.md)

</div>

---

## 项目简介

本项目系统整合儿科学、新生儿医学、儿童生长发育、感染性疾病防控、遗传代谢病诊疗及急重症抢救等核心领域，涵盖 **184 项关键临床技能**，分为 15 大分类。

**适用人群**：儿科医师、医学生、公共卫生工作者、新生儿科医护团队

**参考教材**：人民卫生出版社《儿科学》第 10 版

## 项目结构

```
Pediatrics-PMPH-10edition/
├── SKILL.md              # 核心配置 — 184 项技能注册表
├── README.md             # 本文档 — 项目说明与使用指南
├── <skill-name>/         # 各项技能的详细定义
│   └── SKILL.md          #   技能详情（使用时机、执行步骤、参考文档）
├── scripts/              # 可执行工具脚本
├── config/               # 配置文件
└── tests/                # 验证与测试
```

## 技能分类一览

| 分类 | 技能数 | 说明 |
|------|--------|------|
| 👶 新生儿与围产期医学 | 18 | 黄疸、RDS、溶血、出血、NEC、ROP、BPD 等 |
| 📏 生长发育与营养 | 18 | 体格生长评价、辅食、睡眠、微量营养素等 |
| 💉 免疫接种与传染病防控 | 20 | 计划免疫、麻疹、手足口、结核、川崎病等 |
| 🫁 呼吸系统疾病 | 12 | 肺炎、哮喘、支原体、支气管镜、血气分析等 |
| ❤️ 心血管系统疾病 | 10 | 先心病分类、心衰、心肌炎、Duke 标准等 |
| 🫃 消化与肝胆系统疾病 | 12 | 肠套叠、巨结肠、IBD、胆道闭锁、GERD 等 |
| 🫘 泌尿与肾脏疾病 | 10 | 血尿、肾炎、肾病综合征、AKI、RTA 等 |
| ⚖️ 内分泌与代谢疾病 | 13 | GHD、性早熟、甲减、糖尿病、DKA 等 |
| 🩸 血液与肿瘤疾病 | 9 | ITP、AIHA、血友病、地贫、LCH 等 |
| 🧠 神经与精神行为疾病 | 12 | 癫痫、热性惊厥、ADHD、GBS、重症肌无力等 |
| 🚑 急诊与重症抢救 | 10 | CPR、创伤、溺水、呼吸衰竭、脱水等 |
| 🧬 遗传与先天性疾病 | 7 | 三级预防、遗传病分类、CHARGE、DMD/BMD 等 |
| 🔬 实验室与辅助检查 | 11 | CSF、PKU、CAH、佝偻病、MRI、超声等 |
| 📚 教材与循证医学 | 7 | 教材权威性评估、修订原则、文献推荐等 |
| 🏋️ 综合健康管理 | 9 | 运动、膳食、免疫系统、药物剂量、体格检查等 |

## 快速开始

### 安装

CLI：
```bash
openclaw skills install pediatrics-pmph-10edition
```

Prompt：
```bash
Before installing anything, inspect the ClawHub skill metadata and setup requirements.
If the skill asks you to install a third-party package or CLI, verify its source, maintainer, and package contents before running the install command.
Install the skill "Pediatrics-PMPH-10edition" from ClawHub only after those checks pass.
Keep the work scoped to this skill only.
After install, help me finish setup from verified skill metadata.
Use only the metadata you can verify from ClawHub; do not invent missing requirements.
Ask before making any broader environment changes.
```

### 使用方式

每个技能包含四部分内容：
1. **使用时机** — 何时触发该技能
2. **执行步骤** — 标准化操作流程
3. **注意事项** — 禁忌与警示
4. **参考文档** — 详细补充资料

**示例：**
- "请根据「新生儿低血糖诊断与分层治疗」技能，制定一名出生4小时、血糖1.8 mmol/L的足月儿处理方案。"
- "依据「儿童肾病综合征诊断与分型」技能，分析一名5岁男孩大量蛋白尿、低白蛋白血症、水肿的诊断步骤。"
- "参考「国家免疫规划疫苗应用」和「12月龄内婴儿强制疫苗清单」，为一名2月龄健康婴儿制定0–12月龄全程免疫计划。"

## 关于作者

**小绿绿 xllgreen(https://xllgreen.github.io)** — 九江学院临床医学院学生·科技极客

## 许可证

本项目内容基于人民卫生出版社《儿科学》第10版整理，仅供学习参考。

## Star History

<a href="https://www.star-history.com/?repos=xllgreen%2FPediatrics-PMPH-10edition&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=xllgreen/Pediatrics-PMPH-10edition&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=xllgreen/Pediatrics-PMPH-10edition&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=xllgreen/Pediatrics-PMPH-10edition&type=date&legend=top-left" />
 </picture>
</a>
