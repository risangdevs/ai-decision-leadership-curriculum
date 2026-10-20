# Phase 2 Modules [GROUP]

## Data thinking, evidence, experimentation, and execution

This file consolidates the complete Phase 2 modules in their intended learning order. The navigation table links to stable module anchors within this document.

## Module sequence

| Order | Module | Focus | Primary output |
|---:|---|---|---|
| 1 | [Module 3: Fundamentals of Data Thinking](#module-3) | Connect the business decision to the right analytical question, evidence, and claim strength. | Business Question Map |
| 2 | [Module 4: Data Structure Literacy](#module-4) | Understand entities, grain, keys, relationships, time, population, and aggregation before interpreting results. | Data Structure Diagram and Analytical Dataset Contract |
| 3 | [Module 5: Metrics, Evidence & Decision Specification](#module-5) | Design balanced metrics and specify how evidence will change action. | KPI Catalogue and Decision Specification Document |
| 4 | [Module 6: Experiment Design & Decision Making](#module-6) | Design proportionate validation around the decision, intervention, counterfactual, and meaningful effect. | Experiment Plan |
| 5 | [Module 7: AI for Business Execution](#module-7) | Identify suitable AI opportunities and design controlled human–AI operating models. | AI Opportunity Matrix and AI Execution Specification |

## Progression

```text
Business Question Map
    ↓
Data Structure Diagram
    ↓
KPI Catalogue and Decision Specification
    ↓
Experiment Plan
    ↓
AI Opportunity Matrix
```

Each artifact becomes an input to the next. Learners should not select an AI opportunity before the decision, data structure, metrics, and evidence needs are clear.

## Phase materials

- [Phase 2 Course Guide](phase-2-course-guide.md)
- [Phase 2 Artifact Workbook](phase-2-artifact-workbook.md)
- [Phase 2 Source Guide](phase-2-source-guide.md)
- [Source Origin Map](source-origin-map.md)

## Assessment and delivery control

Use these chapters with the entry, workload, tool/data, accessibility, common-scale, calibration, reassessment, and appeal rules in the [Phase 2 Course Guide](phase-2-course-guide.md). Native 0–2 artifact scores remain visible; common program levels are separate evidence-based judgments.

---

## Consolidated module content

<a id="module-3"></a>

# Module 3: Fundamentals of Data Thinking

## Module purpose

Data thinking is the discipline of connecting a business decision to the right question, evidence, and analytical method. It prevents a common organizational failure: producing technically correct analysis that does not answer the decision maker's real question.

This module teaches leaders and analysts to distinguish five types of analytics, translate business questions into answerable analytical questions, recognize what observational data can and cannot establish, and avoid confusing correlation with causation.

The central idea is:

> The analytical method must match the claim the organization needs to make.

---

## Intended audience

- Business leaders and managers who request or consume analysis
- Analysts, product managers, and transformation teams
- Data, AI, finance, operations, and strategy professionals
- Cross-functional teams that must turn evidence into action

## Suggested duration

120 minutes, including case discussion and question-framing practice.

## How to use this source

This is a comprehensive source chapter rather than a slide script. It can support:

- A 90–120 minute workshop
- A self-paced learning module
- A facilitator-led case discussion
- A manager–analyst working session
- Source material for a shorter executive briefing

## Learning method: analyze before AI

Begin with a realistic business scenario and a small evidence pack, not a definition lecture. Participants first inspect the data, write what they observe, select an analytics type, and draft the question in their own words. Only then may they use AI to challenge the draft.

Required sequence:

1. **Analyze independently:** record patterns, alternative explanations, missing information, and a provisional analytical approach.
2. **Commit a first draft:** complete the Business Question Map before opening an AI assistant.
3. **Challenge with AI:** ask for counterarguments, ambiguity, confounders, or missing questions—not a final answer.
4. **Verify:** test every useful suggestion against the scenario data and the frameworks in this module.
5. **Revise with reasons:** show what changed, what was rejected, and why.

AI must never be listed as the decision owner or cited as evidence for a business conclusion.

## Learning outcomes

By the end of this module, participants will be able to:

1. Distinguish descriptive, diagnostic, predictive, prescriptive, and causal analytics.
2. Select the weakest analytical approach capable of supporting the required decision.
3. Separate a business question from an analytical request.
4. Convert an ambiguous business concern into a precise, testable analytical question.
5. Distinguish observational data from experimental data.
6. Explain why association alone does not establish causation.
7. Identify plausible confounders, reverse causality, selection effects, and measurement artifacts.
8. State conclusions at the strength supported by the evidence.
9. Produce Project Artifact 1: a Business Question Map.

## Evidence base and framework alignment

This module uses the logic of causal inference and experimental design presented in the World Bank and Inter-American Development Bank's [*Impact Evaluation in Practice*](https://www.worldbank.org/en/programs/sief-trust-fund/publication/impact-evaluation-in-practice), including the importance of a counterfactual and the distinction between randomized and non-randomized approaches. Experimental-design guidance is also aligned with the [NIST/SEMATECH Engineering Statistics Handbook](https://www.nist.gov/programs-projects/nistsematech-engineering-statistics-handbook), which emphasizes defining objectives, factors, responses, and design before collecting data.

The five-type taxonomy in this module is a practical teaching synthesis. Descriptive, diagnostic, predictive, and prescriptive analytics are common industry categories. **Causal analytics is treated separately** because estimating what an intervention changes requires a different claim and evidence standard from forecasting what is likely to happen.

---

# 1. Start with the decision, not the data

Organizations often begin with what they have:

- a dashboard,
- a customer database,
- a new AI tool,
- a model someone wants to build, or
- a request to “find insights.”

Data thinking begins elsewhere:

> What decision must be made, and what uncertainty prevents a good choice?

Suppose customer churn rises from 5% to 8%. Five different questions may follow:

1. **What happened?** Churn rose, but where and when?
2. **Why did it happen?** Which mechanisms plausibly explain the rise?
3. **What will happen next?** Which customers or segments are likely to churn?
4. **What should we do?** Which intervention best meets the objective within constraints?
5. **What would a specific action change?** Would faster support actually reduce churn?

These are not variations of one analysis. They require different methods, assumptions, and evidence.

## A decision-first question sequence

Before accepting an analysis request, ask:

1. What decision will this analysis inform?
2. Who owns that decision?
3. What options are available?
4. When is the decision required?
5. What outcome and constraints matter?
6. What would the decision maker do differently for each plausible result?

If no possible result would change the decision, the analysis has low decision value.

---

# 2. The five analytics types

## Overview

| Type | Core question | Typical output | Appropriate claim | Common mistake |
|---|---|---|---|---|
| **Descriptive** | What happened? | Counts, rates, distributions, trends | “The observed data show…” | Treating a pattern as an explanation |
| **Diagnostic** | What may explain what happened? | Segmentation, drill-down, decomposition, anomaly review | “The pattern is consistent with…” | Calling an association a root cause |
| **Predictive** | What is likely to happen? | Forecast, probability, risk score | “Given these conditions, we estimate…” | Assuming a strong predictor is a useful intervention |
| **Prescriptive** | What action best meets the objective? | Recommendation, allocation, optimization, decision rule | “Under these assumptions and constraints, choose…” | Hiding values and trade-offs inside a model |
| **Causal** | What would change because of an action? | Estimated treatment effect or impact | “Compared with the counterfactual, the action changed…” | Using before–after or correlation as proof of impact |

The types are related, but they are not a maturity ladder in which every problem should end in prescriptive analytics. The right type depends on the decision and the evidence available.

## 2.1 Descriptive analytics: what happened?

Descriptive analytics organizes observed data into a faithful account of events or states.

Typical methods include:

- counts and totals,
- means, medians, percentiles, and distributions,
- rates and ratios,
- time trends,
- cross-tabulations,
- cohort summaries,
- dashboards and operational reports.

Example:

> Monthly churn increased from 5.1% to 7.8%. The increase was concentrated among customers in their first 60 days, on the Basic plan, and using Android version 14.

That statement adds useful structure. It does not explain why churn rose.

### Descriptive quality checks

- Is the population clearly defined?
- Is the time window appropriate?
- Is the denominator stable and visible?
- Are definitions consistent across groups and periods?
- Are missing, late, duplicated, or corrected records material?
- Does an average hide a changing distribution?

### When descriptive analysis is enough

Description may be sufficient when the decision rule is already agreed. If inventory below a safety threshold must be replenished, an accurate current-state report may support action without diagnosis or prediction.

## 2.2 Diagnostic analytics: what may explain it?

Diagnostic analytics searches for mechanisms, contributors, or conditions associated with an outcome.

Typical methods include:

- segmentation and drill-down,
- variance decomposition,
- funnel analysis,
- cohort comparison,
- process mining,
- root-cause workshops,
- regression used for conditional association,
- qualitative interviews and operational observation.

Example:

> Churn is 2.3 times higher among customers who experienced two or more app crashes, after comparing customers within the same plan and tenure band.

This is stronger than an uncontrolled comparison, but still may not be causal. Customers with older devices, poor connectivity, or different usage patterns may both experience more crashes and churn more often.

### Diagnosis is an argument, not a label

A credible diagnostic explanation should describe:

1. **Mechanism:** How could the proposed factor produce the outcome?
2. **Sequence:** Did the proposed cause occur before the outcome?
3. **Alternative explanations:** What else could produce the same pattern?
4. **Disconfirming evidence:** What observation would weaken the explanation?
5. **Triangulation:** Do quantitative, qualitative, and process evidence agree?

“The dashboard says so” is not a root-cause method.

## 2.3 Predictive analytics: what is likely to happen?

Predictive analytics estimates an unknown or future outcome from available information.

Typical methods include:

- statistical forecasting,
- regression and classification,
- time-series models,
- survival analysis,
- machine learning risk scores,
- scenario-based probability estimates.

Example:

> Based on behavior through today, the model estimates a 64% probability that Customer A will cancel within 30 days.

Prediction can support prioritization, capacity planning, or early warning. It does not reveal which intervention will change the outcome.

### Prediction quality is more than accuracy

Ask:

- What is the baseline or simple alternative?
- Was testing genuinely separated from model development?
- Does performance hold over time and across relevant groups?
- Are probability estimates calibrated?
- What are the consequences of false positives and false negatives?
- Does the prediction arrive early enough to act?
- Can the organization change the predicted outcome?

### Predictor versus lever

A variable can be highly predictive without being a useful lever. Previous cancellations may predict future cancellations, but changing a database field containing that history will not retain the customer. Predictive features are signals; interventions are actions.

## 2.4 Prescriptive analytics: what should we do?

Prescriptive analytics combines evidence with objectives, constraints, costs, and values to recommend an action.

Typical methods include:

- mathematical optimization,
- simulation,
- decision analysis,
- scheduling and routing,
- inventory optimization,
- policy or business rules,
- ranked recommendations,
- scenario and sensitivity analysis.

Example:

> Given a retention budget of $100,000, contact-center capacity of 2,000 calls, and a maximum offer of 15%, prioritize these customer segments to maximize expected retained contribution margin.

The recommendation depends on more than prediction. It requires estimates of intervention effects, customer value, costs, constraints, and acceptable trade-offs.

### Every prescription contains a policy

Prescriptive systems answer “best according to what?” Leaders must make explicit:

- the objective function,
- constraints and non-negotiable boundaries,
- whose outcomes count,
- the time horizon,
- risk tolerance,
- fairness or service obligations,
- the cost of different errors.

A mathematically optimal answer can still be strategically or ethically unacceptable if the objective is incomplete.

## 2.5 Causal analytics: what would the action change?

Causal analytics estimates the difference an action, policy, or exposure makes relative to what would have happened otherwise.

The central difficulty is the **counterfactual**. For the same customer at the same moment, the organization cannot observe both:

- churn after receiving proactive support, and
- churn without receiving proactive support.

Causal designs construct a credible comparison to approximate the unobserved alternative.

Example:

> Random assignment produced comparable treatment and control groups. Proactive support reduced 30-day churn by 1.8 percentage points, with a 95% confidence interval from 0.7 to 2.9 points, for eligible new customers during the test period.

### Common causal approaches

- Randomized controlled experiments
- Natural experiments
- Difference-in-differences
- Regression discontinuity
- Instrumental variables
- Matching or weighting on observed factors
- Interrupted time series

Methods differ in the assumptions required. A sophisticated method does not rescue a weak comparison.

---

# 3. Selecting the proper analytics approach

## Use the weakest sufficient claim

Stronger claims require stronger evidence. Do not ask for causality when a current-state description supports the decision; do not settle for prediction when the decision depends on the effect of an intervention.

| Decision need | Minimum useful approach | Escalate when… |
|---|---|---|
| Monitor performance | Descriptive | The metric moves and the reason matters |
| Investigate a problem | Diagnostic | A decision requires knowing what an intervention changes |
| Anticipate demand or risk | Predictive | Action changes behavior or resources must be optimized |
| Allocate constrained resources | Prescriptive | Intervention effects are uncertain or unequal |
| Decide whether to scale a program | Causal | Effects are already established and the main issue is allocation |

## Analytics selection questions

1. Is the target a past/current state, future outcome, recommended action, or effect of an action?
2. Must the result explain, forecast, optimize, or estimate impact?
3. What claim will leaders repeat after seeing the result?
4. What is the consequence if that claim is wrong?
5. Is the available data capable of supporting that claim?

## A frequent sequence—but not a mandatory one

Many investigations progress as follows:

> Describe → diagnose → predict → test an intervention → prescribe or scale

The sequence can loop. An experiment may reveal heterogeneous effects that require new descriptive analysis. A prediction system may fail because the entity or time window was defined incorrectly. Good analysis is iterative.

---

# 4. Observational versus experimental data

## Observational data

Observational data arise when the analyst does not control assignment to the exposure or intervention.

Examples:

- transaction records,
- customer support logs,
- website behavior,
- operational sensor data,
- employee records,
- surveys,
- historical marketing campaigns chosen by managers.

Observational data can be large, timely, and behaviorally realistic. They are excellent for description and prediction. Causal inference is possible in some observational settings, but only with a defensible design and explicit assumptions.

## Experimental data

Experimental data arise when the researcher deliberately varies an intervention according to a planned design. Random assignment makes treatment independent of both observed and unobserved pre-treatment characteristics in expectation.

Examples:

- randomly assigning eligible customers to two onboarding flows,
- randomizing store-level promotional displays,
- testing message timing across comparable user groups,
- rotating process settings using a designed industrial experiment.

Experimental data strengthen causal attribution, but experiments are not automatically valid or ethical.

## Comparison

| Dimension | Observational | Experimental |
|---|---|---|
| Assignment | Occurs naturally or through existing decisions | Controlled by a planned protocol |
| Main strength | Real-world coverage; low disruption; historical depth | Stronger causal identification when well executed |
| Main threat | Confounding and selection | Noncompliance, spillover, attrition, weak implementation |
| Typical use | Description, diagnosis, prediction, quasi-experimental impact evaluation | Causal effects and mechanism testing |
| Key question | Why were some units exposed and others not? | Was assignment implemented and preserved as designed? |

## Random sampling is not random assignment

- **Random sampling** helps a sample represent a target population.
- **Random assignment** helps treatment and control groups be comparable.

An experiment can have strong internal validity but poor generalizability if its participants are unrepresentative. A representative survey can describe a population well but cannot establish causal effects merely because sampling was random.

---

# 5. Business questions and analytical requests

## A business question

A business question expresses a decision, problem, opportunity, or outcome in organizational language.

Examples:

- Why are renewals falling?
- Which market should we enter?
- How should we reduce delivery delays?
- Should we launch the new service nationally?

Business questions are valuable but usually underspecified for analysis.

## An analytical request

An analytical request specifies the population, measure, comparison, time, method, and output needed to reduce decision uncertainty.

Example:

> For paid customers whose annual subscriptions became renewable between 1 January and 30 June, compare 30-day renewal rates across acquisition channel, tenure, plan, service incidents, and price-change exposure. Quantify each segment's contribution to the overall decline and report uncertainty and data-quality limitations.

That request supports diagnosis. It does not yet ask whether changing any factor would cause renewal to improve.

## The BQA translation framework

Convert a business concern into an analytical question using nine fields:

| Field | Question to answer |
|---|---|
| **Decision** | What choice will the result inform? |
| **Decision owner** | Who will act on the result? |
| **Population/entity** | Customers, orders, stores, products, employees, or something else? |
| **Outcome** | What precisely is to be measured? |
| **Time** | Observation window, outcome window, and decision deadline? |
| **Comparison/counterfactual** | Compared with whom, what, or when? |
| **Analytics type** | Describe, diagnose, predict, prescribe, or estimate impact? |
| **Constraints** | Budget, capacity, policy, risk, or ethical limits? |
| **Deliverable** | Table, model, experiment result, decision rule, or recommendation? |

### Business Question to Analytical Request template

> To inform **[decision]** by **[decision owner]**, analyze **[population/entity]** during **[time window]**. Measure **[outcome and definition]**, compare **[groups/baseline/counterfactual]**, and use **[analytics type/method]** to determine **[answer required]**. Account for **[constraints/confounders/quality risks]**. Deliver **[output]** by **[deadline]**, including **[uncertainty and limitations]**.

## Example translation

Business question:

> Should we expand weekend delivery?

Possible analytical questions:

- **Descriptive:** What share of orders, revenue, late deliveries, and support contacts currently occurs on weekends by region?
- **Diagnostic:** Which operational bottlenecks contribute most to weekend delays?
- **Predictive:** What weekend order volume and staffing demand are expected by region next quarter?
- **Prescriptive:** Given staffing and fleet constraints, what delivery schedule minimizes cost while meeting the service target?
- **Causal:** For eligible customers, how does offering weekend delivery change conversion, margin, and repeat purchase relative to not offering it?

The same business question can legitimately generate several analytical requests.

---

# 6. Correlation versus causation

## Correlation

Correlation means two variables vary together. The relationship may be positive, negative, nonlinear, conditional, or created by how the data were collected.

Correlation is useful for:

- finding signals,
- generating hypotheses,
- making forecasts,
- prioritizing investigation.

It is not, by itself, evidence that changing one variable will change the other.

## Causation

A causal claim says that intervening on one factor would change an outcome, relative to a credible alternative state.

This is an intervention claim:

> If we change X, Y will change by this amount for this population under these conditions.

## Four reasons correlation can mislead

### 1. Confounding

A third variable influences both the apparent cause and outcome.

Example: customers who contact support churn more. The underlying product problem may cause both the support contact and churn.

### 2. Reverse causality

The proposed outcome influences the proposed cause.

Example: declining employee performance appears associated with more manager check-ins because managers increase monitoring after performance begins to fall.

### 3. Selection bias

The observed groups differ because of how they entered the dataset or received the intervention.

Example: customers offered discounts may appear more likely to churn because staff target discounts at the highest-risk cases.

### 4. Measurement or aggregation artifact

The relationship is created or reversed by definitions, missing data, time windows, or combining groups.

Example: a region's conversion rate rises even though every channel's conversion rate falls, because the mix shifts toward the historically highest-converting channel. This is a form of Simpson's paradox.

## The causality challenge checklist

Before accepting a causal statement, ask:

1. What exactly is the intervention?
2. What is the outcome, and when is it measured?
3. What is the counterfactual?
4. How were units assigned or selected?
5. Could a common cause explain both variables?
6. Could the direction run the other way?
7. Did the cause occur before the effect?
8. Are there spillovers, attrition, or behavior changes caused by measurement?
9. Does the mechanism make sense?
10. How far does the estimate generalize?

## Use calibrated causal language

| Evidence | Appropriate language |
|---|---|
| Descriptive pattern | “increased,” “was concentrated in,” “coincided with” |
| Conditional association | “was associated with,” “was higher among, after adjustment for…” |
| Diagnostic hypothesis | “is consistent with,” “may be explained by” |
| Credible causal design | “increased,” “reduced,” “caused,” with population and assumptions stated |

Avoid laundering uncertainty through verbs. “Drove,” “led to,” and “resulted in” are causal claims.

---

# 7. Worked case: NovaCart renewal decline

NovaCart is a subscription commerce platform. Renewal fell from 74% to 68% in one quarter. During the same period:

- monthly fees increased for some customers,
- average support wait time rose,
- a mobile release produced more crashes,
- the mix of customers shifted toward a lower-priced plan,
- competitors launched aggressive promotions.

## Step 1: descriptive

Define the renewal denominator as subscriptions eligible to renew, not all customer records. Report renewal by eligibility month, plan, tenure, acquisition channel, platform, geography, and price-change exposure.

Finding: most of the aggregate decline comes from newer customers on the Basic plan. Existing Premium customers are stable.

## Step 2: diagnostic

Examine the renewal funnel, customer complaints, crash exposure, support waits, competitor mentions, and price-change timing. Interview a sample of renewed and non-renewed customers.

Finding: non-renewal is associated with crashes, long support waits, and price increases. These factors overlap.

## Step 3: predictive

Estimate which currently eligible customers are at high non-renewal risk and test whether the model beats simple plan-and-tenure rules.

Finding: model discrimination is useful, but risk is concentrated among customers already known to have unresolved incidents.

## Step 4: causal

Randomly assign eligible high-risk customers to normal service or a proactive service-recovery intervention. Measure renewal, margin, complaints, and downstream service load.

Finding: service recovery raises renewal by 3 percentage points for customers with verified technical incidents but produces no detectable benefit for customers without an incident.

## Step 5: prescriptive

Allocate limited support capacity to verified-incident customers with positive expected retained margin. Do not use the churn score alone to determine eligibility.

## Lesson

Each type of analytics contributes something different. The predictive model identifies risk; the experiment identifies who benefits from action; the prescription combines effects, economics, capacity, and policy.

---

# Project Artifact 1: Business Question Map

## Purpose

The Business Question Map prevents a broad concern from becoming a vague request for “insights” or an AI-generated answer. It shows how a real business decision branches into descriptive, diagnostic, predictive, prescriptive, and causal questions—and which questions must be answered first.

## Build from a realistic scenario

Use an actual decision or the NovaCart renewal case. Provide the participant with a short evidence pack containing at least:

- a six- to twelve-period trend,
- two or more segment breakdowns,
- metric definitions and denominators,
- at least one operational change,
- at least one plausible competing explanation,
- a decision deadline and constraint.

The evidence should be sufficient for analysis but incomplete enough to expose uncertainty.

## Business Question Map template

### A. Decision anchor

**Business concern or opportunity:**  
**Decision to be made:**  
**Decision owner:**  
**Decision deadline/frequency:**  
**Available options:**  
**Desired outcome:**  
**Constraints and guardrails:**

### B. Evidence observed before AI

| Observation from the data | Calculation or source | What it may mean | What it does not establish |
|---|---|---|---|
| | | | |

### C. Question branches

| Analytics type | Business question | Analytical question | Required comparison/data | Decision use |
|---|---|---|---|---|
| Descriptive | What happened? | | | |
| Diagnostic | What may explain it? | | | |
| Predictive | What is likely next? | | | |
| Prescriptive | What action best meets the objective? | | | |
| Causal | What would the proposed action change? | | | |

Not every project requires all five branches. Mark nonessential branches and explain why they are unnecessary.

### D. Assumptions and uncertainty

| Assumption or unknown | Why it matters | How it could be checked | Priority |
|---|---|---|---|
| | | | |

### E. Selected analytical request

> To inform **[decision]** by **[owner]**, analyze **[population/entity]** during **[time]**. Measure **[outcome]**, compare **[groups/baseline/counterfactual]**, and use **[analytics type]** to determine **[answer needed]**. Account for **[constraints and validity risks]**. Deliver **[output]** by **[deadline]**.

### F. Analyze–Challenge–Verify trail

**My initial interpretation before AI:**  
**AI challenge requested:**  
**Suggestions verified against data/sources:**  
**Suggestions rejected and why:**  
**Changes made to the map:**  
**Final rationale owned by the participant:**

## Completion standard

The map is complete when another analyst can identify the decision, distinguish observed facts from hypotheses, understand why the analytics type fits, and see what result would change action. A polished AI-generated question without an independent evidence table and reasoning trail is incomplete.

---

# 8. Practice activities

## Activity A: name the analytics type

Classify each request:

1. Estimate next month's call volume by hour.
2. Determine which product categories contributed most to the margin decline.
3. Estimate whether free shipping increases average contribution margin.
4. Choose warehouse-to-order assignments subject to inventory and delivery constraints.
5. Summarize complaint rates by supplier and month.

Suggested answers: predictive; diagnostic; causal; prescriptive; descriptive.

## Activity B: rewrite weak requests

Rewrite each statement as an analytical request:

- “Analyze our customers.”
- “Prove the campaign worked.”
- “Build a churn AI.”
- “Tell us why sales are down.”

Require each rewritten request to specify the decision, population, outcome, time window, comparison, method, and deliverable.

Complete the first draft without AI. Then ask AI only to identify ambiguities or missing assumptions. Accept no proposed rewrite until it has been checked against the original scenario.

## Activity C: correlation challenge

For each observed relationship, generate at least:

- one plausible causal mechanism,
- one confounder,
- one reverse-causality explanation,
- one measurement or selection explanation,
- one design that could distinguish them.

Relationships:

1. Employees who use an AI assistant complete more work.
2. Stores with more staff have higher revenue.
3. Customers receiving discounts churn more often.
4. Products with more reviews sell more units.

---

# 9. Knowledge check

## Questions

1. A risk score accurately predicts late payment. Does that establish that denying high-risk applications will reduce losses?
2. What is the difference between random sampling and random assignment?
3. When is descriptive analytics sufficient?
4. Why is a before–after comparison weak evidence of impact?
5. What makes an analytical request decision-useful?
6. Name four non-causal explanations for a correlation.
7. Why might prescriptive analytics require causal estimates?
8. What is the counterfactual in an experiment?

## Suggested answers

1. No. Prediction estimates who is likely to pay late under observed conditions; it does not establish the effect or broader consequences of denial.
2. Random sampling supports population representation; random assignment supports group comparability for causal inference.
3. When an accurate current-state measure is enough to trigger an agreed decision rule or provide required accountability.
4. Other conditions, trends, composition, or measurement may have changed at the same time.
5. It identifies the decision, owner, population, outcome, time, comparison, analytical approach, constraints, and output.
6. Confounding, reverse causality, selection bias, and measurement/aggregation artifacts.
7. A recommendation often depends on how actions change outcomes, not merely who is likely to experience an outcome.
8. The outcome the treated units would have experienced without the treatment, approximated by a credible comparison group.

---

# 10. Assessment rubric: analytical question specification

Score each dimension from 0 to 2.

| Dimension | 0 | 1 | 2 |
|---|---|---|---|
| Decision connection | No decision stated | Decision implied | Decision and owner explicit |
| Population and entity | Undefined | Partly defined | Unit, eligibility, and exclusions clear |
| Outcome | Vague | Measure named | Formula, event, and window defined |
| Comparison | None | Informal baseline | Defensible comparison/counterfactual |
| Analytics type | Mismatched/absent | Plausible | Correct and justified |
| Time | Missing | One window stated | observation, outcome, and decision timing clear |
| Limitations | Ignored | General caution | Specific assumptions and risks stated |
| Actionability | No action link | Result may inform action | Result-to-action rules are explicit |

Interpretation:

- **13–16:** decision-ready analytical request
- **9–12:** usable after targeted refinement
- **0–8:** likely to produce misaligned analysis

Regardless of score, the Business Question Map is incomplete if the participant did not record observations and an initial interpretation before AI use, or cannot explain why AI suggestions were accepted or rejected.

---

# 11. Facilitator guide

## Suggested 120-minute agenda

| Time | Activity |
|---|---|
| 0–10 min | Opening case and decision-first principle |
| 10–40 min | Five analytics types with examples |
| 40–55 min | Observational versus experimental data |
| 55–75 min | Correlation and causal traps |
| 75–100 min | Business Question Map workshop—independent first draft |
| 100–115 min | NovaCart case discussion |
| 115–120 min | Commitments and close |

## Common misconceptions and responses

**“Diagnostic analytics tells us the cause.”**  
It generates and tests explanations, but a diagnostic association does not automatically identify the effect of changing a factor.

**“A large dataset solves confounding.”**  
More observations reduce some forms of sampling uncertainty. They do not eliminate systematic bias or missing variables.

**“Machine learning is predictive, so it is objective.”**  
Predictions reflect the target, data-generating process, labels, exclusions, and loss function chosen by people.

**“If an experiment is impossible, causality is unknowable.”**  
Credible quasi-experimental methods can support causal inference, but their assumptions must be explicit and tested.

**“Prescriptive is the most advanced and therefore best.”**  
A prescription is only as good as its objective, constraints, causal inputs, and operational feasibility.

---

# 12. Executive job aid

Before approving an analysis, complete this one-minute check:

1. **Decision:** What choice will change?
2. **Claim:** Describe, explain, predict, recommend, or estimate impact?
3. **Entity:** What does one observation represent?
4. **Outcome:** Exactly what is measured?
5. **Comparison:** Against what baseline or counterfactual?
6. **Timing:** Are all windows aligned?
7. **Evidence:** Observational or experimental?
8. **Alternative explanations:** What else could create the pattern?
9. **Uncertainty:** What is not known?
10. **Action:** What happens under each possible result?

---

# 13. Glossary

**Analytical question:** A precise, answerable formulation of an information need tied to a decision.

**Confounder:** A pre-existing factor related to both an exposure and an outcome that can create or distort an association.

**Correlation:** Statistical co-variation between variables; it does not by itself establish cause.

**Counterfactual:** The outcome that would have occurred under an alternative action or condition.

**Diagnostic analytics:** Analysis aimed at understanding contributors or plausible explanations for an observed outcome.

**Experimental data:** Data generated through deliberate variation of an intervention according to a study design.

**Observational data:** Data in which intervention or exposure assignment is not controlled by the analyst.

**Prescriptive analytics:** Analysis that recommends action given objectives, constraints, and evidence.

**Predictive analytics:** Analysis that estimates an unknown or future outcome.

**Selection bias:** Distortion caused by how observations enter, remain in, or are assigned within the data.

---

# 14. Reference notes and further reading

- World Bank and Inter-American Development Bank, [*Impact Evaluation in Practice, Second Edition*](https://www.worldbank.org/en/programs/sief-trust-fund/publication/impact-evaluation-in-practice). Accessible treatment of counterfactuals, randomization, and quasi-experimental methods.
- NIST/SEMATECH, [Engineering Statistics Handbook](https://www.nist.gov/programs-projects/nistsematech-engineering-statistics-handbook). Practical statistical and experimental-design reference.
- NIST/SEMATECH, [What Is Experimental Design?](https://itl.nist.gov/div898/handbook/pri/section1/pri11.htm). Concise statement of objectives, factors, and planned experimental design.
- World Bank DIME Wiki, [Randomized Controlled Trials](https://dimewiki.worldbank.org/Randomized_Control_Trials). Implementation-oriented introduction to treatment and control assignment.
- U.S. Government Accountability Office, [Evidence-Based Policymaking](https://www.gao.gov/products/gao-23-105460). Practices for planning, assessing, and using evidence.

---

# Closing message

Good data thinking is not the ability to apply the most sophisticated method. It is the ability to state the decision, ask the right analytical question, choose evidence that can support the required claim, and stop the conclusion from outrunning the design.

<a id="module-4"></a>

# Module 4: Data Structure Literacy

## Module purpose

Data structure literacy is the ability to understand what a row represents, how business objects relate, which time and population definitions apply, and what aggregation does to meaning. Without it, leaders can be misled by an analysis that looks polished but combines incompatible units, duplicates records, changes denominators, or hides important variation.

This module uses a simple commerce model—customers, orders, products, and transactions—to teach a durable way to inspect any business dataset.

The central principle is:

> Before interpreting a number, know its entity, grain, time window, population, relationship path, and aggregation rule.

---

## Intended audience

- Leaders and managers who review dashboards and analysis
- Business analysts, product managers, and operations teams
- Data stewards, engineers, and reporting teams
- Anyone responsible for defining or approving a dataset

## Suggested duration

120 minutes, including a data-model exercise and misleading-analysis clinic.

## Learning method: inspect the records before asking AI

Use realistic extracts from customer, order, order-line, product, payment, and refund tables. Before any AI use, participants must inspect sample rows, identify likely keys, count duplicates, state the grain, and sketch relationships by hand or with a basic diagramming tool.

AI may later challenge the proposed structure by suggesting missing entities, risky joins, or alternative grains. Participants must verify those suggestions against actual fields, row samples, business rules, and source-system owners. AI must not invent schemas, keys, or relationship rules that are absent from the evidence.

## Learning outcomes

By the end of this module, participants will be able to:

1. Identify entities, attributes, events, measures, and keys.
2. State the grain of a table and an analysis.
3. Map one-to-one, one-to-many, and many-to-many relationships.
4. Distinguish customers, orders, order lines, products, payments, and transactions.
5. Define compatible observation and outcome time windows.
6. Detect join duplication, aggregation masking, inconsistent denominators, and apples-to-oranges comparisons.
7. Design an analysis-ready dataset whose structure matches the analytical question.
8. Document dataset scope, lineage, exclusions, and quality limitations.
9. Produce Project Artifact 2: a Data Structure Diagram supported by a dataset contract.

## Evidence base and framework alignment

This module uses standard relational and dimensional modeling concepts. Microsoft's [star-schema guidance](https://learn.microsoft.com/en-us/power-bi/guidance/star-schema) distinguishes dimension tables that describe business entities from fact tables that record events or observations, and stresses consistent fact-table grain. IBM's [entity-relationship overview](https://www.ibm.com/think/topics/entity-relationship-diagram) defines entities, attributes, keys, and relationship cardinality. For quality, the Office for National Statistics defines statistical quality as fitness for purpose across relevance, accuracy, timeliness, accessibility, and coherence/comparability in its [quality framework](https://www.ons.gov.uk/methodology/methodologytopicsandstatisticalconcepts/qualityinofficialstatistics/qualitydefined).

---

# 1. The six questions behind every number

Before trusting an analysis, ask:

1. **Entity:** What kind of thing is being described?
2. **Grain:** What does one row or observation represent?
3. **Time:** Which event date and window are used?
4. **Population:** Who or what is included in the denominator?
5. **Relationship:** How were tables linked, and can the link duplicate or omit records?
6. **Aggregation:** How were lower-level observations combined?

Consider “average customer revenue is $120.” This is uninterpretable until we know:

- whether “customer” means account, person, household, or subscriber,
- whether the time window is a month, quarter, or lifetime,
- whether refunds and tax are included,
- whether customers with no orders are included,
- whether the average is calculated from customer totals or order rows,
- whether currency and geography are comparable.

Structure is meaning.

---

# 2. Entities, attributes, events, and measures

## Entity

An entity is a recognizable business object or concept about which data are stored.

Examples:

- Customer
- Account
- Product
- Supplier
- Store
- Employee
- Campaign
- Contract

An entity is usually noun-like and persists over time.

## Attribute

An attribute describes an entity.

For a product, attributes might include:

- product ID,
- name,
- brand,
- category,
- standard cost,
- launch date,
- active status.

Attributes can change. A customer's region today may differ from the region at the time of an earlier order. This creates a time-sensitive modeling choice.

## Event

An event is something that happens at a point or interval in time.

Examples:

- order placed,
- product viewed,
- payment authorized,
- item shipped,
- support case opened,
- subscription renewed.

Event tables usually grow as events occur.

## Measure

A measure is a quantity attached to an entity or event.

Examples:

- item quantity,
- sales amount,
- discount,
- delivery duration,
- inventory balance,
- customer lifetime value estimate.

Measures differ in how they can be aggregated. Revenue can often be summed across orders; a percentage usually cannot be safely averaged without its numerator and denominator.

## Keys

- A **primary key** uniquely identifies a record within a table.
- A **foreign key** links a record to another entity or event.
- A **business key** comes from the operating domain, such as an invoice number.
- A **surrogate key** is generated for modeling purposes and can help preserve historical versions.

If a table has no stable key, analysts cannot reliably deduplicate, join, or trace records.

---

# 3. Grain: what one row represents

Grain, or granularity, is the level of detail represented by one row.

Examples:

- one row per customer,
- one row per order,
- one row per product per order,
- one row per payment attempt,
- one row per store per day,
- one row per product category per month.

## The grain statement

Every analytical table should have a one-sentence grain statement:

> One row represents **[one unit]** for **[one time level or event]**, uniquely identified by **[key fields]**.

Example:

> One row represents one product line within one submitted order, uniquely identified by `order_id + line_number`.

## Why grain errors are dangerous

Suppose an order contains three products. Joining the one-row-per-order table to the one-row-per-order-line table creates three rows for that order. If analysts sum order-level revenue after the join, they count the order three times.

This is not a minor technical issue. It can change strategic conclusions.

## Mixed grain

A table has mixed grain when different rows represent different units or time levels.

Examples:

- some rows are individual transactions and others are daily totals,
- budget rows are monthly while actual rows are daily,
- some customer rows are people and others are households,
- a “sales” table mixes orders, refunds, and inventory snapshots without an event type.

Mixed grain should be separated or explicitly modeled. Otherwise, aggregation becomes ambiguous.

---

# 4. Relationships and cardinality

Cardinality describes how records in one entity relate to records in another.

## One-to-one

One record in A relates to at most one record in B.

Example: one order has one current delivery address record in a simplified model.

## One-to-many

One record in A can relate to many records in B.

Examples:

- one customer can place many orders,
- one order can contain many order lines,
- one product can appear in many order lines.

## Many-to-many

Many records in A can relate to many records in B.

Example: orders contain many products and products appear in many orders. The `OrderLine` entity resolves this relationship.

## Relationship map for commerce data

```text
Customer 1 ───< Order 1 ───< OrderLine >─── 1 Product
                     │
                     ├────< PaymentAttempt
                     ├────< Shipment
                     └────< Refund
```

The map clarifies that:

- customer counts should not be obtained by counting order rows,
- order counts should not be obtained by counting order-line rows,
- payments and refunds are financial events, not orders,
- one order may have multiple attempts, shipments, or refunds.

## Join fan-out

Fan-out occurs when joining multiple one-to-many tables multiplies records.

An order with three lines and two payment attempts produces six joined rows if both child tables are joined directly at their raw grain. Summing line revenue or payment amount after that join will overcount.

Safer approaches include:

- aggregate each child table to order grain before joining,
- compute measures in separate fact tables,
- use distinct keys with care,
- validate row counts and totals before and after each join.

## The join audit

For every join, record:

| Field | Example |
|---|---|
| Left grain | one row per order |
| Right grain | one row per payment attempt |
| Expected cardinality | one-to-many |
| Join key | `order_id` |
| Unmatched left records | orders without payment attempts |
| Unmatched right records | orphan attempts |
| Row-count change | 10,000 to 12,400 |
| Measure reconciliation | order value unchanged after right aggregation |

---

# 5. Customers, orders, products, and transactions

These words sound obvious but often hide incompatible definitions.

## Customer

Possible meanings include:

- registered account,
- unique person,
- household,
- organization,
- purchaser within a period,
- active subscriber,
- billing relationship.

Questions to resolve:

- Can one person hold multiple accounts?
- Can one account represent many users?
- Are guests treated as customers?
- When does a prospect become a customer?
- When does a customer become inactive?
- Can identifiers be merged or split?

## Order

An order is a commercial intent or commitment, not necessarily revenue or cash.

Important attributes include:

- order creation time,
- submission time,
- status,
- currency,
- subtotal, tax, shipping, and discount,
- customer or guest identifier,
- channel,
- cancellation status.

An order can be placed, authorized, fulfilled, partially fulfilled, cancelled, returned, or refunded. “Order count” must specify which states are included.

## Product

A product model may distinguish:

- product family,
- product,
- variant or SKU,
- bundle,
- service plan,
- inventory item.

Historical analysis must decide whether to use the category at transaction time or the product's current category. Using current attributes can rewrite history.

## Transaction

“Transaction” may mean:

- order,
- order line,
- payment attempt,
- settled payment,
- ledger entry,
- refund,
- point-of-sale receipt.

Never accept “transaction data” without an event definition.

## A minimum commerce model

| Table | Grain | Primary key | Important foreign keys | Example measures |
|---|---|---|---|---|
| Customer | one customer version | `customer_key` | — | none or modeled scores |
| Order | one order | `order_id` | `customer_key` | subtotal, tax, discount |
| OrderLine | one line in one order | `order_id + line_no` | `product_key` | quantity, line amount |
| Product | one product version | `product_key` | category key | cost, list price |
| PaymentAttempt | one payment attempt | `payment_attempt_id` | `order_id` | attempted and settled amount |
| Refund | one refund event | `refund_id` | `order_id`, possibly line | refund amount |

---

# 6. Time windows

Time is not a filter added at the end. It is part of the analytical design.

## Common time concepts

- **Event time:** when the business event occurred.
- **Processing time:** when the system recorded or processed it.
- **Snapshot date:** the state of an entity at a particular time.
- **Observation window:** period from which predictors or exposures are measured.
- **Outcome window:** period in which the result is measured.
- **Eligibility date:** when a unit enters the analysis population.
- **Reporting period:** period assigned for governance or accounting purposes.

## Leakage

Data leakage occurs when information from after the prediction or decision point is used as if it were available beforehand.

Example: predicting cancellation at the start of a month using a support case that was opened after the cancellation request.

Leakage produces deceptively strong models and unusable decisions.

## Cohorts versus calendar periods

- A **calendar-period view** groups events occurring in the same period.
- A **cohort view** follows units that entered at the same starting point.

For customer retention, a January calendar report may mix customers at many tenure levels. A January acquisition cohort holds the starting context constant and follows comparable customers through time.

## Partial periods

Comparing a complete month with the first 18 days of the current month is an apples-to-oranges comparison unless adjusted. The same issue arises when newer cohorts have had less time to mature.

## Time-window specification

Document:

1. timezone,
2. event timestamp used,
3. window boundaries and inclusion rules,
4. late-arriving data policy,
5. cohort entry rule,
6. maturation or follow-up requirement,
7. seasonality or business-calendar adjustments.

---

# 7. Aggregation and what it can hide

Aggregation summarizes lower-grain data. It is necessary, but every summary removes information.

## Aggregation masking

An aggregate can hide:

- subgroup reversals,
- distribution tails,
- changes in mix,
- unequal effects,
- operational bottlenecks,
- small high-risk populations.

Example:

| Segment | Prior conversion | Current conversion | Current volume mix |
|---|---:|---:|---:|
| Direct | 12% | 11% | 20% |
| Partner | 4% | 3% | 80% |

If the prior period had an even higher share of Partner traffic, total conversion might rise even while conversion falls in both segments. The aggregate tells the truth about the total and misleads about underlying performance if interpreted without the mix.

## Average of averages

Suppose Store A has 10 responses averaging 90 and Store B has 1,000 responses averaging 70. The unweighted average of store averages is 80. The respondent-weighted average is approximately 70.2. Neither is universally correct; they answer different questions.

- Equal store weighting answers: what is the average store's result?
- Response weighting answers: what is the average response result?

The weighting rule must match the decision.

## Additive, semi-additive, and non-additive measures

- **Additive:** can be summed across relevant dimensions, such as line revenue.
- **Semi-additive:** can be summed across some dimensions but not others, such as end-of-day inventory across products but not across days.
- **Non-additive:** should not normally be summed, such as percentages, ratios, and many scores.

For a rate, aggregate the numerator and denominator before dividing. Do not simply average rates unless equal weighting is intended.

---

# 8. Inconsistent denominators

A denominator defines the population at risk or eligible for the measured event.

Examples:

- conversion rate = purchasers / eligible visitors,
- return rate = returned items / delivered items,
- defect rate = defective units / inspected units,
- renewal rate = renewed contracts / contracts eligible to renew.

## Denominator drift

A metric can change because the denominator changes, even if underlying behavior does not.

Examples:

- excluding anonymous visitors from one channel but not another,
- counting all registered users before a data migration and active users after it,
- comparing refunds to orders in one period and to delivered orders in another,
- including new stores that have not completed the measurement window.

## The denominator checklist

For every rate, ask:

1. What event places a unit in the denominator?
2. When does eligibility begin and end?
3. Can a unit appear more than once?
4. Are missing outcomes retained, excluded, or treated as failures?
5. Do numerator and denominator refer to the same entity and time window?
6. Is the definition stable across groups and periods?

## Report counts with rates

A 50% rate may mean 1 of 2 or 50,000 of 100,000. Always provide the numerator and denominator when material.

---

# 9. Apples-to-oranges comparisons

A comparison is invalid or misleading when the compared values differ in material ways beyond the factor being discussed.

## Common incompatibilities

- different entities: orders versus customers,
- different populations: all users versus active subscribers,
- different windows: monthly versus quarterly,
- different maturity: 30-day outcomes for one cohort versus 7-day outcomes for another,
- different geography or currency,
- nominal versus inflation-adjusted money,
- actuals versus targets at different grain,
- gross versus net revenue,
- event time versus processing time,
- current product category versus historical category,
- different data-collection methods.

## Comparability contract

Before comparing A with B, confirm:

| Dimension | A | B | Compatible? |
|---|---|---|---|
| Entity/grain | | | |
| Inclusion/exclusion | | | |
| Time window/maturity | | | |
| Measure formula | | | |
| Currency/unit | | | |
| Source/system | | | |
| Missing-data treatment | | | |
| Adjustment/weighting | | | |

If values are not comparable, either standardize them or explicitly limit the claim.

---

# 10. Designing a proper analytical dataset

## Step 1: begin with the analytical unit

Ask what one row must represent to answer the question.

Question: “Which customers are likely to renew next month?”  
Required grain: one row per customer-subscription at a defined prediction date.

Question: “Which product categories drive returns?”  
Required grain: often one row per delivered order line, with return outcome linked within a defined window.

## Step 2: define eligibility

Specify inclusion and exclusion before examining outcomes.

Example:

> Include paid subscriptions active at 00:00 local time 30 days before renewal eligibility. Exclude employee, test, fraudulent, and legally suspended accounts.

## Step 3: define labels and measures

Write formulas in plain language and code-like notation.

```text
renewed_30d = 1 if an eligible subscription records a successful renewal
within 30 days of renewal_due_at; otherwise 0 after the full window matures.
```

## Step 4: create an as-of rule

Every feature must have been available at the decision time.

```text
feature_cutoff_at <= prediction_at
```

## Step 5: align grains before joining

Aggregate lower-level tables to the analytical unit:

- order lines → customer-period product mix,
- support events → customer-period counts and recency,
- payment attempts → subscription-level failure history.

## Step 6: preserve numerator and denominator

Store component counts alongside derived rates so they can be recomputed correctly.

## Step 7: document provenance and quality

Record:

- source systems,
- extraction timestamp,
- transformation logic,
- identifiers and matching rules,
- exclusions,
- late-arriving data,
- coverage gaps,
- known changes in definitions or systems.

## Step 8: validate

Minimum checks:

- key uniqueness,
- relationship cardinality,
- row counts before and after joins,
- unmatched records,
- duplicate rates,
- plausible ranges,
- missingness by group and time,
- reconciliation to trusted totals,
- consistency of grain within the table,
- leakage test.

---

# 11. Worked case: misleading product profitability

A dashboard reports that Product Alpha generated $2.4 million in revenue and $1.1 million in gross profit, making it the company's most profitable product.

## Structural audit

The dashboard joins:

- one row per order,
- one row per order line,
- one row per refund event,
- current product master attributes.

Problems discovered:

1. Orders with multiple lines duplicate order-level shipping revenue.
2. Lines with multiple partial refunds duplicate original line revenue.
3. Products moved into the Alpha category last month, and the current category is applied to historical sales.
4. Costs are monthly averages while revenue is transaction-time actual.
5. The dashboard excludes cancelled orders from revenue but includes their payment-processing fees in cost.

## Corrected dataset

- Grain: one delivered order line.
- Revenue: net item revenue allocated at line level.
- Refunds: aggregated to order-line level before joining.
- Product category: category effective on the order date.
- Cost: unit cost effective at fulfillment time.
- Payment fees: allocated only to settled orders, with explicit rules.

## Result

After correction, Alpha remains the largest by revenue but falls to fourth in contribution margin. The original dashboard was arithmetically correct for the malformed joined table and materially wrong for the business question.

---

# 12. Misleading-analysis clinic

For each statement, identify the structural risk.

1. “Average order value rose 15%,” but guest checkout was removed from the new system.
2. “The new stores outperform mature stores,” measured by revenue per open day during launch promotions.
3. “Returns are down,” using refunds processed this month divided by orders placed this month.
4. “Customer engagement doubled,” after changing from one row per session to one row per event.
5. “Product B has a higher defect rate,” but B undergoes 100% inspection and A is sampled.

Suggested diagnoses:

1. Population and denominator change.
2. Lifecycle and promotional-context mismatch.
3. Numerator and denominator refer to different cohorts and time lags.
4. Grain changed.
5. Detection and denominator differences.

---

# Project Artifact 2: Data Structure Diagram

## Purpose

The Data Structure Diagram turns the Business Question Map into a visible model of the data needed to answer it. It exposes entity confusion, mismatched grain, join fan-out, missing time logic, and unsupported denominators before analysis begins.

## Analyze the data first

Before drawing the diagram, participants must independently complete a source inspection table.

| Source/table | Five sample rows inspected? | Candidate key | Apparent grain | Row count | Duplicate/key issue | Relevant time field |
|---|---|---|---|---:|---|---|
| | | | | | | |

Do not ask AI to infer the schema before this inspection. Database names can be misleading: a table called `transactions` may contain payment attempts, journal lines, or daily summaries.

## Required diagram notation

Every diagram must show:

- entities and event tables,
- primary and foreign keys,
- one-to-one, one-to-many, or many-to-many cardinality,
- the grain of every event/fact table,
- the timestamp or effective-date field used,
- bridge tables that resolve many-to-many relationships,
- optional relationships and unmatched-record risk,
- the intended analytical unit highlighted,
- the aggregation path from source grain to analytical grain.

## Example

```text
[Customer]
PK customer_key
grain: one customer version
effective_from / effective_to
      1
      │ places
      ▼ many
[Order] ───────────────< [PaymentAttempt]
PK order_id               PK payment_attempt_id
FK customer_key           FK order_id
grain: one order           grain: one attempt
ordered_at                 attempted_at
      1
      │ contains
      ▼ many
[OrderLine] >──────────── 1 [Product]
PK order_id + line_no       PK product_key
FK product_key              grain: one product version
grain: one order line       effective_from / effective_to
```

## Relationship inventory

| From | To | Cardinality | Join key | Optional? | Fan-out risk | Business rule/evidence |
|---|---|---|---|---|---|---|
| | | | | | | |

## Analytical path

**Business question inherited from Artifact 1:**  
**Target analytical unit:**  
**Source-to-target aggregation steps:**  
**Numerator source and grain:**  
**Denominator source and grain:**  
**Observation and outcome windows:**  
**As-of rule:**  
**Known exclusions or coverage gaps:**

## Analyze–Challenge–Verify trail

**Structure inferred independently from records and documentation:**  
**AI challenge requested:**  
**Suggested entities/relationships verified:**  
**Suggestions rejected because evidence did not support them:**  
**Diagram changes and rationale:**

## Completion standard

The diagram is complete when a reviewer can trace each KPI input back to a source, predict how every join changes row counts, identify the analytical grain, and locate the time and denominator rules. An attractive diagram without evidence from source records is incomplete.

---

# 13. Participant activity: build the dataset contract

Use the Business Question Map to produce the Data Structure Diagram first. Then complete the supporting contract:

## Analytical dataset contract

**Business question:**  
**Decision:**  
**Analytical unit / grain:**  
**Primary key:**  
**Population and eligibility:**  
**Observation date/window:**  
**Outcome and outcome window:**  
**Entities required:**  
**Relationships/cardinality:**  
**Measures and aggregation rules:**  
**Denominators:**  
**Exclusions:**  
**As-of/leakage rule:**  
**Source systems:**  
**Known quality risks:**  
**Validation checks:**  
**Owner and refresh schedule:**

Peer reviewers should try to break the proposed structure by finding a duplicate path, mismatched time window, unstable denominator, or hidden subgroup.

Only after peer review may participants use AI to perform a second adversarial review. Every AI-raised issue must be demonstrated with a plausible row or relationship example before it is added to the final artifact.

---

# 14. Knowledge check

## Questions

1. What is data grain?
2. Why can joining Orders to OrderLines overstate order revenue?
3. What is the difference between a customer and a transaction?
4. Why should rates be stored with numerator and denominator?
5. What is aggregation masking?
6. Give an example of an apples-to-oranges comparison.
7. What is data leakage?
8. Why might current product attributes corrupt historical reporting?

## Suggested answers

1. The unit represented by one row or observation.
2. One order may produce multiple line rows, repeating order-level fields.
3. A customer is an entity; a transaction is an event. One customer may have many transactions.
4. To recompute weighted aggregates, expose scale, and verify denominator consistency.
5. Loss of important subgroup or distribution information when data are summarized.
6. For example, comparing a complete quarter with an incomplete month without adjustment.
7. Using information unavailable at the intended prediction or decision time.
8. Because reclassification can be applied retrospectively, changing the apparent historical category mix.

---

# 15. Assessment rubric: analysis-ready dataset

Score 0–2 per dimension.

| Dimension | 0 | 1 | 2 |
|---|---|---|---|
| Grain | absent/mixed | implied | explicit and consistent |
| Keys | unreliable | partly specified | unique and validated |
| Population | unclear | broad rule | eligibility/exclusions precise |
| Time | misaligned | partial | observation/outcome/as-of aligned |
| Relationships | unexamined | mapped | cardinality and fan-out controlled |
| Measures | ambiguous | named | formulas and aggregation behavior defined |
| Denominators | hidden | partly visible | explicit, stable, and reconcilable |
| Quality | unchecked | basic checks | documented lineage and validation suite |

Interpretation:

- **13–16:** ready for controlled analytical use
- **9–12:** requires targeted remediation
- **0–8:** high risk of misleading output

Regardless of score, the Data Structure Diagram is incomplete if the participant did not inspect source records before AI use or cannot show evidence for the proposed keys, grain, and relationships.

---

# 16. Facilitator guide

## Suggested 120-minute agenda

| Time | Activity |
|---|---|
| 0–15 min | Six questions behind every number |
| 15–40 min | Entities, grain, and relationships |
| 40–60 min | Commerce model walkthrough |
| 60–80 min | Time windows and denominators |
| 80–100 min | Aggregation and comparison traps |
| 100–115 min | Data Structure Diagram and dataset-contract exercise |
| 115–120 min | Close and commitments |

## Common misconceptions

**“One row is one record, so the grain is obvious.”**  
Records are system artifacts. Their business meaning must still be stated.

**“Distinct count fixes duplication.”**  
It may fix one count while leaving sums, attribution, and other measures wrong.

**“More granular data are always better.”**  
Fine detail is useful only if it can be governed, linked, and aggregated correctly for the question.

**“A dashboard metric is comparable because the label is unchanged.”**  
Definitions, populations, source systems, and time logic can change under a stable label.

---

# 17. Executive job aid: structural integrity check

Before accepting an analysis, ask the presenter to complete these sentences:

- One row represents…
- The population includes… and excludes…
- The numerator is…
- The denominator is…
- The relevant date is…
- Lower-level records were aggregated by…
- These tables relate as…
- The join changes the row count from… to…
- The comparison is valid because definitions match on…
- The result may hide variation across…

If the team cannot answer, interpretation should pause.

---

# 18. Glossary

**Aggregation:** Combining observations into a summary measure.

**Cardinality:** The number relationship between entities, such as one-to-many.

**Denominator:** The eligible or at-risk population used in a rate or ratio.

**Dimension table:** A table describing business entities used to group and filter facts.

**Entity:** A person, object, place, event type, or concept about which data are stored.

**Fact table:** A table containing observations, events, or measurements at a declared grain.

**Fan-out:** Row multiplication caused by joining one record to multiple related records.

**Grain:** The precise unit represented by one row.

**Key:** One or more fields used to identify or link records.

**Snapshot:** The state of an entity at a defined point in time.

---

# 19. Reference notes and further reading

- Microsoft Learn, [Understand Star Schema and the Importance for Power BI](https://learn.microsoft.com/en-us/power-bi/guidance/star-schema). Definitions of fact tables, dimension tables, relationships, and granularity.
- IBM, [What Is an Entity Relationship Diagram?](https://www.ibm.com/think/topics/entity-relationship-diagram). Conceptual overview of entities, attributes, keys, and cardinality.
- Microsoft Learn, [Many-to-Many Relationship Guidance](https://learn.microsoft.com/en-us/power-bi/guidance/relationships-many-to-many). Examples of higher-grain facts and relationship design.
- Office for National Statistics, [Quality Defined](https://www.ons.gov.uk/methodology/methodologytopicsandstatisticalconcepts/qualityinofficialstatistics/qualitydefined). Fitness-for-purpose dimensions including coherence and comparability.

---

# Closing message

Data do not become trustworthy because they are stored in a table or displayed in a dashboard. Trust begins when the organization can say what every row means, how records relate, who belongs in the population, which time applies, and what aggregation has removed from view.

<a id="module-5"></a>

# Module 5: Metrics, Evidence & Decision Specification

## Module purpose

Metrics shape attention, incentives, and behavior. A useful metric does more than move on a dashboard: it represents an outcome or mechanism that matters, is defined consistently, can be influenced responsibly, and is interpreted with appropriate context.

This module teaches participants to design a balanced measurement system, distinguish meaningful indicators from proxies and vanity metrics, communicate evidence honestly, and convert analysis into an auditable **Decision Specification Document (DSD)**.

The central principle is:

> A metric is not the goal, and evidence is not a decision. The organization must specify how evidence will change action.

---

## Intended audience

- Executives, business-unit leaders, and managers
- Strategy, finance, product, operations, and transformation teams
- Analysts and data professionals who define or report metrics
- Governance, risk, and assurance functions

## Suggested duration

150 minutes, including a KPI design lab and DSD workshop.

## Learning method: calculate and judge before AI

Participants work from a realistic operating pack containing raw counts, denominators, targets, subgroup results, and a draft dashboard. They must independently recompute at least one headline rate, identify a misleading or incomplete metric, and propose a balanced KPI set before using AI.

AI may challenge whether measures are gameable, incomplete, or poorly connected to the decision. Participants must verify suggestions against the Data Structure Diagram, formulas, organizational constraints, and actual stakeholder outcomes. AI cannot choose what the organization should value; metric priorities and trade-offs remain human judgments.

## Learning outcomes

By the end of this module, participants will be able to:

1. Distinguish goals, outcomes, outputs, measures, indicators, targets, and thresholds.
2. Design KPIs connected to a decision and value-creation logic.
3. Balance leading and lagging indicators.
4. Identify weak proxies, vanity metrics, and gameable measures.
5. Detect misleading formulas, denominators, comparisons, and visualizations.
6. Express uncertainty, trade-offs, and guardrails alongside headline performance.
7. Build a metric specification that another team can reproduce.
8. Produce a Decision Specification Document that defines the decision before analysis or implementation.
9. Produce Project Artifact 3: a KPI Catalogue.
10. Produce Project Artifact 4: a Decision Specification Document.

## Evidence base and framework alignment

The module aligns with the OECD's guidance that indicators should be relevant, reliable, valid, feasible, and used sparingly, and that proxy indicators require caution; see its discussion of [results frameworks and indicator selection](https://www.oecd.org/en/publications/monitoring-and-evaluation-of-child-and-youth-policies-and-outcomes-in-ireland_2bd86a9d-en/full-report/component-5.html). Statistical quality dimensions follow the Office for National Statistics' [fitness-for-purpose framework](https://www.ons.gov.uk/methodology/methodologytopicsandstatisticalconcepts/qualityinofficialstatistics/qualitydefined). Visualization guidance draws on the ONS [axes and gridlines standard](https://service-manual.ons.gov.uk/data-visualisation/guidance/axes-and-gridlines), including zero baselines for bars, consistent scales for comparisons, and caution with dual axes.

The **DSD is a practical synthesis created for this curriculum**. It is not a recognized external standard. It integrates decision framing, metric specification, evidence requirements, authority, trade-offs, and learning commitments into one document.

---

# 1. From purpose to measure

Organizations frequently confuse six different ideas:

| Concept | Meaning | Example |
|---|---|---|
| **Goal** | Desired direction or state | Improve customer trust |
| **Outcome** | Change experienced by stakeholders or the business | Fewer avoidable service failures |
| **Output** | Product or activity delivered | Proactive service messages sent |
| **Metric** | Quantitative definition | repeat-contact rate within 14 days |
| **Target** | Desired metric value by a time | below 12% by Q4 |
| **Threshold** | Boundary that triggers action | above 18% for two weeks triggers review |

An organization can hit an output target while missing the outcome. Sending more service messages does not guarantee fewer failures or greater trust.

## A value logic chain

Use this sequence:

> Inputs → activities → outputs → intermediate outcomes → final outcomes → impact

Example:

| Level | Service-recovery example |
|---|---|
| Input | trained agents, incident data, budget |
| Activity | identify affected customers and contact them |
| Output | eligible customers contacted within 24 hours |
| Intermediate outcome | issues resolved; repeat contacts fall |
| Final outcome | renewal and satisfaction improve |
| Impact | profitable retention and stronger trust |

Metrics at only one level create blind spots. Output metrics are fast and controllable; outcome metrics reveal whether the work mattered.

---

# 2. What makes a metric useful?

A decision-useful metric should pass nine tests.

## 2.1 Relevant

It represents an outcome, driver, constraint, or risk that matters to the decision.

## 2.2 Valid

It measures the intended concept rather than a convenient substitute.

## 2.3 Reliable

The same method applied under the same conditions produces consistent results.

## 2.4 Sensitive

It changes when meaningful performance changes and is not dominated by noise.

## 2.5 Timely

It is available early enough to influence action.

## 2.6 Comparable

Definitions, populations, periods, and units allow meaningful comparison.

## 2.7 Actionable

Decision owners know what action to consider when the metric changes.

## 2.8 Balanced

It is paired with measures that reveal cost, quality, risk, and unintended effects.

## 2.9 Governable

It has an owner, source, formula, refresh schedule, change control, and audit trail.

No metric is perfect. The task is to make limitations visible and choose a set that supports the decision at reasonable cost.

---

# 3. KPI design

## What is a KPI?

A key performance indicator is a small number of strategically important measures used to judge progress toward an objective and trigger management attention or action.

Not every reported metric is a KPI. A measure becomes “key” because it is tightly linked to a priority decision or outcome.

## KPI design sequence

1. State the objective.
2. Identify the decision owner and recurring decisions.
3. Map the value logic or causal mechanism.
4. Select a small set of outcome, driver, and guardrail metrics.
5. Write full metric specifications.
6. Establish baselines, targets, thresholds, and uncertainty.
7. Define review cadence and action rules.
8. Test for gaming and unintended behavior.
9. Review whether the measures remain useful.

## KPI architecture

A balanced KPI set usually contains:

- **Outcome metric:** Did the intended result occur?
- **Leading/driver metric:** Are controllable conditions moving in the right direction?
- **Quality metric:** Is the work correct and useful?
- **Efficiency metric:** What resources did it consume?
- **Risk/guardrail metric:** What must not deteriorate?
- **Distribution metric:** Who benefits or bears cost?

Example for contact-center improvement:

| Role | Metric |
|---|---|
| Outcome | repeat-contact rate within 14 days |
| Leading | first-response time for priority incidents |
| Quality | independently audited resolution correctness |
| Efficiency | cost per resolved case |
| Guardrail | complaint escalation and employee workload |
| Distribution | resolution rate by language and customer segment |

## Metric tree

A metric tree decomposes a top outcome into contributing terms.

```text
Contribution margin
├── Net revenue
│   ├── active customers
│   ├── purchase frequency
│   └── net revenue per order
└── Variable cost
    ├── product cost
    ├── fulfillment cost
    ├── service cost
    └── returns and credits
```

A tree is not proof of causality. It is a structured accounting or hypothesis map that helps teams locate where movement originates.

---

# 4. Leading and lagging metrics

## Lagging metrics

Lagging metrics reflect outcomes after they occur.

Examples:

- revenue,
- renewal,
- injury rate,
- delivery success,
- operating margin,
- employee turnover.

Strengths:

- close to the result that matters,
- often easier to validate,
- useful for accountability.

Limitations:

- may arrive too late for corrective action,
- may be influenced by many factors,
- can encourage short-term reactions.

## Leading metrics

Leading metrics track activities or conditions expected to influence later outcomes.

Examples:

- unresolved critical incidents,
- preventive-maintenance completion,
- qualified pipeline coverage,
- percentage of high-risk orders reviewed before release.

Strengths:

- earlier signal,
- often more actionable,
- can support prevention.

Limitations:

- relationship to the outcome may be weak or unstable,
- easier to game,
- can turn activity into a false definition of success.

## Leading is a hypothesis

A leading indicator is only useful if evidence supports a relationship with the desired outcome. Continually test:

1. Does movement in the leading metric precede the outcome?
2. Is the relationship stable across time and segments?
3. Does intervention on the driver change the outcome?
4. What other factor could produce both movements?

The UK Health and Safety Executive's process-safety guidance illustrates the need to review leading and lagging indicators together: good leading results with poor lagging outcomes may indicate that the control system itself is ineffective; poor leading results with acceptable lagging outcomes may mean the leading measure is too remote from the critical control.

---

# 5. Proxy and vanity metrics

## Proxy metric

A proxy metric is an indirect measure used when the desired construct is difficult, slow, or costly to measure.

Examples:

- page views as a proxy for interest,
- training completion as a proxy for competence,
- income as a proxy for socioeconomic status,
- response time as a proxy for service quality.

A proxy is not inherently bad. It is a hypothesis that must be governed.

### Proxy validation questions

- What concept is the proxy intended to represent?
- Why can the concept not be measured directly?
- What evidence links proxy and target?
- When does the relationship fail?
- Can people improve the proxy without improving the target?
- How often will the relationship be revalidated?

## Vanity metric

A vanity metric looks impressive but has weak decision value.

Common characteristics:

- grows cumulatively by design,
- lacks a meaningful denominator,
- is not tied to an outcome,
- is presented without a baseline or target,
- cannot guide action,
- is easy to inflate.

Examples:

- total registered users without active-use definition,
- cumulative AI prompts submitted,
- impressions without qualified reach or conversion,
- reports produced without evidence of use,
- hours of training without capability assessment.

## Turn a vanity metric into a useful measure

“One million app downloads” becomes more useful when paired with:

- activated users / valid installs,
- 30-day retained users / activated users,
- successful task completion,
- cost per retained user,
- complaint and uninstall rate.

---

# 6. Misleading metrics

## Goodhart's pressure

When a measure becomes a target, people adapt behavior to improve the measure. This can weaken the metric's relationship with the real objective.

Examples:

- closing support tickets quickly by marking them resolved prematurely,
- maximizing calls per hour at the expense of resolution,
- growing sales through discounts that destroy margin,
- reducing reported incidents by discouraging reporting.

The response is not “never set targets.” It is to pair metrics, audit outcomes, monitor behavior, and revise measures.

## Common metric distortions

### Hidden denominator

Reporting 5,000 conversions without eligible audience or cost.

### Survivorship

Measuring satisfaction only among customers who remained.

### Changing composition

Average order value rises because low-value customers left.

### Time-horizon mismatch

Rewarding immediate sales when returns and defaults appear later.

### Ratio instability

A rate spikes because the denominator shrank, not because the numerator grew.

### Average masking

Mean service time improves while the 95th percentile worsens materially.

### Incomplete costs

Reporting automation savings without integration, oversight, error correction, and change-management cost.

### Target leakage

Defining success using information unavailable when the decision is made.

## Metric adversarial review

For each KPI, ask:

1. How could a well-intentioned employee improve this metric while harming the goal?
2. How could the metric improve because the population changed?
3. What harm might occur outside the metric's time horizon?
4. Which subgroup could be harmed while the average improves?
5. What data-quality failure would falsely improve the metric?

---

# 7. Visualization as evidence communication

A chart is an argument expressed visually. Design choices affect interpretation.

## Choose chart by task

| Task | Usually suitable |
|---|---|
| Compare categories | bar or dot plot |
| Show change over time | line chart |
| Show distribution | histogram, box plot, percentile plot |
| Show relationship | scatter plot |
| Show part-to-whole | stacked bar, sometimes a simple pie for few categories |
| Show process or funnel | staged bars/funnel with explicit denominators |
| Show exact values | table |

## Integrity rules

- Bar axes should start at zero because bar length encodes magnitude.
- Comparable small-multiple charts should share scales.
- Avoid dual axes that imply visual relationships between unlike scales.
- Show units, denominator, time, source, and relevant definitions.
- Label uncertainty when estimates are noisy.
- Use annotations to explain material events or definition changes.
- Do not use 3D effects that distort area or angle.
- Use color purposefully and accessibly.
- Show the data needed to challenge the headline, not just support it.

## Context layer

Every executive chart should answer:

- Compared with what?
- Is the change large enough to matter?
- Is it within normal variation?
- Is the definition stable?
- Is it broad or concentrated?
- What action, if any, follows?

---

# 8. The Metric Specification Card

Every KPI should have a reproducible specification.

## Template

**Metric name:**  
**Business purpose:**  
**Decision supported:**  
**Owner:**  
**Entity and grain:**  
**Population/eligibility:**  
**Numerator:**  
**Denominator:**  
**Formula:**  
**Time basis:**  
**Data source and lineage:**  
**Refresh cadence and latency:**  
**Dimensions for breakdown:**  
**Baseline:**  
**Target and deadline:**  
**Action thresholds:**  
**Guardrails:**  
**Known limitations:**  
**Change-control history:**

## Worked example

**Metric name:** 30-day renewal rate  
**Purpose:** Track whether eligible subscriptions continue after renewal due date.  
**Decision:** Allocate service-recovery capacity and evaluate renewal initiatives.  
**Owner:** VP Customer Operations.  
**Grain:** one subscription-renewal opportunity.  
**Population:** paid subscriptions reaching renewal due date; exclude test, employee, fraud-blocked, and legally suspended accounts.  
**Numerator:** eligible opportunities with successful payment and active status within 30 days after due date.  
**Denominator:** all matured eligible renewal opportunities.  
**Formula:** numerator / denominator.  
**Time:** cohort by renewal due month; report only after 30-day maturation.  
**Breakdowns:** plan, tenure, acquisition channel, region, incident exposure.  
**Guardrails:** contribution margin, complaints, involuntary churn, discount cost.  
**Limitation:** late payment reconciliation can revise the most recent matured cohort.

---

# Project Artifact 3: KPI Catalogue

## Purpose

The KPI Catalogue is the controlled inventory of measures used to understand the decision in the Business Question Map. It connects each metric to the Data Structure Diagram, defines its role, and prevents a dashboard from becoming an ungoverned collection of convenient numbers.

## Analyze the evidence first

Before asking AI for KPI ideas, participants must:

1. calculate the current headline outcome from numerator and denominator,
2. break it down by at least two decision-relevant dimensions,
3. identify one distribution or tail measure hidden by the average,
4. propose one outcome metric and at least two guardrails,
5. state one behavior each proposed KPI could unintentionally encourage.

## Catalogue template

| KPI ID | Name | Role | Decision/outcome linked | Formula | Entity/grain | Population and time | Owner | Cadence | Target/threshold | Breakdowns | Risk/gaming note | Source tables |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| KPI-01 | | Outcome / leading / lagging / quality / efficiency / guardrail / distribution | | | | | | | | | | |

Attach a full Metric Specification Card for every metric designated as “key.” Supporting diagnostic metrics can have a lighter specification but still require formula, owner, and source.

## Required catalogue balance

The final catalogue should contain the smallest set that covers:

- at least one final outcome,
- one or more plausible leading drivers,
- quality and operational efficiency,
- financial or resource consequence,
- a guardrail for material unintended harm,
- distribution across relevant groups or segments.

Do not force a metric into every category if it adds no decision value. Explain intentional omissions.

## Metric relationship map

For each leading metric, document the hypothesized chain:

> **[Leading activity/condition]** is expected to change **[intermediate outcome]**, which should influence **[lagging outcome]**, provided **[assumptions]** hold.

Label the relationship as:

- accounting identity,
- supported causal relationship,
- predictive association,
- working hypothesis,
- unknown.

This label prevents an attractive metric tree from being mistaken for causal proof.

## Analyze–Challenge–Verify trail

**Metrics calculated independently:**  
**Initial KPI set and rationale:**  
**AI challenge requested:**  
**Suggested metrics verified against available data:**  
**Suggestions rejected as vanity, proxy, duplicative, or infeasible:**  
**Final changes and accountable human rationale:**

## Completion standard

The catalogue is complete when each KPI can be reproduced, traced to source entities, connected to a decision, interpreted with a stable denominator, and balanced by relevant risks. A list of AI-suggested KPI names without formulas and data lineage is incomplete.

---

# Project Artifact 4: Decision Specification Document (DSD)

## Why a DSD exists

Analysis often begins before the decision is defined. The result is scope drift, metric debate after results are known, and recommendations that cannot be implemented.

A DSD is written **before major analysis, experimentation, procurement, or deployment**. It creates a shared contract among the decision owner, analysts, operators, and affected functions.

It answers:

> What decision are we preparing to make, what evidence will count, and how will the evidence translate into action?

## DSD principles

1. One primary decision per document.
2. A named accountable owner.
3. Genuine options, including “do nothing” or “delay” when relevant.
4. Metrics defined before results are reviewed.
5. Evidence standards proportionate to consequence.
6. Trade-offs and guardrails stated explicitly.
7. Decision rules guide judgment but do not erase accountability.
8. Assumptions, dissent, and uncertainty are recorded.
9. A monitoring and reversal plan is included.

## Analyze before AI

The decision owner and participant must complete the first version of the decision statement, options, criteria, trade-offs, and provisional evidence standard without AI. AI may then be used to challenge missing options, surface conflicting criteria, or simulate objections from affected stakeholders. The owner must verify every challenge and retain responsibility for values, thresholds, and the final choice.

Add this record to the DSD:

**Initial decision logic written before AI:**  
**AI challenge requested:**  
**Challenges accepted after verification:**  
**Challenges rejected and why:**  
**Final decision-owner rationale:**

---

# 10. DSD full template

## A. Decision identity

**DSD title and version:**  
**Decision statement:**  
**Decision owner:**  
**Decision date/deadline:**  
**Review and approval roles:**  
**Affected stakeholders:**

Write the decision statement as:

> **[Owner]** must decide **[choice]** by **[date/frequency]** to achieve **[outcome]**, within **[constraints]**.

## B. Context and trigger

**What changed or created the need for a decision?**  
**Why now?**  
**What happens if no action is taken?**  
**What previous decisions or commitments constrain this one?**

Separate observed facts from interpretations.

## C. Scope and decision rights

**In scope:**  
**Out of scope:**  
**Authority retained by the owner:**  
**Authority delegated to teams or systems:**  
**Escalation conditions:**

## D. Options

For each option, describe:

- action,
- owner,
- timing,
- cost and capacity,
- reversibility,
- key dependencies,
- major risks.

Include the status quo or minimum-change option unless genuinely infeasible.

## E. Stakeholders and value

**Who benefits?**  
**Who bears cost or risk?**  
**Whose perspective is absent?**  
**What obligations or rights constrain the choice?**

## F. Decision criteria

Rank or weight the criteria used to compare options.

| Criterion | Definition | Priority/weight | Minimum acceptable |
|---|---|---:|---:|
| Outcome | | | |
| Economics | | | |
| Customer/employee impact | | | |
| Risk/compliance | | | |
| Feasibility | | | |
| Strategic fit | | | |

Weights express policy judgments. They should not be chosen by analysts after seeing which option wins.

## G. Metrics and evidence

**Primary outcome metric:**  
**Leading metrics:**  
**Guardrail metrics:**  
**Equity/distribution metrics:**  
**Baseline and benchmark:**  
**Minimum meaningful effect:**  
**Data and analysis required:**  
**Evidence standard:** descriptive, diagnostic, predictive, causal, or prescriptive.  
**Uncertainty to report:**  
**Evidence owner and independent review:**

Attach Metric Specification Cards.

## H. Assumptions and uncertainties

| Assumption | Why it matters | Evidence | Confidence | Test/mitigation |
|---|---|---|---|---|
| | | | | |

Distinguish:

- uncertainty reducible before the decision,
- uncertainty learnable only during implementation,
- uncertainty that must be accepted.

## I. Trade-offs and constraints

Document:

- speed versus accuracy,
- cost versus service,
- short-term versus long-term outcomes,
- average benefit versus distribution,
- automation versus human control,
- growth versus resilience,
- privacy/security versus data access.

**Non-negotiable constraints:**  
**Acceptable residual risk:**  
**Trade-offs reserved for the decision owner:**

## J. Decision rule and judgment

Specify provisional action logic:

> If **[evidence condition]**, choose or advance **[option]**, provided **[guardrails]** remain within **[bounds]**. If results are inconclusive, **[fallback]**. Exceptions require **[authority and documentation]**.

Decision rules improve consistency. They do not replace judgment when assumptions fail.

## K. Implementation and controls

**Action owner:**  
**Resources and dependencies:**  
**Pilot or rollout sequence:**  
**Human oversight:**  
**Quality controls:**  
**Communication and training:**  
**Incident and escalation process:**

## L. Monitoring, learning, and reversal

**Review cadence:**  
**Monitoring owner:**  
**Leading and lagging indicators:**  
**Stop/pause/rollback conditions:**  
**Reversibility plan:**  
**Post-decision review date:**  
**What will be learned and how will it change future decisions?**

## M. Decision record

Complete after the decision:

**Option selected:**  
**Rationale:**  
**Evidence relied upon:**  
**Material dissent:**  
**Conditions attached:**  
**Approvals:**  
**Date:**

---

# 11. Worked DSD: proactive service recovery

## A. Decision

The VP Customer Operations must decide by 15 October whether to scale proactive service recovery from a pilot to all eligible new subscribers for the next two quarters, to improve profitable renewal without increasing complaints, employee overload, or inequitable service.

## B. Options

1. Stop after pilot.
2. Extend the pilot for more evidence.
3. Scale to customers with verified technical incidents.
4. Scale to all model-identified high-risk customers.

## C. Criteria

- incremental 30-day renewal,
- incremental contribution margin after service cost,
- complaint escalation,
- repeat contacts,
- agent workload,
- consistency across language and region,
- implementation capacity.

## D. Evidence

Primary evidence is a randomized pilot. The primary outcome is 30-day renewal among matured eligible subscriptions. Minimum meaningful effect is 1.5 percentage points. Guardrails include no more than a 0.3-point increase in formal complaints and no increase above agreed workload limits.

## E. Result and decision rule

The intervention improves renewal by 3 points for customers with verified incidents and has no detectable effect for customers identified only by a risk model. Contribution margin is positive in the incident subgroup.

Decision: scale Option 3 in stages, continue learning, and do not authorize risk-score-only treatment.

## F. Monitoring

Weekly operational metrics, monthly matured-outcome review, rollback if complaint or workload guardrails breach for two consecutive periods, and formal reassessment after two quarters.

This example shows why a DSD is more than a recommendation memo: it preserves the intended decision, evidence standard, guardrails, and reversal logic.

---

# 12. Participant activities

## Activity A: KPI surgery

Choose a weak KPI such as “active users,” “tickets closed,” “AI usage,” or “sales.” Redesign it by specifying:

- outcome represented,
- entity and population,
- numerator and denominator,
- time window,
- leading or lagging role,
- guardrails,
- decision and action threshold.

Add the redesigned measure to the KPI Catalogue and complete it independently before requesting AI critique.

## Activity B: metric gaming pre-mortem

Assume employees optimize the KPI exactly as written. List five ways the metric could improve while the objective worsens. Add one prevention or detection measure for each.

## Activity C: DSD sprint

In teams, complete Sections A–J of a DSD for one decision:

- expand a product to a new region,
- automate invoice exception handling,
- change a sales incentive,
- outsource customer support,
- introduce an AI-assisted quality process.

Peer reviewers score whether evidence and action logic were specified before results.

AI critique occurs only after peer review. Participants must record which critique points were verified and whether they changed the DSD.

---

# 13. Knowledge check

## Questions

1. What distinguishes a KPI from an ordinary metric?
2. Why should leading and lagging indicators be reviewed together?
3. When is a proxy metric acceptable?
4. Name three characteristics of a vanity metric.
5. Why should a bar chart generally start at zero?
6. What does a guardrail metric do?
7. Why should the DSD be written before analysis is complete?
8. What belongs in a decision rule?

## Suggested answers

1. A KPI is strategically important, tied to an objective and recurring decision, and expected to trigger management action.
2. Leading measures provide early, controllable signals; lagging measures test whether the intended outcome occurred.
3. When the target construct cannot be measured directly, the relationship is supported and monitored, and limitations are explicit.
4. It lacks a meaningful denominator, action link, outcome relationship, or benchmark and may grow cumulatively by design.
5. Bar length encodes value, so a truncated baseline visually distorts relative size.
6. It ensures improvement in one objective does not create unacceptable harm elsewhere.
7. To prevent metrics, thresholds, and evidence standards from being chosen after results are known.
8. Evidence condition, option/action, guardrail conditions, fallback for inconclusive results, and exception authority.

---

# 14. DSD assessment rubric

Score each dimension 0–2.

| Dimension | 0 | 1 | 2 |
|---|---|---|---|
| Decision | vague topic | choice implied | owner, choice, timing clear |
| Options | one favored option | alternatives listed | genuine, comparable options |
| Criteria | absent | general | ranked/weighted and defined |
| Metrics | labels only | partial formulas | reproducible specifications |
| Evidence | unspecified | method named | claim/evidence standard aligned |
| Trade-offs | hidden | acknowledged | explicit and owned |
| Guardrails | absent | general | measurable bounds and owners |
| Action logic | ad hoc | broad direction | conditions, fallback, exceptions |
| Implementation | ignored | high-level | owners, dependencies, controls |
| Learning | no follow-up | review stated | monitoring, stop, reversal, review |

Interpretation:

- **17–20:** decision-ready
- **12–16:** workable after targeted revision
- **0–11:** likely to produce ambiguous or unauditable decisions

Regardless of score, Artifacts 3 and 4 are incomplete if participants did not independently calculate the headline metric, propose the initial KPI set, and write the initial decision logic before using AI.

---

# 15. Facilitator guide

## Suggested 150-minute agenda

| Time | Activity |
|---|---|
| 0–20 min | From goals to metrics |
| 20–50 min | KPI architecture and metric trees |
| 50–70 min | Leading, lagging, proxy, vanity |
| 70–90 min | Misleading metrics and visualization |
| 90–110 min | KPI Catalogue and Metric Specification Card lab |
| 110–140 min | Decision Specification Document workshop |
| 140–150 min | Peer critique and close |

## Common misconceptions

**“If we can measure it, it should be on the dashboard.”**  
Every measure adds attention and maintenance cost. Include what supports a decision, diagnosis, obligation, or guardrail.

**“A target makes a metric actionable.”**  
A target without ownership and response logic can create pressure without useful action.

**“Leading indicators predict outcomes.”**  
Some do; others merely precede them. The relationship must be validated.

**“The DSD makes the decision mechanical.”**  
It structures evidence and judgment, preserves accountability, and makes exceptions visible.

---

# 16. Executive job aid

For every headline metric, demand:

- purpose,
- formula,
- numerator and denominator,
- owner,
- population and time,
- baseline and target,
- uncertainty or variation,
- breakdowns that could reverse the conclusion,
- guardrail,
- action threshold,
- last definition change.

For every major decision, demand a DSD that states:

- owner and deadline,
- options,
- criteria,
- evidence standard,
- trade-offs,
- guardrails,
- action logic,
- implementation owner,
- monitoring and reversal plan.

---

# 17. Glossary

**Guardrail metric:** A measure used to detect unacceptable side effects or boundary violations.

**Indicator:** A measure used to signal a condition or change, sometimes indirectly.

**KPI:** A strategically important measure tied to an objective and management decision.

**Lagging metric:** A measure of an outcome after it occurs.

**Leading metric:** An earlier measure of an activity or condition believed to influence a later outcome.

**Proxy metric:** An indirect substitute for a construct that is difficult to measure directly.

**Target:** A desired metric value by a defined time.

**Threshold:** A boundary that triggers review, escalation, or action.

**Vanity metric:** A measure that appears impressive but offers little decision value.

---

# 18. Reference notes and further reading

- OECD, [Development of a Results Framework](https://www.oecd.org/en/publications/monitoring-and-evaluation-of-child-and-youth-policies-and-outcomes-in-ireland_2bd86a9d-en/full-report/component-5.html). Guidance on selecting a limited set of useful indicators and using proxies carefully.
- OECD, [Handbook on Constructing Composite Indicators](https://www.oecd.org/content/dam/oecd/en/publications/reports/2008/08/handbook-on-constructing-composite-indicators-methodology-and-user-guide_g1gh9301/9789264043466-en.pdf). Data quality, weighting, normalization, sensitivity, and proxy considerations.
- Office for National Statistics, [Quality Defined](https://www.ons.gov.uk/methodology/methodologytopicsandstatisticalconcepts/qualityinofficialstatistics/qualitydefined). Relevance, accuracy, timeliness, accessibility, and comparability.
- Office for National Statistics, [Axes and Gridlines](https://service-manual.ons.gov.uk/data-visualisation/guidance/axes-and-gridlines). Practical chart integrity guidance.
- U.S. Government Accountability Office, [Evidence-Based Policymaking](https://www.gao.gov/products/gao-23-105460). Practices for planning, building, using, and learning from evidence.

---

# Closing message

Metrics are organizational instruments, not neutral observations. Design them so that improvement represents real value, expose the ways they can fail, and connect them to an explicit decision. The DSD turns that discipline into a repeatable management practice.

<a id="module-6"></a>

# Module 6: Experiment Design & Decision Making

## Module purpose

Experiments help organizations learn what an action changes. They are valuable when a decision depends on causal effect and uncertainty is both material and reducible. But not every question requires an experiment, and a randomized test is not automatically ethical, valid, or useful.

This module teaches participants to decide when experimentation is necessary, formulate a decision-relevant hypothesis, define variables and metrics, choose a validation method, evaluate trade-offs, and translate results into business impact.

The central principle is:

> Design the experiment around the decision and the intervention—not around the easiest metric to move.

---

## Intended audience

- Business, product, operations, and transformation leaders
- Analysts, data scientists, researchers, and experiment owners
- Finance, risk, compliance, and governance teams
- Managers who approve pilots or interpret experiment results

## Suggested duration

150 minutes, including an experiment-design clinic.

## Learning method: design before AI

Participants begin with a realistic decision, baseline data, operational constraints, and an intervention proposal. Before asking AI anything, they must calculate the baseline outcome, identify the unit that receives the intervention, draw the treatment and counterfactual, choose a primary metric from the KPI Catalogue, and write a falsifiable hypothesis.

AI may later act as a hostile design reviewer by identifying validity threats, spillovers, implementation failures, or alternative designs. It must not select the organization's acceptable risk, minimum meaningful effect, ethical boundary, or scale decision. Every AI critique must be verified against the data, operating context, and evidence standards in this module.

## Learning outcomes

By the end of this module, participants will be able to:

1. Decide whether an experiment is necessary, feasible, and ethical.
2. Translate a business decision into a testable hypothesis.
3. Define unit, treatment, control, outcome, and assignment mechanism.
4. Select primary, secondary, and guardrail metrics.
5. Recognize threats to validity including spillover, attrition, novelty, noncompliance, and multiple testing.
6. Compare randomized, quasi-experimental, predictive, simulation, and qualitative validation methods.
7. Interpret effect size, uncertainty, practical significance, and heterogeneity.
8. Evaluate business impact, costs, trade-offs, and scale readiness.
9. Produce Project Artifact 5: an Experiment Plan.

## Evidence base and framework alignment

This module aligns with the [NIST/SEMATECH Engineering Statistics Handbook](https://www.nist.gov/programs-projects/nistsematech-engineering-statistics-handbook), which defines design of experiments as advance planning to obtain data capable of supporting valid, objective conclusions. It also uses the counterfactual and impact-evaluation concepts in the World Bank and Inter-American Development Bank's [*Impact Evaluation in Practice*](https://www.worldbank.org/en/programs/sief-trust-fund/publication/impact-evaluation-in-practice). The World Bank's [randomized controlled trials guide](https://dimewiki.worldbank.org/Randomized_Control_Trials) provides implementation context for assignment, compliance, and analysis.

---

# 1. Business questions that require learning by intervention

Experiments are most useful when the question contains a causal verb:

- Does the new onboarding flow increase activation?
- Will preventive maintenance reduce downtime?
- Does an AI assistant improve case-resolution quality?
- Does the price change increase contribution margin?
- Will flexible scheduling reduce unwanted turnover?

The intervention matters because the organization is considering doing something.

## Prediction is not an experiment

A model may accurately predict who will churn. It does not establish whether a retention offer, service call, or product fix changes churn.

## A pilot is not necessarily an experiment

A pilot may test feasibility, workflow, adoption, or technical integration. If it lacks a credible comparison, it may not estimate impact.

## An experiment is not only an A/B webpage test

Experiments can randomize:

- customers,
- employees or teams,
- stores or regions,
- time periods,
- messages,
- process settings,
- rollout order.

The unit must match how the intervention is delivered and how spillover occurs.

---

# 2. When is an experiment necessary?

Use an experiment when all or most of the following hold:

1. The decision depends on the effect of an action.
2. Existing evidence is not sufficiently credible or transferable.
3. The decision is consequential or difficult to reverse.
4. The organization can vary the action ethically and operationally.
5. Outcomes can be measured within a useful time.
6. A comparison group can be protected from contamination.
7. The expected value of learning exceeds the cost and delay.

## When an experiment may be unnecessary

- The decision requires only description or forecasting.
- The effect is already established in the same context and the implementation risk is low.
- The intervention is required by law or safety policy regardless of measured effect.
- The action is easily reversible and very low consequence, making simple monitoring proportionate.
- The main uncertainty is technical feasibility, for which a prototype test is more appropriate.
- The effect will occur too slowly to inform the decision.

## When an experiment may be inappropriate

- Withholding treatment would violate rights or established duty of care.
- Participants cannot be protected from material harm.
- Assignment would create unacceptable discrimination or legal risk.
- Informed consent or required authorization cannot be obtained.
- Spillovers make the intended contrast meaningless.
- The organization lacks capacity to monitor and stop the test.

## Experiment-necessity gate

| Question | Yes/No |
|---|---|
| Is the required claim causal? | |
| Is the uncertainty material to the decision? | |
| Could new evidence change the choice? | |
| Is controlled variation lawful and ethical? | |
| Can the treatment and comparison be implemented distinctly? | |
| Can outcomes mature before the decision deadline? | |
| Is the value of information greater than test cost and delay? | |

If the causal claim is not required, choose a lighter method. If ethical or operational feasibility fails, redesign or use a credible alternative.

---

# 3. From business question to experiment specification

## Business question

> Should NovaCart deploy an AI drafting assistant for customer-support agents?

This is not yet an experiment specification.

## Decision statement

> The Head of Support must decide whether to deploy the assistant to all English-language chat agents next quarter to improve resolution efficiency while maintaining correctness, customer experience, privacy, and employee control.

## Intervention

Define exactly what changes:

- assistant proposes a draft response,
- agent may edit or reject it,
- approved knowledge sources only,
- no autonomous sending,
- sensitive categories excluded,
- logging and error-reporting enabled.

“Use AI” is not a reproducible treatment.

## Unit of assignment

Possible units:

- conversation,
- customer,
- agent,
- team,
- shift,
- week.

Conversation-level assignment may contaminate behavior because an agent learns from treatment conversations. Agent-level assignment reduces this spillover but requires more agents and must account for different skill levels. The design choice follows the mechanism.

## Population

Specify eligibility and exclusions:

- eligible English-language billing and account chats,
- exclude legal threats, safeguarding, fraud, and identity-compromise cases,
- agents must complete training and consent where required,
- include only shifts with stable system telemetry.

## Counterfactual

The comparison group uses the existing support workflow during the same period under the same staffing and policy conditions.

---

# 4. Hypotheses

## Business hypothesis

A business hypothesis expresses the mechanism and decision-relevant effect.

> Providing an editable, knowledge-grounded draft will reduce time per resolved conversation because agents spend less time retrieving and composing routine information, without increasing incorrect resolution, escalation, complaints, or sensitive-data exposure.

## Statistical hypotheses

For a primary outcome such as time per correctly resolved conversation:

- Null: the average outcome does not differ between treatment and control.
- Alternative: the treatment improves the average outcome by a specified amount or more.

Statistical significance is not the business objective. The effect must also be large enough to matter.

## Minimum meaningful effect

Define the smallest effect that justifies implementation after considering cost and risk.

Example:

> Deployment is economically attractive only if correctly resolved handling time falls by at least 8%, with no material breach of quality or safety guardrails.

This value informs sample-size planning and prevents celebrating trivial but statistically detectable effects.

## Hypothesis quality checklist

- intervention is specific,
- target population is defined,
- mechanism is plausible,
- primary outcome is measurable,
- direction and minimum effect are stated,
- time horizon is stated,
- guardrails are explicit,
- disconfirming result is possible.

---

# 5. Variables and measurement

## Treatment variable

The deliberately varied condition: assistant access versus current workflow.

## Outcome variables

Measures expected to change because of treatment.

Possible outcomes:

- correctly resolved handling time,
- first-contact resolution,
- customer effort,
- repeat contact within 7 days,
- agent cognitive load,
- quality-audit result.

## Covariates

Pre-treatment characteristics used for stratification, precision, or subgroup analysis:

- agent tenure,
- issue type,
- shift,
- customer segment,
- prior workload.

A covariate must be measured before treatment. Variables caused by treatment should not be adjusted for as if they were pre-existing confounders.

## Mediators

Variables on the causal path, such as draft acceptance or editing time. Mediators help explain mechanism but require care: conditioning on them can distort the overall treatment-effect estimate.

## Moderators

Variables across which effects may differ, such as agent experience or issue complexity.

## Confounders

In non-randomized studies, factors related to both treatment and outcome. Proper random assignment aims to break this relationship in expectation.

---

# 6. Metrics for experiments

## Primary metric

One main outcome used to judge the core hypothesis and power the study.

Example:

> Median handling time among conversations independently judged correctly resolved, analyzed at the agent-assignment level.

## Secondary metrics

Outcomes that enrich interpretation but do not replace the primary result opportunistically.

Examples:

- first-contact resolution,
- customer satisfaction,
- response latency,
- agent adoption,
- editing effort.

## Guardrail metrics

Boundaries that must not worsen beyond an agreed amount.

Examples:

- incorrect-resolution rate,
- complaint escalation,
- sensitive-data leakage,
- high-severity hallucination,
- employee workload or distress,
- subgroup performance gap.

## Diagnostic metrics

Measures that verify implementation and mechanism:

- assignment delivered correctly,
- assistant available and responsive,
- percentage of eligible chats exposed,
- draft acceptance and edit rate,
- knowledge-source citation coverage.

## Metric hierarchy

Pre-specify:

1. primary outcome,
2. guardrails,
3. secondary outcomes,
4. diagnostics,
5. exploratory analyses.

This reduces the risk of searching many metrics and reporting only favorable ones.

---

# 7. Core experimental designs

## 7.1 Completely randomized design

Eligible units are randomly assigned to conditions.

Best when units are independent and assignment is operationally simple.

## 7.2 Stratified or blocked randomization

Units are grouped by important pre-treatment characteristics, then randomized within groups.

Example: randomize agents within tenure and performance bands to improve balance and precision.

## 7.3 Cluster-randomized design

Groups rather than individuals are randomized.

Example: randomize stores, teams, or regions when treatment spills across individuals.

Requires analysis and sample planning at the cluster level; many observations within a few clusters do not create the same information as many independent clusters.

## 7.4 Crossover design

Units receive multiple conditions in different periods, with randomized order when feasible.

Useful when effects are reversible and carryover can be controlled. Unsuitable when treatment permanently changes skill or behavior.

## 7.5 Switchback design

Treatment alternates across time blocks for a shared environment such as a marketplace or logistics network.

Risks include time trends, carryover, and interference across blocks.

## 7.6 Factorial design

Tests multiple factors and their interactions efficiently.

Example: test message content and send timing together. The design can reveal whether their combined effect differs from the sum of individual effects.

## 7.7 Stepped-wedge rollout

Clusters transition from control to treatment at different scheduled times until all receive treatment.

Useful when rollout is inevitable and capacity is constrained, but time trends must be modeled carefully.

---

# 8. Randomization and implementation integrity

Randomization is a process, not a column labeled “A/B.”

## Required controls

- define eligible units before assignment,
- use a reproducible randomization procedure,
- conceal assignment when appropriate,
- prevent manual reassignment without audit,
- check treatment delivery,
- preserve assigned groups in analysis,
- record exclusions and attrition,
- monitor contamination and spillover.

## Intent-to-treat

Intent-to-treat analysis compares units according to original assignment, regardless of actual take-up. It preserves the benefit of randomization and estimates the effect of offering or assigning the treatment under real implementation.

Per-protocol or treatment-on-treated analyses may answer different questions but can reintroduce selection bias if adoption is voluntary.

## Balance checks

Pre-treatment characteristics should be examined to detect implementation errors and understand chance imbalances. Passing a set of significance tests does not prove perfect randomization; process evidence matters.

---

# 9. Sample size, uncertainty, and duration

Sample planning depends on:

- baseline outcome rate or variance,
- minimum meaningful effect,
- desired false-positive tolerance,
- desired power,
- assignment unit,
- clustering and repeated measures,
- expected attrition,
- number of conditions and primary comparisons.

## Too small

An underpowered experiment may produce a wide interval compatible with material benefit and harm. “Not significant” then means inconclusive, not “no effect.”

## Too large

A very large experiment can make trivial effects statistically significant. Business impact and guardrails still determine action.

## Duration

Run long enough to cover:

- outcome maturation,
- normal day-of-week or cycle variation,
- novelty and learning effects,
- relevant operational peaks,
- delayed harms such as returns or complaints.

Do not repeatedly peek and stop as soon as a favorable p-value appears unless using a planned sequential method.

---

# 10. Threats to validity

## Internal validity threats

### Noncompliance

Assigned units do not receive or use their condition.

### Attrition

Outcome data are missing differently across groups.

### Contamination

Control units gain access to treatment.

### Spillover/interference

One unit's treatment changes another unit's outcome.

### Instrumentation change

Measurement changes during the test.

### Concurrent interventions

Another policy or release differs between groups.

### Selective reporting

Only favorable outcomes or subgroups are presented.

## External validity threats

- participants differ from the scale population,
- test operators are unusually skilled,
- incentives and attention are higher during the pilot,
- infrastructure behaves differently at scale,
- the market or season changes,
- long-term adaptation differs from short-term response.

## Construct validity threats

The metric may not represent the intended concept. “Tickets closed” is not necessarily “problems solved.”

## Statistical conclusion threats

- low power,
- incorrect unit of analysis,
- ignored clustering,
- extreme outliers,
- multiple comparisons,
- model assumptions that do not fit the data.

---

# 11. Validation methods beyond randomized experiments

Experiments are powerful but not the only validation tool.

## Quasi-experimental methods

Use naturally occurring assignment or discontinuities to approximate a counterfactual.

- Difference-in-differences
- Regression discontinuity
- Instrumental variables
- Interrupted time series
- Matching or weighting

Each requires substantive assumptions. Method names should never substitute for a design argument.

## Backtesting

Apply a forecast or decision rule to historical periods not used in development. Useful for predictive validity, not for proving intervention impact.

## Shadow mode

Run a system without allowing it to affect live decisions. Compare outputs with current practice and later outcomes. Useful for safety and workflow learning.

## Simulation

Model system behavior under alternative policies. Useful where live tests are dangerous or slow, but conclusions inherit model assumptions.

## Usability and human-factors testing

Observe how people understand, use, override, or misuse the intervention. Essential for human–AI systems.

## Qualitative validation

Interviews, observation, and case review can identify mechanisms, harms, missing conditions, and implementation failures that metrics miss.

## Triangulation

Confidence increases when different methods with different weaknesses support the same conclusion.

---

# 12. Trade-offs and business impact

## Translate effect into operational units

Do not stop at “2.1 percentage points.” Estimate:

```text
Incremental outcomes = eligible population × estimated effect
Incremental gross value = incremental outcomes × value per outcome
Incremental net value = gross value − treatment cost − operating cost − expected harm cost
```

Report a plausible range using the effect interval and uncertain business inputs.

## Include full cost

- technology and vendor cost,
- integration and data work,
- employee training and transition,
- monitoring and quality assurance,
- exception handling,
- incident response,
- false-positive and false-negative cost,
- opportunity cost,
- decommissioning or exit cost.

## Heterogeneous effects

Average treatment effect may hide groups that benefit, do not respond, or are harmed.

Subgroup analysis should be:

- motivated in advance where possible,
- adequately powered,
- interpreted with multiple-testing caution,
- connected to a plausible mechanism,
- validated before operational targeting.

## Scale effects

Pilot impact may change when:

- treatment capacity becomes constrained,
- staff attention falls,
- customers adapt,
- supply or market equilibrium changes,
- the target population expands,
- infrastructure reaches load limits.

## Decision categories

Experiment results can support:

- **scale**, when benefit is meaningful and guardrails pass;
- **iterate**, when mechanism is promising but implementation or measurement failed;
- **extend**, when uncertainty remains decision-relevant and more data are valuable;
- **limit**, when effects are positive only for a defined population;
- **stop**, when benefit is insufficient or harm is unacceptable.

---

# Project Artifact 5: Experiment Plan

Use this plan before launching any test. The Experiment Design Brief below is the core of the artifact; the completed artifact also includes baseline analysis, a design diagram, an analysis trail, and sign-off.

## Pre-AI baseline analysis

**Decision inherited from the DSD:**  
**Baseline numerator and denominator:**  
**Baseline outcome calculation:**  
**Relevant segment variation:**  
**Current trend or normal variation:**  
**Operational constraint:**  
**My provisional view of whether an experiment is needed:**  
**Reason an observational comparison would or would not be sufficient:**

## Design diagram

```text
Eligible population at defined time
              │
      assignment mechanism
        ┌─────┴─────┐
        ▼           ▼
   Treatment     Comparison
        │           │
        └─────┬─────┘
              ▼
   common outcome window
              ▼
 effect estimate + guardrails
              ▼
 scale / limit / iterate / stop
```

Label the actual assignment unit, treatment, comparison, outcome window, spillover boundary, and decision rule on the submitted version.

## Experiment Design Brief

## A. Decision

**Decision statement:**  
**Owner and deadline:**  
**Options after the test:**  
**Minimum evidence needed:**

## B. Theory

**Business hypothesis:**  
**Mechanism:**  
**Key assumptions:**  
**Minimum meaningful effect:**

## C. Design

**Population and exclusions:**  
**Unit of assignment:**  
**Treatment:**  
**Control/comparison:**  
**Assignment method:**  
**Stratification/clustering:**  
**Duration and maturation:**  
**Sample-size rationale:**

## D. Measurement

**Primary metric:**  
**Secondary metrics:**  
**Guardrails:**  
**Diagnostics:**  
**Data sources and quality checks:**

## E. Analysis

**Primary estimand:**  
**Analysis population:**  
**Handling of attrition/noncompliance:**  
**Uncertainty method:**  
**Subgroups specified in advance:**  
**Multiple-comparison policy:**

## F. Operations and ethics

**Legal/ethical review:**  
**Consent/notice if required:**  
**Monitoring owner:**  
**Stop conditions:**  
**Incident response:**  
**Data protection:**

## G. Decision rule

**Scale condition:**  
**Iterate/extend condition:**  
**Stop condition:**  
**Guardrail priority:**  
**Exception authority:**

## H. Analyze–Challenge–Verify trail

**Initial design completed before AI:**  
**Weakest point identified by the participant:**  
**AI challenge requested:**  
**Threats or alternatives verified against evidence:**  
**Suggestions rejected and why:**  
**Design changes accepted and rationale:**  
**Decision owner/reviewer sign-off:**

## Completion standard

The plan is complete when the test can be implemented without inventing rules after launch, the analysis can be conducted without choosing outcomes after results are seen, and the decision owner can explain what result triggers scale, iteration, limitation, or stop. An AI-generated hypothesis or sample-size claim without documented inputs and human review is incomplete.

---

# 14. Worked case: AI support assistant

## Decision

Deploy, limit, redesign, or stop an AI drafting assistant.

## Design

- Unit: agent, randomized within tenure and current performance bands.
- Population: eligible routine English-language chat categories.
- Treatment: editable grounded drafts; no autonomous send.
- Control: current knowledge-search and drafting workflow.
- Duration: six weeks after a two-week stabilization period.
- Primary outcome: correctly resolved minutes per eligible conversation.
- Guardrails: severe factual error, privacy incident, complaint escalation, repeat contact, agent workload.

## Result

- Correctly resolved time improves 11%, interval 6%–16%.
- Severe factual errors are unchanged within a narrow pre-specified bound.
- Repeat contacts are unchanged.
- New agents improve 18%; experienced agents improve 4%.
- One excluded issue category shows unacceptable privacy-risk behavior during shadow testing.

## Decision

Scale for eligible categories, maintain exclusions, prioritize new-agent onboarding, require human approval, and run a separate redesign and evaluation for sensitive categories.

## Why the decision is not “AI works”

The evidence applies to a specific tool configuration, workflow, population, period, and set of controls. It does not justify autonomous responses or use in excluded categories.

---

# 15. Participant activities

## Activity A: experiment or not?

Choose a method for each:

1. Estimate next quarter's demand.
2. Determine whether a redesigned invoice reduces payment delay.
3. Verify that a new fraud model can run within latency limits.
4. Understand why operators ignore safety alerts.
5. Estimate the long-term effect of a regulation already applied nationwide.

Possible answers: forecasting; experiment; technical load test/shadow mode; qualitative human-factors study; quasi-experimental or interrupted-time-series design.

## Activity B: break the experiment

Review a proposed test and find at least five threats:

> Stores may choose whether to adopt a new sales tool. After one month, compare revenue in adopting versus non-adopting stores.

Likely threats: self-selection, baseline differences, seasonality, novelty, regression to the mean, different local promotions, short outcome window, adoption measured after treatment, clustering, incomplete cost.

## Activity C: design brief

Complete an Experiment Plan for a real decision. The initial plan must be written before AI use. Peer reviewers must challenge:

- the unit,
- counterfactual,
- metric hierarchy,
- minimum meaningful effect,
- stop conditions,
- scale assumptions.

After peer review, ask AI to identify one additional failure mode and one alternative design. Verify both before revising the plan, and document why each suggestion was accepted or rejected.

---

# 16. Knowledge check

## Questions

1. What makes a business pilot an experiment?
2. Why define the minimum meaningful effect before testing?
3. What is the difference between a primary and guardrail metric?
4. Why randomize clusters rather than individuals?
5. What does intent-to-treat estimate?
6. Why is “not statistically significant” not proof of no effect?
7. Name three threats to external validity.
8. What must be added to an effect estimate to make a scale decision?

## Suggested answers

1. Deliberate variation plus a credible comparison designed to estimate an effect.
2. To plan sample size and distinguish decision-relevant impact from trivial movement.
3. The primary metric tests the core benefit; a guardrail sets acceptable boundaries for harm or degradation.
4. When treatment or behavior spills within groups or is delivered at group level.
5. The effect of assignment or offering treatment under actual uptake.
6. The interval may still include material benefit and harm, especially in a small study.
7. Unrepresentative participants, enhanced pilot attention, scale constraints, short duration, or changing market conditions.
8. Full cost, guardrails, operational feasibility, heterogeneity, uncertainty, and scale assumptions.

---

# 17. Assessment rubric: experiment design

Score 0–2 per dimension.

| Dimension | 0 | 1 | 2 |
|---|---|---|---|
| Decision | absent | implied | owner/options/deadline clear |
| Hypothesis | vague | outcome named | mechanism and minimum effect stated |
| Treatment | “use X” | partial | reproducible intervention |
| Counterfactual | none | weak baseline | credible concurrent comparison |
| Assignment | biased/unclear | method named | unit, randomization, spillover addressed |
| Metrics | many/unranked | primary named | hierarchy and guardrails pre-specified |
| Power/duration | ignored | rough | decision-relevant planning |
| Validity | ignored | some risks | monitoring and mitigation defined |
| Ethics/operations | absent | reviewed informally | approvals, stop, incidents, protection |
| Decision logic | absent | broad | scale/iterate/stop rules explicit |

Interpretation:

- **17–20:** launch-ready subject to formal review
- **12–16:** promising but requires remediation
- **0–11:** high risk of inconclusive or misleading evidence

Regardless of score, the Experiment Plan is incomplete if baseline analysis, the initial hypothesis, and the treatment/comparison design were not produced before AI critique.

---

# 18. Facilitator guide

## Suggested 150-minute agenda

| Time | Activity |
|---|---|
| 0–20 min | When experiments are needed |
| 20–45 min | Hypotheses, variables, and metrics |
| 45–75 min | Experimental designs and assignment |
| 75–100 min | Validity and implementation threats |
| 100–120 min | Interpretation, trade-offs, business impact |
| 120–145 min | Experiment Plan workshop |
| 145–150 min | Close |

## Common misconceptions

**“Randomization guarantees a valid answer.”**  
Assignment can be corrupted; attrition, spillover, measurement failure, and selective reporting remain.

**“If the primary metric improves, scale.”**  
Guardrails, cost, feasibility, heterogeneity, and scale effects also matter.

**“A failed experiment means the idea is bad.”**  
The intervention, implementation, theory, measurement, or design may have failed. The evidence must distinguish them.

**“A statistically significant result is important.”**  
Importance depends on effect size, uncertainty, cost, consequences, and decision threshold.

---

# 19. Glossary

**Attrition:** Missing outcome data because units leave or cannot be measured.

**Control group:** Units representing the comparison condition.

**Estimand:** The precise quantity the analysis seeks to estimate.

**Experiment:** A planned study that deliberately varies an intervention to estimate its effect.

**Guardrail:** A metric boundary protecting against unacceptable side effects.

**Intent-to-treat:** Analysis based on original assignment regardless of uptake.

**Minimum meaningful effect:** Smallest effect large enough to change the decision.

**Power:** Probability of detecting a specified effect under a study design.

**Spillover:** One unit's treatment affects another unit's outcome.

**Treatment:** The intervention or condition deliberately varied.

---

# 20. Reference notes and further reading

- NIST/SEMATECH, [What Is Experimental Design?](https://itl.nist.gov/div898/handbook/pri/section1/pri11.htm). Foundations of objectives, factors, responses, and advance design.
- NIST/SEMATECH, [Choosing an Experimental Design](https://www.itl.nist.gov/div898/handbook/pri/section3/pri3.htm). Overview of randomized, block, factorial, and response-surface designs.
- World Bank and Inter-American Development Bank, [*Impact Evaluation in Practice*](https://www.worldbank.org/en/programs/sief-trust-fund/publication/impact-evaluation-in-practice). Counterfactuals, randomized assignment, quasi-experimental approaches, sampling, and implementation.
- World Bank DIME Wiki, [Randomized Controlled Trials](https://dimewiki.worldbank.org/Randomized_Control_Trials). Operational guidance and links to design resources.

---

# Closing message

An experiment is a decision instrument. Its value lies not in randomization alone, but in testing a precise intervention against a credible alternative, measuring what matters, protecting what must not be harmed, and defining how the result will change action.

<a id="module-7"></a>

# Module 7: AI for Business Execution

## Module purpose

AI creates operational value when it changes how work is performed, coordinated, checked, and improved. Buying a tool or running a pilot is not execution. Organizations must redesign tasks and workflows, define human authority, connect systems and knowledge, measure the combined human–AI process, and build controls that remain effective at scale.

This module teaches participants to identify suitable operational AI opportunities, select an appropriate human–AI configuration, evaluate execution strategies, and scale only when business value and risk controls are demonstrated.

The central principle is:

> Scale a well-designed operating system, not an isolated model demo.

---

## Intended audience

- Executives and functional leaders
- Operations, product, transformation, and technology teams
- Data, AI, risk, legal, security, and governance professionals
- Managers responsible for AI-enabled work

## Suggested duration

150 minutes, including an opportunity-mapping workshop and operating-model design exercise.

## Learning method: earn the right to ask “where can AI help?”

This module begins only after participants have examined the business question, data structure, KPIs, decision logic, and evidence needs in Artifacts 1–5. Participants first analyze the current workflow and baseline performance without AI. They must identify the bottleneck, failure modes, human judgments, and non-AI improvement options before proposing an AI role.

AI may then challenge the opportunity analysis, suggest bounded task patterns, or surface implementation risks. AI cannot nominate itself as the solution, define acceptable harm, remove accountable human judgment, or provide unverified estimates of value. The final opportunity ranking must be owned by the business, workflow, and risk owners.

## Learning outcomes

By the end of this module, participants will be able to:

1. Distinguish AI task capability from operational business value.
2. Identify AI opportunities in high-volume, information-intensive workflows.
3. Evaluate AI for scaling, efficiency, and organizational agility.
4. Choose among assistive, advisory, approval-based, and bounded autonomous configurations.
5. Define which judgments and accountabilities must remain human.
6. Design controls for input, generation, action, monitoring, and recovery.
7. Evaluate operational AI use cases using value, feasibility, risk, and learning criteria.
8. Build a staged execution strategy from discovery through monitored scale.
9. Produce Project Artifact 6: an AI Opportunity Matrix.

## Evidence base and framework alignment

This module is anchored in the [NIST AI Risk Management Framework Core](https://airc.nist.gov/airmf-resources/airmf/5-sec-core/), which calls for clear business context, documented human–AI roles, testing in deployment-like conditions, post-deployment monitoring, appeal and override, incident response, and continual improvement. Generative-AI-specific risks and actions are informed by the [NIST Generative AI Profile](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf).

Workforce implications are framed consistently with the International Labour Organization's [2025 research on generative AI and jobs](https://www.ilo.org/publications/generative-ai-and-jobs-2025-update), which evaluates exposure at task level and emphasizes that occupational effects depend on the mix of tasks rather than job titles alone. These frameworks are general guidance; organizations must apply sector, jurisdiction, labor, privacy, safety, and professional requirements relevant to their context.

---

# 1. AI for execution, not demonstration

An AI demonstration usually answers:

> Can the system produce a plausible output?

Operational execution must answer:

- Does the output improve a real workflow?
- Does it arrive at the right time and in the right system?
- Can people understand, verify, and act on it?
- What happens when it is wrong, unavailable, or attacked?
- Is the total process faster, cheaper, better, or more adaptable?
- Who remains accountable?
- Can performance be monitored and reversed?

The unit of value is the **human–AI work system**, not the model in isolation.

## Work-system chain

```text
Trigger → context/data → AI task → human judgment → action → outcome → feedback
```

Weak implementations optimize the AI task and ignore downstream work. A faster draft that takes longer to verify may create no net efficiency. A high-quality forecast creates no value if replenishment constraints prevent action.

---

# 2. Three strategic contributions of AI

## 2.1 Scaling

AI can extend a repeatable information task across more cases, channels, languages, or hours.

Examples:

- classify every incoming request rather than a sample,
- create first drafts across thousands of product descriptions,
- summarize all case notes before handoff,
- monitor more equipment or transactions for anomalies.

Scaling is valuable when:

- the task is sufficiently consistent,
- inputs are available and lawful to use,
- quality can be measured,
- exceptions can be detected,
- the organization can absorb increased downstream volume.

Scaling a defective process magnifies defects. Standardize and clarify the work before automating it.

## 2.2 Operational efficiency

AI can reduce time, queue length, rework, or marginal processing cost.

Common mechanisms:

- retrieval and summarization,
- drafting and transformation,
- classification and routing,
- forecasting and prioritization,
- anomaly detection,
- bounded workflow orchestration.

Efficiency must be measured end to end:

```text
Net cycle time = AI time + human review + correction + exception handling + recovery
```

Ignoring verification and error cost turns gross automation into fictional savings.

## 2.3 Organizational agility

AI can shorten the time between new information and coordinated response.

Examples:

- synthesizing frontline signals for weekly planning,
- rapidly adapting communications to a policy change,
- generating scenarios when supply conditions shift,
- helping teams search fragmented organizational knowledge,
- translating operating guidance across regions.

Agility is not simply speed. It includes the ability to sense change, decide, execute, and learn without losing control.

---

# 3. Identify opportunities at task level

Job titles are poor units for AI design. Most roles combine:

- routine and novel tasks,
- explicit and tacit knowledge,
- low- and high-consequence judgments,
- digital and physical work,
- individual and collaborative activity.

Break a workflow into tasks before deciding what AI should do.

## Task decomposition template

| Step | Trigger | Input | Task | Output | Current owner | Decision/consequence | Failure mode |
|---|---|---|---|---|---|---|---|
| | | | | | | | |

Then classify each task:

- retrieve,
- extract,
- classify,
- summarize,
- generate,
- predict,
- recommend,
- decide,
- act,
- monitor.

AI suitability differs across the chain. Summarization may be suitable while the final eligibility decision remains human.

## Opportunity signals

Look for tasks that are:

- high volume or repetitive,
- information intensive,
- constrained by search or synthesis time,
- supported by digital inputs,
- measurable at output and outcome levels,
- tolerant of bounded error or reviewable before action,
- bottlenecks in a larger workflow,
- variable in demand and expensive to staff for peaks.

## Warning signals

Exercise caution where tasks involve:

- severe or irreversible consequences,
- rights, eligibility, discipline, or legal status,
- sparse or contested ground truth,
- novel strategic ambiguity,
- tacit interpersonal judgment,
- sensitive data without mature controls,
- outputs that cannot be verified before harm,
- incentives that encourage overreliance.

---

# 4. Operational AI use-case patterns

## 4.1 Knowledge retrieval and synthesis

Use cases:

- policy question answering,
- case or account briefing,
- research synthesis,
- incident timeline construction,
- meeting and handoff summaries.

Controls:

- approved source scope,
- access permissions inherited from source systems,
- citations or traceability,
- freshness metadata,
- refusal when evidence is absent,
- sampling for unsupported claims.

## 4.2 Drafting and transformation

Use cases:

- customer responses,
- reports,
- product content,
- translation,
- code or test drafts,
- structured extraction from documents.

Controls:

- templates and style constraints,
- required fields,
- human approval proportional to consequence,
- sensitive-data filtering,
- factual validation,
- version and provenance tracking.

## 4.3 Classification, routing, and triage

Use cases:

- support routing,
- document classification,
- fraud-alert prioritization,
- quality-inspection triage,
- incident severity suggestion.

Controls:

- calibrated thresholds,
- priority handling for uncertain or high-consequence cases,
- false-negative monitoring,
- override and feedback capture,
- capacity-aware queue design.

## 4.4 Forecasting and planning

Use cases:

- demand, staffing, inventory, cash, or failure forecasting,
- scenario generation,
- early-warning signals.

Controls:

- simple baseline comparison,
- backtesting across changing conditions,
- uncertainty ranges,
- drift monitoring,
- human interpretation of structural changes.

## 4.5 Recommendation and decision support

Use cases:

- next-best action,
- maintenance prioritization,
- resource allocation,
- offer recommendation,
- exception review.

Controls:

- objective and constraints visible,
- causal evidence for interventions where required,
- alternative options shown,
- explanation tied to actual evidence,
- authority and override explicit,
- outcomes tracked after action.

## 4.6 Bounded automation and orchestration

Use cases:

- schedule low-risk routine work,
- populate approved systems,
- execute reversible transactions within thresholds,
- trigger standard notifications,
- reconcile structured records.

Controls:

- allow-listed actions,
- permissions limited by role and context,
- transaction limits,
- pre-action validation,
- idempotency and duplicate prevention,
- full logs,
- safe failure and rollback,
- automatic escalation outside bounds.

---

# 5. Human judgment and AI roles

Human involvement should be designed around what people uniquely contribute and what the system cannot reliably do—not added as a ceremonial approval step.

## Non-delegable human responsibilities

In most material business uses, humans must retain responsibility for:

- setting purpose and acceptable use,
- choosing objectives and trade-offs,
- defining risk tolerance,
- judging novel or ambiguous exceptions,
- considering context absent from data,
- authorizing high-consequence action,
- hearing challenges and appeals,
- accepting accountability for outcomes,
- deciding whether to continue, change, or stop the system.

## AI contribution ladder

| Level | AI role | Human role | Suitable example |
|---|---|---|---|
| 0 | No AI | performs task | sensitive negotiation |
| 1 | Observe | acts; AI logs or detects patterns | workflow analysis |
| 2 | Assist | creates or retrieves; human constructs result | search and summary |
| 3 | Recommend | proposes ranked action; human decides | maintenance prioritization |
| 4 | Execute with approval | prepares action; human authorizes | payment exception release |
| 5 | Bounded autonomy | acts within explicit limits; human monitors exceptions | routine stock replenishment |

The appropriate level depends on consequence, reversibility, uncertainty, oversight capacity, and system maturity.

## The rubber-stamp problem

A human approval step is ineffective when reviewers:

- lack time,
- lack context or expertise,
- cannot inspect evidence,
- are measured only on speed,
- cannot override,
- believe the system is more authoritative,
- receive no feedback on errors.

Effective oversight requires competence, information, time, authority, incentives, and feedback.

## Calibrated reliance

The goal is neither distrust nor blind trust. Users should understand:

- where the system performs well,
- where it is uncertain,
- which conditions are outside scope,
- which errors are most costly,
- how to verify and challenge output,
- how their feedback improves the process.

---

# Project Artifact 6: AI Opportunity Matrix

## Purpose

The AI Opportunity Matrix compares specific workflow tasks—not broad departments or job titles—and makes the reason for selecting, deferring, or rejecting each opportunity visible. It is the final portfolio artifact because a credible AI opportunity depends on the decision, data, metrics, and validation work completed earlier.

## Entry gate: analysis before AI

Before generating AI use cases, participants must independently provide:

- the business decision from the Business Question Map,
- the relevant entities and data constraints from the Data Structure Diagram,
- baseline outcome and guardrails from the KPI Catalogue,
- authority and trade-offs from the DSD,
- the evidence gap and validation approach from the Experiment Plan,
- an 8–12 step map of the current workflow,
- baseline volume, cycle time, quality, cost, exceptions, and known harms,
- at least one non-AI improvement option.

If these inputs are missing, the matrix should record **not ready for AI evaluation** rather than inventing an opportunity.

## Matrix template

| ID | Workflow step and pain point | Proposed AI task | Baseline evidence | Value | Data/process feasibility | Consequence and reversibility | Human judgment retained | Evidence readiness | Learning value | Non-AI alternative | Recommendation |
|---|---|---|---|---:|---:|---|---|---:|---:|---|---|
| AI-01 | | Retrieve / extract / classify / summarize / generate / predict / recommend / bounded action | | 1–5 | 1–5 | | | 1–5 | 1–5 | | Explore / pilot / defer / reject |

Use separate notes for any legal, safety, rights, labor, privacy, or security condition that can override the numeric scores.

## Scoring dimensions

Score use cases across the following dimensions. Scores support discussion; they do not make the decision.

## 6.1 Value

- frequency and volume,
- cycle-time or quality pain,
- financial or strategic value,
- service or employee benefit,
- downstream unlock.

## 6.2 Feasibility

- input availability and quality,
- process standardization,
- system integration,
- output verifiability,
- skill and change capacity,
- vendor or model readiness.

## 6.3 Risk

- consequence and reversibility,
- privacy and security,
- legal or contractual obligations,
- bias and distributional harm,
- hallucination or false-action risk,
- dependence and resilience,
- reputational impact.

## 6.4 Learning value

- can the use case build reusable data, integration, governance, or workforce capability?
- can impact be evaluated within a useful period?
- will learning transfer to other workflows?

## 6.5 Controllability and human judgment

Assess:

- whether output can be verified before action,
- whether errors are reversible,
- whether boundaries can be enforced technically,
- whether a competent human has time and authority to intervene,
- whether affected people can challenge or appeal,
- which value judgments cannot be delegated.

## 6.6 Evidence readiness

Assess whether the organization has:

- a stable baseline,
- representative evaluation cases,
- measurable outcomes and guardrails,
- a credible comparison or validation design,
- owners for monitoring and incidents,
- enough time to learn before scale.

## Opportunity scorecard

| Dimension | 1: low | 3: medium | 5: high |
|---|---|---|---|
| Value | marginal task gain | meaningful local outcome | material enterprise outcome |
| Feasibility | unclear inputs/process | manageable integration | stable data and workflow |
| Risk | severe/irreversible | controllable with review | low consequence/reversible |
| Evidence readiness | no baseline or test path | partial measures/design | measurable with credible validation |
| Learning | isolated | some reusable capability | platform-level learning |

For risk, reverse the score if summing: high score should mean easier to control, not greater danger.

Do not let an average score hide a fatal condition. A single unacceptable legal, safety, or rights risk can stop a use case.

## Portfolio placement

Place each opportunity in one of four action groups:

| Group | Meaning | Next step |
|---|---|---|
| **Explore** | Valuable hypothesis; major feasibility or evidence unknowns | research workflow/data; do not pilot yet |
| **Pilot** | Bounded task, credible value, measurable outcomes, controllable risk | complete AI Execution Specification and stage-gate plan |
| **Defer** | Potential value but dependencies, data, controls, or timing are not ready | name prerequisite and review date |
| **Reject** | Low value or unacceptable/uncontrollable consequence | document reason; do not recycle without material change |

## Analyze–Challenge–Verify trail

**Opportunities identified from workflow analysis before AI:**  
**Baseline calculations used:**  
**Non-AI alternatives considered:**  
**AI challenge requested:**  
**AI-suggested opportunities verified against workflow and data:**  
**Suggestions rejected and why:**  
**Final ranking and accountable owners:**

## Completion standard

The matrix is complete when each opportunity is a bounded task, expected value is tied to a baseline, human judgment is explicit, fatal risks cannot be averaged away, and the next step is justified. A brainstormed list of AI use cases without workflow evidence and non-AI alternatives is incomplete.

---

# 7. AI-assisted execution architecture

A robust workflow uses layered controls.

## Layer 1: input and access

- authenticate users and services,
- enforce least privilege,
- classify and minimize data,
- validate file types and sources,
- prevent unauthorized cross-context access,
- manage retention.

## Layer 2: context and generation

- ground output in approved knowledge,
- define instructions and output schema,
- test for prompt injection and manipulation,
- identify unsupported content,
- separate trusted instructions from untrusted input.

## Layer 3: decision and action

- restrict available tools and actions,
- apply business rules and thresholds,
- require approval for higher-consequence actions,
- check target, amount, and scope before execution,
- prevent duplicate or cascading action.

## Layer 4: monitoring and assurance

- log input, output, model/version, evidence, action, and override,
- sample for quality,
- track outcome and guardrail metrics,
- detect drift and anomalous usage,
- review performance by relevant groups,
- conduct independent testing proportionate to risk.

## Layer 5: response and recovery

- stop or isolate the system,
- fall back to a known manual process,
- reverse recoverable actions,
- notify affected teams or people,
- investigate and document incidents,
- update controls and retrain users.

Defense in depth matters because no single prompt, filter, reviewer, or score is sufficient.

---

# 8. Scaling strategy

## Stage 0: problem and workflow discovery

Outputs:

- decision and workflow map,
- task decomposition,
- baseline performance,
- pain points and constraints,
- stakeholder and risk map,
- non-AI alternatives.

Gate: Is AI plausibly better than process redesign, rules, search, or conventional automation?

## Stage 1: offline evaluation

Outputs:

- representative test set,
- quality and risk taxonomy,
- simple baseline comparison,
- failure analysis,
- preliminary human-use design.

Gate: Does the capability meet minimum quality and safety under realistic conditions?

## Stage 2: shadow mode

The system operates on live inputs without affecting real decisions.

Outputs:

- live distribution performance,
- latency and reliability,
- comparison with current work,
- exception patterns,
- revised controls.

Gate: Is the workflow ready for limited human use?

## Stage 3: assisted pilot

AI output is visible to trained users; action remains human-controlled.

Outputs:

- human–AI outcome evaluation,
- adoption and override behavior,
- net time including verification,
- quality and guardrail results,
- employee and customer feedback.

Gate: Is there demonstrated net business value with acceptable risk?

## Stage 4: controlled rollout

Expand populations or sites gradually with monitoring and support.

Outputs:

- scale reliability,
- subgroup and site performance,
- change-management results,
- incident and fallback evidence,
- unit economics.

Gate: Are performance and controls stable outside the pilot environment?

## Stage 5: monitored scale

Operationalize:

- ownership and service levels,
- model/vendor change control,
- continuous evaluation,
- incident response,
- retraining and competency,
- periodic reauthorization,
- decommissioning and exit plan.

Scale is a governance state, not the end of learning.

---

# 9. Measure the human–AI system

## Capability metrics

- task correctness,
- groundedness or evidence support,
- calibration,
- latency and uptime,
- security and safety test results.

## Human-interaction metrics

- adoption and appropriate-use rate,
- acceptance, edit, and override behavior,
- verification time,
- operator understanding,
- overreliance and underreliance,
- workload and cognitive burden.

## Workflow metrics

- end-to-end cycle time,
- queue and throughput,
- rework and exception rate,
- handoff quality,
- escalation,
- cost per completed outcome.

## Outcome metrics

- customer or employee outcome,
- revenue, margin, quality, or risk,
- differential effects across groups,
- delayed outcomes and unintended consequences.

## Economic measurement

```text
Net value = incremental outcome value
          + labor or capacity value released
          − technology and integration cost
          − oversight and correction cost
          − expected error and incident cost
          − change and opportunity cost
```

“Hours saved” is not automatically cash saved. State whether time becomes reduced staffing cost, absorbed growth, faster service, higher quality, or unclaimed capacity.

---

# 10. Organizational agility and operating model

## Centralize what must be consistent

Shared capabilities may include:

- approved platforms and vendor controls,
- identity, access, and logging,
- model and use-case inventory,
- risk tiers and minimum controls,
- evaluation tooling,
- incident response,
- reusable legal and procurement terms,
- shared knowledge architecture.

## Federate what requires domain knowledge

Business functions should own:

- workflow definition,
- domain quality criteria,
- impact hypotheses,
- affected stakeholder engagement,
- adoption and process change,
- outcome monitoring,
- accountability for use.

## Cross-functional product team

Material use cases need representation from:

- business owner,
- frontline users,
- product/process owner,
- data/AI and engineering,
- security and privacy,
- legal/compliance/risk,
- measurement or experimentation,
- change and learning,
- affected stakeholders where appropriate.

## Reusable capability versus isolated pilot

Prefer investments that create:

- governed connectors,
- common evaluation datasets,
- reusable workflow components,
- standard monitoring,
- shared training,
- documented patterns and anti-patterns.

This reduces duplicate risk and shortens future deployment time.

---

# 11. Workforce and change

AI changes tasks, information flow, skill expectations, and sometimes power. Adoption is not a communications problem alone.

## Workforce questions

- Which tasks are removed, added, or intensified?
- Who performs verification and exception handling?
- Does work become more meaningful or more monitored?
- What expertise could atrophy?
- Who receives productivity gains?
- Are performance targets adjusted to include oversight work?
- Can employees challenge or report problems safely?
- Are job redesign and consultation obligations met?

## Training must be role-specific

Users need to know:

- permitted and prohibited use,
- data-handling rules,
- task-specific verification,
- system limits and common failure modes,
- escalation and incident reporting,
- how performance is monitored,
- when to ignore or override AI output.

Managers need additional capability in interpreting system metrics, resource trade-offs, accountability, and deciding when to pause.

## Preserve expertise

If AI drafts most routine work, employees may receive fewer opportunities to learn foundational patterns. Design:

- deliberate practice,
- rotation through unassisted cases,
- review of errors and edge cases,
- competency checks,
- clear professional responsibility.

---

# 12. Common execution failure modes

## Tool-first adoption

The organization buys access before defining workflows or outcomes.

## Pilot purgatory

Many demonstrations succeed locally, but none meet integration, evidence, risk, or ownership gates for scale.

## Gross savings fiction

Time saved by generation is reported without review, correction, and exception work.

## Hidden human labor

Data cleanup, prompt maintenance, output checking, and recovery are treated as free.

## Automation bias

People accept output because it appears authoritative or review is burdensome.

## Process ossification

The system encodes a weak legacy process and makes it harder to improve.

## Orphaned ownership

Technology owns the tool; the business assumes technology owns outcomes; no one owns the full workflow.

## Uncontrolled model change

A vendor update changes behavior without re-evaluation.

## No exit path

The organization cannot operate when the service fails, pricing changes, or the vendor relationship ends.

---

# 13. AI Execution Specification

Use this document to turn an opportunity into an executable, governable plan.

## A. Outcome and decision

**Business outcome:**  
**Decision owner:**  
**Workflow decision(s) affected:**  
**Baseline:**  
**Target and time horizon:**

## B. Workflow and task

**Trigger:**  
**Current steps and owners:**  
**Bottleneck:**  
**AI task:**  
**Human task:**  
**Final action:**  
**Exceptions:**

## C. Population and boundaries

**Eligible cases/users:**  
**Excluded cases:**  
**Authorized data and sources:**  
**Prohibited data/actions:**  
**Geographic/sector limits:**

## D. Human–AI configuration

**AI level:** observe, assist, recommend, execute with approval, bounded autonomy.  
**Human authority:**  
**Required review:**  
**Override and appeal:**  
**Competency requirements:**

## E. Evidence and metrics

**Capability metrics:**  
**Human-interaction metrics:**  
**Workflow metrics:**  
**Outcome metrics:**  
**Guardrails:**  
**Evaluation design:**  
**Minimum scale criteria:**

## F. Controls

**Access and data:**  
**Grounding/validation:**  
**Action constraints:**  
**Logging and monitoring:**  
**Incident and recovery:**  
**Vendor/model change:**

## G. Operations

**Business owner:**  
**Technical owner:**  
**Risk/control owner:**  
**Support and service level:**  
**Training and change plan:**  
**Fallback process:**  
**Exit/decommissioning:**

## H. Stage gates

**Offline → shadow:**  
**Shadow → pilot:**  
**Pilot → controlled rollout:**  
**Rollout → scale:**  
**Pause/stop conditions:**

---

# 14. Worked case: invoice exception handling

## Current state

Accounts payable receives 40,000 invoices per month. Twenty-two percent require manual review because purchase order, receipt, vendor, tax, or amount fields do not match. Median resolution is four days.

## Opportunity

Use AI to extract fields from varied documents, summarize mismatch evidence, and recommend an exception category. Do not authorize payment autonomously.

## Task design

- OCR and extraction: AI-assisted with confidence checks.
- Document-to-record matching: rules plus probabilistic matching.
- Exception explanation: generated from structured discrepancies with source links.
- Low-risk exact matches: existing rules auto-process.
- Material exceptions: analyst decides.
- Payment authorization: remains under existing financial controls.

## Metrics

- correctly resolved exception time,
- extraction and match accuracy by invoice type,
- manual touches per case,
- duplicate or incorrect payment,
- early-payment discount captured,
- vendor disputes,
- analyst workload,
- cost per resolved invoice.

## Execution path

1. Offline test on representative historical invoices.
2. Shadow mode alongside analysts.
3. Assisted pilot for two low-risk categories.
4. Controlled expansion by vendor/document type.
5. Maintain rule-based straight-through processing for exact matches; AI handles ambiguity but does not approve payment.

## Resulting judgment

AI creates value in evidence extraction and exception preparation. The consequential financial authorization remains under established human and system controls. This is targeted workflow redesign, not blanket automation.

---

# 15. Participant activities

## Activity A: task mining

Select one workflow and map 8–12 steps. For each step, mark:

- task type,
- volume,
- variability,
- consequence,
- verifiability,
- potential AI role,
- human responsibility.

Identify no more than two initial opportunities.

Complete this analysis without AI and place both opportunities in the AI Opportunity Matrix before requesting critique.

## Activity B: role boundary debate

For one use case, assign the highest safe AI level. One group argues for greater automation; another argues for more human authority. Both must use consequence, reversibility, evidence, workload, and monitoring—not intuition alone.

## Activity C: opportunity matrix to execution specification

First compare at least three candidate tasks in the AI Opportunity Matrix. Complete an AI Execution Specification only for a candidate placed in **Pilot**. Scenario options include:

- maintenance work-order prioritization,
- multilingual customer-response drafting,
- contract clause review,
- invoice exception handling,
- demand-planning assistance.

Peer reviewers must identify one hidden labor cost, one unsafe boundary, one missing metric, and one scale assumption.

AI review occurs last. Ask it to challenge the highest-ranked candidate and propose a credible non-AI alternative. Verify the response before changing the ranking.

---

# 16. Knowledge check

## Questions

1. Why is a model demo insufficient evidence of operational value?
2. What is the difference between gross and net cycle-time improvement?
3. Why analyze tasks rather than job titles?
4. Name three non-delegable human responsibilities.
5. When can bounded autonomy be appropriate?
6. Why can a human approval step fail as oversight?
7. What is shadow mode?
8. What evidence should be required before scale?

## Suggested answers

1. It does not establish workflow fit, human use, actionability, outcomes, cost, controls, or recovery.
2. Net improvement includes review, correction, exceptions, and recovery; gross improvement often measures AI generation alone.
3. Jobs contain a mix of tasks with different inputs, consequences, and suitability.
4. Setting purpose and trade-offs, defining risk tolerance, authorizing consequential action, hearing appeals, and accepting accountability.
5. For well-defined, low-consequence or reversible actions within explicit permissions, thresholds, monitoring, and fallback.
6. Reviewers may lack time, information, competence, authority, incentives, or feedback.
7. Running the system on live inputs without allowing its output to affect live decisions.
8. Human–AI outcome improvement over a baseline, acceptable guardrails, operational reliability, full unit economics, subgroup review, and proven controls/fallback.

---

# 17. Assessment rubric: operational AI strategy

Score each dimension 0–2.

| Dimension | 0 | 1 | 2 |
|---|---|---|---|
| Business outcome | tool goal | broad benefit | measurable outcome and owner |
| Workflow | absent | high-level | trigger-to-outcome mapped |
| Task fit | job-level | task named | inputs, outputs, limits defined |
| Human role | “in the loop” | approval named | authority, competence, workload designed |
| Boundaries | absent | exclusions listed | enforceable data/action limits |
| Evidence | demo | technical tests | end-to-end outcome evaluation |
| Metrics | productivity only | mixed set | capability, human, workflow, outcome, guardrails |
| Controls | generic | selected controls | layered prevention, monitoring, recovery |
| Scale | immediate rollout | pilot plan | stage gates and change controls |
| Ownership | technology only | shared informally | business, technical, risk, support owners |

Interpretation:

- **17–20:** credible execution strategy
- **12–16:** viable after targeted redesign
- **0–11:** tool adoption plan, not an operating model

Regardless of score, the AI Opportunity Matrix is incomplete if the workflow and baseline were not analyzed before AI use, no non-AI alternative was considered, or the participant cannot defend the final ranking without appealing to AI authority.

---

# 18. Facilitator guide

## Suggested 150-minute agenda

| Time | Activity |
|---|---|
| 0–20 min | AI as a human–AI work system |
| 20–45 min | Scaling, efficiency, agility |
| 45–75 min | Task decomposition and use-case patterns |
| 75–100 min | Human judgment and layered controls |
| 100–120 min | Stage gates and measurement |
| 120–145 min | AI Opportunity Matrix and selected Execution Specification workshop |
| 145–150 min | Close |

## Common misconceptions

**“The best model will create the most value.”**  
Value depends on workflow timing, action, human behavior, cost, and control—not model quality alone.

**“Adoption is success.”**  
Use is an intermediate measure. Outcomes and guardrails determine success.

**“Human in the loop makes it safe.”**  
Oversight only works when the human can competently and realistically intervene.

**“Automation is the end state.”**  
Assistance or recommendation may create more value when context, exceptions, or accountability are important.

**“Scaling means adding more users.”**  
Scale changes workload, data distribution, infrastructure, incentives, and risk. It requires re-evaluation.

---

# 19. Executive job aid: operational AI review

Before approving scale, ask:

1. Which workflow outcome improves, and against what baseline?
2. Which exact task does AI perform?
3. What remains human, and why?
4. What are the eligible and excluded cases?
5. What is the net time and full cost after review and errors?
6. What happens when the system is wrong or unavailable?
7. Can users inspect evidence, override, and escalate?
8. Which outcome and guardrail metrics passed?
9. Does performance hold across relevant groups and real conditions?
10. Who owns operations, risk, incidents, change, and retirement?

If these cannot be answered, the use case is not ready to scale.

---

# 20. Glossary

**Bounded autonomy:** Permission for an AI-enabled system to act independently within explicit limits and controls.

**Grounding:** Connecting AI output to authorized, relevant source information.

**Human–AI configuration:** The division of tasks, authority, and oversight between people and an AI system.

**Operational AI:** AI embedded in a recurring business workflow with defined ownership, controls, and outcomes.

**Shadow mode:** Live evaluation in which outputs do not influence actual decisions.

**Stage gate:** A predefined evidence and control threshold required to advance deployment.

**Workflow:** The connected sequence from trigger and information through decision, action, and outcome.

---

# 21. Reference notes and further reading

- NIST, [AI Risk Management Framework Core](https://airc.nist.gov/airmf-resources/airmf/5-sec-core/). Business context, human roles, testing, monitoring, incident response, and continual improvement.
- NIST, [AI RMF 1.0](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-1.pdf). Full voluntary framework and human–AI interaction considerations.
- NIST, [Generative AI Profile](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf). Generative-AI risk categories and suggested actions.
- International Labour Organization, [Generative AI and Jobs: A 2025 Update](https://www.ilo.org/publications/generative-ai-and-jobs-2025-update). Task-level exposure analysis and workforce implications.
- International Labour Organization, [Artificial Intelligence Adoption and Its Impact on Jobs](https://www.ilo.org/publications/artificial-intelligence-adoption-and-its-impact-jobs). Discussion of augmentation, productivity, job quality, and algorithmic management.

---

# Closing message

AI execution is disciplined organizational design. Choose a valuable workflow, assign AI a bounded task, preserve accountable human judgment, measure the whole system, build recovery into the design, and scale only after real-world evidence shows that value and controls hold together.
