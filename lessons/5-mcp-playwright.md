# Lesson 5 — Testing with the Playwright MCP Server

**Topic:** External Tools
**Goal:** Add the Playwright MCP server and explore your feature in a browser

## Overview

In the previous lesson, you created and verified the filtering feature with automated tests. While tests validate code, allowing agents to confirm behavior through UI interaction is powerful — agents can respond to issues they observe in the actual interface. This lesson explores how Model Context Protocol (MCP) enables external capabilities for AI agents and adds the Playwright MCP server to let Copilot interact directly with your site.

## Learning Objectives

- Understand Model Context Protocol (MCP) and how the GitHub Copilot app uses it
- Add the Playwright MCP server from app settings
- Request the agent to operate a browser and explore your filtering feature

## Scenario

While unit and end-to-end tests matter, validating UI updates requires actual interaction. The goal is enabling Copilot to use your website as a user would, automating changes while providing greater confidence that updates work as intended.

## What is Model Context Protocol (MCP)?

MCP enables AI agents to communicate with external tools and services in real time. Through MCP, agents access current information (via resources) and perform actions (via tools). An MCP server bridges the AI agent and external tools or services, managing communication between them. Each MCP server represents a distinct set of accessible tools and resources.

Popular MCP servers include:

- **GitHub MCP Server** — provides APIs for managing GitHub repositories, including creating repositories, updating them, and handling issues and pull requests
- **Playwright MCP Server** — enables browser automation using Playwright, allowing agents to navigate pages, complete forms, and click buttons

The GitHub MCP registry enhances discoverability and contributions. Review MCP server source code, verify publishers, and evaluate security implications before use — only trust servers you've thoroughly assessed.

## Adding the Playwright MCP Server

1. Press `Ctrl+,` to open settings
2. Select **MCP servers**
3. Search for "Playwright"
4. Choose Playwright from Popular MCP servers
5. Select **Add server**
6. Press `Esc` to close

## Testing via Playwright

Use this prompt:

> "Start the dev server then use the Playwright MCP server to validate the functionality you just added exists. Use the details in the issue to ensure the newly added behavior matches the specs."

Copilot launches a browser through Playwright MCP, executes each step, and reports findings. You'll observe an actual browser opening on your system. Compare results against acceptance criteria; ask follow-up questions or request code fixes if needed.

## Summary

You've successfully:

- Learned about MCP and its app integration
- Added the Playwright MCP server from settings
- Directed the agent to operate a browser and test your filtering feature

Your feature is built, verified, and working.

## Resources

- What the heck is MCP and why is everyone talking about it?
- Microsoft Playwright MCP Server
- Configuring MCP servers in the GitHub Copilot app

## Next Steps

Continue to [Lesson 6 — Merging with Agent Merge](6-agent-merge.md) to open and merge the pull request.
