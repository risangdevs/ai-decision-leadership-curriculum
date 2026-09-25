# Phase 4 Course Guide: Sustainable AI Decision Leadership

## Phase purpose

Phase 4 is the transition from building useful AI artifacts to running AI as an organizational capability. The learner is no longer evaluated as an analyst or prompt writer. The learner is evaluated as a future **Head of AI Strategy** who must create repeatable decision habits, defend evidence under executive pressure, allocate scarce resources, and govern systems whose benefits and harms are uncertain.

The phase contains:

- [Phase 4 Modules](phase-4-modules[GROUP].md)
- [Final Capstone Workbook](phase-4-final-capstone-workbook.md)
- [Phase 4 Source Guide](phase-4-source-guide.md)

The final operating sequence is:

> **Frame the decision → verify the evidence → assign authority → choose Act, Delay, or Redesign → execute with controls → measure outcomes → learn → adapt or stop**

---

# 1. Completion standard

The course is complete only when the learner can:

1. Operate a weekly, monthly, and quarterly decision cadence without producing meeting theater.
2. Distinguish a useful dashboard from a collection of unowned metrics.
3. Assign a Decision Owner, Data Owner, and Execution Owner with non-overlapping accountability.
4. verify metric definitions, denominators, segments, time windows, and data lineage before recommending action.
5. identify bias, confounders, evidence gaps, and plausible alternative explanations.
6. choose and defend **Act, Delay, or Redesign** under uncertainty.
7. request only additional data that can change a decision.
8. classify data and apply access, consent, retention, and minimum-necessary controls.
9. evaluate an AI vendor as an operational dependency, not a demo.
10. define human oversight, logging, audit, incident, appeal, and shutdown mechanisms.
11. integrate value, risk, cost, fairness, security, legal exposure, and reversibility into one recommendation.
12. defend a complete capstone before an adversarial executive board.

Submission is not completion. A polished proposal that fails scrutiny is not passed.

---

# 2. The Head of AI Strategy standard

The learner must demonstrate five forms of judgment.

| Judgment | Required behavior | Failure signal |
|---|---|---|
| Decision judgment | Defines the choice, owner, deadline, alternatives, and reversibility | Starts with a tool or vague goal |
| Evidence judgment | Knows what the evidence establishes and what it does not | Treats a dashboard, correlation, or AI output as truth |
| Economic judgment | Connects cost and benefit to adoption, workflow, risk, and opportunity cost | Presents only license cost or theoretical hours saved |
| Governance judgment | Matches controls to context and consequence | Uses policy language without operational controls |
| Leadership judgment | Creates dissent, resolves conflict, and assigns accountable action | Seeks consensus, hides uncertainty, or diffuses ownership |

## Non-negotiable behaviors

- Say “I do not know” when evidence is insufficient, then state the next decision-relevant test.
- Never use “AI says” as evidence.
- Never present a metric without its definition, denominator, period, source, and owner.
- Never request more data without explaining which decision branch it could change.
- Never call a human “in the loop” without specifying what they see, when they intervene, and what authority they hold.
- Never call a system fair because a single aggregate metric is acceptable.
- Never confuse an approved pilot with approval to scale.
- Never hide a material residual risk in an appendix.

---

# 3. Integrated decision operating system

The phase produces a single operating system with seven layers.

```text
Purpose and risk appetite
        ↓
Decision portfolio and owners
        ↓
Evidence, metrics, and data contracts
        ↓
AI assistants, workflows, and human authority
        ↓
Decision forums and cadence
        ↓
Execution, monitoring, incidents, and appeals
        ↓
Learning, economics, and portfolio reallocation
```

Every layer must be connected. For example, a model-risk threshold must appear in the evaluation plan, approval gate, dashboard, incident triggers, and operating review—not only in a governance document.

## Decision record as the central object

Every material decision must leave a record containing:

- decision statement and owner;
- decision date and review date;
- alternatives considered;
- evidence used and evidence rejected;
- assumptions, unknowns, and confidence;
- conflicts of interest or stakeholder disagreements;
- expected value, cost, and affected parties;
- chosen action and rationale;
- execution owner, milestones, and control obligations;
- leading indicators, outcome KPIs, counter-metrics, and stop triggers;
- approval, dissent, exceptions, and later outcome.

---

# 4. Running case: Asteria warranty decision system

Phase 4 continues the Asteria Appliances case. Leadership must decide whether to scale an AI-assisted warranty workflow from three product lines to all regions.

## Initial board pack

- The pilot reports a 31% reduction in median handling time.
- Reopening rate reportedly fell from 18% to 12%.
- Vendor-reported recommendation accuracy is 93%.
- Frontline usage reached 76% among eligible agents.
- The CFO expects $2.4 million in annual savings.
- The CTO wants a three-year platform commitment to secure pricing.
- Legal discovered that some historical notes contain special-category or highly sensitive information.
- Security has not completed an indirect prompt-injection test.
- Regional operations leaders disagree about whether local exceptions are represented.

## Evidence injected during the phase

The mentor reveals evidence progressively:

1. The handling-time metric excludes escalated cases.
2. Reopening is measured within 14 days in the pilot and 30 days in the baseline.
3. Accuracy was measured on vendor-curated examples, not live cases.
4. One region has a materially higher false-denial rate.
5. Adoption is high partly because supervisors made the tool the default screen.
6. The savings assume eliminated positions, while Operations plans to redeploy all released capacity.
7. A subcontracted model provider may retain prompts for abuse monitoring.
8. The contract does not guarantee configuration-change notice.
9. Agents can copy sensitive text into an unapproved general-purpose tool.
10. A customer group alleges that the appeals process is inaccessible.

The learner must revise the proposal when the evidence changes. Defending the original recommendation for consistency is a failure.

---

# 5. Delivery plan

Recommended format: nine 2.5-hour sessions plus capstone work and a 90-minute board defense.

| Session | Focus | Required performance | Artifact milestone |
|---:|---|---|---|
| 1 | Decision cadence and ownership | Converts meetings into decision forums | Decision Operating System v0.1 |
| 2 | Anti-patterns, buy-in, shared tools | Diagnoses theater, paralysis, hoarding, and workarounds | Adoption and knowledge plan |
| 3 | Executive metric verification | Reconstructs claims from source to decision | Verification worksheet |
| 4 | Bias, confounders, gaps | Generates and tests rival explanations | Evidence-gap register |
| 5 | Act / Delay / Redesign | Makes a reversible decision under uncertainty | Decision memo v0.1 |
| 6 | Data and vendor governance | Defines classification, access, lifecycle, and due diligence | Governance Framework v0.1 |
| 7 | Model risk, oversight, fairness, explainability | Converts principles into controls and tests | Risk Register v0.1 |
| 8 | Incident and portfolio economics | Runs a tabletop and defends risk-adjusted value | Business Case v1.0 |
| 9 | Integrated pre-board review | Proves traceability across all artifacts | Capstone candidate |
| 10 | Executive board simulation | Defends, revises, or withdraws the proposal | Approve / conditional / redesign / reject |

---

# 6. Mentoring method

## Challenge sequence

For each recommendation, the mentor asks:

1. **Definition:** What exact decision are you asking us to make?
2. **Evidence:** What observation supports it, and what is merely assumed?
3. **Alternative:** What is the strongest competing explanation or option?
4. **Distribution:** Who benefits, who bears errors, and which aggregate hides that?
5. **Economics:** What value is actually realizable, by whom, and when?
6. **Control:** How will failure be prevented, detected, contained, corrected, and learned from?
7. **Authority:** Who may approve, override, appeal, pause, or terminate?
8. **Threshold:** What evidence would make you change your recommendation?

The mentor rejects:

- unsupported confidence;
- jargon as a substitute for mechanisms;
- unbounded data requests;
- responsibility assigned to committees;
- “industry best practice” without contextual fit;
- averages that conceal material segments;
- risk lists without owners, treatments, triggers, or residual exposure;
- benefits without adoption and attribution;
- controls that cannot be tested;
- explanations that do not enable action or challenge.

## Ethical dilemma protocol

Each dilemma is evaluated through six lenses:

1. business objective and lawful authority;
2. people and rights affected;
3. distribution of benefits, burdens, and errors;
4. available alternatives and reversibility;
5. transparency, contestability, and remedy;
6. accountable decision owner and documented rationale.

There is not always a clean answer. The learner is graded on recognizing trade-offs, refusing false certainty, and designing a defensible process.

---

# 7. Assessment and gates

Score each dimension from 0 to 4.

| Score | Meaning |
|---:|---|
| 0 | Missing or contradicted |
| 1 | Claimed but unsupported |
| 2 | Partially specified; material gaps remain |
| 3 | Pilot-ready and evidence-backed |
| 4 | Demonstrated under realistic and adversarial conditions |

Dimensions:

- decision clarity and ownership;
- KPI and evidence integrity;
- experiment and causal discipline;
- assistant and workflow quality;
- value and decision economics;
- privacy, security, legal, and compliance readiness;
- model risk and human oversight;
- responsible AI, fairness, transparency, and contestability;
- operations, incident response, and learning cadence;
- executive communication and response under challenge.

## Hard-stop conditions

Regardless of total score, the capstone cannot pass when any of the following remains:

- no accountable Decision Owner;
- unlawful or unresolved prohibited use;
- no defensible purpose or suitable non-AI comparison;
- high-impact action without effective human authority or appeal;
- sensitive data used without a lawful, authorized, and minimum-necessary basis;
- no reproducible KPI baseline or material denominator mismatch;
- untested critical security path;
- no incident owner, containment route, or shutdown authority;
- benefit claim depends on double counting or unsupported adoption;
- material group harm hidden by aggregate performance;
- residual risk exceeds stated risk appetite without explicit acceptance by authorized leadership.

## Board outcomes

- **Approved:** all hard stops cleared; average score at least 3.2; no dimension below 3.
- **Conditionally approved:** hard stops cleared; limited conditions have named owners, deadlines, and restricted scope.
- **Redesign required:** value may exist, but decision, workflow, evidence, economics, or controls are structurally weak.
- **Rejected:** the use case is unsuitable, unlawful, economically indefensible, or outside risk appetite.

Course completion requires **Approved** or a later **Approved** decision after satisfying every conditional item. “Conditionally approved” alone is not completion.
