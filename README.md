# daily-ai-news

Discovery-first daily AI news visualization focused on long-running data patterns.

## What is included

- `data/daily_ai_news_long_running.csv` — 190 days of daily AI news signals across seven themes.
- `visualizations/discovery_first_ai_news.html` — interactive dashboard with:
  - multi-series trend chart (time patterns)
  - weekday cadence heatmap (operational rhythms)
  - sentiment vs signal scatter (outlier discovery)

## Run locally

From repo root:

```bash
python -m http.server 8000
```

Then open:

- `http://localhost:8000/visualizations/discovery_first_ai_news.html`

## Discovery workflow

1. Scan the trend view to find spikes and sustained ramps.
2. Verify recurring cadence in the weekday heatmap.
3. Inspect high-signal outliers in the sentiment/signal scatter.
4. Form hypotheses only after pattern confirmation.
