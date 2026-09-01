<div align="center">
  <p align="center">
  <img src="assets/ryanpurge-readme-banner.png" alt="RyanSSER/RyanPurge" width="100%" />
</p>

  **A focused Discord plugin for safely removing your own messages.**

  [![Latest Release](https://img.shields.io/github/v/release/RyanSSER/RyanPurge?display_name=tag&label=release&color=5865f2)](https://github.com/RyanSSER/RyanPurge/releases/latest)
  [![Pages](https://github.com/RyanSSER/RyanPurge/actions/workflows/static.yml/badge.svg)](https://github.com/RyanSSER/RyanPurge/actions/workflows/static.yml)
  [![Install for Revenge](https://img.shields.io/badge/install%20for-Revenge-5865f2)](https://ryansser.github.io/RyanPurge/)

  <p>
    <a href="https://ryansser.github.io/RyanPurge/">Install RyanPurge</a>
    ·
    <a href="https://github.com/RyanSSER/RyanPurge/releases/tag/v1.0.8">View release</a>
    ·
    <a href="https://github.com/RyanSSER/RyanPurge/issues">Report an issue</a>
  </p>
</div>

> Deleting messages is better than deleting friendships; this plugin lets you safely and precisely delete your own messages from either a DM or a channel.

RyanPurge is an official **RyanOS** project for Revenge. It provides a deliberate workflow for selecting one DM or channel, reviewing matching messages, and removing only messages owned by the current account.

## Installation

Install RyanPurge directly from the official repository:

```text
https://ryansser.github.io/RyanPurge/
```

In Revenge versions that support plugin repositories, add the repository URL and install **RyanPurge 1.0.8**. If the + button asks for a direct plugin URL instead, use `https://ryansser.github.io/RyanPurge/index.js`. Use only the official RyanOS repository; unofficial mirrors, modified builds, and rebranded packages are not supported.

## Source code

The original readable TypeScript source is available in [`src/index.ts`](src/index.ts). The files in [`builds/com.ryanpurge`](builds/com.ryanpurge) are the compiled plugin artifacts used for installation and release packaging.

## Features

RyanPurge keeps the operation focused and reviewable. It includes safe preview, target selection for DMs and channels, date and content rules, inclusion and exclusion keywords, configurable session limits, deep-history exploration with checkpoints, pause and resume, paced execution, live progress, failed and skipped counters, session history, reports, and copyable audit details.

The interface supports **Arabic RTL** and **English LTR** layouts and is designed for clear and deliberate use.

## Safety boundaries

RyanPurge verifies message ownership before attempting a deletion and does not intentionally delete messages belonging to other accounts. Preview mode does not delete anything. The plugin does not request, store, or process an account token, and it uses the host application's available actions rather than an external REST client.

Discord and the host application may change internal behavior, permissions, message availability, or historical loading. Older history may therefore take longer or produce skipped or failed results when the host cannot expose a message or action. Review the report after every session.

## Official release

The current official release is **RyanPurge 1.0.8**. The exact package and release notes are available on the [GitHub release page](https://github.com/RyanSSER/RyanPurge/releases/tag/v1.0.8).

## Suggestions and contact

Suggestions, improvement ideas, and feature requests are welcome through the repository's [issue tracker](https://github.com/RyanSSER/RyanPurge/issues). For direct contact, reach **RyanOS on GitHub** on Discord.

When sharing screenshots or logs, remove private message contents, account identifiers, tokens, passwords, and other sensitive information first.

## Ownership and permissions

RyanPurge is proprietary software owned by **RyanOS**. No permission is granted to copy, modify, rebrand, rename, redistribute, sell, sublicense, or claim ownership of the plugin, its source code, interface, assets, or compiled package. GitHub visibility or forking does not create a separate license to publish an unofficial build.

Read the complete [proprietary terms](LICENSE.md), [contribution guidelines](CONTRIBUTING.md), [code of conduct](CODE_OF_CONDUCT.md), and [security policy](SECURITY.md).

## Reporting problems

For ordinary reproducible bugs, use the [bug report template](https://github.com/RyanSSER/RyanPurge/issues/new?template=bug_report.md). For feature ideas, use the [feature request template](https://github.com/RyanSSER/RyanPurge/issues/new?template=feature_request.md) or contact **RyanOS on GitHub** on Discord. For security vulnerabilities, follow [SECURITY.md](SECURITY.md) and report privately.

---

© 2026 **RyanOS**. All rights reserved.
