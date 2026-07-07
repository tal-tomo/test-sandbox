<div align="center">

<img src="https://img.shields.io/badge/OneWorld_AI-Platform-0969da?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJ3aGl0ZSI+PGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iMTAiLz48L3N2Zz4=&logoColor=white" alt="OneWorld AI" />

# OneWorld AI Platform

**Your team's shared brain for software engineering**

<br />

[![Website](https://img.shields.io/badge/Website-oneworldai.com-0969da?style=flat-square&logo=google-chrome&logoColor=white)](https://www.oneworldai.com)
&nbsp;
[![Docs](https://img.shields.io/badge/Docs-docs.oneworldai.com-2da44e?style=flat-square&logo=readthedocs&logoColor=white)](https://docs.oneworldai.com)
&nbsp;
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](./LICENSE)

<br />

<p>
OneWorld AI is an AI software engineering agent that runs in your terminal.<br/>
It understands your entire codebase context and shares a knowledge graph across your team,<br/>
so every engineer and agent collaborates from the same live context — never solving the same problem twice.
</p>

</div>

---

<br />

## Highlights

<table>
<tr>
<td width="50%">

**Interactive Sessions** — Chat with the agent to build features, fix bugs, and explore codebases

**Exec Mode** — Scriptable single-command execution for CI/CD and automation

**MCP Integrations** — Extend the agent with external tools (Figma, databases, APIs)

**Session Management** — Resume, fork, search, and sync sessions across machines

**Knowledge Graph** — Shared context across agents and engineers in your organization

</td>
<td width="50%">

**File Uploads** — Upload images, videos, and files to provide visual context

**Cloud Sandbox** — Code, build, and test from anywhere with no local setup

**Team Collaboration** — Real-time collaboration across distributed teams

**Session Sharing** — Share sessions with team members to view, continue, or collaborate

**USD1 Crypto Payments** — Fast, secure cryptocurrency payments with USD1 stablecoin

</td>
</tr>
</table>

<br />

## Getting Started

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

## Usage

<details>
<summary><b>Interactive Mode</b></summary>

<br />

```bash
oneworld                                            # launch the agent
oneworld "review app.tsx and suggest improvements"  # start with a prompt
```

</details>

<details>
<summary><b>Exec Mode (Non-Interactive)</b></summary>

<br />

```bash
oneworld exec "analyze this file and list all TODO comments"
oneworld exec - < prompt.txt                        # pipe from file
```

</details>

<details>
<summary><b>Session Management</b></summary>

<br />

```bash
oneworld --resume              # resume most recent session
oneworld --resume <sessionId>  # resume a specific session
oneworld search "database migration"
```

</details>

<details>
<summary><b>Update</b></summary>

<br />

```bash
oneworld update
```

</details>

<br />

## MCP Integrations

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

## Resources

| | |
|:--|:--|
| Documentation | [docs.oneworldai.com](https://docs.oneworldai.com) |
| CLI Overview | [Getting Started](https://docs.oneworldai.com/cli/getting-started/overview) |

<br />

## License

This project is licensed under the [MIT License](./LICENSE).

---

<div align="center">
<sub>Built with care by the <a href="https://www.oneworldai.com">OneWorld AI</a> team</sub>
</div>
