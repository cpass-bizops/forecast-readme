# RevOps Pipeline Forecast

A per-deal forecasting model that turns a raw CRM pipeline export into a defensible quarter-end number. It scores every open deal's probability of closing, rolls those scores into a quarter-end forecast with a confidence band, and backtests itself against closed history so you know how much to trust the output.

Built for RevOps and sales leaders who are tired of forecasts that are really just negotiations.

## What it does

- Scores close probability for every open deal using stage, age, and historical conversion patterns
- Produces a quarter-end forecast with a low / expected / high confidence band, not a single fragile number
- Backtests against closed-won and closed-lost history and reports its own accuracy
- Surfaces the deals that move the forecast the most, so you know where to focus

## Inputs

A standard pipeline export (CSV) from Salesforce or any CRM, with columns such as:

| Column | Description |
| --- | --- |
| Deal ID | Unique opportunity identifier |
| Stage | Current pipeline stage |
| Amount | Deal value |
| Close Date | Expected close date |
| Created Date | When the deal entered pipeline |
| Owner | Rep or team |

## Outputs

- Per-deal close probability
- Quarter-end forecast with a confidence band
- Backtest accuracy summary against historical closes
- A leadership-ready summary of what to trust and why

## Access

The full model and code live in a private repository. Comment FORECAST on my LinkedIn post and I will send you access.

---

Built by Chris Passarella. https://chrispassarella.com
