# AVGO 1m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-666_923_rows-blue)](https://getdata.finance/datasets/avgo) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/avgo)

### -> [**Download the full AVGO dataset on getdata.finance**](https://getdata.finance/datasets/avgo)

**AVGO 1m OHLCV us stocks historical data** — ultra high-quality 1m OHLCV for **AVGO**. US equity cash and extended sessions — institutional-style OHLCV candles for US stocks. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1m OHLCV** for **AVGO** (US stocks)
- **US equity cash and extended sessions — institutional-style OHLCV candles for US stocks**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **8 timeframes** on [getdata.finance](https://getdata.finance/datasets/avgo) · **666,923** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `AVGO_1m.csv` (48,750 rows, `2026-02-02` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/avgo)** — **666,923** `1m` rows (~40.33 MB), **8 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 3D · 1W), `2011-05-09` -> `2026-07-29`.

## Download sample

**[AVGO_1m.csv](https://github.com/getdata-finance/avgo-1m-ohlcv-stocks-historical-data/blob/main/AVGO_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/avgo-1m-ohlcv-stocks-historical-data/main/AVGO_1m.csv)) · [GitHub Releases](https://github.com/getdata-finance/avgo-1m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/avgo-1m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/avgo-1m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/avgo](https://getdata.finance/datasets/avgo)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/avgo))** |
|---|--:|---|
| Instrument | AVGO · US stocks | AVGO · US stocks |
| Timeframes | `1m` (sample) | **8** — 1m · 3m · 5m · 15m · 30m · 1H · 3D · 1W |
| 1m rows | 48,750 | **666,923** |
| Size | 4.81 MB | ~40.33 MB |
| Period | `2026-02-02` -> `2026-07-31` | `2011-05-09` -> `2026-07-29` |
| File | `AVGO_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/avgo) |
| Coverage report | — | [AVGO coverage](https://getdata.finance/coverage/avgo) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/avgo)**, each full asset archive is delivered as a ZIP with **8 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **3D** · **1W**

GitHub = `1m` sample · [getdata.finance](https://getdata.finance/datasets/avgo) = all **8** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AVGO_1m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-02T14:30:00+00:00 | 325.23 | 325.23 | 319.87 | 323.47 | 69 |
| 2026-02-02T14:31:00+00:00 | 323.47 | 328.19 | 323.47 | 327.62 | 91 |
| 2026-02-02T14:32:00+00:00 | 327.62 | 329.78 | 326.47 | 326.49 | 78 |
| 2026-02-02T14:33:00+00:00 | 326.49 | 326.49 | 323.89 | 324.1 | 17 |
| 2026-02-02T14:34:00+00:00 | 324.1 | 324.55 | 321.75 | 323.02 | 44 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-31T19:55:00+00:00 | 390.19 | 390.97 | 390.11 | 390.75 | 143 |
| 2026-07-31T19:56:00+00:00 | 390.75 | 391.33 | 390.75 | 390.99 | 161 |
| 2026-07-31T19:57:00+00:00 | 390.99 | 391.33 | 390.72 | 391.07 | 215 |
| 2026-07-31T19:58:00+00:00 | 391.07 | 391.07 | 390.17 | 390.22 | 246 |
| 2026-07-31T19:59:00+00:00 | 390.22 | 390.3 | 389.1 | 389.16 | 270 |

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
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
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

The complete **AVGO** archive on **[getdata.finance](https://getdata.finance/datasets/avgo)** includes **8 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 3D · 1W) — **666,923** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full AVGO dataset on getdata.finance](https://getdata.finance/datasets/avgo)**

---
*GetData · AVGO 1m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/avgo) · 2026-08-04 UTC*
