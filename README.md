<div align="center">

# OneWorld AI Platform

### Your team's shared brain for software engineering

[![Website](https://img.shields.io/badge/Website-oneworldai.com-blue?style=flat-square)](https://www.oneworldai.com)
[![Docs](https://img.shields.io/badge/Docs-docs.oneworldai.com-green?style=flat-square)](https://docs.oneworldai.com)

</div>

---

- **Interactive coding sessions** — chat with the agent to build features, fix bugs, and explore codebases
- **Non-interactive (exec) mode** — scriptable single-command execution for CI/CD and automation
- **MCP integrations** — extend the agent with external tools (Figma, databases, APIs, etc.)
- **Session management** — resume, fork, search, and sync sessions across machines
- **Knowledge graph** — shared context across agents and engineers in your organization
- **File uploads** — upload images, videos, and other files directly within a session to provide visual context, enabling the agent to analyze screenshots, UI mockups, error recordings, and more
- **Cloud sandbox** — develop entirely in the cloud with OneWorld's sandbox environment, enabling developers to code, build, and test from anywhere without local setup
> **OneWorld AI** is the cloud platform where every session, every agent, and every engineer work from the same live context — so your whole company builds from the same brain and never solves the same problem twice.

## Highlights

| Feature | Description |
|---------|-------------|
| **Interactive Sessions** | Chat with the agent to build features, fix bugs, and explore codebases |
| **Exec Mode** | Scriptable single-command execution for CI/CD and automation |
| **MCP Integrations** | Extend the agent with external tools (Figma, databases, APIs, etc.) |
| **Session Management** | Resume, fork, search, and sync sessions across machines |
| **Knowledge Graph** | Shared context across agents and engineers in your organization |
| **Cloud Sandbox** | Code, build, and test from anywhere without local setup |

---

## Getting Started

### Prerequisites

- Git 2.x+
- A OneWorld AI account — [sign up here](https://www.oneworldai.com)

### Install

> Visit [docs.oneworldai.com](https://docs.oneworldai.com/cli/getting-started/overview) for platform-specific instructions.

### Authenticate & Verify

```bash
oneworld login       # follow the prompts to save credentials
oneworld --version   # confirm installation
```

---

## Usage

### Interactive Mode

```bash
oneworld                                        # launch the agent
oneworld "review app.tsx and suggest improvements"  # start with a prompt
```

### Exec Mode (Non-Interactive)

```bash
oneworld exec "analyze this file and list all TODO comments"
oneworld exec - < prompt.txt                    # pipe from file
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

---

## MCP Integrations

Extend the agent with external tool servers:

```bash
oneworld mcp add <name> <url-or-command>
oneworld mcp remove <name>
```

**Example** — add Figma:

```bash
oneworld mcp add figma https://mcp.figma.com/mcp --type http
```

---

## Resources

| | Link |
|---|---|
| Documentation | [docs.oneworldai.com](https://docs.oneworldai.com) |
| CLI Overview | [Getting Started](https://docs.oneworldai.com/cli/getting-started/overview) |

---

<div align="center">
<sub>Built with care by the OneWorld AI team</sub>
</div>
