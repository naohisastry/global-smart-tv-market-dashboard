# Methodology

This document explains the methodology, assumptions, data definitions, and limitations used in the Global Smart TV / Connected TV Market Dashboard.

本ファイルは、Global Smart TV / Connected TV Market Dashboard におけるデータ定義、推計方法、前提条件、注意点を整理するための方法論ドキュメントです。

## 1. Purpose of the Dashboard

The dashboard visualizes the structure and competitive dynamics of the global Smart TV and Connected TV market from 2015 to 2025.

It focuses on three main analytical layers:

1. Smart TV shipment trends by major manufacturers
2. TV OS / Connected TV platform reach
3. Regional connected-TV OS share in North America, Europe, and Japan

本ダッシュボードは、2015年〜2025年における世界スマートテレビ／Connected TV市場の構造変化を可視化することを目的としています。

特に以下の3つの観点を重視しています。

1. 主要メーカー別のスマートテレビ出荷台数推移
2. TV OS / Connected TVプラットフォームの到達規模
3. 北米・欧州・日本における接続TV OSシェア

## 2. Data Categories

The dashboard uses several types of data.

### 2.1 Officially disclosed figures

These are figures directly disclosed by companies, platforms, investor relations materials, press releases, or official announcements.

Examples:

- Platform active users
- Device reach
- Annual shipment announcements
- Installed base figures
- Investor presentation metrics

### 2.2 Market research estimates

These are figures based on third-party research firms, industry reports, analyst notes, and market intelligence sources.

Examples:

- Smart TV shipment share
- Regional platform share
- OS-level market share
- Device penetration estimates

### 2.3 Analyst-derived assumptions

Some data points are estimated by combining multiple public sources where direct disclosure is unavailable.

Examples:

- Regional connected-TV OS share where official country-level data is not available
- Approximate comparison between installed base, active devices, and monthly active users
- Japan-specific estimates where global platform data is disclosed but local figures are not

## 3. Key Data Definitions

### 3.1 Smart TV shipments

Smart TV shipments generally refer to annual shipments of internet-connected televisions by manufacturer.

However, definitions may differ by source.

Possible differences include:

- Sell-in shipments to retailers or distributors
- Sell-through sales to end users
- Calendar year versus fiscal year reporting
- Global versus regional shipment scope

For this reason, shipment data should be interpreted as a market structure indicator rather than an exact accounting measure.

### 3.2 TV OS / Connected TV platform reach

TV OS or Connected TV platform reach may refer to several different measurement concepts.

Examples:

- Monthly active users
- Active accounts
- Active devices
- Installed base
- Households reached
- Cumulative devices sold

These figures are not always directly comparable. The dashboard therefore uses them primarily to understand relative platform scale and ecosystem power.

### 3.3 Regional connected-TV OS share

Regional OS share represents the estimated share of connected-TV usage or installed base by operating system or platform in each market.

The dashboard focuses on:

- North America
- Europe
- Japan

Where direct official disclosure is unavailable, regional OS share may be estimated using a combination of public data, market research, device penetration, platform availability, and manufacturer share.

## 4. Treatment of Estimates

The dashboard includes both disclosed figures and estimates.

When a number is not directly disclosed, it should be treated as an analytical estimate rather than a confirmed fact.

Estimate reliability depends on:

- Number of available source references
- Consistency across multiple sources
- Recency of the data
- Whether the source is official, research-based, or secondary
- Whether definitions are clearly stated

The dashboard aims to make such assumptions transparent through source notes and evidence links.

## 5. Source Hierarchy

When multiple sources exist, the following hierarchy is generally used.

1. Official company disclosures
2. Investor relations materials
3. Regulatory filings
4. Official press releases
5. Reputable market research firms
6. Industry publications
7. Secondary articles and commentary
8. Analyst-derived assumptions

公式発表、IR資料、決算資料、プレスリリースを優先し、それらで不足する部分については調査会社・業界メディア・補完推計を使用します。

## 6. Limitations

This dashboard has several limitations.

### 6.1 Different measurement units

The same term, such as “reach” or “active devices,” may be defined differently by each company.

For example:

- Roku may disclose active accounts or streaming households.
- Google TV / Android TV may disclose monthly active devices.
- Fire TV may disclose cumulative devices sold or active users depending on the source.
- Samsung Tizen and LG webOS may disclose device base or platform reach through different metrics.

Therefore, the dashboard should not be read as a perfectly standardized statistical database.

### 6.2 Regional data gaps

North America has relatively more public data on Connected TV platform usage.

Europe and Japan often have fewer directly comparable OS-level disclosures.

For this reason, Europe and Japan figures may include a higher degree of estimation.

### 6.3 Time-series consistency

Some data series may not be available for every year from 2015 to 2025.

Where year-by-year data is unavailable, the dashboard may use:

- Interpolation
- Publicly disclosed milestone figures
- Market trend estimates
- Proxy indicators

### 6.4 Platform overlap

A single household or device may be exposed to multiple platforms.

For example:

- A user may own a Samsung Smart TV but also use Fire TV or Chromecast.
- A TV may run a manufacturer OS while also supporting external streaming devices.
- Platform reach and TV shipment data may overlap conceptually.

Therefore, shipment share, OS share, and platform reach should be interpreted as related but distinct indicators.

## 7. Analytical Focus

The dashboard is designed to support analysis of the following themes.

- Smart TV market structure
- Connected TV platform competition
- TV OS sovereignty
- Manufacturer versus platform power
- Regional differences in CTV ecosystem control
- The strategic position of Google TV, Fire TV, Roku, Tizen, webOS, and other platforms
- Implications for media companies, broadcasters, streaming services, and device manufacturers

## 8. Update Policy

The dashboard should be updated when new public data becomes available.

Recommended update triggers:

- Annual shipment reports
- Major platform reach announcements
- Investor presentations
- New market research releases
- Major OS or device strategy announcements
- Significant changes in regional CTV adoption

Each update should be recorded in `CHANGELOG.md`.

## 9. Related Files

- `README.md` — Project overview and dashboard summary
- `DATA_SOURCES.md` — Source categories and evidence structure
- `index.html` — Interactive dashboard
- `CHANGELOG.md` — Update history
