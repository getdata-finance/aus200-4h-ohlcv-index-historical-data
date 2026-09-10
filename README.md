# AUS200 4h OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-27_682_rows-blue)](https://getdata.finance/datasets/aus200) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/aus200)

### -> [**Download the full AUS200 dataset on getdata.finance**](https://getdata.finance/datasets/aus200)

**AUS200 4h OHLCV index historical data** — ultra high-quality 4h OHLCV for **S&P/ASX 200**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 4h OHLCV** for **S&P/ASX 200** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`4h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/aus200) · **27,682** `4h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `4h` sample updated in sync

> **Sample on GitHub** · `AUS200_4h.csv` (792 rows, `2026-03-10` -> `2026-09-09`, 56.16 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/aus200)** — **27,682** `4h` rows (full `1m`: 5,046,226), **11 timeframes**, `2008-09-10` -> `2026-09-09`.

## Download sample

**[AUS200_4h.csv](https://github.com/getdata-finance/aus200-4h-ohlcv-index-historical-data/blob/main/AUS200_4h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/aus200-4h-ohlcv-index-historical-data/main/AUS200_4h.csv)) · [GitHub Releases](https://github.com/getdata-finance/aus200-4h-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/aus200-4h-ohlcv-index-historical-data/](https://getdata-finance.github.io/aus200-4h-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/aus200](https://getdata.finance/datasets/aus200)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/aus200))** |
|---|--:|---|
| Instrument | S&P/ASX 200 · Index | S&P/ASX 200 · Index |
| Timeframes | `4h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 4h rows | 792 | **27,682** |
| Size | 56.16 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/aus200) |
| Period | `2026-03-10` -> `2026-09-09` | `2008-09-10` -> `2026-09-09` |
| File | `AUS200_4h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/aus200) |
| Coverage report | — | [AUS200 coverage](https://getdata.finance/coverage/aus200) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`4h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/aus200)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `4h` sample · [getdata.finance](https://getdata.finance/datasets/aus200) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `4h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AUS200_4h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-10T20:00:00+00:00 | 8716.78 | 8735.87 | 8705.35 | 8711.87 | 2508.70273 |
| 2026-03-11T00:00:00+00:00 | 8711.87 | 8758.85 | 8711.87 | 8746.87 | 6197 |
| 2026-03-11T04:00:00+00:00 | 8746.87 | 8746.87 | 8670.95 | 8676.45 | 3318 |
| 2026-03-11T08:00:00+00:00 | 8676.45 | 8681.99 | 8617.97 | 8644.98 | 11090 |
| 2026-03-11T12:00:00+00:00 | 8644.98 | 8680.97 | 8623.49 | 8633.98 | 17433 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-08T08:00:00+00:00 | 8894.35 | 8927.35 | 8884.34 | 8926.34 | 4922 |
| 2026-09-08T12:00:00+00:00 | 8926.34 | 8950.35 | 8916.85 | 8938.35 | 4897 |
| 2026-09-08T16:00:00+00:00 | 8938.35 | 8942.84 | 8920.83 | 8928.83 | 3402 |
| 2026-09-08T20:00:00+00:00 | 8928.83 | 8929.83 | 8914.19 | 8922.2 | 453 |
| 2026-09-09T00:00:00+00:00 | 8922.2 | 8945.6 | 8885.59 | 8892.11 | 2654 |

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

df = pd.read_csv('AUS200_4h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AUS200_4h.csv', parse_dates=['datetime'])
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

df = pd.read_csv('AUS200_4h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='4h')
print(pf.stats())
```

## Download full data

The complete **AUS200** archive on **[getdata.finance](https://getdata.finance/datasets/aus200)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **27,682** rows at `4h`, plus all other timeframes in the same ZIP.

**[-> Get the full AUS200 dataset on getdata.finance](https://getdata.finance/datasets/aus200)**

---
*GetData · AUS200 4h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/aus200)*
