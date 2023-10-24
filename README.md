# notify-teams

[![GitHub tag](https://img.shields.io/github/tag/interlok-tooling/notify-teams.svg)](https://github.com/interlok-tooling/notify-teams/tags) ![license](https://img.shields.io/github/license/interlok-tooling/notify-teams.svg)

Gradle action to notify a Teams channel when a build fails or recovers.

# Inputs

## teams-webhook-url

The Teams webhook URL

# Example

```yaml
uses: interlok-tooling/notify-teams@v1
with:
  teams-webhook-url: ${{ secrets.YOUR_TEAMS_WEBHOOK_URL }}
```
