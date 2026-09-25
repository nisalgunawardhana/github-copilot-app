# Lesson 6 — Merging with Agent Merge

**Topic:** Merge
**Goal:** Let Agent Merge fix and land your filtering pull request

## Overview

This lesson teaches about **Agent Merge**, a feature that automates pull request management within the Copilot app. It covers enabling Agent Merge, watching it create PRs, run CI checks, and merge when conditions are met.

## Scenario

The demo-student-management-system project seeks automation for merging vetted and validated pull requests to accelerate development workflows.

## Key Concepts

Agent Merge:

- Automates the final stages of landing pull requests via the Copilot app
- "reads your pull request, addresses what's blocking it — fixing failing CI checks, responding to review comments, rebasing when needed — and merges it as soon as GitHub allows"
- Operates in the background and persists across app restarts
- Deactivates automatically after the PR merges
- Shifts merge responsibility from the user to the agent

## Instructional Steps

1. Return to the previous session with the filtering functionality
2. Select the dropdown adjacent to **Create PR**
3. Choose **Agent merge** to activate the feature

   ![The Create PR dropdown in the GitHub Copilot app expanded, with an arrow pointing to the Agent merge option](../images/lesson6-enable-agent-merge.webp)

4. Select the **Agent merge** button to initiate the process
5. Allow the agent to merge by selecting **Merge pull request** from the dropdown menu

   ![The Agent merge dropdown showing the agent's allowed actions — Address reviews, Fix CI failures, Resolve conflicts — with an arrow pointing to Merge pull request](../images/lesson6-agent-merge-merge.webp)

6. Wait for CI processes to complete successfully before the merge lands

## Learning Outcomes

- Understanding Agent Merge automation capabilities
- Enabling Agent Merge on active sessions
- Observing PR creation, CI execution, and successful merging

## Next Steps

Continue to [Lesson 7 — Planning with canvases](7-canvases.md).
