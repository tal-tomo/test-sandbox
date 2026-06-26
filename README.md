<div align="center">

# 🌐 OneWorld AI Platform

**Your team's shared brain for software engineering**

[![Website](https://img.shields.io/badge/Website-oneworldai.com-0969da?style=for-the-badge&logo=google-chrome&logoColor=white)](https://www.oneworldai.com)
[![Docs](https://img.shields.io/badge/Docs-docs.oneworldai.com-2da44e?style=for-the-badge&logo=readthedocs&logoColor=white)](https://docs.oneworldai.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](./LICENSE)

<br />

> OneWorld AI is an AI software engineering agent that runs in your terminal. It understands your entire
> codebase context and shares a knowledge graph across your team, so every engineer and agent collaborates
> from the same live context — never solving the same problem twice.

</div>

<br />

## ✨ Highlights

| Feature | Description |
|:--------|:------------|
| 💬 **Interactive Sessions** | Chat with the agent to build features, fix bugs, and explore codebases |
| ⚡ **Exec Mode** | Scriptable single-command execution for CI/CD and automation |
| 🔌 **MCP Integrations** | Extend the agent with external tools — Figma, databases, APIs, and more |
| 🔄 **Session Management** | Resume, fork, search, and sync sessions across machines |
| 🧠 **Knowledge Graph** | Shared context across agents and engineers in your organization |
| 📎 **File Uploads** | Upload images, videos, and files to provide visual context for the agent |
| ☁️ **Cloud Sandbox** | Code, build, and test from anywhere — no local setup required |
| 👥 **Cloud Team Collaboration** | Real-time collaboration across distributed teams — share context, sync progress, and co-develop in the cloud |

<br />

## 🚀 Getting Started

### Prerequisites

- **Git** 2.x+
- A **OneWorld AI** account — [sign up here](https://www.oneworldai.com)

### Install

> Visit [docs.oneworldai.com](https://docs.oneworldai.com/cli/getting-started/overview) for platform-specific instructions.

### Authenticate & Verify

```bash
oneworld login       # follow the prompts to save credentials
oneworld --version   # confirm installation
```

<br />

## 📖 Usage

### Interactive Mode

```bash
oneworld                                            # launch the agent
oneworld "review app.tsx and suggest improvements"  # start with a prompt
```

### Exec Mode (Non-Interactive)

```bash
oneworld exec "analyze this file and list all TODO comments"
oneworld exec - < prompt.txt                        # pipe from file
```

### Session Management

```bash
oneworld --resume              # resume most recent session
oneworld --resume <sessionId>  # resume a specific session
oneworld search "database migration"
```

### Update

```bash
oneworld update
```

<br />

## 🔌 MCP Integrations

Extend the agent with external tool servers:

```bash
oneworld mcp add <name> <url-or-command>
oneworld mcp remove <name>
```

**Example** — add Figma integration:

```bash
oneworld mcp add figma https://mcp.figma.com/mcp --type http
```

<br />

## 📚 Resources

<table>
  <tr>
    <td>📄 Documentation</td>
    <td><a href="https://docs.oneworldai.com">docs.oneworldai.com</a></td>
  </tr>
  <tr>
    <td>🏁 CLI Overview</td>
    <td><a href="https://docs.oneworldai.com/cli/getting-started/overview">Getting Started</a></td>
  </tr>
</table>

<br />

## 📝 License

This project is licensed under the [MIT License](./LICENSE).

---

<div align="center">
<sub>Built with ❤️ by the <a href="https://www.oneworldai.com">OneWorld AI</a> team</sub>
</div>
