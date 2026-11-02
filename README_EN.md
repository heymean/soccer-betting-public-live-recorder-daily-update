# Public Soccer Betting Records

> 🇨🇳 [中文版本](README.md) | Chinese version available.

A soccer-loving developer investing with data. This repo is my public record of
daily betting signals and settled results — every match traceable to its source email,
every update immutable through Git history.

> Last update: **2026-11-02 20:16:21**

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