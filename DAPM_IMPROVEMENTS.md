## Observation 001

**Project:**
Warehouse Operations & Inventory Analytics

**Proposed Improvements:**
- A separate Observation Journal significantly improved traceability.
- A seperate Projet Brief, made the case look like real.
- Introduce a separate ANALYTICAL_THINKING.md document to capture initial analytical ideas after Business Understanding.
- Keep the document lightweight and implementation-independent.

**Evidence:**
Observed during Phase 1.

**Action:**
Re-evaluate after Project 5.

**Status:**
Pending validation.

## Observation 002

**Project:**
Warehouse Operations & Inventory Analytics

**Proposed Improvement:**
Introduce a lightweight `DAPM_PHASE_CHECKLIST.md` to define completion criteria for each phase.

**Evidence:**
Observed during transition from Phase 1 to Phase 2.

**Action:**
Re-evaluate after Project 5.

**Status:**
Pending validation.

## Observation 003

**Project:**
Customer Registration System 

**Proposed Improvement:**
Methodology Rule Never introduce stakeholders, business processes, or organizational roles that have not been explicitly identified by the client or validated during the project.

**Business-Driven Column Selection**  
After the Business Understanding phase and before Data Cleaning & Preparation.
Purpose

**Before loading or cleaning data, identify:**

    • Which tables are required?   
    • Which columns are required?   
    • Which columns are irrelevant to the current business question?   

**Benefit**

Instead of cleaning every column:
```
Raw Dataset
      │
      ▼
Clean Everything ❌

We move to:

Business Question
      │
      ▼
Identify Required Columns
      │
      ▼
Load Only Those Columns
      │
      ▼
Clean Only Those Columns
      │
      ▼
Analysis

This leads to:
    • Faster analysis   
    • Lower memory usage   
    • Simpler code   
    • Less unnecessary cleaning   
    • Better alignment with the business objective  
```


**Evidence:**
Observed during project completion

**Action:**
Re-evaluate after Project 5.

**Status:**
Pending validation.

## Observation 004

**Project:**
Warehouse Operations & Inventory Analytics

**Proposed Improvement:**
Introduce a lightweight `PHASE_DELIVERABLES.md` (or an equivalent knowledge handover artifact) to formally capture the validated outputs of each DAPM phase. These outputs would become the primary input for the subsequent phase, establishing an explicit knowledge pipeline throughout the methodology.

**Evidence:**
During the transition from Business Understanding to Stakeholder Analysis, information had to be interpreted from multiple project documents (Project Brief, Project Case Journal, Observations, and Analytical Thinking). There was no single authoritative artifact representing the official outputs of the completed phase.

**Action:**
Observe the transition between every DAPM phase across at least five validation projects. Introduce the artifact only if the same gap consistently appears.

**Status:**
Pending validation.