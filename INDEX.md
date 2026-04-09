---
description: Current index of the ClearBridge skills repository, including active Codex-ready skills, capability groups, and placeholder directories.
---

# ClearBridge Skills Repository

This repository is organized for Codex-compatible skill discovery. Active skills live in `SKILL.md` files with normalized `name` and `description` frontmatter. As of 2026-04-09, the repo contains `81` active skills: `1` core skill and `80` capability skills.

## Core

- `core/clearbridge-context` - primary company context and operating constraints for agents
- `core/paperclip-operating-model/operating-model.md` - supporting operating model documentation, not a standalone skill

## Active Capabilities

### Architecture

- `solution-architecture`
- `business-architecture/business-analysis/skills/ba-orchestration`
- `business-architecture/business-analysis/skills/benchmarking`
- `business-architecture/business-analysis/skills/business-model-canvas`
- `business-architecture/business-analysis/skills/capability-mapping`
- `business-architecture/business-analysis/skills/data-modeling`
- `business-architecture/business-analysis/skills/decision-analysis`
- `business-architecture/business-analysis/skills/design-thinking`
- `business-architecture/business-analysis/skills/estimation`
- `business-architecture/business-analysis/skills/journey-mapping`
- `business-architecture/business-analysis/skills/prioritization`
- `business-architecture/business-analysis/skills/process-modeling`
- `business-architecture/business-analysis/skills/risk-analysis`
- `business-architecture/business-analysis/skills/risk-register`
- `business-architecture/business-analysis/skills/root-cause-analysis`
- `business-architecture/business-analysis/skills/stakeholder-analysis`
- `business-architecture/business-analysis/skills/swot-pestle-analysis`
- `business-architecture/business-analysis/skills/value-stream-mapping`

### Design

- `design-auditor`
- `design-system-lead`
- `product-designer`
- `ui-design-system`
- `ux-researcher-designer`
- `brand-design/brand-guidelines`
- `brand-design/brand-strategist`

### Engineering

#### Automation

- `automation`
- `automation/codex-cli-specialist`
- `automation/prompt-engineer-toolkit`
- `automation/prompt-governance`

#### API Integration

- `api-integration/api-design-reviewer`
- `api-integration/api-test-suite-builder`

#### Development

- `development/senior-architect`
- `development/senior-backend`
- `development/senior-computer-vision`
- `development/senior-data-engineer`
- `development/senior-data-scientist`
- `development/senior-devops`
- `development/senior-frontend`
- `development/senior-fullstack`
- `development/senior-ml-engineer`
- `development/senior-mobile`
- `development/senior-prompt-engineer`
- `development/senior-qa`
- `development/senior-security`

#### Infrastructure

- `infrastucture/database-designer`
- `infrastucture/docker-development`
- `infrastucture/git-worktree-manager`
- `infrastucture/llm-cost-optimizer`
- `infrastucture/mcp-server-builder`
- `infrastucture/migration-architect`
- `infrastucture/rag-architect`
- `infrastucture/release-manager`
- `infrastucture/sql-database-assistant`

### Finance

- `financial-analyst`
- `financial-modeling`
- `pricing-strategy`
- `saas-metrics-coach`

### Marketing

- `campaign-analytics`
- `cold-email`
- `content-creator`
- `content-humanizer`
- `content-production`
- `content-strategy`
- `copywriting`
- `email-sequence`
- `email-template-builder`
- `growth-marketer`
- `landing-page-generator`
- `marketing-analyst`
- `marketing-context`
- `marketing-ideas`
- `marketing-strategy-pmm`
- `social-content`
- `social-media-manager`
- `lead-scoring/lead-qualification`
- `lead-scoring/lead-research`
- `lead-scoring/lead-routing`

### Sales

- `account-executive`
- `customer-success-manager`
- `sales-operations`

## Placeholder Directories Present In Repo

These directories already exist in the tree but do not yet contain active `SKILL.md` files:

- `capabilities/analytics/cohort-analysis`
- `capabilities/analytics/funnel-analysis`
- `capabilities/analytics/metrics-definition`
- `capabilities/architecture/ai-architecture`
- `capabilities/architecture/data-architecture`
- `capabilities/architecture/enterprise-architecture`
- `capabilities/architecture/integration-architecture`
- `capabilities/architecture/system-architecture`
- `capabilities/design/design-systems`
- `capabilities/design/graphic-design`
- `capabilities/design/marketing-materials-design`
- `capabilities/design/prototyping`
- `capabilities/design/ux-ui-design`
- `capabilities/engineering/networks`
- `capabilities/finance/pricing`
- `capabilities/finance/unit-economics`
- `capabilities/marketing/icp-definition`
- `capabilities/marketing/outreach-copywriting`
- `capabilities/marketing/segmentation`
- `capabilities/marketing/value-proposition`
- `capabilities/sales/closing`
- `capabilities/sales/discovery`
- `capabilities/sales/follow-ups`
- `capabilities/sales/objection-handling`

## Codex Readiness Notes

- Every active skill now has a discoverable `description` field.
- Skill names have been normalized where needed to match directory naming and Codex discovery expectations.
- Direct Claude-only metadata references were removed from the main outlier skills that were imported in Claude-first format.
- Repository guides now describe the actual current layout rather than a future target structure.
