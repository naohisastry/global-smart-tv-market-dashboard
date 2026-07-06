# Global Smart TV / Connected TV Market Dashboard (2015–2025)

An interactive market research dashboard analyzing the global Smart TV and Connected TV market from 2015 to 2025, including TV shipment trends, TV OS platform reach, and regional connected-TV OS share across North America, Europe, and Japan.

本ダッシュボードは、2015年〜2025年の世界スマートテレビ／Connected TV市場について、主要メーカー別出荷台数、主要TV OSプラットフォームの到達規模、北米・欧州・日本における接続OSシェアを可視化するインタラクティブな分析ツールです。

## Live Dashboard

https://naohisastry.github.io/global-smart-tv-market-dashboard/

## Keywords

Smart TV, Connected TV, CTV, TV OS, Google TV, Fire TV, Roku, Tizen, webOS, Samsung, LG, Hisense, TCL, media industry, market research, OS sovereignty, dashboard

## 📊 ダッシュボードの主な機能

1. **主要メーカー別出荷台数推移（2015-2025年）**
   * Omdia、Counterpoint、TrendForce等の公表データに基づく主要5社（Samsung、TCL、Hisense、LG、Xiaomi）の出荷推移。
   * TCLの台頭、LGの2025年是正データ等、実勢に即したデータをプロット。
2. **プラットフォーム到達規模（世界市場）**
   * Google TV（月間アクティブデバイス3億台）、Tizen（搭載2.7億台超）、Fire TV（累計2.5億台）、webOS（搭載2億台超）、Roku（8980万世帯）の公式発表値の対比。
   * 測定基準（MAU、累計販売数、アクティブ世帯）の違いに関する注記を包含。
3. **主要地域別OS・接続シェア（北米・欧州・日本）**
   * Parks Associatesの実データ（北米）および地域別の普及特性を考慮した推計データ（欧州・日本）をプロット。
   * 日本市場におけるGoogle/Fire OSの二強構造と国内メーカー独自OSの比率、Samsung（Tizen）の国内撤退に伴うシェア不在を可視化。
4. **出典情報の動的フィルタリング**
   * 上部のタブ（チャート切り替え）と連動し、そのチャートに関連する一次資料・エビデンスリンクのみがページ下部に即座に切り替わって表示されます。

---

## 🛠️ プロジェクトファイル構成

本プロジェクトは、Webサーバー不要でブラウザ上で完結して動作する静的なシングルページアプリケーション（SPA）です。

* **index.html**: ダッシュボードの全機能を包含したHTMLファイル。
  * HTML5によるUI構造設計。
  * Vanilla CSSによるダークモード対応のモダンなプレミアムデザイン（ガラスマージン、ネオン光彩効果等）。
  * Chart.js（CDN経由）を用いた各種インタラクティブチャートの描画。
  * グラフのタブ切り替えおよび出典情報の動的フィルタリングロジック（JavaScript）。

---

## 🚀 動作確認・起動方法

特別なサーバー設定やインストール作業は一切不要です。

1. 本リポジトリの全ファイルをローカルにダウンロードまたはクローンします。
2. `index.html` ファイルをお手持ちのブラウザ（Google Chrome, Safari, Microsoft Edge, Firefoxなど）でダブルクリックして開きます。

---

## 📝 ライセンス・データクレジット

本ダッシュボードに掲載されているデータは、以下の各社の公式IR・プレスリリースおよび調査レポートを収集・整理したものです。
* Google LLC
* Samsung Electronics
* Amazon.com, Inc.
* LG Electronics
* Roku, Inc.
* VIZIO Holding Corp. (Walmart)
* Parks Associates
* TrendForce / Counterpoint / Omdia

各データの詳細な引用箇所および恒久アーカイブリンクは、ダッシュボード下部の「出典情報」にてご確認いただけます。
