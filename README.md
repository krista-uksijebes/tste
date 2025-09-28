# tste activity automation

This repository contains helper scripts for generating Git activity via the GitHub CLI.

- `backfill_commits.py` creates backdated commits that append to `keep.log`.
- `auto_activity.py` prepares quick PRs and issues for smoke tests.
- `activity_automation.py` coordinates the two scripts and can batch-create commits, PRs, and issues.

Run `python3 activity_automation.py --help` for usage details.
