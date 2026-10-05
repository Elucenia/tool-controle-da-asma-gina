<!-- ELUCENIA technical documentation · controle-da-asma-gina · ja · no clinical/professional/rights approval -->

# 喘息症状のコントロール（GINA）

[条件・出典・許諾](https://elucenia.org/ja/tools/controle-da-asma-gina)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 日中症状が週2回を超える

`diurno`

### 喘息による夜間覚醒

`noturno`

### 症状緩和薬（SABA）を週2回より多く使用

`alivio`

### 喘息による活動制限

`limit`

## 方法の版

GINA戦略2021：4週間の症状、4質問、頓用SABA、0/1～2/3～4

## 記載された計算式

過去4週間の該当項目数：日中症状\>週2回、喘息による夜間覚醒、頓用SABA\>週2回（運動前を除く）、活動制限。

0=良好 · 1～2=部分的 · 3～4=不十分。

## 限界・対象集団

ここで計算するGINA 2021の評価は、成人と5歳を超える小児における過去四週間の症状コントロールを対象とし、症状緩和薬の質問は短時間作用性β刺激薬（SABA）について尋ねています。この項目数では、将来の増悪リスク全体、肺機能、併存疾患、吸入手技、治療アドヒアランスを評価できません。症状コントロールと喘息の重症度は同義ではありません。資料の翻案には権利者の条件が引き続き適用されます。

## 参考文献

- [Reddel HK et al. Global Initiative for Asthma Strategy 2021: executive summary and rationale for key changes. Eur Respir J, 2022.](https://doi.org/10.1183/13993003.02730-2021)

- [Global Initiative for Asthma (GINA). Global Strategy for Asthma Management and Prevention (relatório anual).](https://ginasthma.org/reports/)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026
