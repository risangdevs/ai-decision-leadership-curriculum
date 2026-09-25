# Phase 2 Course Guide: Data Thinking, Evidence, and AI Execution

## Purpose

This course guide indexes the five comprehensive source chapters and shows how they form one learning sequence from question framing to AI-enabled execution.

## Grouped modules

- [Phase 2 Modules](phase-2-modules[GROUP].md)
- [Phase 2 Artifact Workbook](phase-2-artifact-workbook.md)
- [Phase 2 Source Guide](phase-2-source-guide.md)

The grouped index links to each source chapter. Each chapter contains purpose, learning outcomes, evidence base, complete teaching narrative, frameworks, templates, a worked case, participant activities, knowledge checks with suggested answers, an assessment rubric, a facilitator guide, a glossary, and authoritative further reading.

---

## Course method: scenario first, analysis before AI

The program uses three non-negotiable learning rules.

### 1. Prefer realistic scenarios over abstract theory

Concepts are introduced through credible business situations containing incomplete data, competing explanations, operational constraints, and consequences. Theory is taught only after participants have encountered the problem it helps solve. Examples should include enough numbers, definitions, and context to require judgment rather than recall.

### 2. Analyze before asking AI

Participants must produce an initial independent analysis before using an AI assistant. For every major activity, use this sequence:

```text
Observe the scenario and data
        ↓
Record an independent interpretation
        ↓
State assumptions, uncertainties, and a provisional decision
        ↓
Use AI to challenge—not originate—the reasoning
        ↓
Verify AI claims against the data and source material
        ↓
Revise the artifact and record what changed
```

The initial analysis can be brief, but it must be visible. If a participant cannot explain their own reasoning before prompting AI, the AI step pauses.

### 3. AI may extend judgment but never replace it

AI may help generate counterarguments, identify missing assumptions, test clarity, compare options, or critique an artifact. It must not be treated as the decision owner, source of truth, or substitute for examining the data. Participants remain responsible for calculations, evidence quality, trade-offs, and conclusions.

### Standard Analyze–Challenge–Verify protocol

Every project artifact uses four passes:

1. **Analyze:** Complete the first version without AI, using the provided scenario, data, and framework.
2. **Challenge:** Ask AI for alternative explanations, missing risks, or weaknesses—not for “the answer.”
3. **Verify:** Check each useful AI suggestion against data, definitions, authoritative sources, and business constraints.
4. **Decide:** Accept, modify, or reject each suggestion and document why.

Facilitators should assess the reasoning trail as well as the final artifact.

---

## Learning sequence

| Module | Core question | Participant artifact | Competency demonstrated |
|---|---|---|---|
| 3 | What kind of analytical claim does the decision require? | **1. Business Question Map** | Select approach; translate questions; distinguish association and causality |
| 4 | What does the data actually represent? | **2. Data Structure Diagram** | Understand structure; detect misleading analysis; design datasets |
| 5 | What should be measured, and how will evidence drive a decision? | **3. KPI Catalogue** and **4. Decision Specification Document** | Design KPIs; interpret metrics; specify a decision |
| 6 | What evidence will show that an intervention works? | **5. Experiment Plan** | Design experiments; validate recommendations; evaluate evidence |
| 7 | Where can AI improve execution without replacing judgment? | **6. AI Opportunity Matrix** | Identify opportunities; integrate judgment; evaluate execution strategy |

The sequence is cumulative:

```text
Business Question Map
    ↓
Data Structure Diagram
    ↓
KPI Catalogue
    ↓
Decision Specification Document
    ↓
Experiment Plan
    ↓
AI Opportunity Matrix
```

Each artifact becomes an input to the next. Participants should not begin the AI Opportunity Matrix before the decision, data structure, metrics, and evidence needs are clear.

## Progressive portfolio gates

| Artifact | Entry input | Exit evidence | Ready for next artifact when… |
|---|---|---|---|
| 1. Business Question Map | realistic decision and evidence pack | selected analytical request and reasoning trail | decision, owner, claim, population, comparison, and uncertainty are explicit |
| 2. Data Structure Diagram | approved Business Question Map and sample records | diagram, relationship inventory, dataset contract | analytical grain, keys, time, joins, and denominators can be traced |
| 3. KPI Catalogue | diagram and available measures | balanced catalogue and metric cards | outcomes, drivers, guardrails, formulas, owners, and sources are defined |
| 4. Decision Specification Document | question map and KPI Catalogue | options, evidence standard, decision logic, monitoring | owner can state what evidence changes action and which trade-offs remain human |
| 5. Experiment Plan | DSD and baseline data | implementation-ready validation plan | counterfactual, unit, metrics, validity risks, ethics, and decision rule are fixed |
| 6. AI Opportunity Matrix | Artifacts 1–5 and workflow baseline | ranked opportunities with explore/pilot/defer/reject decisions | selected task has evidence of value, workable controls, and explicit human authority |

### Portfolio status record

For each artifact, participants maintain:

**Version:**  
**Owner:**  
**Independent analysis completed:** yes / no  
**AI challenge used:** yes / no; purpose:  
**Verification performed:**  
**Material change from prior version:**  
**Reviewer and decision:** draft / revise / approved  
**Dependency created for next artifact:**

An artifact cannot be marked approved if its independent-analysis field is “no.”

---

## Recommended delivery

### Full program

- Five sessions of 120–150 minutes
- One module per session
- Participants apply every module to the same real organizational decision
- Final capstone review after Module 7

### Executive version

- Five sessions of 60–75 minutes
- Keep the opening principle, core framework, worked case, executive job aid, and one activity from each module
- Assign the templates between sessions

### Intensive workshop

- Two days
- Day 1: Modules 3–5
- Day 2: Modules 6–7 and capstone

---

## Capstone assignment

Participants select one realistic organizational decision and progressively submit six artifacts:

1. **Business Question Map:** decision, owner, business questions, analytical questions, analytics type, claim strength, population, comparison, uncertainties, and expected action.
2. **Data Structure Diagram:** entities, events, keys, relationships, cardinalities, grain, time fields, and the path from source records to the analytical unit. An Analytical Dataset Contract supports the diagram.
3. **KPI Catalogue:** outcome, leading, lagging, quality, efficiency, guardrail, and distribution metrics with definitions and ownership. Metric Specification Cards support the catalogue.
4. **Decision Specification Document:** options, criteria, evidence, trade-offs, authority, decision logic, implementation, monitoring, and reversal.
5. **Experiment Plan:** hypothesis, treatment, counterfactual, unit, assignment, metrics, validity risks, ethics, analysis, decision rule, and business-impact calculation.
6. **AI Opportunity Matrix:** workflow opportunities compared on value, feasibility, controllability, human-judgment needs, evidence readiness, and learning value. An AI Execution Specification is completed only for opportunities that pass the matrix.

Each submission includes an **analysis trail**: initial independent position, AI challenges requested, checks performed, changes accepted or rejected, and final rationale.

## Capstone review questions

- Is the decision real and owned?
- Did the participant analyze the scenario and data before using AI?
- Is the participant's reasoning visible, including rejected AI suggestions?
- Does the analytical approach match the claim?
- Can the dataset support the analysis without grain, time, join, or denominator errors?
- Do the metrics represent outcomes rather than activity alone?
- Is causal language supported by the design?
- Are trade-offs and guardrails explicit?
- Is human authority real rather than ceremonial?
- Can the system be monitored, challenged, paused, and reversed?
- Does the expected value include full operational cost?

---

## Shared fictional case

The chapters use a recurring fictional company, NovaCart, to connect the concepts:

- Module 3 investigates a renewal decline and distinguishes five analytics types.
- Module 4 audits commerce entities, grain, joins, time windows, and profitability reporting.
- Module 5 defines renewal and service metrics and produces a DSD.
- Module 6 evaluates an AI support assistant through an experiment.
- Module 7 embeds AI in support and invoice workflows with staged controls.

Facilitators may replace NovaCart with a sector-specific case while preserving the structural questions and templates.

---

## Source-use note

These files are written as comprehensive source chapters, not presentation scripts. When converting them to slides:

- retain definitions and decision logic,
- use one worked example per concept,
- place templates in participant worksheets,
- keep citations in speaker notes or a reference appendix,
- avoid turning nuanced evidence statements into absolute claims,
- preserve the distinction between prediction, prescription, and causation.

The DSD and AI Execution Specification are curriculum frameworks and should be adapted to the organization's formal governance, legal obligations, and sector standards.
