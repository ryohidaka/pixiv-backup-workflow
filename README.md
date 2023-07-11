# pixiv-backup-workflow

Output datas on Pixiv to CSV.

## Overview

This is a GitHub Actions workflow that uses [pixivpy](https://github.com/upbit/pixivpy)

## Notes

pixivpy is an unofficial API client. Please use it at your own risk.
We do not take any responsibility for any damages caused by the use of this tool.
Please use it with the understanding of the above.

## GitHub Actions Environment Variables

| Key             | Description                      | Example            |
| --------------- | -------------------------------- | ------------------ |
| `USER_ID`       | Your Pixiv ID for logging in     | `0123456`          |
| `REFRESH_TOKEN` | Refresh token for Pixiv          | `***_***`          |
| `USER_EMAIL`    | Email address to use for commits | `mail@example.com` |
| `GA_TOKEN`      | GitHub Personal Access Token     | `ghp_******`       |

## Workflows

### Backup Following Users

Get a list of users that the logged-in user is following. Output the CSV and commit the difference.

## Related

- [pixivpy](https://github.com/upbit/pixivpy)
