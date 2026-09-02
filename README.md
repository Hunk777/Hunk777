<pre align="center">
<b>Hunk777</b>
────────────────────────────────────────
  TRADE / INDICATORS
  MQL5 · Pine Script · MetaTrader
────────────────────────────────────────
  Japan
</pre>

<p align="center">
  <strong>Indicator Engineer</strong> — チャートに載せるロジックを設計して実装している
</p>

<p align="center">
  <a href="https://github.com/Hunk777/ema4--9"><img src="https://img.shields.io/badge/repo-ema4--9-111?style=flat-square&labelColor=222" alt="ema4--9" /></a>
  <img src="https://img.shields.io/badge/MQL5-007ACC?style=flat-square" alt="MQL5" />
  <img src="https://img.shields.io/badge/Pine%20Script-v5-2962FF?style=flat-square&logo=tradingview&logoColor=white" alt="Pine" />
  <img src="https://img.shields.io/badge/MetaTrader-4%2F5-009688?style=flat-square" alt="MT" />
  <img src="https://img.shields.io/badge/EMA-4x9-555?style=flat-square" alt="EMA" />
</p>

---

## TRADE

インジケーターと EA を自分で書いている。エントリー信号だけでなく、損切り · 利確 · 時間フィルタまでコードに落とす。

| | |
| --- | --- |
| **Indicators** | EMA cross · signal · panel · alert |
| **Risk** | SL1 · SL2 · TP1 · TP2 · trailing |
| **Automation** | EA · strategy · backtest |
| **Ship log** | a20 → a24 → Pro · Golden Sniper v13 |

### [ema4--9](https://github.com/Hunk777/ema4--9) — EMA Cross Trading System

Pine Script（TradingView）と MQL5（MetaTrader）の両方で同じ思想を実装している。

| レイヤ | ファイル | 内容 |
| --- | --- | --- |
| Indicator | `EMA_Cross_Pro_v1.pine` | EMA 4×9 · 背景シグナル · 情報パネル |
| EA | `Golden_Sniper_v13_2_TimeFilter_Fix.mq5` | 時間フィルタ · 最新版 |
| EA | `EMA_Cross_For_Scal_Pro.mq5` | スキャル特化 |
| EA | `EMA_Cross_BTCUSD_Pro.mq5` | BTCUSD |
| Strategy | `strategy/b1.pine` | バックテスト用 |

```text
  price
    │     ╱╲
    │    ╱  ╲    EMA(4)
    │   ╱    ╲╲
    │  ╱      ╲╲  EMA(9)
    │ ╱        ╲╲________
    └──────────────────────► time

  golden cross  →  long  + SL1/SL2 + TP1/TP2
  dead cross    →  short
```

<details>
<summary>ファイル一覧</summary>

| ファイル | 種別 |
| --- | --- |
| `EMA_Cross_Pro_v1.pine` | Indicator |
| `Golden_Sniper_v13_2_TimeFilter_Fix.mq5` | EA |
| `Golden_Sniper_v9.mq5` | EA |
| `EMA_Cross_For_Scal_Pro.mq5` | EA |
| `EMA_Cross_BTCUSD_Pro.mq5` | EA |
| `EMA_Cross_BTC_Light_v2.x.mq5` | EA |
| `strategy/b1.pine` | Strategy |

</details>

---

## About

**Hunk** · Japan

TRADE を主軸に、Tipster（地図マーケット）と SynapseMap（思考ツール）も並行。

| | |
| --- | --- |
| 1 | TRADE — Pine · MQL5 · EMA Cross · Golden Sniper |
| 2 | Tipster / INFOMAP — 地図 × 情報市場（private） |
| 3 | SynapseMap · Claude Code 監視 |

---

## Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Hunk777&show_icons=true&theme=default&hide_border=true&title_color=111&icon_color=555&text_color=333&count_private=true" alt="stats" height="160" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Hunk777&layout=compact&theme=default&hide_border=true&title_color=111&text_color=333&langs_count=8&exclude_repo=Hunk777" alt="langs" height="160" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Hunk777&theme=default&hide_border=true&background=ffffff&stroke=d0d7de&ring=111&fire=555&currStreakLabel=333" alt="streak" />
</p>

---

## Other repos

| Repo | 内容 |
| --- | --- |
| Tipster `INFOMAP` | 地図マーケット（private） |
| [SynapseMap](https://github.com/Hunk777/SynapseMap) | マインドマップ + Markdown + ガント |
| [Claude-Code-Agent-Monitor](https://github.com/Hunk777/Claude-Code-Agent-Monitor) | エージェント監視 |
| [obsidian-vault](https://github.com/Hunk777/obsidian-vault) | Obsidian 同期 |
| [create-sitee](https://github.com/Hunk777/create-sitee) | フロント実験 |

---

## Stack

MQL5 · Pine Script · TypeScript · React · Expo · Supabase · Node

---

## Now

```text
▸ Golden Sniper / EMA Cross Pro — 実戦向けに改善中
▸ Pine v5 — 信号 · リスク · アラートを一体設計
▸ Tipster — pre-production
```

---

<p align="center">
  <sub>インジケーター · EA は研究目的。実取引は自己責任。</sub>
</p>
