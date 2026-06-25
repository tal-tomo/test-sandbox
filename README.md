# OneWorld AI Platform — Quick Start Guide

A concise onboarding guide for external customers to get up and running with [OneWorld AI](https://www.oneworldai.com).

## What is OneWorld AI?

OneWorld AI is the cloud platform where every session, every agent, and every engineer work from the same live context — so your whole company builds from the same brain and never solves the same problem twice.

Its CLI-based coding agent runs directly in your terminal, helping you write, review, debug, and refactor code through natural language conversations with full access to your local files, git, and shell.

Key capabilities:

- **Interactive coding sessions** — chat with the agent to build features, fix bugs, and explore codebases
- **Non-interactive (exec) mode** — scriptable single-command execution for CI/CD and automation
- **MCP integrations** — extend the agent with external tools (Figma, databases, APIs, etc.)
- **Session management** — resume, fork, search, and sync sessions across machines
- **Knowledge graph** — shared context across agents and engineers in your organization

## Installation

### Prerequisites

- Git 2.x+
- A OneWorld AI account — sign up at [oneworldai.com](https://www.oneworldai.com)

### Install the CLI

Visit [docs.oneworldai.com](https://docs.oneworldai.com/cli/getting-started/overview) for platform-specific installation instructions.

### Authenticate

```bash
oneworld login
```

Follow the prompts to log in and save your CLI credentials locally.

### Verify

```bash
oneworld --version
```

## Basic Usage

### Start an Interactive Session

```bash
oneworld
```

This launches the agent in interactive mode. You can type natural language prompts and the agent will read files, write code, run commands, and more.

You can also start with an initial prompt:

```bash
oneworld "review app.tsx and suggest improvements"
```

### Run a Single Command (Non-Interactive)

For scripting and automation, use `exec` mode:

```bash
oneworld exec "analyze this file and list all TODO comments"
```

You can also pipe input from a file:

```bash
oneworld exec - < prompt.txt
```

### Resume a Previous Session

```bash
oneworld --resume            # resume the most recent session
oneworld --resume <sessionId> # resume a specific session
```

### Search Past Sessions

```bash
oneworld search "database migration"
```

### Update the CLI

```bash
oneworld update
```

## Adding MCP Integrations

Extend the agent with external tool servers using the MCP (Model Context Protocol) system:

```bash
oneworld mcp add <name> <url-or-command>
```

Example — add the Figma integration:

```bash
oneworld mcp add figma https://mcp.figma.com/mcp --type http
```

Remove an integration:

```bash
oneworld mcp remove <name>
```

## Further Resources

- Official documentation: [docs.oneworldai.com](https://docs.oneworldai.com)
- CLI overview: [docs.oneworldai.com/cli/getting-started/overview](https://docs.oneworldai.com/cli/getting-started/overview)
