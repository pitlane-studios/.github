<div align="center">

# Pitlane Studios

**Open-source, self-hosted server manager for Assetto Corsa.**

Run several Assetto Corsa dedicated servers from one web dashboard:
one Docker container per server, configured and monitored from the browser.

[![GitHub stars](https://img.shields.io/github/stars/pitlane-studios/pitlane?style=flat)](https://github.com/pitlane-studios/pitlane)
[![License: AGPL v3+](https://img.shields.io/badge/license-AGPL--3.0--or--later-blue.svg)](https://github.com/pitlane-studios/pitlane/blob/main/LICENSE)

[**Pitlane**](https://github.com/pitlane-studios/pitlane) · [Getting started](https://github.com/pitlane-studios/pitlane#getting-started) · [Roadmap](https://github.com/pitlane-studios/pitlane#roadmap) · [Discord](https://discord.gg/vNaVuc96YH)

</div>

> [!NOTE]
> **Early stage, pre-release.** There is no release or published Docker image yet.
> Star or watch [pitlane](https://github.com/pitlane-studios/pitlane) to follow progress.

## What is Pitlane?

Hosting more than one Assetto Corsa server by hand means juggling `server_cfg.ini`
files, port ranges and processes, and finding out a port is closed only when players
complain. Pitlane gives each server its own isolated container, writes its config
from a form, and shows its status, logs and port reachability in one place.

- **One container per server.** Create, start, stop, restart and delete Assetto Corsa
  dedicated servers, each isolated in Docker.
- **No hand-edited config.** Track and layout, cars, sessions, weather, grip,
  passwords and max clients are set from a form.
- **Port checks.** Conflict detection across servers, next free ports suggested, and a
  reachability check from your public IP.
- **Live monitoring.** Container status and server logs in the browser.
- **Share the controls, not root.** Owner, admin and operator roles; operators only
  see and run the servers assigned to them.

## What's next

Planned, not built yet. Tracked in the
[milestones](https://github.com/pitlane-studios/pitlane/milestones).

- One-command installer, guided first-run setup and a redesigned interface
- Multiple sessions per server, scheduled restarts, content upload, server cloning
- Public status page, crash alerts (Discord webhook, email), CPU and RAM monitoring, REST API

## Repositories

| Repository | What it is | Stack |
|---|---|---|
| [pitlane](https://github.com/pitlane-studios/pitlane) | The web app: Assetto Corsa server management dashboard | PHP 8.4, Symfony 8, PostgreSQL, Docker |
| [pitlane-bot](https://github.com/pitlane-studios/pitlane-bot) | Discord bot for the Pitlane community server (early stage) | TypeScript, discord.js |

## Get involved

- **Try it:** follow the [getting started guide](https://github.com/pitlane-studios/pitlane#getting-started).
- **Contribute:** pick a [`good first issue`](https://github.com/pitlane-studios/pitlane/labels/good%20first%20issue)
  or [`help wanted`](https://github.com/pitlane-studios/pitlane/labels/help%20wanted).
  Open an issue before starting anything large.
- **Talk:** questions, ideas or a server to show off? Join the [Discord](https://discord.gg/vNaVuc96YH).
- **Follow:** star or watch [pitlane](https://github.com/pitlane-studios/pitlane) to hear about the first release.

## License

All Pitlane projects are released under the
[AGPL-3.0-or-later](https://github.com/pitlane-studios/pitlane/blob/main/LICENSE).

<sub>Pitlane is an independent project and is not affiliated with or endorsed by
Kunos Simulazioni or Assetto Corsa.</sub>
