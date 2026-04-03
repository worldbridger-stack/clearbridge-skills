---
description: Repository structure reference for ClearBridge skills, showing the layout of core context, domains, capabilities, and agent assets.
---

clearbridge-skills/
│
├── README.md
├── INDEX.md
│
├── core/                                  # ОБЯЗАТЕЛЬНО подключаются почти всем агентам
│   │
│   ├── clearbridge-context/
│   │   ├── SKILL.md
│   │   ├── concept.md
│   │   ├── business-model.md
│   │   ├── services.md
│   │   ├── lifecycle.md
│   │   ├── current-state.md
│   │   ├── stack.md
│   │   ├── constraints.md
│   │   ├── design-system.md
│   │   └── delivery-rules.md
│   │
│   ├── paperclip-operating-model/
│   │   ├── SKILL.md
│   │   ├── task-lifecycle.md
│   │   ├── roles-and-responsibilities.md
│   │   ├── approvals.md
│   │   └── communication-rules.md
│   │
│   ├── task-execution/
│   │   ├── SKILL.md
│   │   ├── problem-framing.md
│   │   ├── solution-approach.md
│   │   ├── output-structure.md
│   │   └── quality-criteria.md
│   │
│   └── communication/
│       ├── SKILL.md
│       ├── tone-of-voice.md
│       ├── formats.md
│       └── client-communication.md
│
├── domains/                               # ЧТО мы делаем (домены бизнеса)
│   │
│   ├── consulting/
│   │   ├── SKILL.md
│   │   ├── vpc.md
│   │   ├── bmc.md
│   │   ├── as-is-to-be.md
│   │   └── audit-approach.md
│   │
│   ├── ai/
│   │   ├── SKILL.md
│   │   ├── ai-use-cases.md
│   │   ├── ai-architecture.md
│   │   ├── llm-integration.md
│   │   └── ai-risks.md
│   │
│   ├── digital-infrastructure/
│   │   ├── SKILL.md
│   │   ├── connectivity.md
│   │   ├── vpn-strategies.md
│   │   ├── resilience.md
│   │   └── system-design.md
│   │
│   └── product/
│       ├── SKILL.md
│       ├── product-strategy.md
│       ├── ux-principles.md
│       └── mvp-design.md
│
├── capabilities/                          # КАК мы это делаем (атомарные навыки)
│   │architecture/
│
├── business-architecture/          # 🔥 САМЫЙ ВАЖНЫЙ
│   ├── SKILL.md
│   ├── vpc.md
│   ├── bmc.md
│   ├── customer-journeys.md
│   ├── value-flows.md
│   ├── as-is-analysis.md
│   ├── to-be-design.md
│   └── output-format.md
├── system-architecture/
│   ├── SKILL.md
│   ├── principles.md
│   ├── patterns.md
│   └── output-format.md
│
├── solution-architecture/
│   ├── SKILL.md
│   ├── approach.md
│   ├── templates.md
│   └── output-format.md
│
├── enterprise-architecture/
│   ├── SKILL.md
│   ├── frameworks.md
│   └── layers.md
│
├── integration-architecture/
│   ├── SKILL.md
│   ├── patterns.md
│   └── api-strategies.md
│
├── data-architecture/
│   ├── SKILL.md
│   ├── data-modeling.md
│   └── storage-patterns.md
│
└── ai-architecture/
    ├── SKILL.md
    ├── llm-orchestration.md
    └── agent-systems.md
│   ├── marketing/
│   │   ├── segmentation/
│   │   │   ├── SKILL.md
│   │   │   ├── method.md
│   │   │   ├── prompts.md
│   │   │   └── output-format.md
│   │   │
│   │   ├── icp-definition/
│   │   │   ├── SKILL.md
│   │   │   ├── criteria.md
│   │   │   └── output-format.md
│   │   │
│   │   ├── value-proposition/
│   │   │   ├── SKILL.md
│   │   │   ├── framework.md
│   │   │   └── templates.md
│   │   │
│   │   ├── outreach-copywriting/
│   │   │   ├── SKILL.md
│   │   │   ├── patterns.md
│   │   │   └── templates.md
│   │   │
│   │   └── lead-scoring/
│   │       ├── SKILL.md
│   │       ├── scoring-model.md
│   │       └── criteria.md
│   │
│   ├── sales/
│   │   ├── discovery/
│   │   ├── objection-handling/
│   │   ├── closing/
│   │   └── follow-ups/
│   │
│   ├── design/
│   │   ├── ux-research/
│   │   ├── ui-design/
│   │   ├── design-systems/
│   │   └── prototyping/
│   │
│   ├── engineering/
│   │   ├── architecture-design/
│   │   ├── api-integration/
│   │   ├── automation-n8n/
│   │   └── docker/
│   │
│   ├── analytics/
│   │   ├── metrics-definition/
│   │   ├── funnel-analysis/
│   │   └── cohort-analysis/
│   │
│   └── finance/
│       ├── pricing/
│       ├── unit-economics/
│       └── financial-modeling/
│
├── playbooks/                             # ГОТОВЫЕ СЦЕНАРИИ (самое ценное)
│   │
│   ├── ai-diagnostic-sprint/
│   │   ├── SKILL.md
│   │   ├── steps.md
│   │   ├── questions.md
│   │   └── output-template.md
│   │
│   ├── smb-audit/
│   │   ├── SKILL.md
│   │   ├── checklist.md
│   │   └── output-template.md
│   │
│   ├── cold-outreach/
│   │   ├── SKILL.md
│   │   ├── sequence.md
│   │   ├── templates.md
│   │   └── logging-rules.md
│   │
│   └── website-analysis/
│       ├── SKILL.md
│       ├── steps.md
│       └── output-template.md
│
├── tools/                                 # ИНТЕГРАЦИИ
│   │
│   ├── n8n/
│   │   ├── SKILL.md
│   │   ├── patterns.md
│   │   └── workflows.md
│   │
│   ├── wordpress/
│   │   ├── SKILL.md
│   │   ├── content-management.md
│   │   └── structure.md
│   │
│   ├── telegram/
│   │   ├── SKILL.md
│   │   ├── bot-commands.md
│   │   └── flows.md
│   │
│   ├── crm/
│   │   ├── SKILL.md
│   │   ├── data-model.md
│   │   └── pipelines.md
│   │
│   └── figma/
│       ├── SKILL.md
│       ├── collaboration.md
│       └── structure.md
│
└── roles/                                 # АГРЕГАЦИЯ СКИЛЛОВ ПО РОЛЯМ
    │
    ├── cmo/
    │   ├── SKILL.md
    │   └── skill-map.md
    │
    ├── cto/
    │   ├── SKILL.md
    │   └── skill-map.md
    │
    ├── cdo/
    │   ├── SKILL.md
    │   └── skill-map.md
    │
    ├── solution-architect/
    │   ├── SKILL.md
    │   └── skill-map.md
    │
    └── cfo/
        ├── SKILL.md
        └── skill-map.md
