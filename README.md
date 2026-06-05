# 儿科学 Pediatrics-PMPH-10edition
<div align="center">

> *「21世纪医学生指南」*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>
> 基于人民卫生出版社《儿科学》第10版的临床技能手册 — 184 项儿科核心临床技能
<br>
<br>
<img src="/assets/Pediatrics.png" width="260px">
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

**⚠️风险⚠️**：该技能涵盖儿科诊断、剂量、急诊治疗、疫苗接种安排以及面向照护者的护理主题，这些内容可能被误用为独立的医疗建议。

缓解措施：仅将输出作为教育或临床医生审核的参考资料使用，并根据当前官方指南、本地方案和合格儿科专家核实建议。

**⚠️风险⚠️**：源内容并不始终严格执行仅限临床医生的安全界限。

缓解措施：部署系统级医疗安全政策，要求升级至合格临床医生进行诊断、开具处方、剂量分配、急诊护理及自我治疗决策。


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
Install the skill "Pediatrics-PMPH-10edition" (xllgreen/pediatrics-pmph-10edition) from ClawHub only after those checks pass.
Skill page: https://clawhub.ai/xllgreen/pediatrics-pmph-10edition
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

### 提问策略

#### 1.**概念** 
Question:
```bash
法洛四联症的概念
```
Answer：
```bash
## 《儿科学》法洛四联症（Tetralogy of Fallot, TOF）
法洛四联症是**最常见的青紫型先天性心脏病**，占儿童先心病的约 10%。
### 四大畸形
| 序号 | 畸形 | 作用 |
|------|------|------|
| ① | **室间隔缺损（VSD）** | **非限制性**缺损，左右心室压力基本相等 |
| ② | **右心室流出道梗阻（肺动脉狭窄）** | **病情严重程度的核心决定因素** |
| ③ | **主动脉骑跨** | 骑跨于两心室之上，直接接收右室静脉血 |
| ④ | **右心室肥厚** | 继发于肺动脉狭窄的代偿性改变 |
### 青紫机制（核心考点）
肺动脉狭窄严重 → 肺循环血流↓↓
                 ↘
右室压力↑ → VSD处右向左分流 ↑
                ↘
主动脉骑跨直接接收右室静脉血 → 输送到全身 → 青紫

**分流方向完全取决于肺动脉狭窄程度：**
- **狭窄轻** → 左向右分流为主 → 可无明显青紫
- **狭窄重** → 右向左分流为主 → 明显青紫
### 动脉导管状态对青紫的影响
| 状态 | 对青紫的影响 |
|------|-------------|
| **出生后动脉导管未闭** | 部分血液经导管入肺 → 青紫可不明显（"潜伏性青紫"） |
| **动脉导管关闭后** | 肺血流进一步减少 + 漏斗部狭窄逐渐加重 → **青紫日益明显** |
这也是为什么有些患儿出生时不紫，几个月后才逐渐发绀的原因。
### 长期缺氧的后果
持续青紫 **> 6 个月** 可导致：
- **杵状指/趾**
- 骨髓代偿性**红细胞增多** → 血液黏稠度↑ → 易发**脑血栓**或**细菌性脑脓肿**
### 与外科角度的补充
儿科学更强调**病理生理动态演变**（出生后随导管关闭+漏斗部狭窄加重，青紫呈**进行性**），而成人外科更侧重解剖修复方案。
> **一句话总结儿科学核心：** 法洛四联症 = 非限制性 VSD + **严重的肺动脉狭窄**使右向左分流 → 主动脉骑跨接收混合血 → 全身青紫。**狭窄程度 + 动脉导管状态**共同决定青紫出现的时间与严重程度。
```

#### 2.**临床案例分析** 
Question:
```bash
男孩，2岁，因呕吐频繁、水样便3天伴发热，于10月底入院，12小时无尿，查体：T38℃，颜面苍白，皮肤弹性极差，眼窝凹陷，心肺听诊无异常，腹稍胀，肝脾无肿大，跟腱反射未引出，四肢末梢微冷，实验室检查：血钠138mmol/L。最可能的诊断是
```
Answer：
```bash
## 病例分析
| 项目 | 表现 |
|------|------|
| 年龄 | 2岁（轮状病毒高发年龄） |
| 季节 | **10月底**（秋季腹泻高峰期） |
| 症状 | 呕吐 + 水样便 + 发热 |
| 脱水程度 | **重度**（12小时无尿、皮肤弹性极差、眼窝凹陷、四肢冷） |
| 血钠 | **138 mmol/L**（正常范围） |
| 神经体征 | 跟腱反射未引出 |
### 最可能的诊断
**轮状病毒肠炎（秋季腹泻）**
**重型**
**合并重度等渗性脱水**
**伴低钾血症**
**诊断依据：**
1. **流行病学**：10月底（秋冬季） + 2岁婴幼儿 = 轮状病毒肠炎典型画像
2. **临床表现**：先吐后泻，水样便/蛋花汤样便，伴发热
3. **脱水性质**：血钠 138 → **等渗性脱水**
4. **脱水程度**：12小时无尿 + 皮肤弹性极差 + 四肢冷 → **重度脱水**
5. **跟腱反射未引出** → 提示**低钾血症**（严重吐泻丢钾，导致神经肌肉兴奋性↓）
6. **重型判断**：满足频繁呕吐、水样便、发热、脱水、电解质紊乱 → 符合重型腹泻
### 需要紧急处理
1. **补液**：重度等渗性脱水 → **静脉快速扩容**（2:1 等张含钠液 20ml/kg，30–60分钟）
2. **补钾**：见尿补钾，纠正低钾血症
3. **继续补液**：累积损失量 + 继续损失量 + 生理需要量
4. **对症**：补锌、蒙脱石散、肠道微生态制剂
5. **抗病毒**：轮状病毒无特效抗病毒药，对症支持为主
> ⚠️ **鉴别注意：** 跟腱反射消失是低钾的提示线索（但血钠正常可排除高/低渗性脱水）。如血钾检测确认后可诊断低钾血症。
```
#### 3.**考试题目**
Question:
```bash
蛋白质-热能营养不良常见并发的维生素缺乏是（　）。
A.维生素E
B.维生素B1
C.维生素A1
D.维生素C
E.维生素D
```
Answer：
```bash
**答案：C. 维生素A₁**
**依据：**
蛋白质-热能营养不良（PEM，包括 Kwashiorkor 和 Marasmus）患儿最常见的维生素缺乏就是 **维生素A缺乏**。
**临床相关性：**
- 维生素A（视黄醇）的转运需要 **视黄醇结合蛋白（RBP）** 参与合成
- PEM 时肝脏合成 RBP 减少 → 维生素A的转运和释放受阻 → 尽管肝储备可能正常，但**血浆维生素A水平显著降低**
- 可导致 **夜盲 → 干眼症 → Bitot斑 → 角膜软化/溃疡**（严重可致盲）
- 同时免疫功能↓ → 感染风险↑ → 形成恶性循环
**其他选项为什么不对：**
| 选项 | 说明 |
|------|------|
| A. 维生素E | 缺乏少见，且临床表现不特异 |
| B. 维生素B₁ | 脚气病，与精白米饮食相关，非PEM特有 |
| D. 维生素C | 坏血病，非PEM典型并发 |
| E. 维生素D | 佝偻病，虽在营养不良儿中可见，但病因是日照不足/VD摄入少，非PEM特有 |
> 临床上对中重度营养不良患儿常规**补充维生素A**（一次性大剂量口服）就是基于这个原因。
```

**其他示例：**
- "请制定一名出生4小时、血糖1.8 mmol/L的足月儿处理方案。"
- "依据「儿童肾病综合征诊断与分型」技能，分析一名5岁男孩大量蛋白尿、低白蛋白血症、水肿的诊断步骤。"
- "参考「国家免疫规划疫苗应用」和「12月龄内婴儿强制疫苗清单」，为一名2月龄健康婴儿制定0–12月龄全程免疫计划。"

## 关于作者

**小绿绿 xllgreen(https://xllgreen.github.io)** — 九江学院临床医学院学生·科技极客

## 技术支持
<br>
PDF2App项目：https://pdf2app.cn
<br>
Microsoft Visual Studio Code：https://code.visualstudio.com/
<br>
Claude Code for VS Code：https://claude.com/
© 2026 Anthropic PBC
<br>
<br>
<img src="https://cdn.deepseek.com/logo.png?x-image-process=image%2Fresize%2Cw_1920" width="130px">
<br>DeepSeek API：https://platform.deepseek.com/
© 2026 杭州深度求索人工智能基础技术研究有限公司 版权所有
<br>
<br>
<img src="https://cdn.cnbj1.fds.api.mi-img.com/aife/mimo-blog-fe/doc_build/static/image/logo.99baaffe.png" width="130px">
<br>Xiaomi Mimo API：https://platform.xiaomimimo.com/
Copyright © 2010 - 2026 Xiaomi. All Rights Reserved
<br>

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
