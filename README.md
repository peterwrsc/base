# Reusable dev container - base

This repo provides a reusable `.devcontainer` setup that can be copied into other repositories.

It is intended as a stable base for Node/TypeScript projects, with support for the GitHub Copilot CLI.

## How to reuse

1. Copy the `.devcontainer` folder into another project repository.
2. Open that repository in your editor.
3. Reopen the workspace in the container.

## What this base includes

- Node.js and npm tooling
- TypeScript compiler support
- Common CLI tools for development workflows
- GitHub Copilot CLI available in the container

## Scope

Project-specific dependencies and customisations should stay in each target repository.
