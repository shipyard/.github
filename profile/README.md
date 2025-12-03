<img src="https://shipyard.build/images/shipyard-teal.png" width="40%">

Welcome to Shipyard’s official GitHub! Here we offer some resources to help you get started with your deployments. For more information, [check out our docs.](https://docs.shipyard.build/)

## What’s Shipyard?

Shipyard is an **Environment Management** platform for developers and their agents. It creates ephemeral, on-demand copies of your app every time you open a PR. You can share these environments with SSO-enabled links, run E2E and unit tests against them, use them in agentic workflows, and integrate them into your CI/CD pipeline. With Shipyard, all you'll need to start deploying environments is a **Docker Compose** file.

## What’s an ephemeral environment?

Ephemeral environments are full-stack, production-like copies of your app. You're able to spin them up automatically when opening a new PR, and spin them down when you no longer need them. Ephemeral environments are an industry best practice when building and testing during pre-production. 

*Read more at [ephemeralenvironments.io](https://ephemeralenvironments.io)*

---

# Getting Started

If you haven’t already, [kick off a 30 day free trial](https://shipyard.build/signup).

## Starter Apps

These repos are fully Shipyard-ready. Fork your stack of choice:

[React + Flask + SQLAlchemy + LocalStack](https://github.com/shipyard/react-flask-starter)

[React + Express + PostgreSQL + LocalStack](https://github.com/shipyard/react-express-starter)

[React + Django + PostgreSQL + LocalStack](https://github.com/shipyard/react-django-starter)

[Jinja + Flask + SQLAlchemy](https://github.com/shipyard/flask-starter)

## Quickstart

[Read our Quickstart guide](https://docs.shipyard.build/quickstart) to get your app deploying on Shipyard.

---


# Resources

## Shipyard CLI

Install the [Shipyard CLI](https://github.com/shipyard/shipyard-cli) using Homebrew:

```sh
brew tap shipyard/tap
brew install shipyard
```

## Shipyard MCP Server

Use the [Shipyard MCP server](https://github.com/shipyard/shipyard-cli?tab=readme-ov-file#model-context-protocol-mcp-integration) to manage ephemeral environments with your coding agent.

Install for Claude Code:

`claude mcp add shipyard --env SHIPYARD_API_TOKEN=your-token-here --env SHIPYARD_ORG=your-org-name -- shipyard mcp serve`

Install for Codex CLI:

`codex mcp add shipyard --env SHIPYARD_API_TOKEN=your-token-here --env SHIPYARD_ORG=your-org-name -- shipyard mcp serve`


## Community
Want to engage with the Shipyard community? Send us an email at hello@shipyard.build. You can also:
- [Join our Slack](https://shipyardcommunity.slack.com/join/shared_invite/zt-1y44cpq6u-rJT~kg9wArqxP~N1F3K_pA#/shared-invite/email)
- [Check out our blog](https://shipyard.build/blog)
- [Follow us on LinkedIn](https://www.linkedin.com/company/shipyard)
- [Find us on Bluesky](https://bsky.app/profile/shipyard.build)
