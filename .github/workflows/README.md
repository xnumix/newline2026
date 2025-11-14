# Deployment Workflow

Automatically deploys to the VM on every push to `main`.

## What it does

1. SSHs into the VM at 74.178.90.56 as root
2. Runs `/root/apps/newline/update.sh` which pulls latest changes and restarts the container

## Manual deployment

Actions tab → "Deploy to VM" → "Run workflow"
