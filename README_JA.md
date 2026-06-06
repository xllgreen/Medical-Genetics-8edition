# 医学遺伝学 Medical-Genetics-8edition

<div align="center">

> *「21世紀の医学生ガイド」*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>
> 『医学遺伝学』第8版に基づく臨床遺伝スキルハンドブック — 131 の医学遺伝学コア臨床スキル
<br>
<br>
<img src="/assets/Medical-Genetics-8edition.png" width="260px">
<br>

一冊の本を全部読む必要はありません<br>
質問を入力するだけで、教科書が自動的に解決策を見つけます

<br>

**他の言語 / Other Languages:**

[中文](README.md) · [English](README_EN.md) · [日本語](README_JA.md) · [Français](README_FR.md) · [Русский](README_RU.md)

</div>

---

## プロジェクト概要

本项目は、医学遺伝学、ゲノミクス、代謝疾患、出生前診断、遺伝子治療、エピジェネティック制御などの中核領域を系統的に統合し、**131 の必須臨床スキル**を網羅しています。

**対象読者**: 臨床遺伝専門医、医学生、遺伝カウンセラー、精密医療研究者、出生前診断医療チーム

**参考教科書**: 『医学遺伝学』第8版

**⚠️ リスク ⚠️**: 本スキルセットは、臨床、生殖、法医学、または遺伝子治療に関する影響力の高い指針を生成する可能性があります。専門的助言としてのみ使用する場合、リスクが生じる可能性があります。
**緩和策**: 出力はすべて教育目的または臨床医のレビューのためだけに使用してください。診断、治療、妊娠、法医学分析、親子鑑定、遺伝子検査、または遺伝子治療の決定を行う前に、適切な医学的、遺伝学的、または法的な監督が行われていることを確認してください。
**⚠️ リスク ⚠️**: 遺伝学のケース分析には、機密性の高い個人または家族の健康情報が含まれる場合があります。
**緩和策**: 特定可能な遺伝的、生殖的、または家族歴情報を共有または処理する前に、適切な同意、プライバシー、および地域の契約管理を適用する必要があります。

## プロジェクト構造

```
Medical-Genetics-8edition/
├── SKILL.md              # コア設定 — 131スキルレジストリ
├── README.md             # 本ドキュメント — プロジェクト説明と使用ガイド
├── index.md              # スキル完全インデックス
├── <skill-name>/         # 各スキルの詳細定義
│   └── SKILL.md          #   スキル詳細（使用タイミング、手順、注意事項）
└── assets/               # 画像リソース
```

## スキルカテゴリー一覧

| カテゴリー | スキル数 | 説明 |
|----------|---------|------|
| 🧬 遺伝病の分類とメカニズム解析 | 14 | 五分類法、酵素欠損症、コラーゲン病、鎌状赤血球症など |
| 🔬 染色体・ゲノム構造変異 | 16 | 核型記述、G分染、欠失/転座/逆位、多型、GT-AGルールなど |
| 📊 遺伝形式と家系分析 | 10 | AD/AR/XR 家系分析、Lyon仮説、Knudsonの2回打撃説、SRY遺伝子など |
| 🤰 出生前スクリーニングと診断技術 | 6 | NIPT、超音波スクリーニング、PGD、侵襲的/非侵襲的経路選択など |
| ⚕️ 染色体異常と生殖リスク評価 | 12 | 相互転座、ロバートソン転座、腕間/腕内逆位、モザイクなど |
| 🔋 ミトコンドリア遺伝と疾患 | 11 | mtDNA転写翻訳、母系遺伝、閾値効果、生化学的/臨床的/遺伝学的三分類 |
| 🧮 複雑疾患と多遺伝子リスク | 10 | Hardy-Weinberg平衡、ベイズ更新、多遺伝子病症例再発リスクなど |
| 💉 遺伝子治療と分子介入 | 8 | 遺伝子修復/増強、ウイルスベクター選択、CRISPR安全性評価、遺伝子不活性化 |
| 🧫 腫瘍遺伝学とエピジェネティック制御 | 9 | 癌抑制遺伝子、癌原遺伝子、Knudson理論、ヒストン修飾、DNAメチル化 |
| 📡 非コードRNAとバイオマーカー | 3 | miRNA、lncRNA、circRNA心血管バイオマーカー |
| 🏥 特定遺伝病の診断と治療 | 11 | サラセミア、PKU、ポンペ病、テイ・サックス病、白皮症、血友病Aなど |
| ⚖️ システム医学と倫理的応用 | 8 | システム医学、1000ゲノム計画、近親婚、倫理評価、催奇形物質曝露 |
| 🛡️ DNA修復と安定性 | 3 | DNA損傷修復、脆弱部位、NMDナンセンス変異依存分解 |

## クイックスタート

### インストール

CLI:
```bash
openclaw skills install medical-genetics-8edition
```

プロンプト:
```bash
インストール前に、ClawHubのスキルメタデータとセットアップ要件を確認してください。
サードパーティのパッケージやCLIのインストールを求められた場合は、インストールコマンドを実行する前に、そのソース、メンテナー、パッケージ内容を確認してください。
それらの確認が完了した後にのみ、ClawHubからスキル「Medical Genetics 8edition」(xllgreen/medical-genetics-8edition) をインストールしてください。
スキルページ: https://clawhub.ai/xllgreen/medical-genetics-8edition
作業はこのスキルにのみ限定してください。
インストール後、確認済みのスキルメタデータに基づいてセットアップを完了するのを手伝ってください。
ClawHubから確認できるメタデータのみを使用し、要件を独自に作成しないでください。
より広範な環境変更を行う前には質問してください。
```

### 使用方法

各スキルは3つの部分で構成されています：
1. **使用タイミング** — スキルを発動する条件
2. **実行手順** — 標準化された操作フロー
3. **注意事項** — 禁忌と警告

### 質問戦略

#### 1. 概念理解
質問:
```bash
Hardy-Weinberg平衡の法則とは何ですか？
```
回答:
```bash
## Hardy-Weinberg平衡

Hardy-Weinberg平衡は集団遺伝学の基本原理であり、理想的な条件下（ランダム交配、突然変異なし、選択なし、移動なし、無限大の集団サイズ）では、対立遺伝子頻度と遺伝子型頻度が世代を超えて一定に保たれることを説明しています。

### 基本公式
常染色体上の2対立遺伝子（Aとa）の場合：
- p = Aの頻度、q = aの頻度
- p + q = 1
- 遺伝子型頻度：p²(AA) + 2pq(Aa) + q²(aa) = 1

### 臨床応用
- **保因者頻度推定**: AR疾患で発症率q²が既知の場合、保因者頻度2pq ≈ 2q
- **品質管理**: 遺伝子型データがHWEに適合するかどうかを検証
- **集団層別化検出**: HWEからの逸脱は、集団層別化や選択圧の存在を示唆する可能性がある
```

#### 2. 臨床ケース分析
質問:
```bash
表現型が正常な夫婦に、常染色体劣性遺伝病の患儿がすでに一人います。次の子どもにおける再発リスクはどのくらいですか？もし二人の正常な子どもがすでにいる場合、リスクはどのように変化しますか？
```
回答:
```bash
## 遺伝カウンセリング分析

### 基本情報
- 両親とも表現型正常 → 両者とも**保因者**（Aa × Aa）
- すでに一人の患儿あり → 遺伝形式確認済み

### 再発リスク評価

| 状況 | 再発リスク | 説明 |
|------|-----------|------|
| 妊娠あたりの基礎リスク | 25%（1/4） | メンデル比 |
| 患儿が一人いる場合 | 25%（1/4） | 独立事象、妊娠ごとのリスクは不変 |
| 正常な子どもが二人いる場合 | 25%（1/4） | 独立事象、後のリスクに影響なし |
| ベイズ更新後の個別リスク | 低下 | これは「夫婦が保因者である確率」の修正 |

### 重要なカウンセリングポイント
1. **各妊娠は独立**: 前回の結果は後のリスクに影響しない
2. **保因者確認**: 両親への遺伝子検査を推奨
3. **出生前診断**: 次回妊娠時に出生前遺伝子診断が可能
4. **着床前遺伝子診断（PGD）** : 選択可能な選択肢

> ⚠️ 「正常児出産歴による保因者確率の修正」（ベイズ）と「妊娠ごとの再発リスク」（独立事象）は異なる概念であることに注意。
```

#### 3. 試験問題
質問:
```bash
ダウン症候群で最も一般的な核型はどれか。
A. 47,XX,+21
B. 46,XX,der(14;21)(q10;q10),+21
C. 47,XX,+21/46,XX
D. 46,XX,inv(21)
```
回答:
```bash
**解答: A. 47,XX,+21**

**根拠:**
- **遊離型（標準型）** : 47,XX,+21 または 47,XY,+21 — ダウン症候群の **92-95%** を占める
- **転座型**: 例：46,XX,der(14;21)(q10;q10),+21 — **2-4%** を占める
- **モザイク型**: 例：47,XX,+21/46,XX — **2-3%** を占める

**臨床ポイント:**
| 核型タイプ | 割合 | 再発リスク |
|-----------|------|-----------|
| 遊離型 | 92-95% | 母体年齢と相関 |
| 転座型 | 2-4% | 保因者親と相関（母親が均衡転座保因者の場合、リスク約10-15%） |
| モザイク型 | 2-3% | 異常細胞の割合に依存、再発リスクは一般的に低い |

> 注：遊離型がダウン症候群の最も一般的な核型であり、母体年齢と正の相関を示す。
```

## 著者について

**小緑緑 (xllgreen)** (https://xllgreen.github.io) — 九江学院臨床医学院学生・テクノロジー愛好家

## 技術サポート
<br>
PDF2App: https://pdf2app.cn
<br>
Microsoft Visual Studio Code: https://code.visualstudio.com/
<br>
Claude Code for VS Code: https://claude.com/
© 2026 Anthropic PBC
<br>
<br>
<img src="https://cdn.deepseek.com/logo.png?x-image-process=image%2Fresize%2Cw_1920" width="130px">
<br>DeepSeek API: https://platform.deepseek.com/
© 2026 杭州深度求索人工智能基礎技術研究有限公司 All Rights Reserved
<br>
<br>
<img src="https://cdn.cnbj1.fds.api.mi-img.com/aife/mimo-blog-fe/doc_build/static/image/logo.99baaffe.png" width="130px">
<br>Xiaomi Mimo API: https://platform.xiaomimimo.com/
Copyright © 2010 - 2026 Xiaomi. All Rights Reserved
<br>

## Star History

<a href="https://www.star-history.com/?repos=xllgreen%2FMedical-Genetics-8edition&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=xllgreen/Medical-Genetics-8edition&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=xllgreen/Medical-Genetics-8edition&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=xllgreen/Medical-Genetics-8edition&type=date&legend=top-left" />
 </picture>
</a>
