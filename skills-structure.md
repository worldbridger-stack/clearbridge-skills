---
description: Actual repository structure for ClearBridge skills, showing Codex-ready skills, supporting assets, and placeholder directories.
---

# Repository Structure

This document reflects the repository as it exists now, not an aspirational future layout.

```text
clearbridge-skills/
├── INDEX.md
├── skills-structure.md
├── core/
│   ├── clearbridge-context/
│   │   ├── SKILL.md
│   │   ├── busines-model.md
│   │   ├── concept.md
│   │   ├── constraints.md
│   │   ├── current-state.md
│   │   ├── delivery-rules.md
│   │   ├── design-system.md
│   │   ├── lifecycle.md
│   │   ├── packages.md
│   │   ├── services.md
│   │   └── stack.md
│   └── paperclip-operating-model/
│       └── operating-model.md
└── capabilities/
    ├── analytics/
    │   ├── cohort-analysis/            # placeholder, no SKILL.md yet
    │   ├── funnel-analysis/            # placeholder, no SKILL.md yet
    │   └── metrics-definition/         # placeholder, no SKILL.md yet
    ├── architecture/
    │   ├── ai-architecture/            # placeholder, no SKILL.md yet
    │   ├── business-architecture/
    │   │   └── business-analysis/
    │   │       └── skills/
    │   │           ├── ba-orchestration/
    │   │           │   └── SKILL.md
    │   │           ├── benchmarking/
    │   │           │   └── SKILL.md
    │   │           ├── business-model-canvas/
    │   │           │   └── SKILL.md
    │   │           ├── capability-mapping/
    │   │           │   ├── SKILL.md
    │   │           │   └── references/
    │   │           ├── data-modeling/
    │   │           │   └── SKILL.md
    │   │           ├── decision-analysis/
    │   │           │   └── SKILL.md
    │   │           ├── design-thinking/
    │   │           │   └── SKILL.md
    │   │           ├── estimation/
    │   │           │   └── SKILL.md
    │   │           ├── journey-mapping/
    │   │           │   └── SKILL.md
    │   │           ├── prioritization/
    │   │           │   └── SKILL.md
    │   │           ├── process-modeling/
    │   │           │   └── SKILL.md
    │   │           ├── risk-analysis/
    │   │           │   └── SKILL.md
    │   │           ├── risk-register/
    │   │           │   └── SKILL.md
    │   │           ├── root-cause-analysis/
    │   │           │   └── SKILL.md
    │   │           ├── stakeholder-analysis/
    │   │           │   ├── SKILL.md
    │   │           │   └── references/
    │   │           ├── swot-pestle-analysis/
    │   │           │   └── SKILL.md
    │   │           └── value-stream-mapping/
    │   │               └── SKILL.md
    │   ├── data-architecture/          # placeholder, no SKILL.md yet
    │   ├── enterprise-architecture/    # placeholder, no SKILL.md yet
    │   ├── integration-architecture/   # placeholder, no SKILL.md yet
    │   ├── solution-architecture/
    │   │   └── SKILL.md
    │   └── system-architecture/        # placeholder, no SKILL.md yet
    ├── design/
    │   ├── brand-design/
    │   │   ├── brand-guidelines/
    │   │   │   ├── SKILL.md
    │   │   │   └── scripts/
    │   │   └── brand-strategist/
    │   │       ├── SKILL.md
    │   │       └── scripts/
    │   ├── design-auditor/
    │   │   ├── SKILL.md
    │   │   ├── assets/
    │   │   ├── references/
    │   │   └── scripts/
    │   ├── design-system-lead/
    │   │   ├── SKILL.md
    │   │   └── scripts/
    │   ├── design-systems/             # placeholder, no SKILL.md yet
    │   ├── graphic-design/             # placeholder, no SKILL.md yet
    │   ├── marketing-materials-design/ # placeholder, no SKILL.md yet
    │   ├── product-designer/
    │   │   ├── SKILL.md
    │   │   └── scripts/
    │   ├── prototyping/                # placeholder, no SKILL.md yet
    │   ├── ui-design-system/
    │   │   ├── SKILL.md
    │   │   ├── references/
    │   │   └── scripts/
    │   ├── ux-researcher-designer/
    │   │   ├── SKILL.md
    │   │   ├── references/
    │   │   └── scripts/
    │   └── ux-ui-design/               # placeholder, no SKILL.md yet
    ├── engineering/
    │   ├── api-integration/
    │   │   ├── api-design-reviewer/
    │   │   │   ├── SKILL.md
    │   │   │   ├── references/
    │   │   │   └── scripts/
    │   │   └── api-test-suite-builder/
    │   │       ├── SKILL.md
    │   │       └── scripts/
    │   ├── automation/
    │   │   ├── SKILL.md
    │   │   ├── codex-cli-specialist/
    │   │   │   ├── SKILL.md
    │   │   │   ├── assets/
    │   │   │   ├── references/
    │   │   │   └── scripts/
    │   │   ├── prompt-engineer-toolkit/
    │   │   │   ├── SKILL.md
    │   │   │   └── scripts/
    │   │   └── prompt-governance/
    │   │       ├── SKILL.md
    │   │       ├── references/
    │   │       └── scripts/
    │   ├── development/
    │   │   ├── senior-architect/
    │   │   │   ├── SKILL.md
    │   │   │   ├── references/
    │   │   │   └── scripts/
    │   │   ├── senior-backend/
    │   │   │   ├── SKILL.md
    │   │   │   ├── references/
    │   │   │   └── scripts/
    │   │   ├── senior-computer-vision/
    │   │   │   ├── SKILL.md
    │   │   │   ├── references/
    │   │   │   └── scripts/
    │   │   ├── senior-data-engineer/
    │   │   │   ├── SKILL.md
    │   │   │   ├── references/
    │   │   │   └── scripts/
    │   │   ├── senior-data-scientist/
    │   │   │   ├── SKILL.md
    │   │   │   ├── references/
    │   │   │   └── scripts/
    │   │   ├── senior-devops/
    │   │   │   ├── SKILL.md
    │   │   │   ├── references/
    │   │   │   └── scripts/
    │   │   ├── senior-frontend/
    │   │   │   ├── SKILL.md
    │   │   │   ├── references/
    │   │   │   └── scripts/
    │   │   ├── senior-fullstack/
    │   │   │   └── SKILL.md
    │   │   ├── senior-ml-engineer/
    │   │   │   ├── SKILL.md
    │   │   │   ├── references/
    │   │   │   └── scripts/
    │   │   ├── senior-mobile/
    │   │   │   └── SKILL.md
    │   │   ├── senior-prompt-engineer/
    │   │   │   ├── SKILL.md
    │   │   │   ├── references/
    │   │   │   └── scripts/
    │   │   ├── senior-qa/
    │   │   │   ├── SKILL.md
    │   │   │   ├── README.md
    │   │   │   ├── references/
    │   │   │   └── scripts/
    │   │   └── senior-security/
    │   │       ├── SKILL.md
    │   │       ├── references/
    │   │       └── scripts/
    │   ├── infrastucture/
    │   │   ├── database-designer/
    │   │   │   ├── SKILL.md
    │   │   │   ├── README.md
    │   │   │   ├── assets/
    │   │   │   ├── expected_outputs/
    │   │   │   ├── references/
    │   │   │   ├── index_optimizer.py
    │   │   │   ├── migration_generator.py
    │   │   │   └── schema_analyzer.py
    │   │   ├── docker-development/
    │   │   │   ├── SKILL.md
    │   │   │   └── references/
    │   │   ├── git-worktree-manager/
    │   │   │   └── SKILL.md
    │   │   ├── llm-cost-optimizer/
    │   │   │   ├── SKILL.md
    │   │   │   ├── references/
    │   │   │   └── scripts/
    │   │   ├── mcp-server-builder/
    │   │   │   ├── SKILL.md
    │   │   │   └── scripts/
    │   │   ├── migration-architect/
    │   │   │   ├── SKILL.md
    │   │   │   ├── README.md
    │   │   │   ├── assets/
    │   │   │   ├── references/
    │   │   │   └── scripts/
    │   │   ├── rag-architect/
    │   │   │   ├── SKILL.md
    │   │   │   ├── references/
    │   │   │   ├── chunking_optimizer.py
    │   │   │   ├── rag_pipeline_designer.py
    │   │   │   └── retrieval_evaluator.py
    │   │   ├── release-manager/
    │   │   │   └── SKILL.md
    │   │   └── sql-database-assistant/
    │   │       ├── SKILL.md
    │   │       ├── examples/
    │   │       └── references/
    │   └── networks/                   # placeholder, no SKILL.md yet
    ├── finance/
    │   ├── financial-analyst/
    │   │   ├── SKILL.md
    │   │   ├── assets/
    │   │   ├── references/
    │   │   └── scripts/
    │   ├── financial-modeling/
    │   │   └── SKILL.md
    │   ├── pricing/                    # placeholder, no SKILL.md yet
    │   ├── pricing-strategy/
    │   │   ├── SKILL.md
    │   │   └── scripts/
    │   ├── saas-metrics-coach/
    │   │   ├── SKILL.md
    │   │   ├── examples/
    │   │   ├── references/
    │   │   └── scripts/
    │   └── unit-economics/             # placeholder, no SKILL.md yet
    ├── marketing/
    │   ├── campaign-analytics/
    │   │   ├── SKILL.md
    │   │   ├── references/
    │   │   └── scripts/
    │   ├── cold-email/
    │   │   ├── SKILL.md
    │   │   └── scripts/
    │   ├── content-creator/
    │   │   ├── SKILL.md
    │   │   ├── examples/
    │   │   └── scripts/
    │   ├── content-humanizer/
    │   │   ├── SKILL.md
    │   │   └── scripts/
    │   ├── content-production/
    │   │   ├── SKILL.md
    │   │   └── scripts/
    │   ├── content-strategy/
    │   │   └── SKILL.md
    │   ├── copywriting/
    │   │   ├── SKILL.md
    │   │   └── scripts/
    │   ├── email-sequence/
    │   │   ├── SKILL.md
    │   │   └── scripts/
    │   ├── email-template-builder/
    │   │   └── SKILL.md
    │   ├── growth-marketer/
    │   │   ├── SKILL.md
    │   │   └── scripts/
    │   ├── icp-definition/             # placeholder, no SKILL.md yet
    │   ├── landing-page-generator/
    │   │   ├── SKILL.md
    │   │   └── scripts/
    │   ├── lead-scoring/
    │   │   ├── lead-qualification/
    │   │   │   └── SKILL.md
    │   │   ├── lead-research/
    │   │   │   └── SKILL.md
    │   │   └── lead-routing/
    │   │       └── SKILL.md
    │   ├── marketing-analyst/
    │   │   └── SKILL.md
    │   ├── marketing-context/
    │   │   ├── SKILL.md
    │   │   └── scripts/
    │   ├── marketing-ideas/
    │   │   └── SKILL.md
    │   ├── marketing-strategy-pmm/
    │   │   ├── SKILL.md
    │   │   ├── references/
    │   │   └── scripts/
    │   ├── outreach-copywriting/       # placeholder, no SKILL.md yet
    │   ├── segmentation/               # placeholder, no SKILL.md yet
    │   ├── social-content/
    │   │   ├── SKILL.md
    │   │   └── scripts/
    │   ├── social-media-manager/
    │   │   ├── SKILL.md
    │   │   └── scripts/
    │   └── value-proposition/          # placeholder, no SKILL.md yet
    └── sales/
        ├── account-executive/
        │   ├── SKILL.md
        │   └── scripts/
        ├── closing/                    # placeholder, no SKILL.md yet
        ├── customer-success-manager/
        │   ├── SKILL.md
        │   └── scripts/
        ├── discovery/                  # placeholder, no SKILL.md yet
        ├── follow-ups/                 # placeholder, no SKILL.md yet
        ├── objection-handling/         # placeholder, no SKILL.md yet
        └── sales-operations/
            ├── SKILL.md
            └── scripts/
```

## Notes

- `SKILL.md` marks an active skill that can be discovered by Codex.
- Some directories are intentionally present as placeholders for future skills; they are marked inline.
- Supporting materials are kept close to each skill in `references/`, `scripts/`, `assets/`, `examples/`, and `README.md` files.
- The path `capabilities/engineering/infrastucture/` intentionally matches the current on-disk directory name, including the existing spelling.
