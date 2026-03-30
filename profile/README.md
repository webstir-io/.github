# Webstir

Webstir is a server-first, HTML-first framework for building low-JS web apps. The active implementation now lives in the `webstir` monorepo and centers on the Bun orchestrator plus the canonical TypeScript packages under `packages/**`.

## Status
- Experimental and learning-focused — great for exploring ideas and workflows, not yet intended for production workloads.
- APIs, contracts, and workflows may change without notice while the ecosystem stabilizes.
- The active path is the Bun-based monorepo workflow, not the older split-repo or `.NET`-hosted layout.

## Start Here
- [Webstir Monorepo](https://github.com/webstir-io/webstir) — canonical source for the framework, docs, demos, and Bun orchestrator
- [Docs Index](https://github.com/webstir-io/webstir/tree/main/apps/portal/docs) — getting started guides, workflows, explanations, and reference docs
- [Package Registry](https://github.com/orgs/webstir-io/packages) — published packages and release artifacts

## Ecosystem Snapshot
- `webstir`: canonical monorepo for framework code, docs, examples, and the active Bun workflow
- `module-contract` and `testing-contract`: shared contracts for framework plugins and test tooling
- `webstir-frontend`, `webstir-backend`, and `webstir-testing`: published package identities whose active source now lives in the monorepo
- Older split repos like `webstir-dotnet`, `webstir-portal`, `webstir-demos`, and `webstir-hub` remain useful historical or focused references, but they are not the main entrypoint anymore

## Ways to Contribute
- Review the [Code of Conduct](../CODE_OF_CONDUCT.md) and [Contributing](../CONTRIBUTING.md) guidelines
- Check [Security](../SECURITY.md) and [Support](../SUPPORT.md) expectations before reporting vulnerabilities or opening help requests
- Start in [`webstir`](https://github.com/webstir-io/webstir) unless you already know you need a focused provider or historical repo
- Try the tutorials, file issues, or open pull requests with improvements
