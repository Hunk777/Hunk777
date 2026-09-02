<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:FFD700,50:111827,100:0A66C2&height=200&section=header&text=Hunk777&fontSize=68&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Indicator%20Engineer%20%C2%B7%20TRADE&descSize=17&descAlignY=58&descAlign=50" alt="Header" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&duration=2800&pause=900&color=FFD700&center=true&vCenter=true&multiline=true&width=680&height=88&lines=Building+Trading+Indicators;EMA+4+%C3%97+9+%C2%B7+SL+%2F+TP+%C2%B7+Trailing;MQL5+%C2%B7+Pine+Script+%C2%B7+MetaTrader;Golden+Sniper+%C2%B7+EMA+Cross+Pro" alt="Typing intro" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PRIMARY-TRADE%20%2F%20INDICATORS-FFD700?style=for-the-badge&labelColor=111827" alt="TRADE" />
  <img src="https://img.shields.io/badge/location-Japan-red?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Japan" />
</p>

<p align="center">
  <a href="https://github.com/Hunk777/ema4--9"><img src="https://img.shields.io/badge/repo-ema4--9-111?style=flat-square&labelColor=222" alt="ema4--9" /></a>
  <img src="https://img.shields.io/badge/MQL5-007ACC?style=flat-square" alt="MQL5" />
  <img src="https://img.shields.io/badge/Pine%20Script-v5-2962FF?style=flat-square&logo=tradingview&logoColor=white" alt="Pine" />
  <img src="https://img.shields.io/badge/MetaTrader-4%2F5-009688?style=flat-square" alt="MT" />
  <img src="https://img.shields.io/badge/EMA-4x9-555?style=flat-square" alt="EMA" />
  <img src="https://img.shields.io/badge/Golden_Sniper-v13-555?style=flat-square" alt="Golden Sniper" />
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

<p align="center">
  <a href="https://github.com/Hunk777/ema4--9"><img src="https://img.shields.io/static/v1?label=Repository&message=Hunk777%2Fema4--9&color=FFD700&style=for-the-badge&logo=github&logoColor=black" alt="Repo" /></a>
  <img src="https://img.shields.io/github/last-commit/Hunk777/ema4--9?style=for-the-badge&label=last%20commit&color=111827" alt="Last commit" />
</p>

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

**Hunk** · Japan · **Indicator Engineer**

TRADE を主軸に、Tipster（地図マーケット）と SynapseMap（思考ツール）も並行。

| | |
| --- | --- |
| 1 | TRADE — Pine · MQL5 · EMA Cross · Golden Sniper |
| 2 | Tipster / INFOMAP — 地図 × 情報市場（private） |
| 3 | SynapseMap · Claude Code 監視 |

---

## Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Hunk777&show_icons=true&theme=radical&hide_border=true&bg_color=0d1117&title_color=FFD700&icon_color=FFD700&text_color=c9d1d9&count_private=true&include_all_commits=true" alt="stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Hunk777&layout=compact&theme=radical&hide_border=true&bg_color=0d1117&title_color=FFD700&text_color=c9d1d9&langs_count=8&exclude_repo=Hunk777" alt="langs" height="165" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Hunk777&theme=radical&hide_border=true&background=0d1117&stroke=30363d&ring=FFD700&fire=FFD700&currStreakLabel=FFD700&sideLabels=FFD700&dates=888888" alt="streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Hunk777&theme=react-dark&hide_border=true&bg_color=0d1117&color=FFD700&line=FFD700&point=ffffff&area=true&custom_title=Contribution%20Activity" alt="activity" />
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
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:FFD700,50:111827,100:0A66C2&height=120&section=footer&text=Building%20Indicators&fontSize=26&fontColor=ffffff&animation=twinkling" alt="Footer" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Hunk777&label=Profile%20views&color=FFD700&style=flat-square" alt="views" />
</p>

<p align="center">
  <sub>インジケーター · EA は研究目的。実取引は自己責任。</sub>
</p>
