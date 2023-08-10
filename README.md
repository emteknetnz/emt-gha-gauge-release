# GitHub Actions - Gauage release

Gauge whether should do a patch release

Action is designed to be used only within gha-ci and gha-action-ci

This step can be run in a job that has not not run actions/checkout

## Inputs

latest_local_sha (required) - The result of $(git rev-parse HEAD)
