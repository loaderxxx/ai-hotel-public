# AI Hotel — Public Architecture Overview

## Architecture thesis

Hotel-side AI and Personal AI Hotel are separate experience layers connected to one governed operational backbone.

## 1. Experience layer

Guest:
- web/PWA;
- approved messaging;
- voice;
- future hotel app / room devices.

Hotel:
- director cockpit;
- staff inbox;
- department task views;
- operations and quality dashboards.

## 2. Context layer

The platform needs explicit context for:
- property;
- room;
- reservation/stay;
- guest;
- department/team;
- service;
- task/request;
- booking;
- incident;
- approval.

Guest-visible, operational, financial and staff-confidential data must remain separated by policy.

## 3. Capability registry

Each hotel capability should define:
- what action is available;
- where and when it is available;
- required inputs;
- department owner;
- approval rules;
- execution method;
- verification method;
- fallback/escalation.

## 4. Orchestration

The orchestrator can:
- understand multi-step intent;
- build dependencies;
- apply hotel policy;
- invoke connected actions;
- route work to staff;
- track pending states;
- verify outcomes;
- update the relevant guest or manager view.

## 5. Integrations

The platform should integrate with mature hotel systems rather than replace them unnecessarily.

Candidate integration classes:
- PMS / CRS;
- POS;
- housekeeping/task management;
- maintenance;
- restaurant/spa;
- CRM;
- payments;
- messaging;
- transport;
- revenue/finance systems;
- digital key providers.

## 6. Verification

A request is not complete merely because it was sent.

Verification may come from:
- an API confirmation;
- a reservation record;
- a task-completion event;
- staff acknowledgment;
- payment status;
- guest confirmation.

## 7. Governance

The shared platform requires:
- least privilege;
- approval classes;
- human override;
- audit trail;
- explicit execution policies;
- separation of guest and internal data;
- bounded autonomy.

This document intentionally describes the public high-level architecture rather than proprietary internal implementation details.
