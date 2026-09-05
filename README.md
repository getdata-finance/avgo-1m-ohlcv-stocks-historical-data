# AVGO 1m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-684_385_rows-blue)](https://getdata.finance/datasets/avgo) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/avgo)

### -> [**Download the full AVGO dataset on getdata.finance**](https://getdata.finance/datasets/avgo)

**AVGO 1m OHLCV stocks historical data** — ultra high-quality 1m OHLCV for **Broadcom**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **Broadcom** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/avgo) · **684,385** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `AVGO_1m.csv` (55,440 rows, `2026-02-11` -> `2026-09-04`, 5.46 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/avgo)** — **684,385** `1m` rows (full `1m`: 111,138), **11 timeframes**, `2011-05-09` -> `2026-09-04`.

## Download sample

**[AVGO_1m.csv](https://github.com/getdata-finance/avgo-1m-ohlcv-stocks-historical-data/blob/main/AVGO_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/avgo-1m-ohlcv-stocks-historical-data/main/AVGO_1m.csv)) · [GitHub Releases](https://github.com/getdata-finance/avgo-1m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/avgo-1m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/avgo-1m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/avgo](https://getdata.finance/datasets/avgo)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/avgo))** |
|---|--:|---|
| Instrument | Broadcom · US stocks | Broadcom · US stocks |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **684,385** |
| Size | 5.46 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/avgo) |
| Period | `2026-02-11` -> `2026-09-04` | `2011-05-09` -> `2026-09-04` |
| File | `AVGO_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/avgo) |
| Coverage report | — | [AVGO coverage](https://getdata.finance/coverage/avgo) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/avgo)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1m` sample · [getdata.finance](https://getdata.finance/datasets/avgo) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AVGO_1m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-11T19:59:00+00:00 | 337.39 | 337.4 | 337.22 | 337.23 | 29 |
| 2026-02-11T20:00:00+00:00 | 337.23 | 337.31 | 336.89 | 337.04 | 49 |
| 2026-02-11T20:01:00+00:00 | 337.04 | 337.45 | 337.04 | 337.42 | 29 |
| 2026-02-11T20:02:00+00:00 | 337.42 | 337.58 | 337.37 | 337.39 | 33 |
| 2026-02-11T20:03:00+00:00 | 337.39 | 337.4 | 337.21 | 337.38 | 27 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-04T19:55:00+00:00 | 357.61 | 358.09 | 357.61 | 357.88 | 178 |
| 2026-09-04T19:56:00+00:00 | 357.88 | 358.38 | 357.81 | 358.23 | 217 |
| 2026-09-04T19:57:00+00:00 | 358.23 | 358.35 | 357.76 | 358.07 | 213 |
| 2026-09-04T19:58:00+00:00 | 358.07 | 358.27 | 357.69 | 357.73 | 199 |
| 2026-09-04T19:59:00+00:00 | 357.73 | 357.94 | 357.43 | 357.84 | 316 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('AVGO_1m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AVGO_1m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('AVGO_1m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **AVGO** archive on **[getdata.finance](https://getdata.finance/datasets/avgo)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **684,385** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full AVGO dataset on getdata.finance](https://getdata.finance/datasets/avgo)**

---
*GetData · AVGO 1m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/avgo)*
