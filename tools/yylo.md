---
slug: "yylo"
name: "YYLO"
description: "Command-line orchestrator for coding agents with typed task, validation, merge, and release-readiness boundaries and receipt-backed repository changes"
agentSummary: "YYLO is for developers and project operators who want coding agents to work through explicit repository boundaries. In Advanced workspaces it creates exact-base task worktrees, collects receipt-backed validation evidence, and lands completed changes through a managed one-task native Git merge whose verified Git result is recorded with separate, retryable Ledger projection; tests and semantic review remain explicit external project checks. Agent providers and release or deployment authority remain external."
seoTitle: "YYLO: Typed Task Orchestration for Coding Agents"
seoDescription: "Explore YYLO's Advanced-mode workflow for isolated coding-agent task worktrees, receipt-backed validation, and managed native Git delivery for repository changes."
category: "orchestrators"
tags:
  - "coding-agents"
  - "cli"
  - "git-worktrees"
  - "task-management"
  - "native-git"
websiteUrl: "https://yylo.dev"
githubUrl: "https://github.com/yylo-dev/yylo"
pricing: "open-source"
classification: "agent-native"
entityType: "software-application"
developerName: "YYLO"
docsUrl: "https://github.com/yylo-dev/yylo#readme"
licenseUrl: "https://github.com/yylo-dev/yylo/blob/main/LICENSE"
interfaces:
  - "CLI"
deploymentModes:
  - "local"
evidenceSources:
  - title: "YYLO CLI repository README"
    url: "https://github.com/yylo-dev/yylo"
    claim: "The README describes YYLO as a command-line orchestrator for coding agents, repeatable workflows, and receipt-backed repository changes, with typed task, validation, merge, and release-readiness boundaries, and documents agent runs through commands such as yy pi and the agent aliases it lists."
    accessedAt: "2026-09-08"
    sourceType: "official-repository"
  - title: "YYLO CLI typed task and merge flow documentation"
    url: "https://github.com/yylo-dev/yylo#typed-task-and-merge-flow"
    claim: "The documentation describes task start freezing the protected target SHA and creating a dedicated branch/worktree for implementation in Advanced workspaces, finish gating that verifies a clean committed result and queues it without merging (preflight is optional, read-only diagnostics, not a gate), and merge land composing one immutable task source with native Git and expected-old ref protection. Tests and semantic reviews are explicit project checks outside merge, which launches no models, chooses no reviewers, schedules no suites, and maintains no validation cache."
    accessedAt: "2026-09-29"
    sourceType: "official-documentation"
  - title: "YYLO CLI npm registry metadata"
    url: "https://registry.npmjs.org/@yylo/cli"
    claim: "The npm registry metadata for @yylo/cli (MIT) shows the published package with bin commands yylo, yy, and ypl, confirming npm distribution of the yylo and yy commands. Version channels are disclosed rather than conflated: the product website identifies 0.2.2 as the current stable release and 0.2.3-rc.3 as prerelease, while the registry's latest tag points at 0.2.10, an artifact whose own README marks it unreleased source. Capability claims in this listing are pinned to the documented stable channel and current repository documentation, not to the 0.2.10 registry artifact."
    accessedAt: "2026-09-29"
    sourceType: "official-documentation"
verificationLevel: "documentation-reviewed"
reviewedBy: "foo-bender"
reviewedAt: "2026-09-26"
classificationRationaleMd: "YYLO is agent-native because coding agents are the actors it coordinates: it launches agent runs, routes typed tasks into dedicated Advanced-mode worktrees, and delivers protected changes through a managed one-task native Git merge whose verified Git result is recorded with separate, retryable Ledger projection."
inclusionRationaleMd: "Agents work on assigned tasks in isolated exact-base Advanced-mode worktrees, produce receipt-backed commits with bounded logs, and land changes through managed native Git delivery with expected-old ref protection, keeping agent-built repository changes reviewable and recoverable."
bestForMd: "Developers and project operators who want coding agents to work in isolated Advanced-mode task worktrees with a typed lifecycle, validation evidence, and managed native Git delivery."
notBestForMd: "Teams seeking a hosted multi-tenant control plane, a visual dashboard, or orchestration of non-coding business agents."
limitationsMd: "Provider credentials and model availability remain external, coding-agent support relies on separately installed agents such as Pi or Codex, and tagging, publication, deployment, and production mutation require separate authority."
unknownsMd: "No independent benchmark of orchestration reliability or scale has been reviewed for this listing. First-party version surfaces currently disagree: the website names 0.2.2 stable and 0.2.3-rc.3 prerelease while npm latest points at 0.2.10 (marked unreleased source by its own README); capability claims here follow the documented stable channel and repository documentation."
---

YYLO is a command-line orchestrator for coding agents, repeatable workflows, and receipt-backed repository changes. Developers can run a quick agent loop, while project operators assign typed tasks that, in Advanced workspaces, create dedicated branch/worktree environments, collect validation evidence, and land changes through managed native Git delivery that records the verified Git result with separate, retryable Ledger projection.

## So agents can...

- Work on an assigned task in a dedicated, exact-base worktree instead of the shared checkout (Advanced workspaces; Simple mode keeps one shared checkout for bookkeeping)
- Produce receipt-backed commits with bounded logs and terminal-state evidence
- Land changes through a managed one-task native Git merge with expected-old ref protection — merge launches no models, chooses no reviewers, and schedules no suites; tests and semantic review stay explicit project checks
