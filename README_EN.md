# Public Soccer Betting Records

> 🇨🇳 [中文版本](README.md) | Chinese version available.

A soccer-loving developer investing with data. This repo is my public record of
daily betting signals and settled results — every match traceable to its source email,
every update immutable through Git history.

> Last update: **2026-11-01 19:46:31**

## 📊 Cumulative Stats

| Metric | Value |
|---|---|
| Total bets | 30 |
| Settled | 34 |
| Win (win + half win) | 21 |
| Lose (lose + half lose) | 12 |
| Push | 1 |
| Win rate | 61.8% |
| Total stake | 3400.00 |
| Total P/L | +620.50 |
| ROI | +18.25% |

## 📅 Daily Records

| Date | Bets | Settled | P/L | Details |
|---|---|---|---|---|
| 2026-11-01 | 11 | 11 | +103.00 | [EN](daily/2026-11-01/report_EN.md) · [中文](daily/2026-11-01/report.md) |
| 2026-10-31 | 17 | 16 | +300.50 | [EN](daily/2026-10-31/report_EN.md) · [中文](daily/2026-10-31/report.md) |
| 2026-10-30 | 6 | 4 | +142.00 | [EN](daily/2026-10-30/report_EN.md) · [中文](daily/2026-10-30/report.md) |
| 2026-10-29 | 3 | 3 | +75.00 | [EN](daily/2026-10-29/report_EN.md) · [中文](daily/2026-10-29/report.md) |
| 2026-10-28 | 1 | 0 | +0.00 | [EN](daily/2026-10-28/report_EN.md) · [中文](daily/2026-10-28/report.md) |

## 🔒 Verifiability

- Every match keeps its original signal line and result line (`raw_line` in `daily/*/*.json`)
- All data is auto-synced by a private script from source emails, never edited by hand
- Git commit history provides immutable timestamps
- Fixed stake **100 per bet**; profit = stake×(odds-1), half-win +50×(odds-1), half-lose -50