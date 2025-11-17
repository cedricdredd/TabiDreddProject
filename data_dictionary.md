# Data Dictionary: monthly_panel.csv

| Column | Description |
|--------|-------------|
| `rate_level` | Monthly average effective federal funds rate (percent). |
| `sp500_close` | S&P 500 month-end closing level. |
| `realized_vol` | Realized monthly volatility: standard deviation of daily S&P 500 returns within the month. |
| `monthly_return` | Simple monthly return of the S&P 500 based on month-end close. |
| `ret_1m_fwd` | 1-month forward S&P 500 return from this month’s close. |
| `ret_3m_fwd` | 3-month forward S&P 500 return from this month’s close. |
| `ret_6m_fwd` | 6-month forward S&P 500 return from this month’s close. |
| `rate_change` | Month-over-month change in the effective federal funds rate (percentage points). |
| `target_upper` | Monthly average federal funds target upper bound (if available). |
| `target_lower` | Monthly average federal funds target lower bound (if available). |
| `vix_mean` | Monthly average of the CBOE Volatility Index VIX (if available). |
| `high_rate_regime` | Indicator = 1 if rate_level is above the sample median, 0 otherwise. |
| `rising_rate_regime` | Indicator = 1 if monthly rate_change > 0, 0 otherwise. |