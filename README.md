# AVGO 1m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-111_396_rows-blue)](https://getdata.finance/datasets/avgo) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/avgo)

### -> [**Download the full AVGO dataset on getdata.finance**](https://getdata.finance/datasets/avgo)

**AVGO 1m OHLCV stocks historical data** — ultra high-quality 1m OHLCV for **Broadcom**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **Broadcom** (US stocks)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/avgo) · **111,396** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `AVGO_1m.csv` (55,440 rows, `2026-02-06` -> `2026-09-01`). **Full archive on [getdata.finance](https://getdata.finance/datasets/avgo)** — **111,396** `1m` rows, **11 timeframes**, `2025-07-14` -> `2026-09-01`.

## Download sample

**[AVGO_1m.csv](https://github.com/getdata-finance/avgo-1m-ohlcv-stocks-historical-data/blob/main/AVGO_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/avgo-1m-ohlcv-stocks-historical-data/main/AVGO_1m.csv))

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/avgo))** |
|---|--:|---|
| Instrument | Broadcom · US stocks | Broadcom · US stocks |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **111,396** |
| Period | `2026-02-06` -> `2026-09-01` | `2025-07-14` -> `2026-09-01` |
| File | `AVGO_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/avgo) |
| Coverage report | — | [AVGO coverage](https://getdata.finance/coverage/avgo) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/avgo)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes**:

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples refreshed weekly, in sync with getdata.finance.

## Data preview

First and latest rows from the GitHub sample **`AVGO_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-06T20:00:00+00:00 | 326.62 | 326.65 | 326.19 | 326.55 | 73 |
| 2026-02-06T20:01:00+00:00 | 326.55 | 326.79 | 326.46 | 326.66 | 50 |
| 2026-02-06T20:02:00+00:00 | 326.66 | 327.23 | 326.62 | 327.05 | 63 |
| 2026-02-06T20:03:00+00:00 | 327.05 | 327.38 | 327 | 327.17 | 52 |
| 2026-02-06T20:04:00+00:00 | 327.17 | 327.18 | 326.95 | 327.05 | 18 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-01T19:55:00+00:00 | 369.13 | 369.92 | 369.13 | 369.69 | 157 |
| 2026-09-01T19:56:00+00:00 | 369.69 | 369.71 | 368.92 | 369.03 | 158 |
| 2026-09-01T19:57:00+00:00 | 369.03 | 369.33 | 368.93 | 369.33 | 189 |
| 2026-09-01T19:58:00+00:00 | 369.33 | 369.74 | 369.12 | 369.57 | 228 |
| 2026-09-01T19:59:00+00:00 | 369.57 | 370 | 369.52 | 369.77 | 258 |

## Schema

| Column | Description |
| --- | --- |
| `time` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
time,open,high,low,close,volume
```

## Download full data

Full AVGO archive — 11 timeframes, gap-free, updated weekly:

**[-> Get the full AVGO dataset on getdata.finance](https://getdata.finance/datasets/avgo)**
