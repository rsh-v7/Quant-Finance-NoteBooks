# Data

CSV files are not committed (LIBOR-derived and AMERIBOR data are licensed). Download each into this folder with the filename shown:

| File | Series | Source |
|---|---|---|
| `DTB3.csv` | 3-Month Treasury Bill, secondary market rate, daily | [FRED: DTB3](https://fred.stlouisfed.org/series/DTB3) |
| `TEDRATE.csv` | TED Spread, daily (ends 2022-01-21) | [FRED: TEDRATE](https://fred.stlouisfed.org/series/TEDRATE) |
| `AMBOR90T.csv` | AMERIBOR Term-90, daily | [macrotrends](https://www.macrotrends.net/4334/ameribor-term-90-rate-index) |

FRED downloads use the default CSV format (`observation_date,<SERIES>`). The AMERIBOR file is expected with columns `Date,Value` and dates as `MM/DD/YYYY`.
