<p align="center">
  <img height="300" src="https://avatars.githubusercontent.com/u/86734767">
  <h1 align="center">Citadel</h1>
</p>

Citadel allows you to run your own Bitcoin Lightning node and personal server. It is proudly **free and open-source** software. Anyone is free to use, copy, study and change the software in any way as well as distribute it for commercial purposes.

### Our mission

We aim to provide secure nodes and servers for everyone where _you_ are in control of your data, not a big company. We make contributions to various open source projects used on Citadel to make sure we're giving back to the community we build on.

## Overview

#### 💡 Have an idea for a feature? [Discuss a topic](https://github.com/runcitadel/citadel/discussions/new)

#### ⁉ Something isn't working? [Create an issue](https://github.com/runcitadel/citadel/issues/new)

#### 💬 Need help getting started? [Telegram](https://t.me/runcitadel) / [Discord](https://discord.gg/6U3kM2cjdB)

#### 🗞️ Stay up to date: [Twitter](https://twitter.com/runcitadel) / [Blog](https://blog.runcitadel.space)

#### 📚 Find guides & best practices: [Wiki](https://wiki.runcitadel.space)

## Installation

There are many ways to install Citadel. Depending on your hardware and operating system you can follow one of the below step-by-step guides to get started.

#### Raspberry Pi 4: [runcitadel.space/setup](https://runcitadel.space/setup)

#### Debian / Ubuntu: [runcitadel.space/x86](https://runcitadel.space/x86)

#### Migrate from Umbrel: [runcitadel.space/migrate](https://runcitadel.space/migrate)

#### Docker + Sysbox (experimental): [github.com/runcitadel/citadel-dev](https://github.com/runcitadel/citadel-dev)

## Citadel vs. Umbrel

Citadel is a mostly open source and soon to be fully FLOSS Lightning Node implementation based on [Umbrel](https://github.com/getumbrel/umbrel). Most of the codebase has been rewritten and moved away from Umbrel. Citadel offers many improvements over Umbrel:

- faster operating system optimized for Raspberry Pi
- independent and therefore faster app updates
- our own, up-to-date user interface with built-in dark mode
- listening node by default

## Roadmap

Citadel is fully transparent and built by the community. To see milestones and follow current development view the [project board](https://github.com/orgs/runcitadel/projects/3).

## Repositories

| Name                                                     | Description                                                    |
| -------------------------------------------------------- | -------------------------------------------------------------- |
| [citadel](https://github.com/runcitadel/citadel/)        | This overview, issues, discussions and project management      |
| [core](https://github.com/runcitadel/core)               | The core of Citadel                                            |
| [dashboard](https://github.com/runcitadel/dashboard)     | Current frontend                                               |
| [middleware](https://github.com/runcitadel/middleware)   | Communication with bitcoin & lightning implementations         |
| [manager](https://github.com/runcitadel/manager)         | Manages containers, authentication & misc.                      |
| [sdk](https://github.com/runcitadel/sdk)                 | Library to connect applications to Citadel                     |
| [apps](https://github.com/runcitadel/apps)               | Free, open source apps available on Citadel                    |
| [citadel-dev](https://github.com/runcitadel/citadel-dev) | CLI tool to spin up instances of Citadel in a Docker container |

## Contributing

We welcome and appreciate new contributions! The best way to get started is to reach out to us on [Telegram](https://t.me/runcitadel).

## License

Citadel is licensed under the GNU Affero General Public License v3.0 or later.

It includes code from `umbrel-os` and `pi-gen`, which are

```
Copyright (c) 2015 Raspberry Pi (Trading) Ltd.
Copyright (c) 2020 Umbrel. https://getumbrel.com/
```

Additionally, the current dashboard contains code from [Casa](https://github.com/Casa/V2-Casa-Node-UI) and [Umbrel](https://github.com/getumbrel/umbrel-dashboard).

---

_"Being open source means anyone can independently review the code. If it was closed source, nobody could verify the security. I think it's essential for a program of this nature to be open source." — Satoshi Nakamoto_

[![License: AGPL-3.0](https://img.shields.io/badge/License-AGPL%203.0-blue.svg)](https://opensource.org/licenses/AGPL-3.0)
