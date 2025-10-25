# Electrification Copilot (Overview)

**What this is:** A product concept for an internal “copilot” that guides engineers through
validation workflows, auto-documents steps, and surfaces reusable digital-twin assets, **without** any proprietary content.

---

## Problem
Validation and documentation are time-consuming and inconsistent across teams. Onboarding is slow and
tribal knowledge is hard to find.

## Solution
A guided assistant that:
- Provides **checklists** and **next-best-actions** by context (project, subsystem, maturity)
- Auto-generates **validation summaries** and links artifacts
- Recommends **reusable models/assets** based on prior work
- Captures **feedback** and **metrics** to improve guidance

## Experience Flow (at a glance)
```mermaid
sequenceDiagram
User->>Copilot: Select platform + task
Copilot->>Copilot: Load playbook + past artifacts
Copilot-->>User: Show steps + links (Next actions)
User->>Copilot: Complete step / upload artifact
Copilot->>Copilot: Generate summary + recommendations
Copilot-->>User: One-click report + share links
