# Daily Logs

This repository auto-commits a daily log using GitHub Actions.

The workflow runs every day at `00:00 UTC` and can also be triggered manually with `workflow_dispatch`.

Generated files:

- `logs/daily.log` appends a timestamped entry for each run
- `logs/latest.md` stores the latest run summary in Markdown
