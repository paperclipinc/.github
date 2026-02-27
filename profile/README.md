<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/openclaw-rocks/.github/main/profile/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/openclaw-rocks/.github/main/profile/banner-light.svg">
  <img alt="OpenClaw.rocks - Your AI agent. Live in seconds." src="https://raw.githubusercontent.com/openclaw-rocks/.github/main/profile/banner-dark.svg" width="100%">
</picture>

&nbsp;

OpenClaw is an open-source framework for autonomous AI agents. Deploy personal assistants that clear inboxes, manage calendars, monitor prices, and run 3,400+ community automations. Connected to Telegram, Discord, WhatsApp, and Signal. Always on.

**[openclaw.rocks](https://openclaw.rocks)** &mdash; managed hosting, deploy in under a minute. Or self-host on any Kubernetes cluster.

---

### Repositories

| | Repository | What it does |
|---|---|---|
| **Operator** | **[k8s-operator](https://github.com/openclaw-rocks/k8s-operator)** | Kubernetes operator for OpenClaw instances. Secure by default, auto-updates, backup/restore, Prometheus observability, Chromium and Ollama sidecars. |
| **CLI** | **[kubectl-openclaw](https://github.com/openclaw-rocks/kubectl-openclaw)** | kubectl plugin for managing OpenClaw instances from the terminal. |
| **Config** | **[openclaw-config](https://github.com/openclaw-rocks/openclaw-config)** | Production-ready workspace template. Clone, add your API key, run. |
| **Skills** | **[skills](https://github.com/openclaw-rocks/skills)** | Community-maintained agent skills library. |
| **Status** | **[status](https://github.com/openclaw-rocks/status)** | Uptime monitor and public status page. |

### Quick Start

**Self-host on Kubernetes:**

```bash
helm install openclaw-operator \
  oci://ghcr.io/openclaw-rocks/charts/openclaw-operator \
  --namespace openclaw-system --create-namespace
```

**Managed hosting:** Sign up at [openclaw.rocks](https://openclaw.rocks) and connect your first channel in 60 seconds.

---

<sub>Built in Germany. Open source. [openclaw.rocks](https://openclaw.rocks) · [Status](https://openclaw-rocks.github.io/status/) · [hello@openclaw.rocks](mailto:hello@openclaw.rocks)</sub>
