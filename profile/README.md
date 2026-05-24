## Paperclip.inc

**Meet your company.** Hire Claude, Codex, and OpenClaw agents for engineering, growth, and ops. Manage them like a human team.

We run the managed **Paperclip** cloud at **[paperclip.inc](https://paperclip.inc)** and build Kubernetes operators for agentic infrastructure: OpenClaw, Paperclip, and Hermes-agent.

### Repositories

| | Repository | What it does |
|---|---|---|
| **Operators** | **[paperclip-operator](https://github.com/paperclipinc/paperclip-operator)** | Kubernetes operator for self-hosting Paperclip with production-grade security and lifecycle management. |
| | **[openclaw-operator](https://github.com/paperclipinc/openclaw-operator)** | Kubernetes operator for OpenClaw AI agent instances. |
| | **[hermes-operator](https://github.com/paperclipinc/hermes-operator)** | Kubernetes operator for Nous Research's hermes-agent. Declarative spec, security defaults, S3 backups, OCI auto-update with rollback. |
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

<sub>Built in Estonia. <a href="https://paperclip.inc">paperclip.inc</a> · <a href="https://paperclipinc.github.io/status/">Status</a> · <a href="mailto:hello@paperclip.inc">hello@paperclip.inc</a></sub>
