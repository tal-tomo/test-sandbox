<div align="center">

<br />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/%E2%9C%A6_OneWorld_AI-Platform-58a6ff?style=for-the-badge&labelColor=1f2328">
  <img src="https://img.shields.io/badge/%E2%9C%A6_OneWorld_AI-Platform-0969da?style=for-the-badge&labelColor=f6f8fa" alt="OneWorld AI" />
</picture>

<br /><br />

<h1>OneWorld AI</h1>

<h4>Your team's shared brain for software engineering</h4>

<br />

<a href="https://www.oneworldai.com"><img src="https://img.shields.io/badge/Website-oneworldai.com-0969da?style=flat-square&logo=google-chrome&logoColor=white" alt="Website" /></a>
<a href="https://docs.oneworldai.com"><img src="https://img.shields.io/badge/Docs-docs.oneworldai.com-2da44e?style=flat-square&logo=readthedocs&logoColor=white" alt="Docs" /></a>
<a href="./LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow?style=flat-square" alt="License: MIT" /></a>

<br /><br />

<p>
  <em>An AI software engineering agent that runs in your terminal.<br/>
  It understands your entire codebase and shares a knowledge graph across your team,<br/>
  so every engineer and agent collaborates from the same live context —<br/>
  never solving the same problem twice.</em>
</p>

<br />

</div>

---

<br />

## Highlights

<table>
  <tr>
    <th align="left" width="50%">Core</th>
    <th align="left" width="50%">Cloud & Payments</th>
  </tr>
  <tr>
    <td valign="top">

| | |
|:--|:--|
| **Interactive Sessions** | Build features, fix bugs, explore codebases |
| **Exec Mode** | Scriptable execution for CI/CD pipelines |
| **MCP Integrations** | Figma, databases, APIs, and more |
| **Session Management** | Resume, fork, search, sync across machines |
| **Knowledge Graph** | Shared context for your entire org |

  </td>
    <td valign="top">

| | |
|:--|:--|
| **File Uploads** | Images, videos, and files for visual context |
| **Cloud Sandbox** | Code, build, and test — no local setup |
| **Team Collaboration** | Real-time across distributed teams |
| **Session Sharing** | View, continue, or co-develop any session |
| **USD1 Payments** | Fast, secure stablecoin transactions |

  </td>
  </tr>
</table>

<br />

## Getting Started

```bash
# 1. Install (see docs for platform-specific steps)
# https://docs.oneworldai.com/cli/getting-started/overview

# 2. Authenticate
oneworld login

# 3. Verify
oneworld --version
```

> **Prerequisites:** Git 2.x+ and a [OneWorld AI account](https://www.oneworldai.com)

<br />

## Usage

<details open>
<summary><strong>Interactive Mode</strong></summary>

```bash
oneworld                                            # launch the agent
oneworld "review app.tsx and suggest improvements"  # start with a prompt
```

</details>

<details>
<summary><strong>Exec Mode</strong> — non-interactive, CI/CD friendly</summary>

```bash
oneworld exec "analyze this file and list all TODO comments"
oneworld exec - < prompt.txt                        # pipe from file
```

</details>

<details>
<summary><strong>Session Management</strong></summary>

```bash
oneworld --resume              # resume most recent session
oneworld --resume <sessionId>  # resume a specific session
oneworld search "database migration"
```

</details>

<details>
<summary><strong>Update</strong></summary>

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

<details>
<summary><strong>Example:</strong> Add Figma integration</summary>

```bash
oneworld mcp add figma https://mcp.figma.com/mcp --type http
```

</details>

<br />

## Resources

<div align="center">

| | |
|:--|:--|
| Documentation | **[docs.oneworldai.com](https://docs.oneworldai.com)** |
| CLI Overview | **[Getting Started Guide](https://docs.oneworldai.com/cli/getting-started/overview)** |

</div>

<br />

## License

Licensed under the [MIT License](./LICENSE).

---

<div align="center">
<br />
<sub>Built with care by the <a href="https://www.oneworldai.com">OneWorld AI</a> team — powering the future of collaborative engineering</sub>
<br /><br />
</div>
