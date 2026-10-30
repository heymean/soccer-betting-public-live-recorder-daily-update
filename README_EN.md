# Public Soccer Betting Records

> 🇨🇳 [中文版本](README.md) | Chinese version available.

A soccer-loving developer investing with data. This repo is my public record of
daily betting signals and settled results — every match traceable to its source email,
every update immutable through Git history.

> Last update: **2026-10-31 01:35:01**

## 📊 Cumulative Stats

| Metric | Value |
|---|---|
| Total bets | 7 |
| Settled | 0 |
| Win (win + half win) | 0 |
| Lose (lose + half lose) | 0 |
| Push | 0 |
| Win rate | 0.0% |
| Total stake | 0.00 |
| Total P/L | +0.00 |
| ROI | +0.00% |

## 📅 Daily Records

| Date | Bets | Settled | P/L | Details |
|---|---|---|---|---|
| 2026-10-31 | 1 | 0 | +0.00 | [EN](daily/2026-10-31/report_EN.md) · [中文](daily/2026-10-31/report.md) |
| 2026-10-30 | 6 | 0 | +0.00 | [EN](daily/2026-10-30/report_EN.md) · [中文](daily/2026-10-30/report.md) |

## 🔒 Verifiability

- Every match keeps its original signal line and result line (`raw_line` in `daily/*/*.json`)
- All data is auto-synced by a private script from source emails, never edited by hand
- Git commit history provides immutable timestamps
- Fixed stake **100 per bet**; profit = stake×(odds-1), half-win +50×(odds-1), half-lose -50