# Phase 4 Modules [GROUP]

## Sustainable AI decision leadership

This file consolidates the complete Phase 4 modules in their intended learning order. The navigation table links to stable module anchors within this document.

## Module sequence

| Order | Module | Focus | Primary output |
|---:|---|---|---|
| 1 | [Module 14: Building AI-Driven Decision Habits](#module-14) | Turn AI work into a durable decision cadence with ownership, institutional memory, shared tools, and learning loops. | Decision Operating System |
| 2 | [Module 15: Executive Decision Simulation](#module-15) | Exercise executive judgment under time pressure, incomplete evidence, metric defects, stakeholder conflict, and changing facts. | Defensible Act, Delay, or Redesign decision record |
| 3 | [Module 16: AI Governance & Decision Economics](#module-16) | Integrate legal, ethical, security, data, vendor, operational, risk, and economic decisions across the AI lifecycle. | Governance framework and AI risk register |

## Progression

```text
Repeatable decision habits and ownership
    ↓
Executive judgment under pressure
    ↓
Lifecycle governance and decision economics
    ↓
Final capstone defense
```

The phase tests whether the learner can operate, challenge, govern, and economically justify an AI-enabled decision system—not merely describe one.

## Phase materials

- [Phase 4 Course Guide](phase-4-course-guide.md)
- [Phase 4 Final Capstone Workbook](phase-4-final-capstone-workbook.md)
- [Phase 4 Source Guide](phase-4-source-guide.md)
- [Source Origin Map](source-origin-map.md)

---

## Consolidated module content

<a id="module-14"></a>

# Module 14: Building AI-Driven Decision Habits

## Module purpose

AI becomes sustainable when it changes how an organization decides, executes, learns, and stops—not when it produces more reports. This module converts AI work into a repeatable decision cadence with clear ownership, shared tools, institutional memory, and defenses against common organizational failure modes.

## Learning outcomes

The learner can:

1. Design weekly, monthly, and quarterly forums with distinct decision purposes.
2. Assign a Decision Owner, Data Owner, and Execution Owner.
3. Turn metrics into decisions, commitments, and learning loops.
4. Detect dashboard theater, analysis paralysis, and data hoarding.
5. Build buy-in without diluting accountability.
6. govern shared AI tools and reusable knowledge.
7. Produce a Decision Operating System that can survive leadership turnover.

Suggested duration: two 2.5-hour sessions plus a four-week operating pilot.

---

# 1. Decision cadence

A cadence is not a calendar of meetings. It is a designed sequence that matches decision speed to evidence speed, reversibility, and consequence.

## Cadence design questions

- What changes fast enough to review weekly?
- Which outcomes require a month of data before interpretation?
- Which resource allocations should change only quarterly?
- What can be decided asynchronously?
- What event overrides the normal cadence?
- Who can call an emergency review?
- What decision expires if not revisited?

## Cadence architecture

| Forum | Primary horizon | Purpose | Typical decisions | Not for |
|---|---|---|---|---|
| Weekly operating review | 1–6 weeks | Detect, unblock, correct | Exceptions, experiments, incidents, execution trade-offs | Reopening strategy every week |
| Monthly strategy review | 1–12 months | Interpret, prioritize, adapt | Scale/pause pilots, resource shifts, policy changes | Reading every dashboard tile |
| Quarterly planning | 1–3 years | Allocate, sequence, retire | Portfolio funding, risk appetite, capability plan | Ratifying decisions already made elsewhere |
| Event-triggered review | Immediate | Contain or reconsider | Incident, control breach, legal change, major drift | Waiting for the next scheduled meeting |

Each forum must define inputs, pre-read deadline, quorum, decision rights, time box, outputs, and escalation path.

---

# 2. Weekly operating review

## Objective

Keep execution aligned with the approved decision while detecting exceptions early.

## Required pre-read

One page, distributed before the meeting:

- decisions due this week;
- KPI, counter-metric, and control status;
- material changes since last review;
- incidents, near misses, and exceptions;
- experiments reaching a decision threshold;
- blocked actions and owner requests;
- assumptions invalidated;
- decisions carried over, with reason.

## 45-minute agenda

1. **Five minutes — commitments:** What was promised? What changed?
2. **Ten minutes — exceptions:** Which thresholds were crossed?
3. **Fifteen minutes — decisions:** Choose, assign, and timestamp.
4. **Ten minutes — execution:** Resolve dependencies and capacity conflicts.
5. **Five minutes — learning:** What should be added to the knowledge base?

## Meeting outputs

- decision record;
- action, owner, and due date;
- accepted risk or escalation;
- experiment continuation or stop;
- knowledge update;
- unresolved dissent.

If the meeting produces discussion but no decision, action, escalation, or explicit “no change,” it has failed.

---

# 3. Monthly strategy review

## Objective

Determine whether the AI initiative is improving the target decision and remains strategically, economically, and ethically justified.

## Required questions

- Did the business outcome move, or only the AI activity metric?
- Is the causal story still plausible?
- Which segment improved, stagnated, or was harmed?
- What was the total operating cost, including review and rework?
- Which controls failed, generated friction, or were bypassed?
- Which assumptions changed?
- Are users adopting the workflow or creating shadow processes?
- Should scope, authority, or funding change?
- What should stop?

## Monthly decision categories

- continue within scope;
- expand a test;
- restrict a permission;
- revise workflow or policy;
- reallocate people or budget;
- commission a targeted investigation;
- pause or terminate.

The monthly forum owns interpretation and prioritization. It does not take over the Execution Owner’s daily work.

---

# 4. Quarterly planning

## Objective

Allocate scarce organizational attention, money, data, and risk capacity across the AI portfolio.

## Quarterly portfolio questions

- Which decisions create the most value if improved?
- Which AI initiatives earned the right to scale?
- Which initiatives should be retired despite sunk cost?
- Where is the portfolio overexposed to one vendor, model, dataset, or team?
- Which shared capabilities should be funded once and reused?
- What new legal, market, security, or workforce conditions change priorities?
- Which benefits were realized in finance or operations, not merely modeled?
- What is the aggregate risk and change burden across simultaneous deployments?

## Portfolio matrix

| Initiative | Decision improved | Evidence of value | Residual risk | Readiness | Dependency | Next-quarter allocation | Decision |
|---|---|---|---|---|---|---|---|

Quarterly planning must include retirement. A portfolio that only adds projects is not governed.

---

# 5. Core ownership model

## Decision Owner

Accountable for the business decision and its consequences.

Responsibilities:

- approves the decision statement and acceptable trade-offs;
- determines when evidence is sufficient;
- chooses Act, Delay, or Redesign;
- accepts residual business risk within delegated authority;
- resolves cross-functional conflict;
- signs the decision record.

The Decision Owner cannot delegate accountability to the model, analyst, vendor, or committee.

## Data Owner

Accountable for a defined data domain and its permitted use.

Responsibilities:

- defines meaning, authoritative source, and quality thresholds;
- approves access and purpose within policy;
- ensures lineage, classification, retention, and deletion;
- resolves competing definitions;
- discloses limitations and known quality issues;
- coordinates with privacy, security, and records owners.

The Data Owner does not decide the business action solely because the data belongs to their domain.

## Execution Owner

Accountable for turning the decision into operational results.

Responsibilities:

- converts the decision into plan, capacity, milestones, and dependencies;
- operates controls and escalation paths;
- tracks adoption, exceptions, and counter-metrics;
- reports execution truth, including failure;
- coordinates incident containment and recovery;
- returns outcome evidence to the Decision Owner.

The Execution Owner cannot redefine success after implementation.

## Required supporting roles

| Role | Accountability |
|---|---|
| AI System Owner | Performance, configuration, change control, and technical lifecycle |
| Risk/Compliance Owner | Applicable obligations, control assurance, and risk escalation |
| Security Owner | Threat model, access, monitoring, response, and recovery |
| Finance Partner | Cost baseline, benefit realization, and accounting treatment |
| Affected-party advocate | Impact, usability, accessibility, contestability, and remedy |

## Ownership test

Ask each named owner separately:

1. What can you approve without another committee?
2. What evidence must you receive?
3. What threshold forces escalation?
4. What can you stop?
5. What failure are you personally accountable for explaining?

If the answers conflict, ownership is not yet real.

---

# 6. Dashboard theater

Dashboard theater occurs when the display of metrics substitutes for a decision process.

## Warning signs

- more than one screen of “key” metrics;
- no metric owner or decision linked to a metric;
- status colors without thresholds or response rules;
- activity counts presented as outcomes;
- averages without distributions or segments;
- targets changed after results arrive;
- stale data with a real-time visual design;
- no counter-metrics or control indicators;
- executives read numbers aloud instead of making choices;
- identical dashboard for every audience.

## Metric-to-decision contract

| Metric | Definition | Owner | Decision informed | Threshold | Response | Counter-metric | Review cadence |
|---|---|---|---|---|---|---|---|

Delete any metric that has no plausible decision user unless it is a required control or diagnostic measure.

## Exercise: destroy the dashboard

Give the learner a 24-tile executive dashboard. Require them to retain no more than:

- one north-star outcome;
- three to five drivers;
- two to four counter-metrics;
- critical control and incident indicators;
- one distributional view.

For every retained metric, demand the decision it changes.

---

# 7. Analysis paralysis

Analysis paralysis is not “too much rigor.” It is failure to convert uncertainty into a bounded decision.

## Causes

- unclear Decision Owner;
- no decision deadline;
- irreversible framing of a reversible choice;
- request for certainty instead of risk tolerance;
- broad data gathering with no value-of-information test;
- fear of political accountability;
- conflicting stakeholder incentives;
- no default action if the deadline passes.

## Countermeasures

- classify the decision as reversible, difficult to reverse, or irreversible;
- define the minimum evidence threshold before analysis;
- use downside limits, pilot scope, staged funding, and stop rules;
- price delay and missed opportunity;
- request data only when it can change a branch;
- document dissent and let the authorized owner decide;
- set an expiry date for the decision.

## Decision deadline template

> By **[date]**, **[Decision Owner]** will choose **[alternatives]** for **[scope]**. The minimum evidence is **[thresholds]**. If evidence remains incomplete, the default is **[action]** because **[risk rationale]**. The decision will be reviewed on **[date/event]**.

---

# 8. Data hoarding

Data hoarding is the accumulation or restriction of data without a justified decision purpose. It appears both as “collect everything” and “share nothing.”

## Why it happens

- data is treated as political power;
- ownership and stewardship are confused;
- teams fear blame for quality issues;
- access processes are slow or arbitrary;
- future AI value is used to justify indefinite retention;
- no shared definitions or data contracts exist;
- incentives reward local control instead of enterprise outcomes.

## Sustainable response

- define data products or domains with accountable owners;
- require purpose, minimum fields, duration, and authorized users;
- offer tiered access: aggregate, masked, pseudonymized, row-level;
- log and review access;
- publish definitions, quality, lineage, and limitations;
- create time-bound research environments;
- enforce deletion and revoke unused access;
- reward documented reuse and quality improvement.

Data democratization does not mean universal raw-data access. It means governed, proportionate access to decision-relevant evidence.

---

# 9. Buy-in without governance by consensus

Buy-in is willingness and capability to enact a decision. It is not unanimous approval.

## Stakeholder map

| Stakeholder | Gains | Burdens/risks | Authority | Evidence they trust | Likely resistance | Engagement |
|---|---|---|---|---|---|---|

## Sources of resistance

- rational concern about harm, workload, job security, or accountability;
- loss of professional discretion or status;
- poor workflow fit;
- prior transformation failure;
- metrics that punish honest reporting;
- exclusion from design;
- hidden disagreement about the problem;
- misinformation or capability gaps.

## Buy-in sequence

1. Name the decision and non-negotiable constraints.
2. Involve people who know the work and those who bear errors.
3. Surface losses, not only benefits.
4. Separate consult, recommend, approve, execute, and appeal rights.
5. Demonstrate with representative cases.
6. Provide training, time, support, and fallback.
7. measure adoption quality and workarounds, not logins alone.
8. Close the feedback loop publicly.

The mentor must ask: “Whose buy-in do you want because they have essential knowledge, and whose buy-in do you want because you fear opposition?”

---

# 10. Shared AI tools

An organization should make the safe path easier than shadow AI.

## Shared tool portfolio

- approved general-purpose assistant;
- domain assistants with governed sources;
- prompt and evaluation library;
- workflow automation platform;
- model gateway or approved provider catalog;
- secure sandbox for experimentation;
- monitoring and evaluation service;
- incident and feedback channel;
- searchable knowledge repository.

## Minimum product requirements

- clear permitted and prohibited uses;
- identity, role-based access, and offboarding;
- data-use and retention settings;
- model/version visibility;
- source citation where relevant;
- feedback and escalation;
- audit events proportionate to risk;
- accessibility and user support;
- evaluation before material changes;
- export and exit path.

## Centralize or federate?

Centralize controls, reusable infrastructure, vendor assurance, and minimum standards. Federate domain decisions, local knowledge, workflow design, and outcome ownership. Centralization without domain authority creates bottlenecks; federation without standards creates unmanaged risk and duplication.

---

# 11. Knowledge sharing

Knowledge sharing converts individual experiments into organizational capability.

## What to preserve

- approved prompts and known limitations;
- evaluation sets and failure examples;
- decision records and outcome reviews;
- metric definitions and data contracts;
- workflow patterns and control designs;
- vendor findings and contract constraints;
- incidents, near misses, and corrective actions;
- reusable code, connectors, and templates;
- retired approaches and why they failed.

## Knowledge quality rules

Every item needs an owner, scope, effective date, source, status, review date, and retirement path. Searchability without authority creates a faster route to outdated advice.

## Learning review

After every material decision, incident, or experiment:

1. What did we expect?
2. What happened?
3. What did we misunderstand?
4. Which artifact, control, or assumption changes?
5. Who else needs this knowledge?
6. When will the change be verified?

Avoid blame-free language that erases accountability. The review should be psychologically safe and factually demanding.

---

# 12. Module project: Decision Operating System

## Required components

1. Decision inventory and prioritization method.
2. Weekly, monthly, quarterly, and event-triggered forum charters.
3. Decision/Data/Execution Owner matrix.
4. Decision record template and repository rules.
5. KPI-to-decision contract.
6. escalation, exception, dissent, and expiry rules.
7. Shared AI tool catalog and access model.
8. Knowledge architecture and review process.
9. Adoption, training, and change plan.
10. Four-week pilot with at least three real or simulated decisions.

## Stress tests

- The Decision Owner misses two meetings.
- Finance and Operations use different denominators.
- A senior executive asks for a metric to be removed.
- A regional leader refuses to share data.
- A popular assistant is found to use an unapproved model.
- A pilot improves speed but worsens appeal outcomes.
- A control creates a queue that erases the projected value.
- The sponsor leaves the company.

## Completion standard

Another leadership team can operate the cadence, trace decisions to evidence and owners, detect exceptions, and preserve learning without relying on the learner’s personal memory or influence.

<a id="module-15"></a>

# Module 15: Executive Decision Simulation

## Module purpose

This module trains executive judgment under time pressure, incomplete evidence, stakeholder conflict, and changing facts. The learner must verify claims before acting, refuse invalid comparisons, identify what is missing, and still make a proportionate decision.

## Learning outcomes

The learner can:

1. Lead an executive data review without being controlled by the deck.
2. Reconstruct material metrics from definition to source.
3. detect denominator, segmentation, and time-window errors.
4. separate bias, confounding, uncertainty, and missing evidence.
5. choose Act, Delay, or Redesign.
6. request targeted additional data using value-of-information logic.
7. document dissent, assumptions, and decision conditions.

Suggested duration: three 2-hour simulations plus individual preparation.

---

# 1. Executive data review protocol

Use six passes. Do not debate the recommendation before completing the first three.

## Pass 1 — Decision

- What exact decision is due?
- Who owns it?
- What is the deadline?
- What alternatives exist, including doing nothing?
- Is the decision reversible?
- What is the cost of delay?

## Pass 2 — Claim

- What are the three claims that carry the recommendation?
- Are they facts, calculations, interpretations, forecasts, or assumptions?
- Which claim would most change the decision if false?

## Pass 3 — Metric

- definition;
- unit of analysis;
- numerator and denominator;
- source and lineage;
- inclusion and exclusion rules;
- time window;
- missing-data treatment;
- segments;
- uncertainty;
- owner and reproduction status.

## Pass 4 — Explanation

- What mechanism is proposed?
- What rival explanations fit the evidence?
- What changed at the same time?
- What selection effects exist?
- Is causality necessary for this decision?

## Pass 5 — Consequence

- Who gains and who bears errors?
- What is the downside magnitude and detectability?
- What happens under a plausible worst case?
- Can the action be staged, contained, or reversed?

## Pass 6 — Decision

- Act, Delay, or Redesign?
- scope, owner, resources, controls, and deadline;
- evidence to monitor;
- stop, escalation, or review trigger;
- dissent recorded.

---

# 2. Metric verification

## Metric verification card

| Field | Required entry |
|---|---|
| Metric name | Human-readable name |
| Decision use | Exact choice it informs |
| Definition | Operational specification |
| Numerator | Events/value counted |
| Denominator | Eligible population/exposure |
| Unit | Case, customer, day, dollar, agent, etc. |
| Population | Inclusion/exclusion rules |
| Time | Event time, processing time, cohort, and lag |
| Segments | Required cuts and suppression rules |
| Source/lineage | System, table, transformation, version |
| Quality | Missingness, duplication, timeliness, known error |
| Reproduction | Independent check and date |
| Owner | Person accountable for definition and quality |

## Verification sequence

1. Read the written definition before viewing the chart.
2. Recompute one central number from source or a traceable extract.
3. Reconcile totals to an authoritative system.
4. inspect exclusions and missing records.
5. compare a small sample of source records manually.
6. check whether definition or instrumentation changed.
7. ask the Data Owner to sign the metric card.

AI may help generate queries and checks. It does not certify correctness.

---

# 3. Denominators

The denominator defines who or what had the opportunity to experience the event.

## Common failures

- complaints per customer versus per transaction;
- errors per reviewed case versus all eligible cases;
- adoption among invited users versus active users;
- incident counts without exposure volume;
- conversion among visitors versus qualified leads;
- savings per automated case excluding exceptions;
- fairness rate using different eligibility criteria across groups;
- reopened cases divided by cases resolved in a different period.

## Denominator interrogation

- Who could have entered the numerator?
- Who was excluded and why?
- Is exposure equal across segments?
- Does the denominator change over time?
- Are repeated events attached to a person, case, or opportunity?
- Is the denominator observed, estimated, or inferred?
- Would another reasonable denominator reverse the recommendation?

## Exercise

“False denial fell by 40%.” The learner must refuse to interpret the claim until given counts and eligible cases for both periods, selection into review, confidence intervals, and segment definitions.

---

# 4. Segmentation

Aggregate performance is a starting point, not a conclusion.

## Candidate segments

- customer need or eligibility;
- product, channel, geography, or language;
- new versus repeat users;
- workflow path and exception type;
- case complexity or value at risk;
- protected or sensitive group where lawful and appropriate;
- model, prompt, source, or configuration version;
- human reviewer, team, tenure, or workload;
- before/after policy or process changes.

## Segment discipline

- pre-specify critical segments when possible;
- show counts and uncertainty;
- suppress or aggregate unsafe small cells;
- correct or validate after extensive subgroup searching;
- do not infer personal characteristics casually;
- distinguish diagnostic analysis from decisions about people;
- investigate both performance disparity and burden disparity.

## Simpson’s paradox drill

Provide two regions where the AI workflow performs better within each case-complexity tier but worse in aggregate because the AI receives more complex cases. The learner must identify the composition shift and refuse the aggregate comparison.

---

# 5. Time windows

Time choices can manufacture a result.

## Required time concepts

- event date versus record date;
- cohort window versus observation window;
- calendar time versus elapsed time;
- lag between action and outcome;
- seasonality and business cycle;
- ramp, learning, and novelty effects;
- policy, model, or instrumentation change points;
- censoring of cases whose outcome has not matured.

## Time-window challenge

For every before/after chart ask:

- Why does the window start there?
- Are both periods comparable in length and season?
- Are late-arriving outcomes complete?
- Did user mix, policy, or capacity change?
- Does the result persist with alternative reasonable windows?
- Was the cutoff selected after seeing the result?

---

# 6. Bias

Bias is systematic distortion or uneven impact. It is not limited to model training.

## Executive bias map

| Layer | Example | Executive question |
|---|---|---|
| Framing | Optimize speed while ignoring denial quality | Whose outcome is absent? |
| Sampling | Pilot uses high-performing teams | Who was selected out? |
| Measurement | Appeals used as proxy for wrong decisions | Who cannot or will not appeal? |
| Historical data | Past exceptions reflect unequal discretion | Are labels normatively acceptable? |
| Model | Error differs by language | Which groups bear failure? |
| Interface | Recommendation shown before evidence | Does design create automation bias? |
| Workflow | Humans review only low-confidence cases | Is performance compared on equivalent cases? |
| Feedback | Denied cases generate less future data | Does deployment change the evidence? |
| Presentation | Average hides regional harm | What distribution is concealed? |
| Governance | Affected people cannot contest | What remedy exists? |

The learner must distinguish statistical disparity, operational inequity, unlawful discrimination, and ethical concern. They may overlap, but they are not interchangeable conclusions.

---

# 7. Confounders

A confounder influences both the apparent cause and outcome, creating or distorting an association.

## Confounder search

Ask what also changed in:

- customer or case mix;
- staffing, training, incentives, or workload;
- policy and eligibility rules;
- channel routing;
- product quality or seasonality;
- system instrumentation;
- macroeconomic or competitor conditions;
- reviewer behavior caused by the pilot;
- escalation criteria;
- capacity and queue length.

## Executive response

Do not demand a perfect causal estimate when a safe reversible pilot is enough. Do demand stronger identification before an irreversible, high-cost, or high-impact scale decision.

Possible responses:

- randomization or phased rollout;
- matched comparison;
- difference-in-differences with assumptions checked;
- interrupted time series;
- regression or stratification;
- negative controls;
- sensitivity analysis;
- qualitative process investigation.

Method names do not establish validity. The learner must state assumptions and failure modes.

---

# 8. Evidence gaps

## Gap categories

- definition gap;
- data-quality or lineage gap;
- representativeness gap;
- causal gap;
- subgroup or affected-party gap;
- security/control gap;
- legal or consent gap;
- economics or adoption gap;
- operational capacity gap;
- future-drift gap.

## Evidence-gap register

| Gap | Why it matters | Decision branch affected | Current proxy | How to close | Cost/time | Owner | Deadline | If unresolved |
|---|---|---|---|---|---|---|---|---|

Not all gaps deserve closure. Some are immaterial; some can be bounded by controls; some make action unacceptable.

---

# 9. Act / Delay / Redesign framework

## Act

Choose **Act** when:

- the decision is sufficiently defined;
- evidence meets the pre-agreed threshold;
- downside fits risk appetite;
- critical controls are effective;
- ownership and capacity exist;
- action can be monitored and adapted.

Act may mean a bounded pilot, not full scale.

## Delay

Choose **Delay** only when:

- a specific missing fact can materially change the choice;
- the fact can be obtained within a defined time;
- delay costs less than the expected decision improvement;
- interim risk is controlled;
- a decision date and default action are set.

“We need more data” without these conditions is avoidance.

## Redesign

Choose **Redesign** when the current decision or intervention cannot be responsibly evaluated or controlled, but the underlying problem remains valuable.

Redesign may change:

- decision statement;
- target population or scope;
- human/AI authority;
- workflow and escalation;
- metric or experiment;
- data source;
- vendor or architecture;
- commercial model;
- remedy or affected-party process.

## Decision matrix

| Evidence adequacy | Consequence/reversibility | Control readiness | Default |
|---|---|---|---|
| High | Low consequence/reversible | Adequate | Act |
| Moderate | Reversible and bounded | Adequate | Act as pilot |
| Low but decision-relevant gap is closable | Any | Interim controls exist | Delay with deadline |
| Evidence structurally mismatched | Any | Any | Redesign |
| Adequate evidence of unacceptable harm or poor value | Any | Any | Do not proceed |

---

# 10. Additional data requests

## Value-of-information test

Before requesting data, state:

1. the uncertain claim;
2. the decision alternatives it affects;
3. the possible findings;
4. how each finding changes the decision;
5. collection cost, delay, privacy, and security burden;
6. minimum sample or evidence standard;
7. owner and delivery date;
8. default if unavailable.

## Request template

> To decide between **[A]** and **[B]**, we need **[specific field/analysis]** for **[population]** over **[window]**, segmented by **[dimensions]**, because a result above/below **[threshold]** would change the recommendation from **[branch]** to **[branch]**. The Data Owner is **[name]**; delivery is **[date]**; if unavailable, we will **[default]**.

Reject “all available customer data,” “a bigger sample,” and “more granular data” unless the decision logic is explicit.

---

# 11. Simulation 1: The irresistible dashboard

## Scenario

The COO requests immediate global scale after a pilot dashboard shows:

- handling time down 31%;
- reopening down 33%;
- accuracy at 93%;
- adoption at 76%;
- projected savings of $2.4 million.

## Hidden evidence releases

Release one every eight minutes:

1. escalated cases are excluded from handling time;
2. reopening windows differ;
3. accuracy comes from vendor-curated cases;
4. two pilot teams received extra staffing;
5. usage is measured as one login per week;
6. savings assumes headcount removal;
7. one language segment shows twice the false-denial rate.

## Learner task

Lead a 30-minute review and issue an Act, Delay, Redesign, or stop decision with owners and conditions.

## Pass standard

The learner reconstructs at least the three pivotal metrics, identifies the invalid comparisons, protects the harmed segment, and does not let deadline pressure erase evidence integrity.

---

# 12. Simulation 2: Growth versus consent

## Scenario

The Chief Growth Officer proposes using support transcripts and CRM notes to personalize retention offers. The prototype suggests a 6% conversion lift.

Stakeholder conflict:

- Growth wants to launch before a seasonal peak.
- Legal questions whether the new use matches the collection context.
- Data Science says names can be removed.
- Customer Support warns transcripts contain intimate and financial details.
- CFO estimates a four-week delay costs $900,000 in opportunity.
- A competitor has already launched a similar feature.

## Required issues

- purpose and lawful/authorized basis;
- meaningful consent where applicable;
- de-identification limits;
- minimum necessary fields;
- sensitive inferences;
- fairness and vulnerable customers;
- notice, opt-out, and contestability;
- validity of the 6% estimate;
- alternative design using less data.

## Ethical dilemma

Would the recommendation change if the system is legally permissible but customers would reasonably feel betrayed when the use is explained plainly?

---

# 13. Simulation 3: Security incident during scale vote

## Scenario

Ten minutes before the board vote, Security reports that a retrieved vendor document contained an indirect prompt injection. In testing, the assistant attempted to expose system instructions and generated an unauthorized action request. No confirmed customer data left the environment.

## Pressure

- CEO wants to characterize it as a test-only issue.
- CTO says a patch is available.
- Legal wants facts preserved and external obligations assessed.
- Operations cannot return to the old workflow without a backlog.
- Vendor requests 48 hours to investigate.
- An investor asks whether management previously overstated readiness.

## Learner task

Decide containment, communication, evidence preservation, workflow fallback, board disclosure, vendor demand, and criteria to resume.

---

# 14. Simulation scoring

Score 0–4 on:

- decision framing;
- metric verification;
- denominator discipline;
- segmentation and time logic;
- bias and confounder analysis;
- evidence-gap prioritization;
- value-of-information requests;
- stakeholder and ethical judgment;
- decisiveness under uncertainty;
- decision record quality.

## Automatic failure behaviors

- repeats an unverified metric as fact;
- hides or dismisses material segment harm;
- requests broad data without purpose or authority;
- assigns accountability to “the team”;
- approves action without a control for a known critical risk;
- delays without deadline, owner, or default;
- claims causality from a simple before/after comparison;
- treats legal approval as ethical sufficiency.

## Completion artifact

Submit three decision records, metric verification cards, an evidence-gap register, and a short reflection naming one judgment error the learner made and the operating change that prevents recurrence.

<a id="module-16"></a>

# Module 16: AI Governance & Decision Economics

## Module purpose

Governance is the operating system that lets an organization pursue AI value within its obligations and risk appetite. It is not a policy binder and it is not synonymous with compliance. This module integrates data, vendor, model, security, legal, ethical, operational, and economic decisions across the AI lifecycle.

## Learning outcomes

The learner can:

1. Classify data and apply purpose, access, consent, retention, and minimum-necessary controls.
2. Evaluate AI vendors across technology, data, operations, economics, and exit risk.
3. Identify model, system, human, and organizational risks.
4. distinguish security, privacy, legal, compliance, ethics, and enterprise risk questions.
5. Design meaningful human oversight, traceability, logging, and audit.
6. Build and test an AI incident response plan.
7. operationalize transparency, fairness, explainability, and contestability.
8. combine risk-adjusted value, control cost, and option value in an investment decision.
9. Produce a governance framework and risk register that drive real decisions.

Suggested duration: three 2.5-hour sessions plus one incident tabletop.

> This module provides a governance method, not jurisdiction-specific legal advice. Applicable law and regulatory duties must be determined with qualified counsel for the organization, use case, people, sector, and geography.

---

# 1. Governance starts with context

Before selecting controls, document:

- business purpose and prohibited purposes;
- decision and affected parties;
- system role: retrieve, generate, predict, recommend, decide, or act;
- consequence and reversibility of error;
- data categories and flows;
- provider, deployer, user, and downstream roles;
- jurisdictions and sector obligations;
- supply chain and subprocessors;
- human authority, appeal, and remedy;
- risk appetite and escalation thresholds;
- lifecycle stage and change frequency.

A low-risk writing assistant and an employment-screening system should not have the same approval path. A common baseline is useful; controls must remain context-dependent.

---

# 2. Governance architecture

## Three lines of accountability

1. **Business and technology owners** operate the system, controls, and outcomes.
2. **Risk, privacy, security, legal, and compliance functions** set standards, advise, challenge, and monitor.
3. **Independent assurance or audit** tests whether design and operation match claims.

Independence is lost when the same person designs a control, approves the exception, and certifies effectiveness.

## Decision rights

| Decision | Recommends | Approves | Executes | Challenges/assures | Can stop |
|---|---|---|---|---|---|
| Use-case intake | Product/business | Decision Owner | Product | Risk functions | Risk executive for hard stop |
| Data use/access | Product + Data Owner | Authorized data/privacy owner | Platform/data team | Privacy/security | Data/privacy owner |
| Pilot | Cross-functional review | Delegated sponsor | Execution Owner | Legal/security/risk | Incident or risk owner |
| Scale | Portfolio committee | Executive owner | Business + technology | Independent assurance | Named executives |
| Material change | System Owner | Defined by change tier | Engineering/operations | Relevant reviewers | Change authority |
| Incident resume | Incident lead | Authorized business/risk owner | Operations | Legal/security/compliance | Designated authority |
| Retirement | System + business owner | Decision Owner | Operations/technology | Records/privacy/security | Decision Owner |

## Lifecycle gates

- intake and prohibited-use screen;
- impact and risk classification;
- data and vendor approval;
- design and threat review;
- evaluation and control validation;
- limited pilot approval;
- scale approval;
- continuous monitoring and material-change review;
- incident, suspension, and reauthorization;
- retirement, deletion, and records closure.

---

# 3. Data sensitivity

Sensitivity depends on context, combination, inference, and consequence—not only field labels.

## Practical classification

| Level | Examples | Default handling |
|---|---|---|
| Public | Approved public content | Integrity and license checks |
| Internal | Policies, ordinary operational data | Workforce access; approved services |
| Confidential | Commercial plans, contracts, nonpublic performance | Need-to-know, encryption, logging |
| Restricted | PII, credentials, regulated or highly sensitive data | Explicit authorization, strong controls, narrow purpose |
| Prohibited for tool/use | Secrets or categories the system may not process | Block, detect, report, and remediate |

## Context escalation

Raise sensitivity when data:

- can be linked back to a person;
- reveals or enables sensitive inference;
- is combined with another dataset;
- concerns children or vulnerable people;
- affects employment, credit, health, education, housing, safety, or rights;
- contains credentials, security architecture, or trade secrets;
- is subject to contract, localization, privilege, or sector rules;
- can cause material harm if inaccurate as well as if disclosed.

The governance inventory must include prompts, retrieved context, outputs, embeddings, logs, annotations, feedback, evaluation sets, and backups—not only training data.

---

# 4. Access control

Use least privilege, purpose limitation, separation of duties, and time-bounded access.

## Access design

- authenticate users and services;
- authorize by role, attribute, task, and data scope;
- separate read, recommend, approve, and execute permissions;
- isolate development, testing, and production;
- prevent a model from inheriting the requesting user’s broadest access;
- use short-lived credentials and managed secrets;
- review privileged and dormant access;
- revoke access on role change or offboarding;
- log sensitive access and investigate anomalies;
- require step-up approval for exceptional actions.

## AI-specific access problem

Retrieval can expose a document a user could not find manually but is technically allowed to access. Authorization at query time, source-level permissions, result filtering, and leakage tests are required. Security through obscurity is not access control.

---

# 5. PII, consent, and purpose

## PII and linkability

Personally identifiable information includes direct identifiers and data that can reasonably identify or be linked to a person in context. Pseudonymization reduces some risk but is not the same as anonymization. Free text often contains unexpected identifiers.

## Purpose test

For each data use record:

- original collection context;
- proposed AI purpose;
- legal/authorized basis;
- compatibility with expectations and commitments;
- necessity and proportionality;
- parties receiving or processing data;
- notice and rights;
- alternative using less or different data;
- decision and approver.

## Consent

Where consent is relied upon, test whether it is informed, specific, freely given where required, understandable, documented, and withdrawable without deceptive friction. Consent is not a universal remedy for an unnecessary or unfair system.

Do not infer “consent” from silence, bundled terms, employment power imbalance, or the mere fact that data exists.

---

# 6. Retention and deletion

“Keep it because it may help a future model” is not a retention policy.

## Retention schedule fields

| Data/artifact | Purpose | System of record | Owner | Trigger | Period | Legal hold | Deletion method | Verification |
|---|---|---|---|---|---|---|---|---|

Cover:

- raw inputs and attachments;
- prompts and conversation history;
- model outputs;
- retrieval indexes and embeddings;
- evaluation and annotation data;
- operational and security logs;
- decision and approval records;
- backups and vendor copies;
- derived features and cached data.

Deletion must propagate to replicas and vendors as contractually and technically possible. Where deletion from a trained model is not practicable, the decision must be addressed before training, not discovered after a request.

---

# 7. Minimum necessary principle

Use the least data, precision, people, time, access, and model capability needed for the purpose.

## Minimum-necessary challenge

For every field ask:

1. Which system behavior uses it?
2. What decision quality changes without it?
3. Can an aggregate, band, mask, token, or derived feature work?
4. Can processing occur locally or in a controlled boundary?
5. Who needs raw values?
6. How long is it needed?
7. What new harm becomes possible by including it?

Run an ablation test: remove the field or reduce precision and measure whether performance changes enough to justify the added exposure.

---

# 8. AI vendor evaluation

A vendor assessment is a decision about dependency, control, and exit—not a feature comparison.

## Evaluation domains

| Domain | Questions | Evidence |
|---|---|---|
| Corporate/financial | Can the vendor sustain service and obligations? | Ownership, financial condition, insurance, references |
| Product fit | Does it solve the defined task under real constraints? | Trial on representative cases |
| Model/system | Which models, versions, limits, and change policies? | Model/system cards, evals, release process |
| Data | What is collected, used, retained, localized, or shared? | Data flow, contract, subprocessor list |
| Security | How are identity, encryption, isolation, vulnerabilities, and incidents handled? | Architecture, tests, certifications, incident terms |
| Privacy | What roles, rights support, deletion, and transfer mechanisms exist? | DPA, privacy documentation, operational test |
| Legal/IP | Who owns inputs/outputs; what indemnity and restrictions apply? | Contract terms, counsel review |
| Responsible AI | How are safety, bias, transparency, and abuse evaluated? | Methods, results, limitations, governance |
| Operations | What availability, support, monitoring, change notice, and recovery exist? | SLA, runbooks, status history |
| Economics | What drives cost and variance? | Unit pricing, minimums, egress, services, scenarios |
| Exit | Can data, prompts, evaluations, and workflow be moved? | Export test, deletion certificate, transition terms |

## Vendor red flags

- refuses to describe subprocessors or data use;
- can change material behavior without notice;
- uses broad rights to customer data;
- offers benchmark claims without methods or denominators;
- treats certifications as proof of use-case safety;
- cannot support deletion, access review, or incident evidence;
- has no tested fallback or export path;
- contract caps liability far below plausible exposure;
- roadmap promises replace current controls;
- demo data is cleaner than operational data.

## Proof-of-control tests

- retrieve only records the test user may access;
- submit deletion and export requests;
- trigger a failed tool call and observe recovery;
- change model or configuration in a test environment;
- simulate provider outage and quota limit;
- test prompt injection and sensitive-data leakage;
- request evidence needed for an incident investigation;
- calculate cost under downside volume and review scenarios.

---

# 9. Model and system risks

## Risk taxonomy

- incorrect or fabricated output;
- overconfidence and poor calibration;
- harmful or prohibited content;
- prompt injection and tool manipulation;
- sensitive-data disclosure or memorization;
- retrieval of stale, malicious, or unauthorized sources;
- unfair or uneven error and burden;
- distribution, concept, policy, and behavior drift;
- brittle performance under novel inputs;
- automation bias and skill degradation;
- feedback loops and self-reinforcing labels;
- excessive agency, privilege, or action speed;
- model/provider update without adequate re-evaluation;
- dependency, outage, rate, latency, and cost volatility;
- evaluation contamination and benchmark gaming;
- provenance, copyright, or content authenticity issues.

## Control hierarchy

Prefer controls in this order where feasible:

1. avoid the unsuitable use;
2. reduce scope, sensitivity, or authority;
3. use deterministic rules or trusted sources;
4. prevent through access, architecture, validation, and isolation;
5. detect through tests, monitoring, review, and feedback;
6. contain through limits, queues, sandboxing, and kill switches;
7. correct through appeal, rollback, remediation, and learning;
8. transfer limited financial exposure contractually or through insurance.

Human review is one control, not a universal control.

---

# 10. Security

Apply security across the full system and supply chain.

## Threat surfaces

- user prompt and uploaded content;
- retrieved documents and external websites;
- training, fine-tuning, and evaluation pipelines;
- APIs, tools, plugins, and agents;
- identities, secrets, and service accounts;
- vector stores, caches, logs, and telemetry;
- model artifacts and dependencies;
- user interface and approval design;
- vendor administration and support access;
- output consumed by downstream code or people.

## Minimum security plan

- asset and data-flow inventory;
- threat model including foreseeable misuse;
- secure configuration and change control;
- input/content handling and injection defense;
- output validation and encoding;
- least privilege and action limits;
- dependency and supplier management;
- vulnerability reporting and remediation;
- monitoring, anomaly detection, and alert ownership;
- backups, fallback, recovery, and exercise schedule;
- red-team and adversarial evaluation proportionate to risk.

Treat model output as untrusted input to downstream systems.

---

# 11. Compliance, legal, ethics, and enterprise risk

These perspectives overlap but ask different questions.

| Perspective | Core question |
|---|---|
| Compliance | Which binding rules and internal policies apply, and can conformity be evidenced? |
| Legal | What rights, duties, liability, privilege, contract, IP, labor, and litigation issues exist? |
| Privacy | How does data processing affect people, and how is personal data governed? |
| Security | How can confidentiality, integrity, availability, and control be compromised? |
| Ethics/responsible AI | Is the use legitimate, proportionate, fair, transparent, and contestable beyond minimum legality? |
| Enterprise risk | How does uncertainty affect objectives, capital, reputation, resilience, and risk appetite? |

Legal approval does not establish ethical legitimacy or business value. Ethical concern does not by itself specify legal status. Record both.

## Jurisdiction map

| Jurisdiction/sector | Organizational role | System/use classification | Data/people in scope | Obligations | Effective dates | Owner | Counsel confirmation |
|---|---|---|---|---|---|---|---|

Review at intake, before launch, before geographic expansion, and after a material legal or product change.

---

# 12. Human oversight

Meaningful oversight requires capability, information, authority, time, incentives, and evidence.

## Oversight design

Specify:

- which outputs or cases are reviewed;
- whether review is before or after action;
- evidence shown to the reviewer;
- uncertainty and limitations disclosed;
- independent information available;
- actions: accept, edit, reject, escalate, pause, reverse;
- review time and workload;
- competence and training;
- disagreement and override capture;
- quality sampling of accepted and rejected outputs;
- protection against retaliation for escalation;
- escalation and appeal routes.

## Oversight failure modes

- rubber-stamping plausible output;
- reviewer sees only the model conclusion;
- volume makes genuine review impossible;
- automation bias or fear of disagreeing;
- human becomes accountable without authority;
- only low-confidence outputs are reviewed, hiding confident errors;
- reviewer edits are not measured;
- override rate is treated as performance without checking correctness.

Test oversight with realistic workload and deliberate model errors.

---

# 13. Audit trail and logging

## Audit trail

An audit trail reconstructs governance and decision history: approvals, versions, evidence, exceptions, changes, and outcomes.

## Operational logging

Logging captures system events needed for performance, security, investigation, and recovery.

## Minimum traceability fields

- request/case identifier;
- timestamp and environment;
- authorized user/service and role;
- model/provider/version/configuration;
- prompt or instruction version;
- source identifiers and effective versions;
- relevant tool calls, parameters, and results;
- validation and policy-check results;
- output and confidence/uncertainty signals where meaningful;
- human review, edit, override, and approval;
- final action and downstream result;
- exception or incident link.

## Logging trade-offs

Logs can themselves expose sensitive data. Define purpose, minimization, access, integrity, retention, monitoring, and legal hold. Do not log secrets. Hashing or redaction must preserve sufficient investigative value.

## Audit questions

- Can we reproduce why a decision occurred?
- Can we identify everyone and every system that touched it?
- Can we distinguish the original record from later edits?
- Can we find all cases affected by a bad configuration or source?
- Can we prove controls operated, not merely existed on paper?

---

# 14. Incident response

## AI incident definition

An AI incident or near miss may involve harm, policy breach, unauthorized disclosure/action, material performance failure, unfair impact, security compromise, loss of availability, misleading content, control failure, or inability to reconstruct an event.

## Response lifecycle

1. **Prepare:** owners, severity, contacts, evidence, fallback, exercises.
2. **Detect and report:** user, monitoring, vendor, or external signal.
3. **Triage:** scope, affected parties, ongoing harm, legal duties.
4. **Contain:** suspend action, revoke access, isolate source, switch fallback.
5. **Preserve:** prompts, logs, versions, records, decisions, and timeline.
6. **Investigate:** root cause, affected cases, control failures, supplier role.
7. **Communicate:** internal leadership, affected parties, customers, regulators, insurer, vendor as applicable.
8. **Correct and remediate:** fix, reverse, notify, compensate, retrain, or redesign.
9. **Recover:** validate before resuming; stage reintroduction.
10. **Learn:** update controls, tests, risk register, training, and knowledge base.

## Severity dimensions

- actual and potential harm;
- people and records affected;
- sensitivity and rights involved;
- duration and ongoing exposure;
- system authority and reach;
- reversibility and remedy;
- legal/reporting consequence;
- evidence integrity and uncertainty.

## Tabletop injects

- logs omit the model version;
- vendor classifies the issue differently;
- affected cases span two jurisdictions;
- rollback increases operational backlog;
- a journalist contacts Communications;
- the same vulnerability exists in another assistant;
- an executive asks to resume before root cause is known.

---

# 15. Responsible AI

Responsible AI is the demonstrated alignment of purpose, process, performance, impact, and accountability with organizational values, rights, and obligations.

## Operational questions

- Is the purpose legitimate and proportionate?
- Is AI necessary or materially better than alternatives?
- Are affected people represented in design and review?
- Are benefits and burdens distributed acceptably?
- Can people know, understand, challenge, and obtain remedy?
- Is performance adequate in context, including relevant segments?
- Are security, privacy, safety, and resilience maintained?
- Are owners accountable across the lifecycle?
- Is evidence available for independent challenge?

A principles statement without thresholds, owners, tests, and remedies is branding.

---

# 16. Transparency

Transparency must be audience-specific and useful.

| Audience | Needed transparency |
|---|---|
| Affected person | AI involvement, purpose, data use, meaningful factors, rights, challenge route |
| User/reviewer | capability, limitations, sources, uncertainty, required checks |
| Executive | value, risk, assumptions, incidents, ownership, residual exposure |
| Auditor/regulator | lifecycle documentation, evidence, logs, controls, changes, outcomes |
| Public/partner | proportionate description of use, safeguards, and accountability |

Do not disclose details that create security risk or violate others’ privacy. “Proprietary” is not a blanket reason to deny meaningful explanation or accountability.

---

# 17. Fairness

Fairness is a contextual decision about relevant groups, harms, opportunities, and legitimate objectives. No single metric resolves it.

## Fairness process

1. Identify affected parties and possible harms.
2. Examine the historical and institutional context.
3. Define the legitimate objective and eligibility rules.
4. Select relevant groups and intersections lawfully.
5. Choose metrics tied to the harm: error, allocation, quality, delay, burden, or access.
6. show counts, uncertainty, and data limitations.
7. Investigate mechanisms, not only disparities.
8. Evaluate mitigation trade-offs and alternatives.
9. Provide human review, challenge, and remedy.
10. Monitor after deployment for feedback effects and drift.

## Fairness traps

- “fairness through unawareness” while proxies remain;
- matching aggregate accuracy with unequal error types;
- treating past decisions as unquestionable ground truth;
- reducing a policy problem to a model threshold;
- fixing measured groups while ignoring unmeasured exclusion;
- publishing subgroup metrics so small that privacy is compromised;
- assuming every disparity is caused by the model or is acceptable because it predated the model.

---

# 18. Explainability

Explainability should enable the intended person to understand, verify, act, or challenge.

## Explanation levels

- **System:** purpose, boundaries, data, model role, and controls.
- **Process:** how information flows and who decides.
- **Outcome:** principal factors and evidence relevant to a specific result.
- **Recourse:** what can be corrected, supplied, challenged, or appealed.
- **Technical:** behavior, evaluation, uncertainty, and limitations for specialists.

A technically accurate feature-attribution chart can still be useless to a customer. A simple reason code can be misleading if it omits the real decision process. Test explanations with the intended audience.

---

# 19. Decision economics

Governance changes economics. Controls cost money, but missing controls create expected loss, delay, rework, and option destruction.

## Risk-adjusted value

```text
Expected annual value
= realizable revenue or cost benefit
+ strategic/option value
- build and change cost
- recurring operating cost
- control and assurance cost
- expected loss from residual risk
- disruption and exit cost allocation
```

Do not collapse severe low-probability harms into a single expected-value number when law, rights, safety, or risk appetite requires a hard constraint.

## Benefit realization

For each claimed benefit identify:

- baseline owner;
- mechanism;
- operational change required;
- adoption and ramp;
- finance treatment;
- attribution method;
- lag;
- countervailing cost elsewhere;
- responsible benefit owner;
- evidence and review date.

## Real-options thinking

A limited pilot can buy information while preserving the option to scale. Modular architecture, short contracts, data portability, reversible permissions, and staged funding increase option value. Large commitments before evidence destroy it.

## Control economics

Compare controls using:

- risk reduction;
- reliability and testability;
- implementation and operating cost;
- user friction and adoption effect;
- failure modes and coverage;
- effect on time to value;
- reversibility and reuse.

The cheapest control may be unreliable. The strongest control may make the workflow unusable. The objective is acceptable residual risk with positive, realizable value.

---

# 20. Risk register

## Required fields

| ID | Risk scenario | Cause | Event | Impact | Affected parties | Inherent likelihood/impact | Controls | Control evidence | Residual risk | Owner | Trigger/KRI | Treatment | Due | Status |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|

Write scenarios, not labels:

> Because outdated regional policy may be retrieved, the assistant could recommend an invalid denial, causing customer harm, rework, and regulatory exposure.

“Bias,” “privacy,” or “hallucination” alone is not an actionable risk statement.

## Risk treatment choices

- avoid;
- reduce;
- transfer limited exposure;
- accept within authority;
- pursue opportunity with safeguards.

Acceptance requires an authorized owner, rationale, duration, monitoring, and review trigger.

---

# 21. Ethical dilemmas

## Dilemma A — performance versus access

Removing a sensitive attribute makes the interface simpler, but prevents measurement of a suspected disparity. Decide whether and how to collect it for auditing while restricting operational use.

## Dilemma B — employee augmentation versus surveillance

Detailed interaction logs improve coaching and incident investigation, but can become individual productivity surveillance. Define purpose boundaries, access, retention, labor engagement, and prohibited uses.

## Dilemma C — transparency versus security

Customers need meaningful reasons for decisions, but revealing exact fraud controls enables gaming. Design layered explanations and recourse without exposing exploitable rules.

## Dilemma D — benefit versus consent

Historical support text could improve safety detection, but customers were not told it would train an AI system. Evaluate lawful authority, expectations, alternatives, minimization, and trust.

## Dilemma E — fairness versus aggregate value

The system produces large overall benefit but worsens outcomes for a small, already disadvantaged group. Consider redesign, compensation, protected fallback, differential thresholds, non-deployment, and who may legitimately accept the trade-off.

---

# 22. Module project: Governance Framework

## Required components

1. AI system and use-case inventory.
2. Risk-tiering method and prohibited-use screen.
3. RACI/decision-rights matrix and approval gates.
4. Data classification, purpose, access, and retention map.
5. Vendor due-diligence scorecard and contract requirements.
6. Model/system evaluation and change-control standard.
7. Human oversight and affected-party remedy design.
8. Logging, audit, monitoring, and reporting specification.
9. Incident response plan and completed tabletop report.
10. Responsible AI assessment: transparency, fairness, explainability.
11. Risk register with residual-risk acceptance.
12. Risk-adjusted economics and benefit-realization plan.
13. Retirement and exit plan.

## Governance effectiveness tests

- Can a reviewer trace one material decision end to end?
- Can the organization identify every active AI use and owner?
- Does access actually fail for an unauthorized user?
- Does deletion complete across internal and vendor systems?
- Does a material model change trigger evaluation?
- Can an affected person reach a human and obtain remedy?
- Does an incident invoke a tested fallback?
- Are unfair segment outcomes visible and actionable?
- Can Finance verify realized value?
- Can the organization exit the vendor without losing essential records or capability?

## Completion standard

The framework must make a difficult decision easier, block an unacceptable use, reveal a material risk, or improve control evidence. If it merely produces documents, it has failed.
