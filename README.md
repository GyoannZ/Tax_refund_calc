# 免税計算機（Tax Refund Calculator）

このプロジェクトは、日本で買い物をする観光客のために、商品の税込価格から免税対象額、手数料、最終的な支払額を自動で計算できるシンプルなウェブアプリです。  
This project is a simple web app that allows travelers in Japan to calculate tax-free amounts, handling fees, and the final payment based on the product's tax-included price.

GitHub Pages で公開されており、スマートフォンや PC のブラウザで簡単に利用できます。  
The app is published on GitHub Pages and is accessible via smartphones and PC browsers.

---

## 主な機能 / Features

- 金額入力タイプの選択：税込価格と税抜価格、どちらを基準に計算するかを選択可能
  Selectable Input Type: Choose whether to calculate based on the price with or without tax.

- 消費税率 10%・8%に対応  
  Supports 10% and 8% tax rates

- 手数料 1.55%を自動計算、1 円未満は切り捨て
  Automatically calculates a 1.55% handling fee with fractions rounded down.

- 実際の支払金額・免税金額を即時表示  
  Instantly displays the actual payment and refund amount

- 多言語対応（日本語、英語、中国語、韓国語、フランス語、タイ語、ロシア語、インドネシア語、繁体字中国語）  
  Multilingual support (Japanese, English, Chinese, Korean, French, Thai, Russian, Indonesian, Traditional Chinese)

- レスポンシブデザイン（スマホ対応）  
  Responsive design (mobile-friendly)

---

## デモページ / Demo Page

[計算機を開く / Try the Calculator](https://gyoannz.github.io/Tax_refund_calc/)

---

## 使用技術 / Technologies

- HTML / CSS / JavaScript
- 言語切り替え（簡易 i18n）  
  Simple language-switching logic (i18n)

---

## 利用方法 / How to Use

1. 金額の種類を選択：「税抜金額」または「税込金額」を選択します（デフォルトは「税抜金額」）。  
   Select Price Type: Choose "Price w/o Tax" or "Price w/ Tax" (defaults to "w/o Tax").
2. 金額を入力：対応する入力欄に商品の金額を入力します。
   Enter the Amount: Input the product price in the corresponding field.
3. 消費税率（10% または 8%）を選択  
   Select the tax rate (10% or 8%)
4. 「計算する」ボタンをクリック：以下の項目が自動で計算・表示されます。  
   Click the "Calculate" Button: The following items will be calculated and displayed:
   - 税込金額 / Price including Tax
   - 税抜金額 / Price excluding Tax
   - 返金金額 / Refund Amount
   - 手数料（1.55%）/ Handling fee (1.55%)
   - 実際の支払金額 / Final payment amount
5. 言語を切り替え：画面上部のボタンでいつでも表示言語を切り替えられます。
   Switch Language: You can change the display language at any time using the buttons at the top.

---

## ライセンス / License

このプロジェクトは [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.ja) ライセンスのもとで公開されています。  
著作権 © 2025 XINGTIAN ZHANG  
無断での改変・商用利用は禁止されています。

This project is licensed under the [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/) license.  
Copyright © 2025 XINGTIAN ZHANG  
Modification and commercial use are prohibited without permission.

[![License: CC BY-NC-ND 4.0](https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-nd/4.0/)
