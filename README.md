# coder helper scripts

Some basic helper scripts I use to manage https://ben.cdr.dev (a VM)

## Features

- Create arbitrary DB backups
- Restore to an arbitary DB backup
- Upgrade to latest version (and run backup priorr)
- Upgrade to an un-released build artifact (and run backup prior)
- Downgrade to a version (and restore from a backup)

## Requirements

- `gh` CLI is installed and authenticated
- `$CODER_HELPERS_WORKSPACE` is set to the dir of your workspace (e.g. `/home/coder/coder-helper-scripts`)
- You are running Coder as a system service on a Debian or Ubuntu VM