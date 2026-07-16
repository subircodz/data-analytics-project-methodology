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
Implemented.

**Status:**
Validated ✅

---

## Observation 002

**Project:**
Warehouse Operations & Inventory Analytics

**Proposed Improvement:**
Introduce a lightweight `PHASE_CHECKLIST.md` to define completion criteria for each phase.

**Evidence:**
Observed during transition from Phase 1 to Phase 2.

**Action:**
Implemented.

**Status:**
Validated ✅

---

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
🟡 Pending validation.

---

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
🟡 Pending validation.

---

## Observation 005

**Project:**
Distribution Center & Logistics Analytics

**Proposed Improvement:**
Add a guiding principle to DAPM clarifying that the phases represent analytical activities rather than isolated meetings. Information relevant to later phases may naturally emerge during earlier client discussions and should be captured immediately, then validated during the appropriate DAPM phase.

**Evidence:**
During the Stakeholder Analysis phase, the client naturally revealed several business requirements and potential KPIs while discussing stakeholder information needs. The current methodology does not explicitly explain whether such information should be deferred until the corresponding phase or documented immediately. This created uncertainty during the validation project, despite the information being valuable and relevant.

**Action:**
Observe future validation projects to determine whether information consistently overlaps across DAPM phases. If this behavior is common, introduce an "Information Discovery Principle" (or equivalent guidance) in DAPM v0.2 to clarify that the methodology organizes and validates information rather than restricting when it may be discovered.

**Status:**
🟡 Pending validation.

---

## Observation 005

**Project:**
Warehouse Operations & Inventory Analytics

**Proposed Improvement:**
Re-evaluate the role of `PROJECT_CASE_JOURNAL.md` for medium and large-scale analytics projects. Consider whether detailed consultant–client discussions should reside within their respective phase documents, allowing the Project Case Journal to be simplified or retired if it no longer provides unique value.

**Evidence:**
During the validation project, a single `PROJECT_CASE_JOURNAL.md` was sufficient because the project was intentionally scoped as a prototype with concise discussions. However, it became evident that in real-world engagements spanning multiple months, the journal could grow into a very large document, making it difficult to navigate and maintain. At the same time, creating detailed phase documents while retaining a comprehensive journal may introduce unnecessary duplication, particularly since the project README already serves as the primary navigation entry point.

**Action:**
Continue using the current Project Case Journal during additional validation projects. Observe whether it consistently provides value beyond the dedicated phase documentation. If future evidence shows that phase documents adequately capture consultant discussions and project history, consider simplifying or retiring the Project Case Journal in a future DAPM release.

**Status:**
🟡 Pending validation.