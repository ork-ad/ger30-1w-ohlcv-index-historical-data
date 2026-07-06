# GER30 1w OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_943_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full GER30 dataset on ork.ad**](https://ork.ad/)

**GER30 1w OHLCV Stock index historical data** — ultra high-quality 1w OHLCV for **DAX**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 1w OHLCV** for **DAX** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1w`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **2,943** `1w` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `1w` sample updated in sync

> **Sample on GitHub** · `GER30_1w.csv` (105 rows, `2024-07-01` → `2026-06-29`). **Full archive on [ork.ad](https://ork.ad/)** — **2,943** `1w` rows (~0.16 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `1970-02-09` → `2026-06-29`.

## Download sample

**[GER30_1w.csv](https://github.com/ork-ad/ger30-1w-ohlcv-index-historical-data/blob/main/GER30_1w.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/ger30-1w-ohlcv-index-historical-data/main/GER30_1w.csv)) · [GitHub Releases](https://github.com/ork-ad/ger30-1w-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/ger30-1w-ohlcv-index-historical-data/](https://ork-ad.github.io/ger30-1w-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | DAX · Stock index | DAX · Stock index |
| Timeframes | `1w` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 1w rows | 105 | **2,943** |
| Size | 0.01 MB | ~0.16 MB |
| Period | `2024-07-01` → `2026-06-29` | `1970-02-09` → `2026-06-29` |
| File | `GER30_1w.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`1w` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `1w` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `1w` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`GER30_1w.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2024-07-01T00:00:00Z | 18262.29 | 18672.43 | 18038.16 | 18516.29 | 234321.0 |
| 2024-07-08T00:00:00Z | 18516.29 | 18791.89 | 18221.3 | 18721.78 | 284513.0 |
| 2024-07-15T00:00:00Z | 18721.78 | 18758.17 | 18153.13 | 18177.0 | 381121.0 |
| 2024-07-22T00:00:00Z | 18177.0 | 18660.12 | 18097.68 | 18471.24 | 493948.0 |
| 2024-07-29T00:00:00Z | 18471.24 | 18585.52 | 17620.9 | 17722.79 | 588012.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-06-01T00:00:00Z | 25058.57 | 25373.38 | 24510.36 | 24579.64 | 1925016.0 |
| 2026-06-08T00:00:00Z | 24579.64 | 24831.45 | 23965.03 | 24676.35 | 3862983.0 |
| 2026-06-15T00:00:00Z | 24676.35 | 25167.88 | 24676.35 | 24986.24 | 2331061.0 |
| 2026-06-22T00:00:00Z | 24986.24 | 25178.38 | 24557.82 | 24648.2 | 1945854.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('GER30_1w.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1D').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('GER30_1w.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('GER30_1w.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1W')
print(pf.stats())
```

## Download full data

The complete **GER30** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **2,943** rows at `1w`, plus all other timeframes in the same ZIP.

**[→ Get the full GER30 dataset on ork.ad](https://ork.ad/)**

---
*GetData · GER30 1w OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-06 UTC*