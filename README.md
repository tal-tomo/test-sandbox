<div align="center">

# 🌐 OneWorld AI Platform

**Your team's shared brain for software engineering**

<br />

[![Website](https://img.shields.io/badge/Website-oneworldai.com-0969da?style=for-the-badge&logo=google-chrome&logoColor=white)](https://www.oneworldai.com)
[![Docs](https://img.shields.io/badge/Docs-docs.oneworldai.com-2da44e?style=for-the-badge&logo=readthedocs&logoColor=white)](https://docs.oneworldai.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](./LICENSE)

<br />

<img src="https://img.shields.io/badge/Built_with-AI-blueviolet?style=flat-square" />
<img src="https://img.shields.io/badge/Platform-macOS%20%7C%20Linux%20%7C%20Windows-informational?style=flat-square" />

<br /><br />

> 💡 OneWorld AI is an AI software engineering agent that runs in your terminal. It understands your entire
> codebase context and shares a knowledge graph across your team, so every engineer and agent collaborates
> from the same live context — never solving the same problem twice.

</div>

---

## ✨ Highlights

<table>
  <tr>
    <td>💬</td><td><b>Interactive Sessions</b></td>
    <td>Chat with the agent to build features, fix bugs, and explore codebases</td>
  </tr>
  <tr>
    <td>⚡</td><td><b>Exec Mode</b></td>
    <td>Scriptable single-command execution for CI/CD and automation</td>
  </tr>
  <tr>
    <td>🔌</td><td><b>MCP Integrations</b></td>
    <td>Extend the agent with external tools — Figma, databases, APIs, and more</td>
  </tr>
  <tr>
    <td>🔄</td><td><b>Session Management</b></td>
    <td>Resume, fork, search, and sync sessions across machines</td>
  </tr>
  <tr>
    <td>🧠</td><td><b>Knowledge Graph</b></td>
    <td>Shared context across agents and engineers in your organization</td>
  </tr>
  <tr>
    <td>📎</td><td><b>File Uploads</b></td>
    <td>Upload images, videos, and files to provide visual context</td>
  </tr>
  <tr>
    <td>☁️</td><td><b>Cloud Sandbox</b></td>
    <td>Code, build, and test from anywhere — no local setup required</td>
  </tr>
  <tr>
    <td>👥</td><td><b>Team Collaboration</b></td>
    <td>Real-time collaboration — share context, sync progress, and co-develop</td>
  </tr>
  <tr>
    <td>🔗</td><td><b>Session Sharing</b></td>
    <td>Share sessions with your team — view, continue, or collaborate together</td>
  </tr>
  <tr>
    <td>💰</td><td><b>USD1 Crypto Payments</b></td>
    <td>Pay with USD1 stablecoin — fast, secure cryptocurrency payments</td>
  </tr>
</table>

---

## 🚀 Getting Started

### Prerequisites

| Requirement | Version |
|:--|:--|
| Git | 2.x+ |
| OneWorld AI Account | [Sign up here](https://www.oneworldai.com) |

### Install

> 📦 Visit [docs.oneworldai.com](https://docs.oneworldai.com/cli/getting-started/overview) for platform-specific instructions.

### Authenticate & Verify

```bash
oneworld login       # follow the prompts to save credentials
oneworld --version   # confirm installation
```

---

## 📖 Usage

<details>
<summary><b>💬 Interactive Mode</b></summary>

<br />

```bash
oneworld                                            # launch the agent
oneworld "review app.tsx and suggest improvements"  # start with a prompt
```

</details>

<details>
<summary><b>⚡ Exec Mode (Non-Interactive)</b></summary>

<br />

```bash
oneworld exec "analyze this file and list all TODO comments"
oneworld exec - < prompt.txt                        # pipe from file
```

</details>

<details>
<summary><b>🔄 Session Management</b></summary>

<br />

```bash
oneworld --resume              # resume most recent session
oneworld --resume <sessionId>  # resume a specific session
oneworld search "database migration"
```

</details>

<details>
<summary><b>🔁 Update</b></summary>

<br />

```bash
oneworld update
```

</details>

---

## 🔌 MCP Integrations

Extend the agent with external tool servers:

```bash
oneworld mcp add <name> <url-or-command>
oneworld mcp remove <name>
```

<details>
<summary><b>Example — Figma Integration</b></summary>

<br />

```bash
oneworld mcp add figma https://mcp.figma.com/mcp --type http
```

</details>

---

## 📚 Resources

| | Link |
|:--|:--|
| 📄 Documentation | [docs.oneworldai.com](https://docs.oneworldai.com) |
| 🏁 CLI Overview | [Getting Started](https://docs.oneworldai.com/cli/getting-started/overview) |

---

## 📝 License

This project is licensed under the [MIT License](./LICENSE).

---

<div align="center">

<sub>Built with ❤️ by the <a href="https://www.oneworldai.com">OneWorld AI</a> team</sub>

</div>
