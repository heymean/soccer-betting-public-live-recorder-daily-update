# Public Soccer Betting Records

> 🇨🇳 [中文版本](README.md) | Chinese version available.

A soccer-loving developer investing with data. This repo is my public record of
daily betting signals and settled results — every match traceable to its source email,
every update immutable through Git history.

> Last update: **2026-11-02 20:26:28**

## 📊 Cumulative Stats

| Metric | Value |
|---|---|
| Total bets | 7 |
| Settled | 7 |
| Win (win + half win) | 3 |
| Lose (lose + half lose) | 2 |
| Push | 2 |
| Win rate | 66.7% |
| Total stake | 700.00 |
| Total P/L | +123.00 |
| ROI | +17.57% |

> Win rate: (win + 0.5×half-win) / (win + 0.5×half-win + lose + 0.5×half-lose). Half results count as 0.5. Push excluded.

## 📅 Recent 3 Days

| Date | Bets | Settled | Win rate | P/L | ROI | Details |
|---|---|---|---|---|---|---|
| 2026-11-02 | 5 | 5 | 66.7% | +74.00 | +14.80% | [EN](daily/2026-11-02/report_EN.md) · [中文](daily/2026-11-02/report.md) |
| 2026-11-01 | 2 | 2 | 66.7% | +49.00 | +24.50% | [EN](daily/2026-11-01/report_EN.md) · [中文](daily/2026-11-01/report.md) |

## 📅 Recent 30 Matches

| Kickoff | League | Match | Side/Handicap | Odds | HT | FT | Result | P/L |
|---|---|---|---|---|---|---|---|---|
| 2026-11-02 04:00 | 西甲 | 毕尔巴鄂竞技 vs 皇家社会 | 上半场·主队 -0.25 | 2.06 | 2-1 | 2-1 | ✅ Win | +106.00 |
| 2026-11-02 03:45 | 意甲 | 尤文图斯 vs 那不勒斯 | 上半场·客队 0 | 2.17 | 0-0 | 2-0 | ⚪ Push | +0.00 |
| 2026-11-02 01:30 | 西甲 | 埃尔切 vs 巴伦西亚 | 上半场·主队 0 | 1.64 | 0-0 | 0-1 | ⚪ Push | +0.00 |
| 2026-11-02 01:00 | 意甲 | 莱切 vs 热那亚 | 上半场·客队 0 | 1.68 | 1-2 | 1-2 | ✅ Win | +68.00 |
| 2026-11-02 00:30 | 德甲 | 法兰克福 vs 汉堡 | 上半场·主队 -0.50 | 1.97 | 0-2 | 3-1 | ❌ Lose | -100.00 |
| 2026-11-01 23:15 | 西甲 | 桑坦德竞技 vs 皇家马德里 | 上半场·客队 +1.00 | 1.99 | 0-3 | 0-3 | ✅ Win | +99.00 |
| 2026-11-01 22:00 | 意甲 | 弗洛西诺内 vs 都灵 | 上半场·主队 -0.25 | 2.11 | 0-0 | 2-0 | 🟡 Half Lose | -50.00 |

## 📅 All Records

| Date | Bets | Settled | P/L | Details |
|---|---|---|---|---|
| 2026-11-02 | 5 | 5 | +74.00 | [EN](daily/2026-11-02/report_EN.md) · [中文](daily/2026-11-02/report.md) |
| 2026-11-01 | 2 | 2 | +49.00 | [EN](daily/2026-11-01/report_EN.md) · [中文](daily/2026-11-01/report.md) |

## 🔒 Verifiability

- Every match keeps its original signal line and result line (`raw_line` in `daily/*/*.json`)
- All data is auto-synced by a private script from source emails, never edited by hand
- Git commit history provides immutable timestamps
- Fixed stake **100 per bet**; profit = stake×(odds-1), half-win +50×(odds-1), half-lose -50