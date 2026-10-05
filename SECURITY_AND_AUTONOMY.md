# AI Hotel — Security and Autonomy Principles

## Default posture

Read-only first.

AI Hotel must earn operational trust before executing actions. Early pilots should prioritize observation, summaries, recommendations, drafts and explicitly approved low-risk actions.

## Autonomy levels

### L0 — Observe
Read data and summarize it.

### L1 — Recommend
Suggest actions, risks and priorities.

### L2 — Draft
Prepare messages, tasks, reports and approvals for a human to review.

### L3 — Execute low-risk actions
Execute reversible, low-risk actions only when allowed by written hotel policy.

### L4 — Execute bounded workflows
Run predefined workflows with logging, limits and escalation.

### L5 — High autonomy
Not a pilot-stage target.

## Approval required by default

Require human approval for:
- high-impact financial actions;
- pricing actions;
- refunds;
- legal commitments;
- HR/personnel actions;
- access-control or security actions;
- emergency/safety actions;
- sensitive guest communications;
- public reputation replies;
- irreversible changes.

## Guest authority

Guest-facing actions also need explicit permission boundaries.

Examples:
- informational actions may be immediate;
- reversible no-cost service requests may be delegated after identity validation;
- paid or capacity-constrained bookings may require confirmation;
- material reservation changes or cancellations require explicit confirmation;
- unsupported/high-risk actions route to a human.

## Audit trail

Every material AI action should record:
- source/context;
- actor;
- policy used;
- recommendation or action;
- approval status;
- time;
- result;
- exception/escalation.

## Data handling

Use least privilege. Separate guest data, staff data, financial data and operational data. Do not expose unnecessary personal data to models or tools.

## Pilot principle

The first pilot should prove trust, control and measurable value before expanding automation.
