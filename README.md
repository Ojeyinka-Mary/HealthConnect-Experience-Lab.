# HealthConnect Clinic Experience Lab

### Improving Patient Appointment Attendance and Healthcare Support Using Data & AI

HealthConnect is a multidisciplinary healthcare project exploring how **data, predictive modelling, machine learning and Generative AI** can be combined to address two connected challenges: understanding missed-appointment patterns and improving routine patient support.

> **Business Need → Evidence → Decision → Intervention → Measurable Value**

---

## Project Architecture

Four technical workstreams contribute to a shared solution, coordinated through Project Management.

| Workstream           | Primary Contribution                                                            |
| -------------------- | ------------------------------------------------------------------------------- |
| **Data Analytics**   | Data preparation, KPI development, exploratory analysis and attendance insights |
| **Data Science**     | Feature development, predictive modelling, evaluation and candidate refinement  |
| **Machine Learning** | Model implementation, scoring, technical verification and pipeline integration  |
| **Generative AI**    | Patient support, behavioural testing, safety boundaries and escalation          |

**Project Management** provides the coordination layer across these workstreams, with responsibility for schedule, dependencies, risks, issues, decisions, handoffs, testing coordination and readiness control.

The delivery model is **controlled-parallel and dependency-driven**: workstreams can progress independently, but material outputs must satisfy their downstream dependencies before they are treated as integrated.

---

## Delivery Model

HealthConnect progresses through:

**Data Foundation → Analytical Evidence → Predictive Development → Technical Integration → Testing & Refinement → Final Integration**

For material handoffs:

> **Produce → Check → Transfer → Use → Verify → Accept**

This creates an important distinction throughout the project:

**Done is not automatically integrated.
Integrated is not automatically validated.
Validated is not automatically ready.**

---

## Project Progression

### Week 4 — Foundation

Established the initial project control environment through:

* Project Charter
* Scope & Work Breakdown Structure
* Stakeholder Register
* Risk & Dependency Register
* Communication Approach
* High-Level Timeline

### Week 5 — Execution

Moved into controlled delivery through:

* Task and progress tracking
* Schedule updates
* Dependency monitoring
* Cross-workstream coordination
* Issue and decision management
* Project status control

### Week 6 — Integration Preparation

The technical workstreams moved toward a shared evidence base.

**Data Analytics** strengthened the cleaned and enriched dataset, exploratory analysis and KPI framework.

**Data Science** progressed predictive no-show modelling through comparative evaluation and model refinement.

**Machine Learning** developed the scoring pathway and began integration testing, while maintaining a clear distinction between a technical stand-in estimator and the final Data Science candidate.

**Generative AI** entered targeted behavioural testing, where an emergency-disclaimer inconsistency was identified and subsequently refined.

### Week 7 — Testing & Refinement

Week 7 changed the project's emphasis from building components to **challenging whether those components behaved as expected**.

Testing and validation covered:

* analytical and dashboard components;
* model robustness and segment performance;
* ML pipeline, batch scoring and regression behaviour;
* negative-input handling and reproducibility;
* model explainability;
* Generative AI safety and boundary scenarios; and
* cross-workstream handoffs and unresolved dependencies.

The ML pipeline reached **69/69 automated tests passing** and processed **948/948 records** during batch-scoring validation.

The refined Data Science candidate recorded a **5-fold ROC-AUC of 0.6771 ± 0.0090**, alongside additional recall, threshold, segment and overfitting analysis.

Generative AI testing reached **eight live-tested scenarios cumulatively**. Scenarios affected by validation-environment availability remain explicitly classified as blocked rather than being treated as failures.

---

## Evidence Base

The project established an initial **48.46% no-show rate** as a baseline measure.

Attendance patterns were examined across:

* previous attendance/no-show history;
* appointment lead time;
* distance;
* age and gender;
* appointment timing and characteristics; and
* reminder status.

These are treated as **observed associations rather than causal findings**.

A distance pattern around **30–40 km** has been retained as an analytical observation requiring further interpretation, rather than being used to claim that distance causes non-attendance or that reminders are ineffective.

**No-Show Rate** and **Show Rate** remain the principal baseline measures for later intervention assessment.

---

## Integration Map

The project's most important interfaces are not simply technical connections; they are **points where one workstream's output becomes another workstream's input or decision basis**.

### Analytics → Data Science

Analytical findings and dataset outputs are available for predictive development. Formal downstream disposition remains to be completed.

### Data Science → Machine Learning

The refined candidate has been characterised, but **actual transfer and receiving-side confirmation of the final candidate remain outstanding**.

The ML stand-in estimator used during earlier technical testing is therefore not represented as evidence of final DS→ML integration.

### Machine Learning → Decision Path

Technical scoring has been substantially verified. The downstream relationship between **model score, classification threshold, decision and intervention** remains to be validated.

### Generative AI → Patient Support

Selected scheduling, emergency and boundary behaviours have been tested. Broader safety, consistency and privacy-sensitive coverage remains in progress.

### All Workstreams → HealthConnect

Full end-to-end solution validation remains a Week 8 activity.

---

## Current Project Position

### 🟠🔴 AMBER-RED — CONTROLLED INTEGRATION

| Control Area                  | Current Position                  |
| ----------------------------- | --------------------------------- |
| **Stage**                     | Final Integration                 |
| **DS → ML**                   | Pending actual candidate transfer |
| **ML Technical Validation**   | Substantially established         |
| **Operational Decision Path** | Pending validation                |
| **GenAI Validation**          | Conditional                       |
| **Cross-Track Acceptance**    | In progress                       |
| **End-to-End Validation**     | Outstanding                       |
| **Week 8 Progression**        | **Conditionally Ready**           |

The project has therefore moved into Week 8 under a **controlled transition**, with unresolved technical and interface conditions carried forward rather than reclassified as complete.

---

## Week 8 Focus

The immediate delivery sequence is:

**Candidate Transfer → Schema Reconciliation → Model Execution → Output Validation → Threshold & Decision Testing → Intervention Validation → Cross-Track Acceptance → End-to-End Testing → Final Readiness**

In parallel, outstanding Generative AI scenarios and safety/consistency coverage will continue to be resolved.

---

## Project Management Perspective

HealthConnect has reinforced a principle that sits at the centre of its delivery model:

> **The value of a project output is determined not only by whether it exists, but by whether the next part of the system can reliably use it.**

Project Management therefore tracks more than task completion. The control focus is on **handoffs, dependencies, evidence, unresolved interfaces and the conditions required for the next decision**.

---

## Repository Scope

This repository captures the HealthConnect journey from project foundation through:

**Planning → Execution → Analytical Development → Predictive Modelling → Technical Integration → Testing → Refinement → Final Integration**

It brings together the technical workstreams and the project controls used to move them toward a shared, evidence-based solution.

---

**Programme:** AnalystLab Africa Experience Lab
**Project:** Improving Patient Appointment Attendance and Healthcare Support Using Data & AI
**Current Stage:** Week 8 — Final Integration
**Overall Status:** 🟠🔴 **AMBER-RED — Controlled Integration**
