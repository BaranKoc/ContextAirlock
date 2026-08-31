<div align="center">

# ContextAirlock

### Controlled context for AI agents.

**Use the power of AI on real work without handing over your entire workspace.**

[![Project Status](https://img.shields.io/badge/status-early%20design%20%26%20prototyping-7c3aed?style=flat-square)](#project-status)
[![Focus](https://img.shields.io/badge/focus-user--controlled%20disclosure-0f766e?style=flat-square)](#the-idea)

</div>

---

AI agents are remarkably capable when they have context. The problem is that real context is rarely clean, isolated, or harmless. A spreadsheet prepared for a simple analysis may also contain names, contact details, internal pricing, commercial notes, or information unrelated to the task.

Today, that often leaves people with two uncomfortable choices: give an agent broad access and disclose too much, or withhold the files and lose much of the agent's value.

**ContextAirlock is being built to create a better choice.**

It sits between AI agents and sensitive local content, helping people decide what a specific task actually needs, review what will be shared, and keep the rest outside the conversation.

## The idea

An airlock does not open every door at once. It creates a controlled passage between two environments.

ContextAirlock brings that idea to AI-assisted work:

> Your files remain the source of truth. The agent receives only the context allowed for the current task. You stay in control of the passage between them.

Instead of treating access as a single yes-or-no permission, ContextAirlock is designed around deliberate disclosure. The source, purpose, recipient, level of detail, and resulting output should all remain visible and understandable to the person doing the work.

## What the experience should feel like

1. **Choose the source**  
   Add the files relevant to the job rather than exposing a whole workspace.

2. **Describe the outcome**  
   Start naturally in the AI conversation: explain the analysis, table, or result you want.

3. **Review the context**  
   See what the agent would receive, what has been removed or transformed, and who the recipient is.

4. **Approve the passage**  
   Nothing broader is disclosed silently. If the task needs more context, the change comes back to you.

5. **Receive a new result**  
   The approved work produces a separate artifact, leaving the original source unchanged.

## Two clear ways to work

ContextAirlock is designed to make the active privacy choice obvious rather than burying it in settings.

### Protected mode

The agent receives a purpose-built **Safe View**: a reduced version of the source containing only the approved fields and level of detail. Information can be excluded, masked, generalized, grouped, or replaced with task-specific aliases before anything is shared.

You review the actual outgoing view first. If an appropriate Safe View cannot be created, the task stops and asks for a decision. It does not quietly reveal more.

### Direct mode

Sometimes the selected source really does need to be shared as-is. Direct mode makes that an explicit choice. The active mode, selected sources, and intended recipient remain visible so convenience is never mistaken for protection.

| You can review | The product is designed to keep under your control |
|---|---|
| Which sources are in the task | Files outside the selected task |
| Which information the agent will receive | Information removed from the approved view |
| Which privacy mode is active | The link between protected aliases and original values |
| Who the context is intended for | Private records needed to verify what happened |
| What changed when more detail was requested | Any expansion you have not approved |

## Why ContextAirlock is different

### Control before disclosure

The important moment is not after data has already been sent. ContextAirlock is centered on the decision before that moment: preview, understand, approve.

### Least context, not maximum access

The goal is not to give an agent a smaller copy of everything. It is to create the smallest useful view for one defined task.

### No silent fallback

If protected context is insufficient, the product should pause. Moving to broader or raw disclosure is a new user decision, not an automatic recovery path.

### Results are checked on the way back

Agent output is not treated as correct merely because it looks convincing. ContextAirlock is designed to validate that a result belongs to the right task and approved sources before it becomes a final artifact.

### Built around user agency

Automation should reduce effort without hiding consequential choices. ContextAirlock aims to make privacy boundaries understandable to ordinary users, not only security specialists.

## First destination

The first product journey focuses on a familiar business task:

> Turn selected CSV or modern Excel files into a new analysis table through a conversation with an AI agent.

The initial protected experience is intentionally narrow. It focuses on structured data, predictable transformations, a faithful preview of what will be shared, and an explicit approval step. More advanced assistance may come later, but it will not replace the same disclosure controls.

This narrow starting point matters. ContextAirlock is not trying to promise every file type, every privacy problem, and every AI workflow on day one. It is starting where user control can be made concrete and testable.

## Who it is for

ContextAirlock is for people who want to use capable AI agents on meaningful local work but are not comfortable granting broad, opaque access to their files.

That may include:

- analysts working with operational spreadsheets,
- founders and small teams handling commercially sensitive data,
- consultants moving between client contexts,
- researchers working with restricted or identifying fields,
- privacy-conscious users who want to see what leaves their device,
- builders exploring safer human–agent workflows.

## Product principles

- **The active mode should always be clear.**
- **Every disclosure should have a purpose and a recipient.**
- **More access should require a new decision.**
- **Original sources should not be changed in place.**
- **Private mappings and sensitive records should stay local.**
- **Agent output should be treated as untrusted until checked.**
- **A failed protection step should stop safely, not continue optimistically.**
- **Evidence should come before security claims.**

## Project status

ContextAirlock is currently in **early design and prototyping**. The repository is being introduced before a usable protected release exists so the product direction can be communicated clearly from the beginning.

At this stage:

- the product problem and core principles are defined,
- the first spreadsheet-centered journey has been selected,
- early prototypes will use synthetic data only,
- protected operation is not yet available for real or sensitive information,
- no security guarantee should be inferred from the current repository.

The path forward is deliberately evidence-led:

1. validate the basic agent experience with synthetic examples,
2. prove that protected source material remains outside ordinary agent access,
3. add user-reviewed Safe Views and explicit disclosure approval,
4. complete the conversational spreadsheet-to-analysis journey,
5. explore optional smarter privacy assistance without weakening user control.

## What ContextAirlock does not promise

ContextAirlock is not a claim of perfect privacy or zero leakage. It is not a general-purpose agent sandbox, an AI model provider, or a promise to understand every kind of sensitive information automatically.

The project will describe protection only where the boundary has been implemented, tested, and documented. Until then, ideas remain goals—not guarantees.

---

<div align="center">

### Let agents see what the task needs—not everything you have.

ContextAirlock is at the beginning. This README describes the destination and the principles that will govern the journey.

</div>
