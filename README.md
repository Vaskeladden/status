# Vaskeladden Status

This repository hosts the status page for Vaskeladden services, powered by [Upptime](https://upptime.js.org).

## Monitored Services

- **Admin** - https://admin.vaskeladden.no
- **Meme** - https://meme.vaskeladden.no
- **Web** - https://web.vaskeladden.no
- **Dashboard** - https://dashboard.vaskeladden.no

## Status Page

Visit [status.vaskeladden.no](https://status.vaskeladden.no) to view the live status page.

## How It Works

- GitHub Actions monitors all services every 5 minutes
- Downtime automatically creates a GitHub Issue
- Status page is generated and deployed to GitHub Pages
- Slack notifications alert the team on incidents

## Configuration

Edit `.upptimerc.yml` to:
- Add/remove monitored services
- Configure notification channels
- Customize the status page appearance

## License

MIT - Upptime is open source
