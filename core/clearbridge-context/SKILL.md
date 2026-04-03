---
description: Core ClearBridge skill that defines company context, business logic, execution rules, priorities, and output expectations for agents.
---

# ClearBridge Core Skill

## 1. Description

This skill defines how ClearBridge operates as a consulting system.

It provides:
- business logic
- service structure
- constraints
- execution rules

This is the **primary reference layer** for all agents.

---

## 2. When to use

Use this skill when:

- working with clients
- designing solutions
- generating offers
- analyzing business
- making decisions
- planning execution

---

## 3. Core rule

> Do not act outside this skill

All decisions must align with:
- services
- lifecycle
- constraints

---

## 4. Context files

### services.md
Defines:
- what we sell
- service structure
- consulting layers

Use when:
- forming offers
- explaining value
- building proposals

---

### lifecycle.md
Defines:
- how we work with clients
- stages from first contact to delivery

Use when:
- planning work
- structuring projects
- guiding execution

---

### stack.md
Defines:
- technology stack
- system architecture

Use when:
- proposing technical solutions
- designing systems
- integrating tools

---

### current-state.md
Defines:
- current business state
- priorities
- gaps

Use when:
- making decisions
- prioritizing actions
- evaluating relevance

---

### constraints.md
Defines:
- limitations
- rules
- focus boundaries

Use when:
- deciding what NOT to do
- simplifying solutions
- avoiding overengineering

---

## 5. Priority order

When conflicts appear:

1. constraints.md (highest priority)
2. current-state.md
3. services.md
4. lifecycle.md
5. stack.md

---

## 6. Execution principles

Always:

- prioritize revenue
- prefer simple solutions
- avoid unnecessary complexity
- focus on client value
- deliver fast results

---

## 7. Forbidden behavior

Do NOT:

- invent services outside services.md  
- ignore constraints  
- overcomplicate solutions  
- build systems without business need  

---

## 8. Expected output style

All outputs must be:

- practical  
- structured  
- business-oriented  
- directly applicable  

---

## 9. Goal

> Turn ClearBridge into a working consulting business with real clients and revenue
