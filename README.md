<p align="center">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset=".github/logo-dark.svg">
    <source media="(prefers-color-scheme: dark)" srcset=".github/logo-light.svg">
    <img alt="CodePier" src=".github/logo-light.svg" width="320">
  </picture>
</p>

<h3 align="center">The visual command center for Kubernetes</h3>

<p align="center">
  <a href="https://github.com/codepier/codepier/releases/latest"><img alt="Latest Release" src="https://img.shields.io/github/v/release/codepier/codepier?style=flat-square&color=blue"></a>
  <img alt="Platforms" src="https://img.shields.io/badge/platform-macOS%20%7C%20Windows%20%7C%20Linux-lightgrey?style=flat-square">
  <a href="https://codepier.dev"><img alt="Website" src="https://img.shields.io/badge/codepier.dev-visit-blue?style=flat-square"></a>
</p>

---

<!-- Add a screenshot here: ![CodePier Screenshot](.github/screenshot.png) -->

**CodePier** is a desktop app that gives your team a single interface to develop, debug, and ship on Kubernetes — without wrestling with YAML and terminals.

Connect to your clusters, expose services locally, code inside containers, stream logs across pods, and manage releases — all from one window.

## Features

### Develop

- **Service Tunnels** — Expose remote Kubernetes services to your local machine with one click
- **Container Development** — Edit code running inside containers with real-time sync and hot reload
- **Log Streaming** — Stream and search logs across multiple pods simultaneously

### Ship

- **Release Management** — Build, track, and deploy releases with rollback support
- **Preview Environments** — Spin up isolated environments for branches and pull requests
- **Build Tracking** — Monitor builds and swap between versions instantly

### Operate

- **Cost Visibility** — See resource usage and cost breakdowns across namespaces and workloads
- **Secrets Management** — View and manage Kubernetes secrets safely
- **Drift Detection** — Know when live state diverges from your desired configuration
- **Git Sync** — Keep infrastructure in sync with your Git repository

### Collaborate

- **Team Workspaces** — Share cluster access and configurations across your team
- **Audit Logs** — Track who changed what, and when
- **Import Existing Workloads** — Bring in your current Kubernetes deployments with zero changes

## Download

<table>
  <tr>
    <td align="center"><b>macOS</b></td>
    <td align="center"><b>Windows</b></td>
    <td align="center"><b>Linux</b></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/codepier/codepier/releases/latest">Download .dmg</a></td>
    <td align="center"><a href="https://github.com/codepier/codepier/releases/latest">Download .exe</a></td>
    <td align="center"><a href="https://github.com/codepier/codepier/releases/latest">Download .AppImage</a></td>
  </tr>
</table>

Or browse all versions on the [Releases](https://github.com/codepier/codepier/releases) page.

## Getting Started

1. **Download** the app for your platform from the link above
2. **Sign in** to your CodePier account (or create one at [codepier.dev](https://codepier.dev))
3. **Connect a cluster** — add your kubeconfig or follow the guided setup
4. **Start developing** — tunnel services, stream logs, or swap into a container

## Auto Updates

CodePier checks for updates automatically and installs them in the background. You'll always be on the latest version without lifting a finger.

## CLI Companion

For terminal-first workflows, the **CodePier CLI** lets you swap Kubernetes pods with your local dev environment directly from the command line.

Install it from [codepier/codepier-cli](https://github.com/codepier/codepier-cli).

## Links

- [Website](https://codepier.dev) — Learn more about CodePier
- [CodePier CLI](https://github.com/codepier/codepier-cli) — Kubernetes dev environment swap from the terminal
