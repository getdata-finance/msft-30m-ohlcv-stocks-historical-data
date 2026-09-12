# MSFT 30m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-40_468_rows-blue)](https://getdata.finance/datasets/msft) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/msft)

### -> [**Download the full MSFT dataset on getdata.finance**](https://getdata.finance/datasets/msft)

**MSFT 30m OHLCV stocks historical data** — ultra high-quality 30m OHLCV for **Microsoft**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 30m OHLCV** for **Microsoft** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`30m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/msft) · **40,468** `30m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `30m` sample updated in sync

> **Sample on GitHub** · `MSFT_30m.csv` (1,651 rows, `2026-03-12` -> `2026-09-11`, 157.07 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/msft)** — **40,468** `30m` rows (full `1m`: 634,891), **11 timeframes**, `2011-05-09` -> `2026-09-11`.

## Download sample

**[MSFT_30m.csv](https://github.com/getdata-finance/msft-30m-ohlcv-stocks-historical-data/blob/main/MSFT_30m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/msft-30m-ohlcv-stocks-historical-data/main/MSFT_30m.csv)) · [GitHub Releases](https://github.com/getdata-finance/msft-30m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/msft-30m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/msft-30m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/msft](https://getdata.finance/datasets/msft)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/msft))** |
|---|--:|---|
| Instrument | Microsoft · US stocks | Microsoft · US stocks |
| Timeframes | `30m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 30m rows | 1,651 | **40,468** |
| Size | 157.07 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/msft) |
| Period | `2026-03-12` -> `2026-09-11` | `2011-05-09` -> `2026-09-11` |
| File | `MSFT_30m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/msft) |
| Coverage report | — | [MSFT coverage](https://getdata.finance/coverage/msft) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`30m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/msft)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `30m` sample · [getdata.finance](https://getdata.finance/datasets/msft) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `30m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`MSFT_30m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-12T13:30:00+00:00 | 397.44 | 398.41 | 394.64 | 395.44 | 3375 |
| 2026-03-12T14:00:00+00:00 | 395.44 | 397.44 | 395.38 | 396.35 | 4272 |
| 2026-03-12T14:30:00+00:00 | 396.35 | 398.48 | 395.54 | 397.9 | 4123 |
| 2026-03-12T15:00:00+00:00 | 397.9 | 398.26 | 395.18 | 396.39 | 3620 |
| 2026-03-12T15:30:00+00:00 | 396.39 | 397.13 | 395.71 | 396.67 | 3239 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-11T17:30:00+00:00 | 494.75 | 494.98 | 494.06 | 494.62 | 1509 |
| 2026-09-11T18:00:00+00:00 | 494.62 | 495.45 | 494.23 | 495.34 | 1544 |
| 2026-09-11T18:30:00+00:00 | 495.34 | 496.17 | 495.04 | 495.95 | 1442 |
| 2026-09-11T19:00:00+00:00 | 495.95 | 496.79 | 495.95 | 496.58 | 1380 |
| 2026-09-11T19:30:00+00:00 | 496.58 | 496.61 | 494.72 | 495.48 | 1870 |

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

df = pd.read_csv('MSFT_30m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('MSFT_30m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('MSFT_30m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='30min')
print(pf.stats())
```

## Download full data

The complete **MSFT** archive on **[getdata.finance](https://getdata.finance/datasets/msft)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **40,468** rows at `30m`, plus all other timeframes in the same ZIP.

**[-> Get the full MSFT dataset on getdata.finance](https://getdata.finance/datasets/msft)**

---
*GetData · MSFT 30m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/msft)*
