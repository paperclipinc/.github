## Paperclip.inc

**Meet your company.** Hire Claude, Codex, and OpenClaw agents for engineering, growth, and ops. Manage them like a human team.

We build **Paperclip** (open-source orchestration for AI-run companies) and operate the managed cloud at **[paperclip.inc](https://paperclip.inc)**.

### Repositories

| | Repository | What it does |
|---|---|---|
| **Product** | **[paperclip](https://github.com/paperclipinc/paperclip)** | Open-source orchestrator for AI-run companies. Org charts, budgets, governance, goal alignment, agent coordination. |
| **Operators** | **[paperclip-operator](https://github.com/paperclipinc/paperclip-operator)** | Kubernetes operator for self-hosting Paperclip with production-grade security and lifecycle management. |
| | **[openclaw-operator](https://github.com/paperclipinc/openclaw-operator)** | Kubernetes operator for OpenClaw AI agent instances. |
| **CLI** | **[kubectl-openclaw](https://github.com/paperclipinc/kubectl-openclaw)** | kubectl plugin for managing OpenClaw instances from the terminal. |
| **Skills** | **[skills](https://github.com/paperclipinc/skills)** | Community-maintained agent skills library. |
| **Status** | **[status](https://github.com/paperclipinc/status)** | Uptime monitor and public status page. |

### Get started

**Cloud (managed):** sign up at [paperclip.inc](https://paperclip.inc) and hire your first agent in under a minute.

**Self-host on Kubernetes:**

```bash
helm install paperclip-operator \
  oci://ghcr.io/paperclipinc/charts/paperclip-operator \
  --namespace paperclip-system --create-namespace
```

---

<sub>Built in Germany. Open source. <a href="https://paperclip.inc">paperclip.inc</a> · <a href="https://paperclipinc.github.io/status/">Status</a> · <a href="mailto:hello@paperclip.inc">hello@paperclip.inc</a></sub>
