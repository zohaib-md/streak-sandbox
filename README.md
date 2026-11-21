# streak-sandbox

A small sandbox repo used to keep the daily GitHub contribution streak alive.

## What's here

| File | Purpose |
| --- | --- |
| `streak.txt` | Append-only activity log, updated by the daily streak workflow |
| `.github/workflows/streak.yml` | Scheduled job that appends a timestamp to `streak.txt` |

## How it works

A GitHub Actions schedule runs once a day and commits a new line to `streak.txt`.
Nothing here is meant for production use — it exists purely to keep the
contribution graph warm and to have a safe place to test git workflows.
