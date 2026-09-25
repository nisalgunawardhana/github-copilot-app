# Lesson 1 — Install the Copilot App

**Topic:** Setup
**Goal:** Install the app, connect your project, and get oriented in the workspace

## Overview

The GitHub Copilot app is **a desktop application for agent-driven development** that integrates with GitHub repositories, branches, and CI pipelines. This lesson guides you through installation, authentication, and initial workspace orientation.

## Learning Objectives

- Install the GitHub Copilot app and authenticate with GitHub
- Add your project repository to the application
- Navigate the workspace and locate pre-populated issues
- Conduct a quick chat conversation within the app

## Scenario

A team is adopting AI agents to manage a growing backlog. The Copilot app serves as a centralized hub for directing agent work, managing issues, executing agents, reviewing changes, and merging pull requests.

## Installation Steps

1. Visit the GitHub Copilot app landing page
2. Download the version matching your operating system (Windows, macOS, or Linux)
3. Launch the application after installation
4. Select **Sign in to GitHub** and complete authentication
5. Choose your `demo-student-management-system` fork during setup
6. Select your theme preferences and complete onboarding

## Workspace Navigation

The sidebar contains four main sections:

- **Sessions** — isolated workspaces where agents operate independently
- **Quick chats** — conversational features for questions and brainstorming
- **My work** — native GitHub integration displaying issues and pull requests
- **Automations** — scheduled or on-demand agent tasks

## Backlog

The official workshop's Tailspin Toys template seeds a backlog of issues automatically. Since `demo-student-management-system` is a fork rather than a template instance, create a few issues yourself to follow along, for example:

- Allow users to filter students by class or status
- Update repository coding standards
- Implement pagination on the student list page

## Quick Chat Feature

Use quick chats to ask lightweight questions without creating a branch or session. Example prompt:

> "How does the GitHub Copilot app use worktrees?"

This feature is designed for a "fast, throwaway question" that requires no session setup.

## Key Takeaway

Each session runs in its own isolated git worktree, enabling parallel agent execution without conflicting changes.

## Next Steps

Continue to [Lesson 2 — Running your first agent session](2-add-star-rating.md) to ship your first small change with an agent.
