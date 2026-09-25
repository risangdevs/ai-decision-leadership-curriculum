# Phase 3 Artifact Workbook

## How to use this workbook

Build all five projects around one organizational problem. Keep every version. Do not polish away failed tests; they are evidence of learning.

For every material change, record:

| Version | Date | Author | Change | Evidence/reason | Tests rerun | Approver |
|---|---|---|---|---|---|---|
| | | | | | | |

Use these evidence labels consistently:

- **FACT:** directly supported by a cited source or reproducible data.
- **CALCULATION:** derived from shown inputs and formula.
- **INTERPRETATION:** plausible meaning of evidence.
- **ASSUMPTION:** claim required for the design but not established.
- **HYPOTHESIS:** testable proposed explanation.
- **UNKNOWN:** important gap not yet resolved.
- **DECISION:** choice made by an authorized owner.

---

# Part A. Project framing

## A1. One-page project charter

**Project name:**  
**Executive sponsor:**  
**Decision owner:**  
**Workflow/product owner:**  
**Technical owner:**  
**Risk/security/privacy owners:**  
**Frontline representative:**  
**Affected-party representative:**  

### Problem and outcome

**Observed problem (not a solution):**  

**Who experiences it:**  

**Evidence that it exists:**  

**Decision to be made:**  

**Target outcome:**  

**Baseline:**  

**Time horizon:**  

**Constraints:**  

### Alternatives to investigate

| Alternative | Value mechanism | Required change | Evidence needed |
|---|---|---|---|
| Current state | | | |
| Process/policy change | | | |
| Traditional software/automation | | | |
| AI augmentation | | | |
| Bounded AI automation | | | |
| Other | | | |

### Initial red-team challenge

**Why might this be the wrong problem?**  

**Who might be harmed or burdened?**  

**What would make AI unnecessary?**  

**What would cause the project to stop immediately?**  

---

# Part B. Project 1 — Prompt Library

## B1. Library index

| Prompt ID | Name | Task | Owner | Version | Status | Last eval | Pass rate | Known limitation |
|---|---|---|---|---|---|---|---:|---|
| | | | | | Draft/Test/Approved/Retired | | | |

## B2. Prompt card

### Identity

**Prompt ID and version:**  
**Owner:**  
**Approved models/configuration:**  
**Purpose:**  
**Primary user:**  
**Permitted use:**  
**Prohibited use:**  

### Task contract

**Inputs and definitions:**

| Variable | Meaning | Source | Required? | Validation | Sensitivity |
|---|---|---|---|---|---|
| | | | | | |

**Authorized evidence:**  

**Instructions:**  

**Rules and constraints:**  

**Uncertainty and abstention behavior:**  

**Escalation conditions:**  

**Output schema:**  

**Examples included and why:**  

### Evaluation

**Unit of evaluation:**  
**Gold/reference construction:**  
**Scoring rubric:**  
**Pass thresholds:**  
**Critical failures with zero tolerance:**  
**Holdout strategy:**  

## B3. Test case

| Field | Entry |
|---|---|
| Test ID | |
| Category | Normal/edge/adversarial/regression/out-of-scope |
| Input | |
| Context/sources | |
| Expected behavior | |
| Prohibited behavior | |
| Scoring method | |
| Actual result | |
| Pass/fail | |
| Failure layer | Requirement/data/retrieval/prompt/model/tool/validation/human/workflow |
| Follow-up | |

## B4. Minimum test portfolio

| Category | Required cases | Included? |
|---|---:|---|
| Ordinary representative cases | 10 | |
| Boundary/ambiguous cases | 5 | |
| Missing data | 3 | |
| Conflicting/outdated sources | 3 | |
| Out-of-scope | 3 | |
| Direct/indirect prompt injection | 5 | |
| Sensitive-data or unauthorized request | 3 | |
| Counterfactual pairs | 3 pairs | |
| Strict schema/validation | 3 | |
| Known-failure regressions | All | |

## B5. Prompt change report

**Observed failure:**  
**Root cause hypothesis:**  
**Smallest proposed change:**  
**Risk of overfitting or regression:**  
**Tests rerun:**  
**Before/after results:**  
**Decision:** approve / revise / reject / retire  

---

# Part C. Project 2 — AI Assistant Specification

## C1. Executive specification

**Assistant name/version:**  
**Business owner:**  
**Users:**  
**Problem:**  
**Target outcomes:**  
**AI role:** retrieve / extract / classify / summarize / draft / recommend / act  
**Reserved human decisions:**  
**Pilot scope:**  

## C2. Scope

| Dimension | In scope | Out of scope | Detection | Route |
|---|---|---|---|---|
| Users | | | | |
| Intents/tasks | | | | |
| Channels | | | | |
| Regions/products | | | | |
| Data | | | | |
| Decisions | | | | |
| Actions | | | | |

## C3. Stakeholders and affected parties

| Stakeholder | Interest/impact | Authority | Evidence/knowledge | Required involvement | Concern |
|---|---|---|---|---|---|
| | | | | | |

## C4. Requirements

| ID | Type | Requirement | Acceptance test | Threshold | Owner |
|---|---|---|---|---|---|
| | Functional/quality/safety/security/privacy/operational/human | | | | |

## C5. Knowledge-source register

| Source | Owner | Authority | Scope | Effective date | Refresh | Access rule | Conflict precedence | Removal process |
|---|---|---|---|---|---|---|---|---|
| | | | | | | | | |

## C6. Tool and permission matrix

| Tool | Purpose | Data read | Action/write | Credential | Parameter validation | Approval | Rate/step limit | Recovery |
|---|---|---|---|---|---|---|---|---|
| | | | | | | | | |

## C7. Rule register

| Rule ID | Source/owner | Rule | Enforcement layer | Exception | Test | Change approval |
|---|---|---|---|---|---|---|
| | | | Prompt/code/schema/IAM/workflow | | | |

## C8. Escalation matrix

| Trigger | Detection | Queue/role | Packet | SLA | Allowed interim action | User message |
|---|---|---|---|---|---|---|
| | | | | | | |

## C9. Human review design

**Decision reviewed:**  
**Evidence visible:**  
**Uncertainty/conflict visible:**  
**Available actions:**  
**Time and workload assumption:**  
**Reviewer training/proficiency test:**  
**How automation bias will be tested:**  
**How overrides and corrections feed learning:**  

## C10. Value hypothesis

| Capability | User behavior change | Workflow effect | Business outcome | Measure | Guardrail |
|---|---|---|---|---|---|
| | | | | | |

## C11. Architecture decision record

**Decision:**  
**Context:**  
**Options considered:**  
**Choice and rationale:**  
**Trade-offs:**  
**Risks/controls:**  
**Evidence needed to revisit:**  
**Owner/date:**  

---

# Part D. Project 3 — AI Workflow

## D1. Current-state map

| Step | Trigger | Input | Activity/decision | Owner | System | Output/state | Touch/wait time | Volume | Failure |
|---|---|---|---|---|---|---|---|---|---|
| | | | | | | | | | |

## D2. Baseline

| Metric | Definition/formula | Source | Period | Overall | Segment variation | Data concern |
|---|---|---|---|---:|---|---|
| | | | | | | |

## D3. Future-state workflow

| Step | Type | Input | Transformation/decision | Output | Owner | System | Control | Audit event |
|---|---|---|---|---|---|---|---|---|
| | deterministic/AI/human/tool | | | | | | | |

## D4. State and transition table

| Current state | Event/condition | Next state | Authorized actor | Validation | Side effect | Failure state |
|---|---|---|---|---|---|---|
| | | | | | | |

## D5. Decision and authority table

| Decision | Criteria | Input provenance | AI role | Human owner | Approval threshold | Appeal/reversal |
|---|---|---|---|---|---|---|
| | | | | | | |

## D6. Data contract

| Field | Meaning | Source/owner | Type/unit | Required | Validation | Freshness | Classification | Missing/conflict behavior | Retention |
|---|---|---|---|---|---|---|---|---|---|
| | | | | | | | | | |

## D7. Failure mode and effects analysis

Use severity, occurrence, and detectability as structured judgments, not pseudo-precise truth.

| Failure | Cause | Effect/affected party | Severity | Detection | Prevention | Containment/recovery | Owner | Test |
|---|---|---|---:|---|---|---|---|---|
| | | | | | | | | |

## D8. Threat scenarios

| Threat | Asset | Entry path | Preconditions | Impact | Prevent | Detect | Respond/recover | Test |
|---|---|---|---|---|---|---|---|---|
| Prompt injection | | | | | | | | |
| Sensitive-data disclosure | | | | | | | | |
| Improper output handling | | | | | | | | |
| Excessive agency | | | | | | | | |
| Retrieval poisoning/stale content | | | | | | | | |
| Credential abuse | | | | | | | | |
| Unbounded consumption | | | | | | | | |

## D9. Audit event schema

| Field | Purpose | Source | Sensitive? | Retention | Access |
|---|---|---|---|---|---|
| Event/correlation ID | | | | | |
| Timestamp/state | | | | | |
| User/service identity and role | | | | | |
| Input/source references | | | | | |
| Prompt/model/config version | | | | | |
| Tool request/result | | | | | |
| Validation/guardrail results | | | | | |
| Human decision/edit/reason | | | | | |
| Final action/outcome | | | | | |

## D10. Monitoring and response

| Signal | Formula/source | Segment | Baseline | Alert | Owner | Response playbook |
|---|---|---|---:|---:|---|---|
| | | | | | | |

## D11. Prototype test log

| Test | Expected | Actual | Pass | Trace/log ID | Defect | Retest |
|---|---|---|---|---|---|---|
| | | | | | | |

## D12. Pilot plan

**Population and exclusions:**  
**Duration/volume:**  
**Comparison:**  
**Training:**  
**Daily/weekly review:**  
**Entry criteria:**  
**Scale criteria:**  
**Pause criteria:**  
**Stop criteria:**  
**Rollback method:**  
**Decision owner and date:**  

---

# Part E. Project 4 — Analytics Notebook

## E1. Analysis contract

**Decision:**  
**Population/unit:**  
**Outcome:**  
**Timeframe/comparison:**  
**Data cutoff:**  
**Metric definitions:**  
**Exclusions:**  
**Missing-data policy:**  
**Privacy constraints:**  
**Validation required:**  

## E2. Data inventory

| Dataset/table | Owner | Extraction/version | Grain | Population | Key | Sensitive fields | Quality concerns |
|---|---|---|---|---|---|---|---|
| | | | | | | | |

## E3. Hypothesis register

| ID | Hypothesis | Mechanism | Prediction | Required data | Confounder | Falsifier | Result |
|---|---|---|---|---|---|---|---|
| | | | | | | | |

## E4. Finding card

**Finding:**  
**Label:** observation / calculation / interpretation / recommendation  
**Population/timeframe:**  
**Formula or method:**  
**Evidence/table/chart:**  
**Magnitude and uncertainty:**  
**Alternative explanation:**  
**Bias/quality concern:**  
**Cross-validation:**  
**Decision implication:**  

## E5. Cross-validation log

| Claim | Method 1 | Method 2 or independent source | Agreement | Sensitivity | Conclusion |
|---|---|---|---|---|---|
| | | | | | |

## E6. Bias review

| Stage | Potential bias | Evidence | Affected group | Mitigation/check | Residual limitation |
|---|---|---|---|---|---|
| Framing | | | | | |
| Selection | | | | | |
| Measurement | | | | | |
| Missingness | | | | | |
| Labeling | | | | | |
| Analysis | | | | | |
| Presentation | | | | | |
| Action/feedback | | | | | |

## E7. AI-use log

| Task AI assisted | Input/data exposure | Output used | Verification | Human owner | Limitation |
|---|---|---|---|---|---|
| | | | | | |

## E8. Recommendation

**Decision requested:**  
**Finding:**  
**Evidence:**  
**Uncertainty:**  
**Affected stakeholders:**  
**Alternatives:**  
**Recommendation:** act / pilot / investigate / do not proceed  
**Guardrails:**  
**Owner/review date:**  
**Change/stop trigger:**  

---

# Part F. Project 5 — AI Business Case

## F1. Decision request

**Requested decision/funding:**  
**Owner and date:**  
**Problem and baseline:**  
**Proposed scope:**  
**Strategic fit:**  
**Recommendation:**  

## F2. Evidence register

| Claim | Evidence label | Source/link | Publisher/date | Method/sample | Independence | Limitations | Confidence |
|---|---|---|---|---|---|---|---|
| | Fact/calculation/interpretation/assumption | | | | | | |

## F3. Alternative comparison

| Criterion | Current state | Process/non-AI | Buy/partner | AI assist | Bounded automation |
|---|---|---|---|---|---|
| Outcome value | | | | | |
| Time to evidence | | | | | |
| Total cost | | | | | |
| Data/workflow readiness | | | | | |
| Risk/reversibility | | | | | |
| Adoption burden | | | | | |
| Strategic control | | | | | |

## F4. Cost model

| Cost | One-time | Recurring fixed | Variable unit cost | Downside | Base | Upside | Owner/source |
|---|---:|---:|---:|---:|---:|---:|---|
| Discovery/design | | | | | | | |
| Data/knowledge preparation | | | | | | | |
| Integration/build | | | | | | | |
| Security/legal/procurement | | | | | | | |
| Model/platform/infrastructure | | | | | | | |
| Human review/exceptions | | | | | | | |
| Evaluation/monitoring | | | | | | | |
| Training/change/support | | | | | | | |
| Incident/appeal/remediation | | | | | | | |
| Exit/contingency | | | | | | | |

## F5. Benefit model

| Benefit | Baseline | Mechanism | Unit value | Eligible volume | Adoption/ramp | Realization rate | Annual range | Owner |
|---|---:|---|---:|---:|---:|---:|---:|---|
| | | | | | | | | |

## F6. Risk/control register

| Risk | Affected party | Inherent level | Controls | Control test | Residual level | Owner | Accept/mitigate/avoid/transfer |
|---|---|---|---|---|---|---|---|
| | | | | | | | |

## F7. KPI contract

| KPI | Type | Formula/denominator | Source | Segment | Baseline | Target/guardrail | Cadence | Owner/action |
|---|---|---|---|---|---:|---:|---|---|
| | Outcome/leading/quality/risk/adoption/technical | | | | | | | |

## F8. Scenario and ROI

| Input/output | Downside | Base | Upside | Source/logic |
|---|---:|---:|---:|---|
| Eligible volume | | | | |
| Adoption | | | | |
| Benefit per successful case | | | | |
| AI success rate | | | | |
| Review time | | | | |
| Total cost | | | | |
| Realized benefit | | | | |
| Net benefit | | | | |
| ROI | | | | |
| Payback | | | | |

**Break-even condition:**  
**Most sensitive assumptions:**  
**Non-financial benefits/harms:**  

## F9. Adoption plan

| Group | Current work | Future work | Benefit/concern | Training/support | Feedback/channel | Owner |
|---|---|---|---|---|---|---|
| | | | | | | |

## F10. Stage-gated funding

| Stage | Scope | Funding | Entry evidence | Exit evidence | Stop condition | Decision owner |
|---|---|---:|---|---|---|---|
| Discovery | | | | | | |
| Prototype | | | | | | |
| Pilot | | | | | | |
| Bounded deployment | | | | | | |
| Scale | | | | | | |

---

# Part G. Architecture review pack

## G1. Pre-read checklist

- [ ] One-page problem, outcome, baseline, and scope
- [ ] Current and future workflow maps
- [ ] System context/data-flow diagram
- [ ] Assistant specification
- [ ] Prompt library and evaluation report
- [ ] Data and knowledge-source registers
- [ ] Decision/authority and permission matrices
- [ ] Threat and risk/control registers
- [ ] Prototype trace and failure demonstrations
- [ ] Analytics notebook
- [ ] Business case and scenario model
- [ ] Pilot, fallback, incident, and rollback plans
- [ ] Open issues and explicit decision requests

## G2. Review scorecard

Score 0 missing, 1 claimed, 2 partial, 3 pilot-ready, 4 demonstrated.

| Dimension | Score | Evidence | Blocking issue | Required action/owner |
|---|---:|---|---|---|
| Problem/outcome clarity | | | | |
| Workflow and decision rights | | | | |
| Data/evidence fitness | | | | |
| Functional quality | | | | |
| Safety/security/privacy/fairness | | | | |
| Human oversight/contestability | | | | |
| Reliability/fallback/recovery | | | | |
| Observability/auditability | | | | |
| Cost/value | | | | |
| Adoption/operating ownership | | | | |

## G3. Mandatory attack script

The review lead assigns expected system behavior before the demonstration.

| Attack | Expected safe behavior | Actual | Evidence/log | Result |
|---|---|---|---|---|
| Missing required input | | | | |
| Ambiguous request | | | | |
| Unsupported task | | | | |
| User prompt injection | | | | |
| Injection inside retrieved document | | | | |
| Unauthorized source/request | | | | |
| Stale/conflicting source | | | | |
| Fabricated but plausible fact | | | | |
| Invalid tool parameters | | | | |
| Tool timeout after success | | | | |
| Duplicate event/action | | | | |
| Dependency outage | | | | |
| Cost/step runaway | | | | |
| High-impact exception | | | | |
| Reviewer automation bias | | | | |
| Distribution/subgroup shift | | | | |

## G4. Review decision

**Decision:** reject / revise and re-review / approve shadow mode / approve limited pilot / approve bounded deployment  

**Conditions:**  

**Accepted residual risks and owner:**  

**Required fixes and dates:**  

**Next gate:**  

**Approvers:**  

---

# Part H. Final production-readiness checklist

“Yes” requires linked evidence.

## Problem and ownership

- [ ] A named owner controls the workflow outcome.
- [ ] The baseline and affected populations are documented.
- [ ] A simpler non-AI alternative was evaluated.
- [ ] Scope and prohibited use are unambiguous.

## Data and knowledge

- [ ] Every required input has an owner and contract.
- [ ] Sources have authority, access, freshness, and precedence rules.
- [ ] Personal/confidential data are minimized and permitted.
- [ ] Deletion and retention behavior are tested.

## Model, prompt, and retrieval

- [ ] Prompt/config/model versions are controlled.
- [ ] Retrieval and answer quality are evaluated separately.
- [ ] Holdout, adversarial, counterfactual, and regression tests pass thresholds.
- [ ] Unknown, missing, and conflicting evidence produce safe behavior.

## Tools and security

- [ ] Tools use minimum functionality and least privilege.
- [ ] Parameters and outputs are validated.
- [ ] High-impact actions require enforceable approval.
- [ ] Injection, data disclosure, excessive agency, and consumption attacks are tested.
- [ ] Duplicate/partial transactions are contained.

## Human system

- [ ] Reviewers see evidence and uncertainty.
- [ ] Reviewers can reject, edit, escalate, pause, and appeal.
- [ ] Reviewer proficiency and automation bias are tested.
- [ ] Workload, incentives, training, and accessibility are addressed.

## Operations

- [ ] State, actions, approvals, versions, and outcomes are auditable.
- [ ] Monitoring has thresholds, owners, and playbooks.
- [ ] Manual fallback, rollback, and restoration are tested.
- [ ] Incident, complaint, and appeal routes work.
- [ ] Model, prompt, policy, data, and vendor changes trigger re-evaluation.

## Value and adoption

- [ ] End-to-end outcome improves against a credible baseline.
- [ ] Quality and risk guardrails remain within tolerance.
- [ ] Human review and exception costs are included.
- [ ] Benefits have realization owners.
- [ ] ROI survives plausible downside assumptions.
- [ ] Scale and stop criteria are precommitted.

## Final learner reflection

1. Which assumption changed most during the phase?
2. Which failure was hardest to contain?
3. Where did deterministic logic outperform an LLM?
4. What evidence justified each increase in autonomy?
5. What remains unknown after the pilot?
6. Who bears the residual risk?
7. What future change would invalidate the approval?

