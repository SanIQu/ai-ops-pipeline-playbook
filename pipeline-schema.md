# Pipeline Schema

This document defines the structure used to track initiatives within the execution pipeline.

The goal is to create a consistent way for teams to report progress, identify risks, and coordinate work across an organization.

---

## Pipeline Stages

Work items move through the following stages:

**1. Intake**  
New ideas, requests, or initiatives are submitted for consideration.

**2. Scoped**  
The initiative has defined scope, owner, and initial timeline.

**3. In Progress**  
Execution has begun and work is actively underway.

**4. In Review**  
Work is nearing completion and undergoing review, validation, or testing.

**5. Ready**  
The initiative is complete and ready for release or rollout.

**6. Released**  
The initiative has been delivered or launched.

**7. Post-Release Insights**  
Performance and feedback are collected to inform improvements.

---

## Required Fields

Each pipeline item should include the following fields.

**Work Item Name**  
A short name describing the initiative.

**Owner (DRI)**  
The person responsible for driving the work forward.

**Stage**  
Current pipeline stage.

**Target Release Window**  
Expected delivery date or release timeframe.

**Dependencies**  
Other teams, systems, or initiatives that must be completed first.

**Risk Level**  
Low / Medium / High.

**Latest Update**  
Short progress update (1–2 sentences).

**Decision Needed**  
Indicates whether leadership input is required.

**Stakeholders**  
Teams or leaders who should be informed of progress.

---

## Example Pipeline Entry

Example format:

- **Work Item:** Search Improvements  
- **Owner:** Product Team  
- **Stage:** In Progress  
- **Target Window:** Q3  
- **Dependencies:** Search infrastructure upgrade  
- **Risk Level:** Medium  
- **Latest Update:** Prototype deployed in staging environment.  
- **Decision Needed:** No  
- **Stakeholders:** Product, Engineering, Customer Success

---

## Design Principles

A good pipeline system should:

- Make work visible across teams
- Surface dependencies early
- Reduce status meeting overhead
- Enable faster decision-making
- Provide leadership with clear operational insight
