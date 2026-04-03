---
description: Overview of the business-analysis plugin, including scope boundaries, available skills, agents, and installation guidance.
---

# Business Analysis Plugin

BABOK v3-based business analysis techniques for Claude Code. Provides skills, agents, and commands for capability mapping, stakeholder analysis, value stream mapping, and user journey mapping.

## Scope Boundary

**business-analysis** = **BABOK Analysis Techniques for Strategy and Planning**

| This Plugin | NOT This Plugin (See requirements-elicitation) |
|-------------|-----------------------------------------------|
| Strategic analysis (SWOT, PESTLE, Porter's) | Stakeholder interviews |
| Capability mapping | Document extraction |
| Process modeling (BPMN) | Gap analysis |
| Value stream mapping | Requirements synthesis |
| Stakeholder power/interest matrices | Quality scoring (6Cs) |
| Journey mapping methodology | Requirements-specific prioritization |

**Key Differentiator:** This plugin provides **BABOK analysis techniques for understanding business context, strategy, and operations**. Requirements-elicitation focuses on **gathering requirements from stakeholders and documents**.

### When to Use This Plugin vs requirements-elicitation

| Scenario | Use This Plugin | Use requirements-elicitation |
|----------|-----------------|------------------------------|
| "I need to understand the strategic business context" | ✅ | |
| "I need to gather requirements from stakeholders" | | ✅ |
| "I need to map organizational capabilities" | ✅ | |
| "I have documents with hidden requirements to extract" | | ✅ |
| "I need to prioritize features, capabilities, or investments" | ✅ prioritization | |
| "I need to prioritize the *requirements* I've gathered" | | ✅ prioritization-methods |
| "I need a comprehensive journey mapping methodology" | ✅ journey-mapping | |
| "I need to create a journey map from elicited requirements" | | ✅ journey-map command |

### Handoff Pattern

```text
business-analysis:stakeholder-analysis → requirements-elicitation:interview → requirements-elicitation:synthesize → spec-driven-development:spec-author
```

## Installation

```bash
/plugin install business-analysis@claude-code-plugins
```

## Features

### Skills (19)

| Skill | Description |
| ----- | ----------- |
| `babok-techniques` | BABOK v3 technique framework and selection guidance |
| `ba-orchestration` | Multi-technique workflow coordination |
| `benchmarking` | Competitive and industry benchmarking analysis |
| `business-model-canvas` | Osterwalder/Lean Canvas business model design |
| `capability-mapping` | Hierarchical business capability models (L1-L3) |
| `data-modeling` | Conceptual, logical, physical data modeling |
| `decision-analysis` | Decision tables, trees, and analysis frameworks |
| `design-thinking` | Human-centered design process facilitation |
| `estimation` | Function points, story points, effort estimation |
| `impact-mapping` | Goal-actor-capability-feature mapping |
| `journey-mapping` | User experience mapping with personas, touchpoints, emotions |
| `prioritization` | MoSCoW, Kano, weighted scoring, WSJF |
| `process-modeling` | BPMN process diagrams and workflow modeling |
| `risk-analysis` | Risk identification, assessment, and mitigation |
| `risk-register` | Risk register creation and management |
| `root-cause-analysis` | Fishbone diagrams, 5 Whys analysis |
| `stakeholder-analysis` | Power/Interest matrices, RACI charts, communication planning |
| `swot-pestle-analysis` | Strategic environmental analysis |
| `value-stream-mapping` | Lean waste identification (TIMWOODS), flow efficiency |

### Agents (9)

| Agent | Description |
| ----- | ----------- |
| `ba-orchestrator` | Coordinates multi-technique BA workflows |
| `capability-analyst` | Strategic capability discovery and modeling |
| `data-modeler` | Conceptual, logical, and physical data structure design |
| `journey-facilitator` | User journey mapping facilitation |
| `problem-solver` | Root cause analysis with Fishbone and 5 Whys |
| `process-modeler` | BPMN process diagram generation |
| `stakeholder-facilitator` | Multi-persona stakeholder workshops |
| `strategic-analyst` | SWOT, PESTLE, and Porter's Five Forces analysis |
| `value-stream-analyst` | Lean value stream analysis |

### User-Invocable Skills (9)

| Skill | Description |
| ----- | ----------- |
| `/business-analysis:business-model-canvas` | Create Business Model Canvas or Lean Canvas |
| `/business-analysis:capability-mapping` | Create capability model with Mermaid visualization |
| `/business-analysis:journey-mapping` | Create user journey map with emotion curve |
| `/business-analysis:prioritization` | Prioritize items using MoSCoW, Kano, or weighted scoring |
| `/business-analysis:risk-register` | Create or update risk register with mitigation plans |
| `/business-analysis:root-cause-analysis` | Perform root cause analysis with Fishbone/5 Whys |
| `/business-analysis:stakeholder-analysis` | Run stakeholder analysis with matrices |
| `/business-analysis:swot-pestle-analysis` | SWOT, PESTLE, or Porter's Five Forces analysis |
| `/business-analysis:value-stream-mapping` | Analyze value stream, identify waste and bottlenecks |

## Recommended BA Workflow

The canonical business analysis workflow follows BABOK v3 progression:

```text
1. stakeholder-analysis   → Identify and map stakeholders (Power/Interest, RACI)
2. capability-mapping     → Create hierarchical capability model (L1-L3)
3. value-stream-mapping   → Analyze operational flow, identify waste
4. journey-mapping        → Map user experience with emotions and pain points
5. prioritization         → Rank capabilities/initiatives by value/effort
6. → HANDOFF: requirements-elicitation:interview → Gather detailed requirements
```

**Entry Point:** Start with `/business-analysis:stakeholder-analysis` to identify who to involve.

**Exit Point:** Hand off to `requirements-elicitation` when you need to gather detailed requirements from identified stakeholders.

## Workflows

### Strategic Planning

```text
1. Stakeholder Analysis → Identify key stakeholders
2. Capability Mapping → Create capability model
3. Benchmarking → Compare against industry
4. SWOT/PESTLE Analysis → Environmental scan
5. Prioritization → Investment decisions
```

### Customer Experience Improvement

```text
1. Stakeholder Analysis → Identify user segments
2. Journey Mapping → Map current experience
3. Value Stream Mapping → Identify operational waste
4. Capability Mapping → Link to capabilities
5. Prioritization → Impact vs effort matrix
```

### Process Optimization

```text
1. Process Modeling → Capture current process (BPMN)
2. Value Stream Mapping → Identify waste and bottlenecks
3. Journey Mapping → User experience perspective
4. Root Cause Analysis → Identify improvement areas
5. Estimation → Plan improvement effort
```

## Output Formats

All techniques produce outputs in three formats:

1. **Narrative Summary**: Human-readable markdown documentation
2. **Structured Data**: YAML for downstream processing and integration
3. **Visual Diagrams**: Mermaid diagrams for documentation

## Related Skills (Cross-Plugin)

| Phase | Plugin | Skill | Purpose |
|-------|--------|-------|---------|
| STRATEGY | business-analysis | stakeholder-analysis, capability-mapping, swot-pestle | Understand business context |
| ELICITATION | requirements-elicitation | interview-conducting, document-extraction | Gather detailed requirements |
| SPECIFICATION | spec-driven-development | spec-author, gherkin-authoring | Write formal specifications |

## License

MIT
