# Optional — Incorporate Foundry

**Topic:** AI agents
**Goal:** Prepare a project and model, build and deploy a grounded agent, and connect it to the site

## Overview

This optional workshop section introduces a **Backer Concierge** feature for Tailspin Toys using Microsoft Foundry Canvas within GitHub Copilot. The journey progresses through three modules, each providing a checkpoint and safe stopping point.

## The Three-Module Journey

1. **Prepare Project and Model** — establishes catalog boundaries, creates the Foundry project and model deployment, and validates them in Canvas
2. **Build and Deploy the Agent** — scaffolds the Backer Concierge, conducts local testing, deploys the hosted agent, and retests it
3. **Connect the Agent to the Site** — adds a local credential-safe proxy, implements an accessible chat widget, and creates end-to-end tests

## Important Considerations

- Microsoft Foundry Canvas and hosted agents remain in **public preview**
- The journey creates **billable Azure resources** requiring subscription, region, quota, and cost approval
- Cleanup guidance applies even when stopping after module completion

## Resource Cleanup Instructions

You must remove Azure resources to avoid charges. The guide provides terminal commands for:

- Stopping local services and servers
- Running `azd down --purge` for hosted agent deployments
- Verifying subscription and resource group status
- Deleting the dedicated workshop resource group (`rg-tailspin-toys`)

## Next Steps

Continue to [Lesson 9 — Review and next steps](9-review.md).
