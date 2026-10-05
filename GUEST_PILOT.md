# Personal AI Hotel — Concierge Pilot

STATUS: PROPOSED VALIDATION MVP

## Goal

Validate whether guests and hotel staff obtain measurable value from one AI conversational layer before deep integration work.

## Pilot scope

- one hotel;
- a limited number of consenting stays;
- English and Russian;
- approved hotel information plus one operational request category initially;
- expansion only after review of accuracy, handover and staff workload.

Candidate categories for selection, not simultaneous launch:
1. hotel information;
2. housekeeping timing;
3. amenities;
4. breakfast/restaurant;
5. taxi/transfer;
6. late checkout;
7. maintenance issue;
8. human concierge escalation.

## Concierge MVP

Front stage:
- guest speaks or types naturally;
- guest sees transparent request status.

Back stage:
- AI orchestration;
- approved automation where available;
- structured human tasks where APIs are unavailable;
- explicit verification.

Some work can remain manual during validation. The purpose is to prove demand and workflow value before integration cost.

## Test scenarios

- single request;
- multi-intent request;
- conflicting schedule;
- paid booking needing approval;
- unavailable service;
- hotel delay;
- guest changes mind;
- Russian-language request;
- staff escalation;
- failed action that must not be presented as confirmed.

## Measurement

Guest:
- usage per stay;
- completion rate;
- time saved perception;
- satisfaction;
- repeated use;
- trust.

Hotel:
- staff touches;
- response time;
- missed requests;
- workload;
- escalation burden;
- upsell conversion where measurable.

System:
- intent accuracy;
- clarification rate;
- false-confirmation rate;
- pending-task leakage;
- duplicate actions;
- verification coverage.

## Evaluation before live use

Start with synthetic or approved redacted cases, then staff evaluation alongside the current process. A live pilot requires agreement on policy ownership, participation, data handling, operational coverage and a stop procedure.

Test conflicting or expired rules, missing availability, duplicate messages and failed staff handovers. An accepted request, confirmed booking and completed service are different states.

Measure staff review and correction effort as well as handling time. Compare the proposed experience with the current tools and workflow.

[Address-specific proposal](proposals/address/PROPOSAL.md)

## Decision gate

Move toward an integrated MVP only if:
- guests repeatedly use the product for real requests;
- staff accepts the workflow;
- completion is reliable;
- false confirmations are controlled;
- there is a credible buyer/value case.
