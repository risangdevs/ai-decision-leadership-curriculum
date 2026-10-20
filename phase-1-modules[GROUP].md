# Phase 1 Modules [GROUP]

## AI decisions and decision framing

This file consolidates the complete Phase 1 modules in their intended learning order. The navigation table links to stable module anchors within this document.

## Module sequence

| Order | Module | Focus | Primary output |
|---:|---|---|---|
| 1 | [Module 1: AI & Data-Driven Leadership Decisions](#module-1) | Start with the decision, test whether AI is appropriate, and define authority and oversight. | AI Decision Suitability Canvas |
| 2 | [Module 2: Decision Framing — From Symptoms and Problems to Decisions](#module-2) | Move from symptoms and assumed causes to a clear, owned, evidence-ready decision. | Root Cause Analysis, Decision Statement, Stakeholder Map, and Assumption Log |

## Progression

```text
Decision and AI suitability
    ↓
Problem diagnosis and decision framing
    ↓
Phase 1 decision portfolio
```

Complete Module 1 before Module 2 so the decision context, AI role, and human authority are explicit before detailed framing begins.

## Phase materials

- [Phase 1 Course Guide](phase-1-course-guide.md)
- [Phase 1 Artifact Workbook](phase-1-artifact-workbook.md)
- [Phase 1 Source Guide](phase-1-source-guide.md)
- [Source Origin Map](source-origin-map.md)

## Assessment and delivery control

Use these chapters with the entry, workload, accessibility, source-control, common-scale, calibration, reassessment, and appeal rules in the [Phase 1 Course Guide](phase-1-course-guide.md). A completed template is not evidence of proficiency unless the learner independently defends and revises it under challenge.

---

## Consolidated module content

<a id="module-1"></a>

# Module 1: AI & Data-Driven Leadership Decisions

## Module purpose

AI creates value only when it improves a real decision. Leaders therefore need to begin with the decision—not with a model, tool, vendor, or dataset.

This module gives leaders a disciplined way to examine a decision, identify where better evidence could help, decide whether AI is appropriate, and define the authority and oversight required for responsible use.

The module culminates in an **AI Decision Suitability Canvas** that answers one executive question:

> For this decision, should AI be used at all, and if so, where, how, and under whose authority?

---

## Intended audience

- Executives and senior leaders
- Business-unit and functional leaders
- Transformation, strategy, data, and technology leaders
- Managers accountable for AI-enabled processes

## Suggested duration

90–120 minutes, including discussion and application.

## How to use this source

This is a comprehensive source chapter, not a slide script. It can be adapted into:

- A 90–120 minute executive workshop
- A 30–45 minute leadership briefing
- A self-paced learning module
- A facilitator-led case discussion
- A decision-governance playbook

The main narrative is in Sections 1–12. Sections 13–17 provide cases, the canvas, practice, assessment, and an executive job aid. Sections 18 onward deepen the material for facilitators, transformation teams, risk leaders, and practitioners.

This module is part of the [Phase 1 course guide](phase-1-course-guide.md). It should be taught as a mastery-based dialogue rather than a continuous lecture. Begin each learning block by asking what the learner already believes, introduce one concept at a time, challenge the reasoning with a business case, and require the learner to revise the AI Decision Suitability Canvas before progressing. The companion [Module 2 source](#module-2) develops the upstream skill of moving from symptoms and root causes to an actionable decision frame.

## Course-goal alignment

| Required topic | Where it is developed |
|---|---|
| How AI changes organizational decision making | Sections 1–3, 6, 18–21 |
| Decision support versus human judgment | Sections 6–7 and 22 |
| When AI should be used | Section 5 and the suitability canvas |
| When human judgment should dominate | Sections 7, 11, and 22 |
| Impact on speed, cost, and risk | Section 8 and Section 20 |
| Decision suitability for AI | Sections 5, 14, and the worked case |
| Automation bias and over-trust | Section 10 |
| Human oversight | Sections 11, 12, and 22 |

The required competency is demonstrated when the learner can independently determine whether AI is appropriate for a decision, identify the major AI-related risks, and defend a completed suitability assessment using evidence rather than technological enthusiasm.

## Learning-loop prompts

Use these questions repeatedly rather than saving them for the end:

- Why do you believe this?
- What evidence supports it?
- Could AI be wrong here—and what would follow?
- What assumptions exist?
- Who owns this decision?
- What data would change your mind?

Do not advance because the learner can repeat terminology. Advance when the learner can apply it to an unfamiliar case, respond to counterevidence, and improve the canvas after critique.

## Learning outcomes

By the end of this module, participants will be able to:

1. Define the business decision before considering an AI solution.
2. Map a decision from information through outcome.
3. Decompose a large decision into smaller decision points with clear owners.
4. Locate uncertainty and identify where additional data could materially improve the decision.
5. Assess whether AI is appropriate for a particular decision.
6. Choose an appropriate role for AI: observe, analyze, predict, recommend, or automate.
7. Distinguish machine-generated evidence from accountable human judgment.
8. Evaluate AI in terms of speed, cost, risk, and consequences—not accuracy alone.
9. Design meaningful human oversight and retain human accountability.
10. Complete an AI Decision Suitability Canvas for a real organizational decision.

## Evidence base and framework alignment

This module synthesizes established decision practice, human-factors research, and public AI governance frameworks. In particular:

- The **NIST AI Risk Management Framework (AI RMF 1.0)** organizes AI risk work around Govern, Map, Measure, and Manage. It calls for organizations to define business context, document system scope and human oversight, compare benefits and costs, test in conditions similar to deployment, track emergent risks, and provide feedback and appeal mechanisms. This module translates those ideas into an executive decision workflow. See [NIST AI RMF 1.0](https://doi.org/10.6028/NIST.AI.100-1).
- The **OECD AI Principles** emphasize human-centred values, transparency, robustness, and accountability across the AI lifecycle. The principles specifically connect transparency with a person’s ability to understand and challenge an outcome. See the [OECD AI Principles](https://oecd.ai/en/ai-principles).
- The **U.S. Government Accountability Office AI Accountability Framework** groups key practices under governance, data, performance, and monitoring. See the [GAO AI Accountability Framework](https://www.gao.gov/products/gao-21-519sp).
- The role ladder used here is informed by human-automation research distinguishing information acquisition, information analysis, decision and action selection, and action implementation. See Parasuraman, Sheridan, and Wickens, [“A Model for Types and Levels of Human Interaction with Automation”](https://www.cs.uml.edu/~holly/91.550/papers/sheridan-autonomy.pdf).

These sources are reference points rather than a substitute for sector-specific policy or legal advice. Regulatory obligations depend on the jurisdiction, decision, organization, people affected, and way the system is used.

---

# 1. The leadership principle: start with the decision

Organizations often begin an AI initiative with a solution-shaped question:

- Where can we use generative AI?
- What could we automate?
- Which model should we buy?
- How can we use all the data we have collected?

These questions are premature. They encourage teams to find a use for a technology rather than solve a meaningful problem.

The better starting point is:

> What decision are we trying to improve?

A well-defined decision includes six elements:

1. **Decision:** What choice must be made?
2. **Decision owner:** Who has the authority and accountability to make it?
3. **Timing:** When must the choice be made, and how often does it recur?
4. **Options:** What courses of action are genuinely available?
5. **Success criteria:** What outcome should the decision improve?
6. **Constraints:** What legal, ethical, financial, operational, or strategic boundaries apply?

### A useful decision statement

Use this template:

> **[Decision owner]** must decide **[choice]** by **[time or frequency]**, using **[relevant evidence]**, to achieve **[desired outcome]**, while respecting **[constraints].**

Example:

> The regional service director must decide which maintenance requests to prioritize each morning, using equipment condition, customer impact, technician capacity, and safety information, to reduce service disruption while meeting safety and contractual obligations.

This is much more useful than saying, “We need predictive maintenance AI.” It leaves open the possibility that the best intervention is better data, a clearer policy, process redesign, additional capacity, conventional analytics—or no technology change at all.

### Leadership prompt

Ask participants to identify a current “AI opportunity” in their organization and rewrite it as a decision statement. If the decision owner, timing, options, and intended outcome are unclear, the opportunity is not yet ready for AI evaluation.

---

# 2. Map the full decision process

A decision is not a single moment. It is a chain:

> **Information → Interpretation → Decision → Action → Outcome**

Weak AI initiatives often optimize one link while ignoring the rest. A model may produce a highly accurate forecast, for example, but create no value because managers do not trust it, the recommendation arrives too late, or the organization cannot act on it.

## The five-stage decision chain

| Stage | Core question | Typical failure | Leadership test |
|---|---|---|---|
| **Information** | What facts, observations, and signals are available? | Data are missing, delayed, biased, inconsistent, or irrelevant. | Do we have evidence that is timely, representative, and fit for this decision? |
| **Interpretation** | What does the information mean in context? | Correlation is mistaken for cause; context is ignored; assumptions remain hidden. | Which interpretations are plausible, and what assumptions produce them? |
| **Decision** | Which option should be chosen? | Criteria conflict; authority is unclear; a recommendation becomes a default. | Who chooses, according to which priorities and boundaries? |
| **Action** | What will be done as a result? | The choice is not translated into timely, feasible action. | Can the organization act, and who owns execution? |
| **Outcome** | What happened, for whom, and with what side effects? | Success is measured too narrowly or too late; learning never returns to the process. | Did the action improve the intended result without unacceptable harm? |

## The feedback loop

The process should not stop at the outcome. Results need to feed back into future information and interpretation. Leaders should ask:

- Did the decision produce the intended effect?
- Were there unintended consequences?
- Did the underlying environment change?
- Does the decision rule or AI system need to be adjusted?
- Are outcomes being measured for all materially affected groups?

Without this feedback loop, the organization cannot learn whether the AI-supported decision remains useful over time.

### Application exercise: decision-chain map

Choose a recurring decision. For each stage, record:

- The activity performed
- The person or role responsible
- The evidence used
- The systems involved
- The delay or friction present
- The most important failure mode

Then identify the weakest link. Improving that link may create more value than adding AI elsewhere in the chain.

---

# 3. Break large decisions into smaller decision points

“Approve the loan,” “hire the candidate,” “launch the product,” and “respond to the incident” sound like single decisions. In practice, each contains a sequence of smaller judgments.

For example, a product launch decision may include:

1. Is customer demand strong enough?
2. Is the product ready for the promised use?
3. Can operations support the expected volume?
4. Are legal and compliance conditions satisfied?
5. Which customer segment should receive the first release?
6. What price and channel should be used?
7. What evidence would trigger a delay, expansion, or withdrawal?

AI may be suitable for one decision point and unsuitable for another. It might estimate demand or detect quality issues, while human leaders retain responsibility for strategic timing, reputational trade-offs, or whether the residual risk is acceptable.

## Assign an owner to every decision point

For each decision point, identify:

- **Decision owner:** Has authority to make the choice and remains accountable for it.
- **Evidence providers:** Supply data, analysis, expertise, or AI outputs.
- **Challengers:** Test assumptions, identify missing perspectives, and raise exceptions.
- **Action owner:** Executes the decision.
- **Affected parties:** Experience the consequences and may need a route to question or appeal the outcome.

One person may fill several roles, but the roles should not be left implicit. “The system decided” is never an adequate description of accountability.

## Decision decomposition worksheet

| Decision point | Owner | Evidence needed | Current method | Consequence of error | Possible AI role |
|---|---|---|---|---|---|
| What must be determined? | Who has authority? | What would improve the judgment? | How is it done today? | Who or what is affected? | None, observe, analyze, predict, recommend, automate |

### Leadership insight

The more consequential the decision, the more important it is to separate the decision into components. Decomposition exposes where AI can contribute and prevents automation of a large, ambiguous judgment simply because one part of it can be predicted.

---

# 4. Locate uncertainty and determine the value of better data

Data are useful when they reduce uncertainty that matters to the choice. More data are not automatically better. A larger volume of irrelevant or low-quality information may create false confidence without changing the correct course of action.

## Five common sources of uncertainty

1. **Input uncertainty:** Are the underlying facts complete, accurate, timely, and representative?
2. **Interpretation uncertainty:** Could the same facts reasonably support different explanations?
3. **Outcome uncertainty:** What is likely to happen under each option?
4. **Execution uncertainty:** Can the organization carry out the chosen action as intended?
5. **Environmental uncertainty:** Could regulation, customer behavior, competition, or other conditions change?

## The value-of-information test

Before seeking more data, ask:

1. What do we currently not know?
2. Which available choices could change if we knew it?
3. How much could a better-informed choice improve the outcome or reduce harm?
4. Can the information be obtained in time and at a reasonable cost?
5. Would the information actually be used, or would the same decision be made regardless?

If new information would not change the decision, collecting it has little decision value. If a small amount of better evidence could prevent a costly error, it may have high value even if it does not eliminate all uncertainty.

## Data quality is decision-specific

Data do not need to be perfect. They need to be fit for the intended decision. Leaders should examine:

- **Relevance:** Do the data represent the factors that matter?
- **Coverage:** Are important cases or groups missing?
- **Timeliness:** Are the data current enough for the decision cycle?
- **Consistency:** Are measures defined and collected in comparable ways?
- **Provenance:** Do we know where the data came from and how they were produced?
- **Legitimacy:** Is using the data lawful, ethical, and consistent with stakeholder expectations?
- **Feedback quality:** Can decisions be connected to later outcomes so performance can be evaluated?

### Beware of proxies

AI frequently uses measurable variables as proxies for concepts that are harder to observe. “Engagement” may stand in for performance, postcode for financial risk, or historical promotion for leadership potential. A proxy may be predictive while still being strategically misleading or unfair.

Leaders should ask: *What are we actually measuring, what are we treating it as a substitute for, and when does that relationship fail?*

---

# 5. Decide whether AI is appropriate

AI is most useful when a decision contains a well-defined information task that can be performed from observable patterns at a worthwhile scale. It is less suitable when the central challenge is defining values, resolving novel ambiguity, negotiating legitimacy, or accepting responsibility for severe consequences.

## Conditions that strengthen the case for AI

- The decision or information task occurs frequently or at significant scale.
- The target outcome is clear enough to measure.
- Relevant historical or operational data exist.
- Patterns in those data are likely to remain informative.
- The organization can act on the output in time.
- Performance and consequences can be monitored.
- Errors can be detected, contained, reversed, or appealed.
- The expected benefit exceeds implementation, oversight, and failure costs.

## Conditions that weaken the case for AI

- The decision is rare, novel, or highly context-dependent.
- Objectives are disputed or cannot be reduced to a stable measure.
- Historical data reflect practices the organization intends to change.
- The environment is changing faster than the model can be validated.
- Errors could cause severe, irreversible, or unequal harm.
- Affected people cannot understand, challenge, or appeal the result.
- Responsibility would become unclear.
- A simple rule, process change, or conventional analysis would solve the problem.

## The “simpler alternative” challenge

Before approving AI, compare it with at least three alternatives:

1. Improve the underlying process.
2. Improve data visibility through reporting or conventional analytics.
3. Use a clear rule, checklist, or threshold.
4. Add or redirect human expertise.
5. Do nothing and accept the current level of uncertainty.

AI should be selected because it produces a better overall decision system—not because it is the most novel option.

## A practical suitability screen

Rate each question as low, medium, or high:

- How clear is the decision and intended outcome?
- How repeatable is the task?
- How strong and relevant are the available data?
- How stable is the operating environment?
- How observable are the eventual outcomes?
- How easy is it to detect and correct an error?
- How severe are the consequences of being wrong?
- How much human or societal judgment is required?

A strong use case typically has high clarity, repeatability, data quality, outcome observability, and reversibility. High consequence severity, high ambiguity, and high value judgment point toward stronger human control—or no AI use at all.

---

# 6. Choose the right role for AI

AI can participate in a decision process at different levels of authority. The appropriate role depends on the task, the quality of evidence, the consequence of error, and the ability of humans to intervene.

## The AI role ladder

| Role | What AI does | Example | Human responsibility |
|---|---|---|---|
| **Observe** | Captures, detects, classifies, or summarizes signals. | Flag unusual equipment readings. | Confirm whether the signal is relevant and decide what follows. |
| **Analyze** | Organizes evidence, identifies patterns, or compares scenarios. | Cluster customer complaints by theme. | Interpret causes, context, and business significance. |
| **Predict** | Estimates a future outcome or probability. | Estimate the chance of late delivery. | Decide what probability means and what action is justified. |
| **Recommend** | Proposes an option or ranks alternatives. | Recommend which shipments to expedite. | Review the recommendation, consider omitted factors, and accept or override it. |
| **Automate** | Executes a predefined decision and action without prior human review in each case. | Automatically reorder low-risk, standard inventory. | Set boundaries, monitor results, handle exceptions, and stop the system when necessary. |

Moving up the ladder increases the system’s influence over outcomes. It also increases the need for evidence, controls, monitoring, and clear authority.

## Use the least-authoritative role that creates value

If observation solves the problem, do not begin with automated action. If a prediction gives leaders enough evidence to make a better choice, do not assume the system should recommend the action. If recommendation works, do not automate until the organization has learned how the system behaves in routine and unusual conditions.

This approach allows the organization to build evidence before increasing AI authority.

---

# 7. Separate AI decision support from human judgment

AI can produce evidence. It cannot decide what an organization should value or accept responsibility for the consequences.

An AI output becomes a decision only when it is combined with criteria, priorities, authority, and action. Those elements remain organizational and human.

## When human judgment should dominate

Human judgment should carry greater weight when the decision involves:

- **Ambiguity:** The problem or desired outcome is not clearly defined.
- **Novelty:** The situation differs materially from the system’s past data.
- **Ethical considerations:** Rights, fairness, dignity, consent, or social legitimacy are at stake.
- **Strategic trade-offs:** Leaders must balance competing objectives with no single correct measure.
- **High consequences:** An error could seriously affect safety, livelihood, liberty, health, reputation, or long-term strategy.
- **Relationship and trust:** The way a decision is made and communicated matters as much as the result.
- **Contested evidence:** Experts or stakeholders reasonably disagree about what the available information means.

## What meaningful human judgment looks like

Human involvement is not meaningful merely because a person clicks “approve.” It is meaningful when the person:

- Understands the decision and the AI system’s intended role.
- Has access to the relevant evidence, not just the recommendation.
- Has enough time and competence to assess the case.
- Knows the system’s important limitations and common failure modes.
- Has genuine authority to challenge, override, defer, or stop the process.
- Is not punished for using that authority responsibly.
- Records the reason for consequential overrides and approvals.

If the process makes agreement with AI faster, easier, and safer for the reviewer than disagreement, nominal human review may simply conceal automation.

---

# 8. Evaluate value through speed, cost, and risk

Accuracy is important, but it is not a complete business case. Leaders should examine how AI changes the whole decision system.

## Speed

Consider:

- Time from new information to decision
- Time from decision to action
- Ability to respond continuously or at greater frequency
- Delay introduced by validation, escalation, or human review
- Whether faster decisions are actually more valuable

Speed can improve outcomes, but it can also allow mistakes to propagate faster.

## Cost

Consider the full lifecycle cost:

- Data collection, cleaning, access, and governance
- Model acquisition or development
- System integration and process redesign
- Human review and exception handling
- Monitoring, testing, and audit
- Training and change management
- Security, legal, and compliance work
- Vendor dependence and switching cost
- Correction, appeal, and remediation when errors occur

An AI system that reduces visible labor but creates substantial hidden oversight and remediation cost may not be economical.

## Risk

Consider:

- Operational and safety risk
- Financial loss
- Legal and regulatory exposure
- Bias and unequal impact
- Privacy and security
- Reputation and stakeholder trust
- Strategic dependence on a vendor or model
- Loss of internal expertise
- Systemic risk when one error is repeated at scale

## Build a balanced value hypothesis

Use this structure:

> If AI performs **[specific role]** at **[specific decision point]**, we expect **[measurable improvement in speed, cost, or outcome]**, while keeping **[named risks]** within **[defined limits]** through **[controls and oversight].**

Every proposed use should have both value measures and guardrail measures.

### Example measures

| Value measures | Guardrail measures |
|---|---|
| Decision turnaround time | Serious errors per 1,000 decisions |
| Cost per case | Unequal error rates across relevant groups |
| Prevented downtime | Override and appeal outcomes |
| Revenue or retention uplift | Customer complaints and trust indicators |
| Staff capacity released | Incidents outside the system’s intended scope |

---

# 9. Examine the consequences of being wrong

Leaders should not ask only, “How accurate is the model?” They should ask, “What happens when it is wrong?”

## False positives and false negatives

Suppose an AI system flags transactions as potentially fraudulent.

- A **false positive** occurs when a legitimate transaction is flagged. The organization may inconvenience a customer, block an important payment, increase review cost, or damage trust.
- A **false negative** occurs when actual fraud is not flagged. The organization may suffer loss, create exposure, or fail to protect the customer.

Improving one error type may worsen the other. The threshold cannot be chosen on technical performance alone; it reflects business priorities, risk appetite, and consequences for affected people.

## Use a consequence matrix

| | AI says “act” | AI says “do not act” |
|---|---|---|
| **Action was warranted** | True positive: desired detection | False negative: missed need or risk |
| **Action was not warranted** | False positive: unnecessary intervention | True negative: correct non-intervention |

For each cell, ask:

- Who benefits?
- Who carries the cost?
- How severe is the consequence?
- How quickly will the error be detected?
- Can it be reversed or appealed?
- Could the same error be repeated at scale?

## Unexpected situations

Historical performance does not cover every future condition. AI can fail when:

- The environment changes.
- Inputs are outside the range seen during development.
- People adapt their behavior to the system.
- A rare event combines factors not previously observed.
- Data pipelines fail while the output still appears plausible.
- The system is used for a purpose or population beyond its validated scope.

Leaders should define boundaries for intended use and identify signals that indicate the system is outside those boundaries.

---

# 10. Recognize automation bias and over-trust

Automation bias is the tendency to accept a system’s output too readily, especially when the system is usually reliable, its reasoning is difficult to inspect, or staff are under time pressure.

It can appear in two forms:

- **Commission error:** Following an incorrect recommendation.
- **Omission error:** Failing to notice something because the system did not flag it.

## Conditions that increase over-trust

- Outputs are presented with unjustified precision or confidence.
- The recommendation appears before the reviewer forms an independent view.
- Staff have little time or weak access to source evidence.
- Overrides require extra work or managerial explanation.
- System agreement is rewarded while challenges are treated as inefficiency.
- Users misunderstand what the model was trained or validated to do.
- Long periods of good performance reduce vigilance.

## Design responses

- Show relevant evidence and uncertainty, not only a recommended action.
- Require independent assessment before revealing the AI output in selected high-risk cases.
- Make override and escalation easy.
- Train with realistic failure examples, not only normal cases.
- Audit both acceptance and override patterns.
- Rotate or sample cases for expert review.
- Avoid anthropomorphic language that suggests the system understands or possesses authority.
- Make the intended scope and limitations visible at the point of use.

The right leadership message is:

> An AI recommendation is evidence, not a verdict.

---

# 11. Design meaningful human oversight

Oversight should be designed around specific decisions and failure modes. Adding a generic “human in the loop” is not enough.

## Four human interventions

1. **Review:** Inspect the evidence and proposed output before action.
2. **Challenge:** Question the model, request more information, or seek a second opinion.
3. **Override:** Choose a different action and record the reason.
4. **Stop:** Pause or disable the AI-supported process when boundaries are breached or performance becomes unsafe.

## Oversight patterns

### Human-in-the-loop

A human approves every consequential output before action. Appropriate when individual cases require context or consequences are significant.

### Human-on-the-loop

The system operates within defined boundaries while humans monitor performance and intervene in exceptions. Appropriate for higher-volume, lower-consequence, reversible decisions with strong monitoring.

### Human-over-the-loop

Humans govern the overall system: approve its purpose, set policies and thresholds, monitor aggregate impact, investigate incidents, and decide whether it should continue. This level is required even when individual actions are automated.

## Triggers for mandatory review or escalation

- Low confidence or missing critical data
- Conditions outside the validated scope
- Conflicting evidence or model outputs
- Material impact on rights, safety, employment, access, or livelihood
- Unusual or high-value cases
- Affected-person challenge or appeal
- Sudden change in error rate, input distribution, or outcome pattern
- Security, privacy, or integrity concern

## Stop conditions

Before deployment, define when the process must pause. Examples include:

- A serious adverse event
- Performance below an agreed threshold
- Material disparity across affected groups
- Loss of a required data source
- Evidence of manipulation or security compromise
- Use beyond approved scope
- Inability to explain, reconstruct, or audit consequential decisions

Oversight is meaningful only if a named person has the authority and operational ability to act on these conditions.

---

# 12. Keep accountability with humans

AI can participate in a decision process, but it cannot own organizational responsibility. Accountability remains with the people who authorize the system, define the policy, select thresholds, deploy it, and act on its outputs.

## A practical accountability structure

Every AI-supported decision process should name:

- **Executive sponsor:** Accountable for the business purpose, risk acceptance, and continued use.
- **Decision owner:** Accountable for the decision or decision policy.
- **System owner:** Responsible for technical operation, monitoring, maintenance, and incident response.
- **Data owner:** Responsible for data access, quality, provenance, and permitted use.
- **Control or risk owner:** Provides independent challenge and confirms required controls.
- **Frontline user:** Uses or supervises outputs within defined authority.
- **Appeal or remediation owner:** Responds when affected people challenge an outcome or suffer harm.

## Questions every accountable leader should be able to answer

- Why is AI being used for this decision?
- What evidence shows it improves the overall process?
- What is it allowed—and not allowed—to do?
- What are the most serious known failure modes?
- Who can override or stop it?
- How are affected people protected and heard?
- What evidence would cause us to change or withdraw the system?

Accountability cannot be transferred to a model, an algorithm, a vendor, or “the data.”

---

# 13. Worked case: prioritizing maintenance requests

## The situation

A national service company receives thousands of maintenance requests each week. Delays cause equipment downtime and customer dissatisfaction. Leaders propose an AI system to “automate maintenance decisions.”

## Step 1: Define the decision

> The regional service director must decide each morning which requests receive technicians that day, using safety risk, equipment condition, customer impact, contractual priority, location, and technician capacity, to reduce disruption while meeting safety and service obligations.

## Step 2: Decompose the decision

The apparent single decision contains several smaller ones:

1. Is the information in each request complete?
2. What type of fault is likely?
3. How likely is failure or escalation within a defined period?
4. How severe would the consequence be?
5. Which technician has the right capability and location?
6. Which requests should take priority when objectives conflict?
7. Should an unusual or high-consequence case be escalated?

## Step 3: Locate uncertainty

- Fault descriptions are inconsistent.
- Some equipment has rich sensor data; other equipment has little history.
- Failure likelihood is uncertain.
- Customer impact depends on local context.
- Technician availability changes during the day.
- Rare safety situations may not resemble historical cases.

## Step 4: Choose AI roles

- **Observe:** Extract equipment type, symptoms, location, and urgency indicators from requests.
- **Analyze:** Group similar incidents and identify missing information.
- **Predict:** Estimate the likelihood of service failure within 24 hours.
- **Recommend:** Rank routine requests using approved criteria.
- **Automate:** Do not initially automate final priority or dispatch decisions.

## Step 5: Preserve human judgment

The regional service director retains authority over final prioritization. Mandatory review applies to safety-related cases, low-confidence predictions, strategic customers, conflicting contractual obligations, and situations outside the validated equipment types.

## Step 6: Evaluate value and risk

Value measures:

- Reduction in triage time
- Faster response to genuine high-risk cases
- Reduction in preventable downtime
- Better use of technician capacity

Guardrail measures:

- High-risk cases incorrectly assigned low priority
- Unequal service levels by geography or customer type
- Override patterns and reasons
- Incidents involving missing or unreliable input data
- Customer complaints and successful appeals

## Step 7: Define oversight

- Supervisors review all safety cases before dispatch decisions are finalized.
- A weekly expert sample checks both flagged and unflagged requests.
- Operations pauses use if the missed-high-risk rate exceeds the agreed boundary.
- The decision owner reviews thresholds monthly during the pilot.
- Customers and frontline employees have a route to report suspected errors.

## Conclusion

AI is appropriate as bounded decision support for information extraction, pattern analysis, prediction, and prioritization. It should not own the final allocation decision during the initial deployment. Automation may later be considered for routine, low-consequence cases if pilot evidence shows stable performance and effective exception handling.

For a completed, evidence-based application of all 12 canvas fields to this scenario, include illustrative baseline data, alternatives, error consequences, pilot gates, oversight triggers, and a four-part executive conclusion.

---

# 14. AI Decision Suitability Canvas

Complete the canvas for one clearly defined decision. Concise, evidence-based answers are more valuable than optimistic claims.

## A. Decision and value

### 1. Decision statement

Who decides what, when, using which evidence, for what intended outcome, and within which constraints?

### 2. Decision points and owners

What smaller choices make up the decision? Who owns each one?

### 3. Desired value

What should improve: quality, speed, cost, consistency, reach, resilience, or risk? How will improvement be measured?

## B. Evidence and uncertainty

### 4. Current evidence

What information is used today? Is it relevant, representative, timely, traceable, and legitimate to use?

### 5. Material uncertainty

What is not known? Which uncertainty could change the preferred action?

### 6. Consequences of error

What are the false-positive, false-negative, and unexpected-situation consequences? Who bears each cost? Can errors be reversed or appealed?

## C. AI fit and authority

### 7. Suitability of AI

Is the task clear, repeatable, measurable, data-supported, monitorable, and stable enough for AI? What simpler alternatives were considered?

### 8. AI role

Should AI observe, analyze, predict, recommend, or automate? At which specific decision point?

### 9. Human judgment

Which judgments must remain human because they involve ambiguity, novelty, ethics, strategic trade-offs, relationships, or high consequences?

## D. Controls and accountability

### 10. Oversight design

When must a human review, challenge, override, escalate, or stop the process? What are the explicit triggers?

### 11. Accountability

Who is the executive sponsor, decision owner, system owner, data owner, control owner, and remediation owner?

### 12. Learning plan

How will outcomes, errors, overrides, appeals, and unintended effects be monitored? What evidence will support expansion, redesign, or withdrawal?

## Executive conclusion

Complete all four statements:

> **Use decision:** We should / should not use AI for this decision because…

> **AI role:** AI should observe / analyze / predict / recommend / automate…

> **Boundary:** AI must not…

> **Authority:** Final authority remains with…

---

# 15. Participant activity: canvas workshop

## Instructions

Work individually or in small groups on a real organizational decision.

1. Write a one-sentence decision statement.
2. Decompose it into three to seven decision points.
3. Mark the points with the greatest uncertainty.
4. Identify where better data could change the chosen action.
5. Screen the decision for AI suitability.
6. Select the least-authoritative AI role that could create meaningful value.
7. Describe the most consequential false positive and false negative.
8. Define at least three mandatory human-intervention triggers.
9. Name the accountable human owner.
10. Present the executive conclusion in no more than 90 seconds.

## Peer challenge questions

- Is the decision defined clearly enough to evaluate?
- Is the proposed AI role attached to a specific decision point?
- Does the proposal confuse prediction with judgment?
- What important evidence or stakeholder perspective may be missing?
- Who bears the cost when the system is wrong?
- Can the reviewer genuinely override the system?
- Is a simpler intervention likely to work?
- What would cause the organization to stop using the system?

---

# 16. Knowledge check

## Questions

1. Why should an AI initiative begin with a decision statement?
2. What are the five stages of the decision chain?
3. Why should a large decision be decomposed into smaller decision points?
4. When does additional data have decision value?
5. Name the five possible roles for AI in this module.
6. Why is model accuracy insufficient as the sole success measure?
7. What is the difference between a false positive and a false negative?
8. What makes human review meaningful rather than ceremonial?
9. What is automation bias?
10. Who remains accountable for an AI-supported organizational decision?

## Suggested answers

1. It clarifies the owner, choice, timing, evidence, outcome, and constraints before a solution is selected.
2. Information, interpretation, decision, action, and outcome.
3. Different points may have different owners, uncertainties, consequences, and appropriate roles for AI.
4. When it could change the preferred action or materially reduce the cost of error in time to matter.
5. Observe, analyze, predict, recommend, and automate.
6. A system may be accurate yet slow, costly, unactionable, unfair, fragile, or harmful when wrong.
7. A false positive triggers action when it was not warranted; a false negative fails to trigger action when it was warranted.
8. The reviewer must have evidence, competence, time, independence, and real authority to challenge, override, escalate, or stop.
9. The tendency to accept or rely on automated output too readily, including failing to act when a system does not issue an alert.
10. The relevant human leaders and organizational owners; accountability cannot be assigned to AI.

---

# 17. Executive job aid

Before approving an AI-supported decision process, ask:

- What exact decision are we improving?
- Who owns it?
- Which decision point needs help?
- What uncertainty are we reducing?
- Would better data, a simple rule, or process redesign be enough?
- What role will AI play—and why is that the minimum necessary role?
- Which judgments must remain human?
- What happens when AI is wrong?
- Who bears the cost of each type of error?
- How will speed, cost, outcomes, and risk change?
- When must a person review, challenge, override, or stop the process?
- Who is accountable for the result?
- How will we learn whether the system should expand, change, or be withdrawn?

If these questions cannot be answered clearly, the decision is not ready for AI deployment.

---

# 18. Deeper foundation: what makes a decision good?

A good outcome does not prove that a decision was good. A poor process can get lucky, and a disciplined process can still produce a bad result under uncertainty. Leaders should therefore judge both the quality of the decision process and the eventual outcome.

## Six elements of decision quality

### 1. A useful frame

The frame defines the problem, scope, perspective, and time horizon. A narrow frame can make the wrong problem look solvable.

Questions:

- What event triggered this decision?
- Is this the underlying decision or a symptom of another problem?
- Whose perspective defines success?
- What is inside and outside the scope?
- What assumptions are embedded in the way the problem is described?

Example: “Which employees are likely to leave?” frames the issue as prediction. “What working conditions can we change to retain critical capability?” frames it as an intervention decision. The second question may produce more useful action.

### 2. Genuine alternatives

A decision requires alternatives. If only one option is considered, analysis may merely rationalize a predetermined action.

Alternatives can include:

- Act now, later, or not at all
- Change policy, process, staffing, technology, or incentives
- Pilot in a narrow context
- Use AI only for selected cases
- Use AI as evidence without making it visible to the first reviewer
- Retain the current process while improving data collection

### 3. Relevant information

Information should distinguish among alternatives. It is valuable when it changes beliefs, choices, or the confidence with which action can be taken. Data that confirm what leaders already assume may feel reassuring without improving the decision.

### 4. Explicit values and trade-offs

Decisions usually involve multiple objectives: cost, growth, safety, fairness, employee experience, customer trust, resilience, and time. AI can estimate consequences, but leaders must determine how competing objectives should be weighed.

Making trade-offs explicit prevents a technical metric from silently becoming organizational policy. For example, optimizing fraud detection for “accuracy” hides the relative value placed on catching fraud versus avoiding disruption to legitimate customers.

### 5. Sound reasoning

Reasoning connects evidence and alternatives to expected consequences. Leaders should distinguish:

- Observation from inference
- Correlation from causation
- Forecast from recommendation
- Probability from certainty
- Model confidence from business confidence
- A measurable target from the full objective

### 6. Commitment to action and learning

A high-quality choice still fails if it is not implemented. The decision needs a named action owner, resources, a timetable, and feedback. For AI-supported decisions, it also needs monitoring and a route to correct individual and systemic errors.

## Prediction is not decision

A prediction estimates what may happen. A decision chooses what to do. The gap between them contains values, constraints, alternatives, risk appetite, and authority.

For example:

> Prediction: This customer has a 72% estimated probability of cancelling within 60 days.

That prediction does not answer:

- Whether the estimate is reliable for this type of customer
- Whether intervention is worthwhile
- Which intervention is appropriate
- Whether contacting the customer could have a negative effect
- How limited retention resources should be allocated
- Whether a different business policy is causing the problem

AI can support the evidence layer without resolving the entire decision.

## Decision versus decision policy

Leaders also need to distinguish an individual choice from the policy that governs many choices.

- **Case decision:** Should this specific claim be reviewed?
- **Decision policy:** Which claims should be reviewed, using what threshold, exceptions, and escalation rules?

An AI system may apply a decision policy at scale. Humans remain accountable for selecting that policy, determining acceptable error trade-offs, monitoring consequences, and changing it when conditions shift.

---

# 19. Decision types and where AI tends to fit

## Strategic, tactical, and operational decisions

| Decision type | Typical characteristics | Examples | Likely AI contribution | Human role |
|---|---|---|---|---|
| **Strategic** | Infrequent, ambiguous, long horizon, high uncertainty, identity-shaping | Enter a market, acquire a company, change the business model | Scenario analysis, evidence synthesis, sensitivity analysis | Define objectives, interpret novelty, negotiate trade-offs, own commitment |
| **Tactical** | Periodic resource allocation within strategy | Set quarterly inventory, allocate budget, choose campaign mix | Forecast, optimize, compare scenarios, recommend allocations | Set constraints, test assumptions, resolve cross-functional trade-offs |
| **Operational** | Frequent, structured, time-sensitive | Route a delivery, flag a transaction, reorder inventory | Observe, predict, rank, recommend, sometimes automate | Govern policy, review exceptions, monitor system and aggregate outcomes |

Operational decisions are often more amenable to automation because they repeat, generate feedback, and can be bounded. Strategic decisions may still benefit from AI, but usually as analysis or evidence support rather than autonomous choice.

## Common decision patterns

### Detection

Question: Is a relevant condition present?

Examples include fraud, defects, anomalies, safety hazards, and policy violations. Central issues are prevalence, false alarms, missed cases, and whether a reliable ground truth exists.

### Forecasting

Question: What is likely to happen, when, and with what uncertainty?

Examples include demand, failure, churn, cash flow, and delivery delay. Central issues are horizon, calibration, changing conditions, and whether the organization can act on the forecast.

### Prioritization or triage

Question: Which cases should receive scarce attention first?

Examples include service tickets, inspections, patient queues, and sales leads. Central issues are whose need is prioritized, whether low-ranked cases disappear from view, and how capacity constraints shape outcomes.

### Allocation

Question: How should scarce resources be distributed?

Examples include staff, capital, stock, appointments, and aid. Central issues are optimization objectives, fairness constraints, and distributional effects.

### Eligibility or approval

Question: Does a person or case meet a threshold?

Examples include lending, benefits, insurance, employment, and access to services. These can materially affect people and commonly require strong legal, fairness, explanation, contestability, and human-oversight safeguards.

### Generation and drafting

Question: What content should be produced to support work?

Examples include reports, summaries, responses, plans, or code. The decision is not simply “generate text”; it includes whether the content is accurate, appropriate, authorized, safe to disclose, and fit for its audience.

---

# 20. Measure the human–AI decision system

Evaluating the model alone is insufficient. The unit of analysis is the whole system: data, model, interface, people, workflow, controls, action, and outcome.

## Establish the baseline

Before a pilot, document current performance:

- How long does the decision take?
- What does each case cost?
- How often do different errors occur?
- How consistent are decisions across people, teams, time, and locations?
- Which groups receive different outcomes?
- How often are decisions appealed or reversed?
- What is the current outcome quality?

Without a baseline, a team can show that an AI model works without showing that it improves the real process.

## Four layers of measurement

### Layer 1: Model performance

Depending on the task, measures may include:

- **Sensitivity or recall:** Of the cases that truly require detection, how many are found?
- **Specificity:** Of the cases that do not require detection, how many are correctly left unflagged?
- **Precision:** Of the cases flagged, how many truly warrant the flag?
- **Calibration:** When the system says “70%,” do comparable cases occur roughly 70% of the time?
- **Ranking quality:** Are higher-risk cases actually concentrated near the top?
- **Robustness:** Does performance hold under noise, missing data, or reasonable input variation?
- **Subgroup performance:** Do relevant groups experience materially different error rates or quality?

### Layer 2: Human–AI interaction

Measure how people use the system:

- Acceptance and override rates
- Time spent reviewing evidence
- Agreement among reviewers
- Correct and incorrect overrides
- Escalation frequency
- Whether reviewers detect simulated or seeded errors
- Differences by experience, workload, shift, or location
- Whether the system changes what evidence people seek

An extremely low override rate can indicate excellent performance—or a review process that discourages independent judgment. The number is meaningful only when investigated in context.

### Layer 3: Workflow performance

Measure the process:

- End-to-end cycle time
- Queue length and backlog
- Cost per case
- Exception-handling burden
- Downstream rework
- Availability and downtime
- Time to detect and correct an error
- Capacity released or newly consumed

### Layer 4: Outcomes and impact

Measure what ultimately matters:

- Customer, employee, citizen, or patient outcomes
- Safety and operational incidents
- Revenue, loss, service level, or productivity
- Distribution of benefits and harms
- Complaints, appeals, and successful reversals
- Trust and behavioral response
- Long-term or system-level effects

The NIST AI RMF recommends evaluation in conditions similar to deployment, ongoing tracking of existing and emergent risks, and feedback processes that allow end users and affected communities to report problems or appeal outcomes. See the [AI RMF Core](https://airc.nist.gov/airmf-resources/airmf/5-sec-core/).

## Why base rates matter

Even a seemingly strong detector may produce many false alarms when the event is rare.

Imagine 1,000 cases where the true adverse event occurs in 1% of cases. A system with 90% sensitivity and 90% specificity would produce approximately:

- 9 true positives
- 1 false negative
- 99 false positives
- 891 true negatives

Although both sensitivity and specificity are 90%, only about 8% of the flagged cases would be true positives. Leaders need the complete consequence picture, not a single performance percentage.

## Thresholds are policy choices

Changing a threshold alters who is flagged, who is missed, workload, cost, and harm. The choice should reflect:

- Relative consequence of false positives and false negatives
- Available capacity to review or intervene
- Risk tolerance
- Legal and ethical boundaries
- Distributional effects
- Ability to detect and reverse errors

Technical teams can show the trade-off curve. Accountable leaders must choose and authorize the operating point.

## Compare four configurations

Where feasible, a pilot should compare:

1. Human judgment without AI
2. AI output without human modification in a controlled evaluation
3. Human judgment with AI support
4. A simpler rule or conventional analytical alternative

This reveals whether the combined human–AI system actually performs better than either component and whether AI is superior to a simpler option.

---

# 21. From idea to operation: stage gates

AI suitability is not a one-time approval. Evidence should be reviewed at several gates.

## Gate 0: Problem acceptance

Required evidence:

- Clear decision statement and owner
- Strategic relevance
- Baseline performance
- Affected stakeholders
- Initial consequence and rights analysis

Possible outcomes: reject, reframe, investigate, or proceed.

## Gate 1: Intervention choice

Required evidence:

- Decision-chain map
- Root causes and uncertainty
- Comparison with non-AI alternatives
- Expected value hypothesis
- Proposed AI role and boundary

Possible outcomes: improve process or data, use conventional analytics, test AI, or stop.

## Gate 2: Design approval

Required evidence:

- Data provenance and fitness assessment
- Evaluation plan and baseline
- Human-oversight design
- Security, privacy, legal, ethical, and operational review
- Failure modes, escalation triggers, and stop conditions
- Named owners and resources

Possible outcomes: redesign, limited prototype, or controlled pilot.

## Gate 3: Pilot readiness

Required evidence:

- Performance in representative conditions
- User training and competency checks
- Logging, monitoring, and incident processes
- Appeal or correction route
- Rollback plan
- Explicit limits on users, cases, geography, and duration

Possible outcomes: shadow mode, advisory pilot, limited live pilot, or no deployment.

## Gate 4: Scale decision

Required evidence:

- Comparison with baseline and alternatives
- Model, human–AI, workflow, and outcome measures
- Error and incident analysis
- Feedback from users and affected stakeholders
- Cost and capacity evidence
- Residual risk acceptance by the accountable owner

Possible outcomes: scale, continue the pilot, narrow use, redesign, or withdraw.

## Gate 5: Continued-operation review

Required evidence:

- Performance and impact trends
- Changes in users, data, context, law, or vendor system
- Overrides, complaints, appeals, and incidents
- Emerging misuse and out-of-scope use
- Whether the system remains better than alternatives

Possible outcomes: continue, recalibrate, retrain, restrict, suspend, or retire.

## Shadow, advisory, and controlled modes

- **Shadow mode:** The system produces outputs that do not affect live decisions. Teams compare them with real decisions and outcomes.
- **Advisory mode:** Users can see the output, but humans retain active case-level authority.
- **Controlled automation:** Only predefined low-risk cases are automated; exceptions and samples receive review.
- **Expanded automation:** Broader automation occurs only after evidence demonstrates that controls, monitoring, and recovery work in practice.

## Minimum decision record

For consequential uses, retain a decision record containing:

- Decision purpose and owner
- Approved AI role and intended scope
- Prohibited and out-of-scope uses
- Data and model or service version
- Performance and risk evidence supporting approval
- Thresholds, exceptions, escalation, and stop conditions
- Human roles and training requirements
- Monitoring metrics and review frequency
- Known limitations and residual risks
- Approval date, approvers, conditions, and next review date

Documentation supports continuity, challenge, learning, and accountability. The [OECD accountability principle](https://oecd.ai/en/dashboards/ai-principles/P9) connects accountability with lifecycle traceability and systematic risk management.

---

# 22. Human oversight by design

Human oversight should be matched to the failure modes, not added as a label after the system is built.

## Oversight design questions

### Competence

- Does the reviewer understand the domain decision?
- Does the reviewer understand what the AI output does and does not mean?
- Has the reviewer practiced with realistic errors and edge cases?

### Information

- Can the reviewer inspect the underlying case evidence?
- Can the reviewer see missing or low-quality inputs?
- Is uncertainty communicated in a form the reviewer can use?
- Can the reviewer obtain information unavailable to the model?

### Time and workload

- Is there enough time for genuine review?
- Does alert volume create fatigue?
- Does the process preserve attention for hard cases?
- What happens during peak demand or staff shortage?

### Authority and incentives

- Can the reviewer override, escalate, or pause the process?
- Are overrides easy to make and safe to report?
- Do productivity targets pressure reviewers to accept outputs?
- Is the reviewer accountable for a result without having real control?

### Feedback

- Will reviewers learn the eventual outcome?
- Are incorrect acceptances and overrides investigated?
- Is frontline experience used to improve the system and policy?

## Match the intervention to the risk

| Situation | Oversight response |
|---|---|
| Routine, low-consequence, reversible case | Automated handling with sampling, monitoring, and easy recovery |
| Moderate consequence or uncertain evidence | Human review before action |
| High consequence, novel, or out-of-scope case | Specialist review or multi-person authorization |
| Rights-affecting decision | Notice, meaningful explanation, contestability, and authorized human reconsideration as applicable |
| System anomaly or drift signal | Suspend affected use, investigate, and require reauthorization |

The [EU AI Act](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32024R1689) requires effective human oversight for high-risk AI systems and describes oversight as proportionate to risk, autonomy, and context. It also expects relevant oversight personnel to be able to understand limitations, detect anomalies, avoid over-reliance, interpret outputs, override or reverse outputs, and interrupt the system. Applicability and obligations should be assessed with qualified legal and risk professionals.

The UK Information Commissioner’s Office similarly emphasizes that meaningful human intervention must involve someone with suitable authority and capability to change the outcome and should consider relevant information beyond the automated output. See [ICO guidance on AI and data protection](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/artificial-intelligence/guidance-on-ai-and-data-protection/).

---

# 23. Buying AI: executive vendor due diligence

Buying a service does not transfer accountability. A vendor may operate the model, but the deploying organization determines why and where it is used, what decisions it affects, and what risk it accepts.

## Purpose and evidence

- What exact task was the system designed for?
- For which populations, languages, geographies, and operating conditions has it been evaluated?
- What evidence supports the vendor’s performance claims?
- Are results based on representative deployment conditions or a controlled benchmark?
- What is the relevant baseline and simpler alternative?

## Data

- What are the sources, dates, provenance, permissions, and known limitations of training, tuning, and evaluation data?
- What customer data will the service collect, retain, reuse, or expose to subprocessors?
- Can the vendor demonstrate performance for the organization’s actual inputs and affected groups?
- How are missing, corrupted, adversarial, or out-of-range inputs handled?

## Model and service change

- Can the vendor change the model without prior notice?
- How are material updates tested and communicated?
- Can the organization pin a version, conduct regression tests, or delay an update?
- Does performance depend on third-party models that may change separately?

## Oversight and audit

- What logs are available?
- Can individual outputs be reconstructed and investigated?
- Does the organization have rights to assess, audit, or obtain independent assurance?
- How will incidents, vulnerabilities, and material performance changes be reported?
- Can affected decisions be corrected or reversed?

## Security, resilience, and continuity

- How are access, data isolation, secrets, model endpoints, and administrative privileges secured?
- What are the uptime, recovery, and incident-response commitments?
- What happens if the provider fails, withdraws the product, changes terms, or becomes inaccessible?
- Can data, configurations, logs, and decision records be exported in a usable form?

## Commercial alignment

- Do pricing structures encourage excessive use or automation?
- What are the costs of monitoring, human review, rework, and exit?
- Who bears remediation cost when the system causes harm?
- Are intellectual-property, confidentiality, indemnity, and liability terms aligned with the use?

## Exit plan

Before adoption, specify how the organization will:

- Stop the service safely
- Restore a manual or alternative process
- Preserve records needed for audit or appeal
- Export or delete data
- Maintain critical expertise
- Communicate material changes to users and affected stakeholders

---

# 24. Special considerations for generative AI

Generative AI produces new content rather than only a score or classification. It can participate in many stages of the decision chain, but its fluent output can create a misleading impression of knowledge and authority.

## Productive roles

Generative AI may help:

- Summarize large bodies of material
- Extract structured information from documents
- Generate questions, options, scenarios, or counterarguments
- Draft routine communications for human review
- Translate or reformat content
- Support retrieval from an approved knowledge base
- Create a first-pass analysis that a qualified person verifies

## Distinctive risks

### Fabricated or unsupported content

The system may produce plausible but false statements, sources, calculations, or explanations. Fluency is not evidence of accuracy.

### Variability

The same or similar prompt may produce different answers. A workflow should not assume deterministic behavior unless the implementation has been tested accordingly.

### Context and instruction failure

The system may overlook constraints, follow malicious instructions embedded in retrieved content, or confuse authoritative and untrusted material.

### Sensitive-data leakage

Users may submit confidential, personal, regulated, or proprietary information to a service without understanding retention or reuse.

### Intellectual-property and provenance risk

Generated content may lack reliable provenance, reproduce protected material, or create uncertainty about permitted use.

### Persuasive overreach

Confident tone, apparent empathy, or detailed explanations may encourage users to treat generated content as expert judgment.

## Controls for decision support

- Ground outputs in approved sources where possible.
- Require citations that can be opened and checked; do not treat generated citations as valid until verified.
- Separate source text, model inference, and human conclusion.
- Use structured outputs and validation for fields that feed downstream systems.
- Prevent unreviewed external communication for consequential content.
- Restrict tools, data access, and actions to the minimum needed.
- Treat retrieved documents and external content as untrusted input.
- Test prompts and workflows with adversarial, ambiguous, incomplete, and out-of-scope cases.
- Keep a reliable record of input, retrieved context, output, model or service version, human changes, and final action where proportionate.
- Define when the user must stop and consult a qualified expert.

## A generative-AI decision test

Before using a generative system, ask:

1. Is the output a draft, evidence summary, recommendation, or final action?
2. How will factual claims be verified?
3. What sources is it allowed to use?
4. What information must never be submitted?
5. Who is qualified to review the result?
6. What happens if the output is persuasive but wrong?
7. Can the system take actions, and if so, what permissions and confirmation gates apply?
8. How will an incident be detected, contained, and investigated?

---

# 25. Additional case studies

## Case A: customer-complaint triage

### Proposed use

Classify incoming complaints, detect urgency, summarize the issue, and route each case.

### Decision decomposition

1. Is the submission a complaint, inquiry, or other request?
2. Is there a safety, vulnerability, legal, or reputational indicator?
3. Which team should handle it?
4. What priority should it receive?
5. What immediate acknowledgment is appropriate?

### Suitability conclusion

AI is suitable for observation and analysis: extract fields, summarize, and suggest routing. It may recommend priority for routine cases. High-impact indicators, low-confidence cases, and unusual submissions require human review. Automated final responses should be limited to narrow acknowledgments that do not resolve the complaint or make commitments.

### Measures

- Routing accuracy and time to first response
- High-urgency cases missed
- Unnecessary escalations
- Reopened cases and customer corrections
- Performance across channels, languages, and accessibility needs

## Case B: employee promotion

### Proposed use

Rank employees for promotion based on performance and career history.

### Decision concerns

Historical data may encode earlier opportunity gaps, manager bias, uneven access to high-visibility assignments, or a leadership model the organization intends to change. Performance measures may be proxies for team resources or role design. Promotion also involves potential, readiness, organizational need, and accountability for fair opportunity.

### Suitability conclusion

AI should not make or automatically rank final promotion decisions. A bounded analytical role may be justified—for example, checking whether evidence is complete, identifying inconsistent application of stated criteria, or showing patterns for governance review. Human panels should examine contextual evidence and remain accountable. Affected employees need transparent criteria and appropriate routes to correction or appeal.

### Leadership lesson

The existence of historical outcome data does not make a decision suitable for prediction. If the organization does not want to reproduce the past, past decisions are a questionable target.

## Case C: market entry

### Proposed use

Use AI to decide whether the company should enter a new national market.

### Decision concerns

The decision is infrequent, strategic, and exposed to regulatory, competitor, geopolitical, cultural, and execution uncertainty. Historical analogies may be weak. The organization must balance growth, capital risk, brand, capability, and opportunity cost.

### Suitability conclusion

AI can analyze and synthesize: structure market evidence, compare scenarios, test assumptions, surface contrary signals, and update forecasts. It should not own the recommendation or final decision. The executive team remains responsible for the strategic trade-off and commitment.

### Leadership lesson

Low suitability for automation does not imply zero value from AI. AI can strengthen the information and interpretation stages while human judgment dominates the decision.

## Case D: routine purchase-order replenishment

### Proposed use

Automatically reorder standard, low-value stock when predicted inventory falls below an operating threshold.

### Suitability conclusion

This can be a strong candidate for bounded automation when demand, lead time, supplier, price, and stock constraints are reliable; errors are limited and reversible; and exceptions can be identified. Humans set policy, approve suppliers and thresholds, monitor aggregate results, and review unusual orders.

### Automation boundaries

- Maximum order value and quantity
- Approved suppliers and items
- Stable price range
- No safety-critical or regulated materials
- Escalation for demand shocks, stock anomalies, or supplier changes
- Immediate stop on data-pipeline failure or unexplained order surge

---

# 26. Managing an AI decision portfolio

An organization with many AI-supported decisions needs two levels of governance. The **AI Decision Suitability Canvas** evaluates each decision in its own context. A **portfolio view** shows whether those individually reasonable uses create shared exposures, conflicting policies, concentrated authority, or cumulative harm when considered together.

The portfolio is a register of *decisions*, not merely a list of models or vendors. One model may support several decisions, and one decision may depend on several models, data sources, human teams, and policies. Both relationships matter.

## Portfolio view: illustrative example

The following view uses fictional decisions and organizations. Consequence tiers are teaching judgments, not legal classifications. In a real organization, the tier must be justified by the affected people, severity and reversibility of error, scale of use, and local obligations.

The self-contained Markdown views below can be read or printed with this chapter. The [interactive portfolio prototype](/Users/risang/.codex/visualizations/2026/09/21/01a0c2f5-d355-7062-ace6-64c5cd0c040f/ai-decision-portfolio.html) presents the same six cases with selectable decisions and a consequence filter.

### Portfolio summary

| Measure | Illustrative portfolio |
|---|---:|
| AI-supported decisions | 6 |
| High-consequence decisions | 3 |
| Automated decision points | 1 |
| Live / pilot / design | 2 / 2 / 2 |
| Shared dependencies requiring portfolio oversight | 2 |

### View 1 — consequence × AI authority

This matrix makes a portfolio-level pattern visible: the most consequential decisions use AI for analysis, prediction, or recommendation, while the only automated decision point is bounded and relatively low consequence.

| Consequence of error | Observe | Analyze | Predict | Recommend | Automate |
|---|---|---|---|---|---|
| **High** | — | Promotion evidence check | Fraud alert review | Maintenance prioritization | — |
| **Medium** | — | Market-entry scenarios | — | Customer complaint triage | — |
| **Low** | — | — | — | — | Routine stock replenishment |

The matrix is a screening view, not an approval rule. High-consequence decisions can still benefit from AI evidence, and a low-consequence use can still be unsafe if it operates at enormous scale, crosses a rights boundary, or lacks effective controls.

### View 2 — decision register

| Decision point | AI role | Consequence | Accountable decision owner | Stage | Human control | Primary measures |
|---|---|---|---|---|---|---|
| Fraud alert review | Predict | High | Risk Operations Lead | Live | Analyst reviews alerts; high-value cases escalate. | Missed fraud, false alarms, successful appeals |
| Maintenance prioritization | Recommend | High | Regional Service Director | Pilot | Director approves daily priorities; safety cases escalate. | Missed high-risk faults, downtime, override reasons |
| Promotion evidence check | Analyze | High | Chief People Officer | Design | Human panel decides; AI cannot rank candidates. | Criteria consistency, adverse impact, corrections |
| Customer complaint triage | Recommend | Medium | Customer Care Lead | Pilot | Sensitive and low-confidence cases receive review. | Misroutes, urgent cases missed, customer corrections |
| Market-entry scenarios | Analyze | Medium | Strategy Director | Design | Executive team owns the strategic choice. | Scenario assumptions, forecast error, decision review |
| Routine stock replenishment | Automate | Low | Supply Chain Lead | Live | Value limits, exception queue, and stop switch. | Stockouts, excess stock, anomalous orders |

### View 3 — shared dependencies

| Shared dependency | Decisions affected | Portfolio-level concern | Required response |
|---|---|---|---|
| **Atlas ML platform** | Fraud review, complaint triage, maintenance prioritization | A provider change, outage, or common failure mode could affect three decision processes simultaneously. | Maintain a joint change log, regression tests for each decision, incident escalation, and a fallback for each workflow. |
| **Customer profile data** | Fraud review, complaint triage | A quality, access, or governance failure could propagate into different customer-facing outcomes. | Assign one data owner; monitor quality and permitted use across both decisions; test downstream effects when definitions change. |

These are **shared exposures**, not reasons to merge the decisions. The business purpose, acceptable errors, human authority, and controls still need to be assessed separately for each use.

## Six cases behind the view

### 1. Fraud alert review — high consequence, live prediction

**Decision:** Which transactions warrant analyst review or intervention? The AI estimates fraud likelihood; it does not itself decide to block every flagged transaction. A false positive can disrupt a legitimate customer, while a false negative can permit loss. The Risk Operations Lead owns the operating threshold and escalation policy. Portfolio oversight should examine whether customer-profile data changes simultaneously alter this use and complaint triage.

### 2. Maintenance prioritization — high consequence, pilot recommendation

**Decision:** Which requests receive technicians first? AI recommends a ranking, but the Regional Service Director approves the daily plan. Safety cases and unfamiliar equipment bypass routine ranking for specialist review. During the pilot, the organization should compare human-only and AI-supported prioritization and record both correct and incorrect overrides. The shared AI platform means a vendor update must be tested against this workflow, not just the fraud workflow.

### 3. Promotion evidence check — high consequence, design-stage analysis

**Decision:** What evidence should a human promotion panel consider, and has it applied stated criteria consistently? AI may check completeness or reveal inconsistent application of criteria. It must not automatically rank candidates or make a final promotion choice. Historical promotion data may reproduce earlier opportunity gaps, so the Chief People Officer must justify any data use, examine adverse impact, and provide correction routes.

### 4. Customer complaint triage — medium consequence, pilot recommendation

**Decision:** Which team and urgency level should receive each complaint? AI extracts information and suggests routing. A missed urgent complaint may have serious consequences even if most misroutes are merely inconvenient; sensitive and uncertain cases therefore require review. The Customer Care Lead should monitor language and channel differences, customer corrections, and whether shared customer-profile data are appropriate for this purpose.

### 5. Market-entry scenarios — medium consequence, design-stage analysis

**Decision:** Should the organization enter a new market, and under what conditions? AI can synthesize evidence and compare scenarios, but strategic trade-offs, uncertainty, and commitment remain with the executive team. The Strategy Director should record assumptions and use the system to test alternatives rather than treating a generated recommendation as a verdict.

### 6. Routine stock replenishment — low consequence, live bounded automation

**Decision:** Should an approved standard item be reordered within pre-agreed quantity and value limits? AI may automate routine orders because cases repeat, outcomes are measurable, and errors are usually reversible. The Supply Chain Lead still owns thresholds, supplier policy, exceptions, and the stop switch. Any unusual order size, price, supplier change, or data-pipeline failure exits the automated path.

## What the portfolio reveals that individual canvases may miss

1. **Concentration risk:** Three decisions depend on the same provider. Independent case approvals will not detect the full impact of a provider-wide change or outage.
2. **Data propagation:** The same customer-profile data feed two different decisions. A changed definition, missing field, or access problem can create correlated errors.
3. **Authority distribution:** The only automated point is low consequence and bounded. High-consequence uses retain active human authority, but this must be verified in actual workflows, not inferred from policy labels.
4. **Lifecycle clustering:** Two uses are live, two are pilots, and two are in design. Governance capacity must cover operation and incident response as well as new approvals.
5. **Cumulative customer impact:** A customer may be affected by both fraud review and complaint triage. Portfolio monitoring should look for repeated friction, not only error rates inside each process.
6. **Control consistency:** Similar escalation terms such as “high value” or “low confidence” may mean different things across teams. The organization needs common definitions where useful without imposing one threshold on unlike decisions.

## Portfolio operating model

Each decision owner remains accountable for their own decision process. A central portfolio steward—such as an AI governance lead or cross-functional risk committee—maintains the inventory and challenges shared risks. The steward does not replace the decision owner or become the universal approver of every case.

| Cadence | Review question | Typical participants | Output |
|---|---|---|---|
| **Weekly operational review** | Are incidents, overrides, drift signals, or customer challenges emerging? | Decision owners, operations, system and data owners | Corrective actions and escalations |
| **Monthly portfolio review** | Are shared vendors, data, thresholds, or teams creating correlated risk? | Portfolio steward, risk, legal/privacy, technology, affected business owners | Cross-decision risk actions and priority changes |
| **Quarterly executive review** | Does the portfolio still support strategy and risk appetite? Should authority or scale change? | Executive sponsors and governance leadership | Continue, expand, restrict, or retire decisions |

An incident in one decision should trigger review of other decisions using the same component, data source, model version, vendor, or policy. This cross-decision impact check is the essential difference between a portfolio view and six separate dashboards.

## Minimum fields for a real portfolio register

- Decision name, purpose, and decision owner
- AI role and specific decision point affected
- Consequence tier and rationale
- Affected people or groups
- Deployment stage and approved scope
- Model, vendor, data, and policy dependencies
- Human review, escalation, override, and stop conditions
- Value measures and guardrail measures
- Recent incidents, appeals, overrides, and outcome trends
- Last approval, next review date, and open actions

The portfolio should be updated when a decision changes purpose, data, model, authority, affected population, or operating context—not only when a new AI tool is purchased.

---

# 27. Facilitation guide

## Recommended 120-minute agenda

| Time | Activity | Purpose |
|---|---|---|
| 0–10 min | Opening case and individual vote | Expose assumptions about AI and authority |
| 10–25 min | Start with the decision | Practice writing a decision statement |
| 25–40 min | Decision chain and decomposition | Locate the real decision points and owners |
| 40–55 min | Uncertainty and value of data | Distinguish useful evidence from more data |
| 55–70 min | AI suitability and role ladder | Choose whether and where AI fits |
| 70–85 min | Error consequences and automation bias | Move beyond headline accuracy |
| 85–100 min | Oversight and accountability | Design review, override, stop, and ownership |
| 100–115 min | Canvas team exercise | Apply the full method |
| 115–120 min | Executive conclusion | Commit to a go, no-go, or bounded pilot position |

## Opening case prompt

> A business unit proposes an AI system that predicts which customers are likely to cancel. The vendor reports 88% accuracy and estimates that the system could save the retention team 30% of its time. Should the organization deploy it?

Ask participants to vote yes, no, or not enough information. Then ask what they would need to know. Expected questions include:

- What decision will the prediction change?
- What is the current cancellation rate?
- What does “accuracy” mean?
- What intervention follows a high-risk score?
- What are the costs of unnecessary contact and missed customers?
- Does the retention team have capacity to act?
- Which customers were represented in evaluation data?
- Could the intervention itself affect cancellation?
- Who owns the threshold and final action?

The purpose is not to find one answer. It is to demonstrate that model performance is only one part of decision suitability.

## Facilitation notes by topic

### Decision definition

Listen for technology nouns replacing decision verbs. If a group says “the decision is predictive maintenance,” ask: “Who chooses what action, and when?”

### Decomposition

Participants may describe a workflow without identifying points of choice. Ask: “Where could two reasonable people choose differently?” and “Which of those choices carries the consequence?”

### Uncertainty

Groups often label all missing data as equally important. Ask: “If you knew this, would you choose differently?”

### AI role

Push for a precise verb. “Support” is too broad. Ask whether AI observes, analyzes, predicts, recommends, or acts.

### Oversight

If the answer is “a human will review,” ask who, with what evidence, under what time pressure, with what authority, and against which trigger.

### Accountability

If multiple owners are named, ask who signs the go-live or continued-operation decision and who answers when an affected person challenges an outcome.

## Common misconceptions and responses

| Misconception | Facilitator response |
|---|---|
| “The system is objective because it uses data.” | Data reflect choices about measurement, inclusion, labels, history, and objectives. Ask which human decisions created the target and dataset. |
| “A human approves every result, so the risk is covered.” | Test whether the human has time, evidence, competence, and authority to disagree. |
| “Higher accuracy is always better.” | Ask which errors changed, for whom, and at what operating threshold. |
| “We can remove bias by excluding sensitive fields.” | Other fields may act as proxies, and bias can enter through labels, sampling, objectives, workflow, and unequal consequences. |
| “The vendor is responsible for the AI.” | The organization still owns the decision to deploy, the operating context, the action, and obligations to affected people. |
| “Automation will remove cost.” | Add integration, monitoring, review, exceptions, incidents, change management, and exit cost. |
| “If the pilot works, we can scale it everywhere.” | Evidence is bounded by the pilot’s population, context, users, volume, and operating conditions. |

---

# 28. Assessment rubric for the AI Decision Suitability Canvas

Score each dimension from 1 to 4.

| Dimension | 1 — Weak | 2 — Developing | 3 — Sound | 4 — Executive-ready |
|---|---|---|---|---|
| **Decision clarity** | Technology or task is named, but no decision | Some choice and outcome are visible | Owner, choice, timing, outcome, and constraints are clear | Frame, alternatives, dependencies, and boundaries are explicit |
| **Decomposition and ownership** | Decision treated as one block | Some steps identified | Material decision points and owners identified | Evidence, challenge, action, and affected-party roles also clear |
| **Uncertainty and data** | Assumes more data are better | Missing data listed | Decision-relevant uncertainty and data fitness assessed | Value of information, proxies, provenance, and feedback quality addressed |
| **AI suitability** | AI presumed necessary | Benefits asserted with limited comparison | Fit and non-AI alternatives evaluated | Go/no-go logic is evidence-based and limitations are explicit |
| **AI role and boundary** | “AI support” is undefined | General role named | Specific role attached to a decision point | Least-authoritative role selected with prohibited uses defined |
| **Error consequences** | Accuracy is the only measure | Some errors acknowledged | False positives, false negatives, and affected parties analyzed | Severity, distribution, reversibility, scale, and unexpected cases addressed |
| **Human judgment** | Human involvement is symbolic | Reviewer is named | Reviewer has information, time, competence, and authority | Judgment domains, incentives, escalation, and independent challenge are designed |
| **Value and measurement** | Efficiency claim only | A benefit metric exists | Baseline, value, and guardrail measures defined | Model, human–AI, workflow, outcome, and distribution measures linked |
| **Oversight and controls** | Generic monitoring promised | Some controls named | Review, override, stop, and feedback triggers defined | Controls are tested, resourced, logged, and tied to owners and thresholds |
| **Accountability and lifecycle** | Responsibility assigned to team or vendor | Some owners named | Executive, decision, system, data, control, and remediation ownership defined | Stage gates, reapproval, incident, appeal, and retirement responsibilities complete |

## Interpretation

- **34–40:** Suitable for executive go/no-go consideration, subject to supporting evidence.
- **26–33:** Promising but requires targeted design work before approval.
- **18–25:** Material gaps; reframe the decision or redesign the intervention.
- **10–17:** Not ready for AI evaluation or deployment.

A high score does not prove that AI should be used. A well-completed canvas may produce a clear, well-supported “no.”

---

# 29. Glossary

**Accountability:** The obligation of a person or organization to answer for decisions, actions, and consequences and to take corrective action where needed.

**AI decision support:** Use of AI to supply observations, analysis, predictions, or recommendations while a human or organizational process retains final decision authority.

**Automation bias:** A tendency to over-rely on automated output, including following incorrect advice or failing to notice a problem that was not flagged.

**Calibration:** The degree to which predicted probabilities correspond to observed frequencies.

**Concept drift:** A change in the relationship between inputs and the outcome being predicted.

**Contestability:** The practical ability of an affected person to question an outcome and seek review or correction.

**Decision owner:** The person with authority and accountability for a decision or decision policy.

**Decision point:** A specific choice within a wider process where alternatives exist.

**False negative:** A case the system fails to flag even though the target condition is present.

**False positive:** A case the system flags even though the target condition is absent.

**Ground truth:** The reference used to determine the correct label or outcome. Ground truth may itself contain uncertainty, delay, or human judgment.

**Human-in-the-loop:** A configuration in which a person reviews or approves individual outputs before action.

**Human-on-the-loop:** A configuration in which a person supervises an operating system and intervenes in exceptions or when monitoring indicates a problem.

**Human-over-the-loop:** Governance of the overall purpose, policy, boundaries, risks, and continued use of the system.

**Model drift:** A decline or change in model performance over time, potentially caused by changes in data, behavior, environment, or operations.

**Precision:** The proportion of flagged cases that are true positives.

**Proxy:** A measurable variable used as a substitute for another concept that is harder to observe directly.

**Recall or sensitivity:** The proportion of true target cases correctly detected.

**Residual risk:** Risk remaining after controls have been applied.

**Risk tolerance:** The amount and type of risk an organization is willing to accept in pursuit of its objectives.

**Threshold:** The operating cutoff at which a score or probability produces a different classification or action.

**Value of information:** The improvement in a decision that could result from obtaining additional evidence, considering its cost and timing.

---

# 30. Reference notes and further reading

## Core governance frameworks

1. National Institute of Standards and Technology. *Artificial Intelligence Risk Management Framework (AI RMF 1.0).* 2023. [Official publication](https://doi.org/10.6028/NIST.AI.100-1). Useful for governance, context mapping, measurement, human oversight, risk treatment, monitoring, and feedback.
2. NIST Trustworthy and Responsible AI Resource Center. [AI RMF Core and Playbook resources](https://airc.nist.gov/airmf-resources/airmf/5-sec-core/). Useful for operational practices and lifecycle risk management.
3. Organisation for Economic Co-operation and Development. [OECD AI Principles](https://oecd.ai/en/ai-principles), updated 2024. Useful for human-centred values, transparency, robustness, and accountability.
4. U.S. Government Accountability Office. *Artificial Intelligence: An Accountability Framework for Federal Agencies and Other Entities.* 2021. [GAO-21-519SP](https://www.gao.gov/products/gao-21-519sp). Useful for governance, data, performance, monitoring, and audit questions.

## Human oversight and automated decisions

5. Parasuraman, R., Sheridan, T. B., and Wickens, C. D. “A Model for Types and Levels of Human Interaction with Automation.” *IEEE Transactions on Systems, Man, and Cybernetics—Part A*, 30(3), 2000. [Author-hosted PDF](https://www.cs.uml.edu/~holly/91.550/papers/sheridan-autonomy.pdf). Provides a foundational distinction among information acquisition, information analysis, decision selection, and action implementation.
6. European Union. *Regulation (EU) 2024/1689 (Artificial Intelligence Act).* [Official text on EUR-Lex](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32024R1689). Article 14 addresses human oversight for high-risk systems; Article 26 includes obligations for deployers of high-risk systems.
7. UK Information Commissioner’s Office. [Guidance on AI and data protection](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/artificial-intelligence/guidance-on-ai-and-data-protection/). Useful for meaningful human review, automation bias, individual rights, explainability, and data-protection risk.

## How the references inform this module

| Module concept | Main supporting source |
|---|---|
| Begin with purpose, context, and a go/no-go decision | NIST AI RMF Map and Manage functions |
| Compare benefits, monetary and non-monetary costs, and risk | NIST AI RMF Map 3 |
| Observe, analyze, decide, and act as distinct automation functions | Parasuraman, Sheridan, and Wickens |
| Human oversight must be proportionate and operationally effective | EU AI Act Article 14; NIST AI RMF |
| People need information to understand and challenge outcomes | OECD transparency principle; ICO guidance |
| Accountability, traceability, and lifecycle risk management | OECD accountability principle; GAO framework |
| Test before deployment and monitor in operation | NIST AI RMF Measure; GAO monitoring principle |
| Feedback and appeal are part of system performance | NIST AI RMF Measure 3.3; OECD transparency principle; ICO guidance |

---

# Closing message

AI does not improve decisions merely by being present. It creates value when it is assigned a precise, evidence-based role inside a decision process that has clear goals, capable human judgment, meaningful oversight, and accountable ownership.

The leadership task is not to maximize the number of decisions touched by AI. It is to design better decision systems—and to know when AI belongs in them.

<a id="module-2"></a>

# Module 2: Decision Framing — From Symptoms and Problems to Decisions

## Module purpose

Organizations frequently solve the wrong problem well. A visible symptom becomes a project, an assumed cause becomes a fact, and a preferred solution becomes the decision before alternatives have been considered.

This module teaches a disciplined path:

> **Symptom → problem → possible causes → tested root-cause explanation → decision → action**

The goal is not to eliminate all uncertainty before acting. It is to frame a decision clearly enough that leaders know what must be chosen, who owns the choice, which assumptions remain, what evidence matters, and which stakeholders must be involved.

The module produces four evolving artifacts:

1. A **Root Cause Analysis**
2. A **Decision Statement**
3. A **Stakeholder Map**
4. An **Assumption Log**

Together with Module 1's **AI Decision Suitability Canvas**, these form the Phase 1 decision portfolio.

---

## Intended audience

- Executives and managers responsible for organizational decisions
- Strategy, transformation, operations, data, and technology teams
- Product and program leaders
- Analysts who translate business concerns into decision support
- Cross-functional teams considering AI-enabled interventions

## Suggested duration

120–180 minutes, preferably delivered as two sessions with application work between them. The mastery-based format may take longer because the facilitator does not advance until the learner can apply the concepts.

## Learning outcomes

By the end of the module, the learner will be able to:

1. Distinguish a symptom from a problem, cause, decision, and solution.
2. Conduct a proportionate root-cause inquiry without converting assumptions into facts.
3. Use the 5 Whys as a branching, evidence-seeking method rather than a ritual.
4. Apply the course's 4P Decision Framework.
5. Identify, classify, and prioritize assumptions for validation.
6. Map decision owners, affected parties, implementers, evidence providers, and challengers.
7. Write a concise, actionable decision statement.
8. Reframe a solution-first proposal into a decision that allows genuine alternatives.

## Expected competency

The learner demonstrates competence by independently:

- Identifying plausible root causes systematically
- Writing a decision statement with owner, choice, timing, objective, evidence, and constraints
- Separating facts, interpretations, assumptions, and hypotheses
- Identifying whose interests, knowledge, authority, and exposure matter
- Validating the highest-risk assumptions before proposing or approving a solution

## Evidence base and terminology

The 5 Whys guidance in this module follows the principle described by the [American Society for Quality](https://asq.org/quality-resources/five-whys): repeat “why” until the inquiry reaches useful causal depth; the number may be fewer or greater than five. UK Ministry of Defence quality guidance likewise describes the method as iterative, notes that a problem may have multiple root causes, and recommends it mainly for simple to moderately difficult problems. See [JSP 940, Part 2](https://assets.publishing.service.gov.uk/media/687918b30263c35f52e4ddb9/JSP_940_Ministry_of_Defence_policy_for_Quality__part_2_guidance.pdf).

Decision-statement guidance is aligned with [Structured Decision Making](https://www.structureddecisionmaking.org/the-steps/decision-statements/), which emphasizes the decision maker, problem, actions under consideration, objectives, timeframe, location, and constraints. Stakeholder mapping draws on the UK Government Analysis Function's [stakeholder-mapping guidance](https://analysisfunction.civilservice.gov.uk/policy-store/stakeholder-mapping/), while extending it to distinguish formal power from exposure to consequences.

There is no single universally accepted “4P Decision Framework.” This course deliberately defines its own version—**Problem, People, Process, and Parameters**—as a memory aid for decision framing. It should not be presented as an external standard.

---

# 1. Learning method: the mastery loop

Every major concept uses the same sequence:

1. **Elicit:** Ask what the learner already knows or believes.
2. **Introduce:** Explain one concept, distinction, or tool.
3. **Challenge:** Present counterevidence or a difficult question.
4. **Apply:** Use a realistic business case.
5. **Solve:** Require the learner to make and defend a choice.
6. **Critique:** Evaluate reasoning, not merely the conclusion.
7. **Reveal:** Surface blind spots, assumptions, missing stakeholders, or weak evidence.
8. **Improve:** Revise the relevant artifact together.

The facilitator should not move to the next concept until the learner can explain the current one in their own words and apply it to a different case.

## Opening diagnostic

Before teaching, ask the learner:

1. What is the difference between a symptom and a problem?
2. What makes something a root cause rather than a contributing factor?
3. If leaders already prefer a solution, what is the decision?
4. Who should define a problem: the budget owner, the process owner, or the person experiencing it?
5. What assumption in a recent decision turned out to be wrong?

Record the answers. Return to them at the end of the module so the learner can identify how their reasoning changed.

---

# 2. Symptoms, problems, causes, decisions, and solutions

These terms describe different elements of reasoning. Treating them as interchangeable creates premature solutions.

| Element | Meaning | Example: maintenance operations | Diagnostic question |
|---|---|---|---|
| **Symptom** | An observable sign that current performance differs from what is expected or desired | Median triage time is 45 minutes; urgent requests are sometimes ranked too low | What is visibly happening? |
| **Problem** | A consequential gap between the current and desired state, affecting particular people or objectives | Maintenance requests are not prioritized reliably or quickly enough to meet service and safety needs | Why does this gap matter, to whom, and under what conditions? |
| **Cause** | A factor that contributes to the problem through a plausible mechanism | Requests often lack equipment IDs; urgency labels differ by region | How could this factor produce the observed gap? |
| **Root cause** | A sufficiently upstream, evidence-supported cause that is actionable and whose treatment would materially reduce recurrence | Intake was designed for logging requests rather than providing decision-quality information, with no owner for shared triage standards | If this changed, would the problem recur less often? |
| **Decision** | A choice among feasible alternatives under an accountable owner | Should Northstar standardize intake and triage before testing AI-assisted prioritization, and how? | Who must choose what, by when? |
| **Solution** | An action selected after the decision | Redesign the form, harmonize urgency definitions, train intake staff, and run a bounded pilot | Which alternative was chosen, and why? |

## Why symptoms are seductive

Symptoms are visible and urgent. Leaders often attach a familiar solution to them:

- Sales are down → launch a campaign.
- Customer complaints are up → install a chatbot.
- Decisions are slow → automate them.
- Staff turnover is high → add a retention bonus.
- Equipment downtime is rising → buy predictive maintenance software.

Each proposal may eventually be appropriate. None follows logically from the symptom alone.

## Three tests

### The observation test

Can the statement be verified without accepting an explanation?

“Complaints rose 20%” is an observation. “Customers are dissatisfied because agents are poorly trained” contains a causal interpretation.

### The intervention test

Does the statement already name what should be done?

“We need an AI chatbot” is a solution. “Customers wait too long for answers to routine account questions” is closer to a problem.

### The ownership test

Does the statement reveal who must make a choice?

“Improve customer service” is an aspiration. “The Customer Care Director must choose how to reduce response time within the current staffing budget” is a decision frame.

## Mastery check

Classify each statement, then rewrite any mixed statement:

1. “We need AI to reduce churn.”
2. “Monthly churn rose from 4% to 7%.”
3. “Should the Chief Product Officer prioritize reliability fixes, retention offers, or both during the next two quarters?”
4. “Support delays caused churn.”
5. “New customers who experienced two or more crashes churned at a higher observed rate.”

Do not proceed until the learner recognizes that statements 1 and 4 contain unverified assumptions, statement 2 is a symptom, statement 3 is a decision, and statement 5 is evidence of an association rather than proof of cause.

---

# 3. Define the problem before explaining it

A problem statement should describe the performance gap without embedding an unverified cause or preferred solution.

## Problem statement template

> **[Population or process]** is experiencing **[observable gap]** during **[time and context]**, compared with **[expected state or standard]**, resulting in **[material consequence]**. The scope includes **[boundary]** and excludes **[boundary]**.

Example:

> Across Northstar's four service regions, routine maintenance requests take a median of 45 minutes to receive a priority and 12% of later-confirmed urgent cases are initially ranked too low, compared with the required 30-minute decision standard and agreed safety/service thresholds. This framing covers request intake and prioritization but not technician repair quality after arrival.

This does not state that poor forms, inadequate staffing, or a lack of AI caused the problem. Those remain hypotheses.

## The problem-quality checklist

- Is the affected population or process specified?
- Is the gap observable and measurable?
- Is there a meaningful comparison or expected state?
- Are timing and operating context clear?
- Are consequences described without exaggeration?
- Is the scope narrow enough to investigate but wide enough to avoid hiding causes?
- Is causal language reserved for findings supported by evidence?

## Challenge question

If the observed metric returned to target tomorrow, would the underlying concern be resolved? If not, the metric may be a symptom or proxy rather than the problem itself.

---

# 4. Root cause analysis

Root cause analysis is a structured effort to explain why a problem occurs and what changes could prevent or materially reduce recurrence. It is not a search for one person to blame, and it does not guarantee a single ultimate cause.

## Root cause versus contributing factor

A factor is useful to call a root cause when it is:

- **Causally plausible:** A credible mechanism connects it to the problem.
- **Evidence-supported:** Observations, records, experiments, interviews, or process evidence support the link.
- **Upstream enough:** It explains why more immediate failures occurred.
- **Actionable:** The organization can intervene on it or protect against it.
- **Material:** Changing it would likely reduce recurrence or consequence.

A contributing factor may worsen the problem without being sufficient or primary. Multiple contributing factors can interact. For a complex organizational problem, a causal map is often more honest than one root-cause label.

## A proportionate RCA process

### Step 1: Stabilize urgent harm

If safety, legal, customer, or operational harm is continuing, contain it first. Investigation should not delay necessary protection.

### Step 2: Define the event or gap

Specify what happened, when, where, to whom, at what frequency, and against which expectation.

### Step 3: Gather multiple forms of evidence

Use quantitative records, process traces, direct observation, documents, and interviews with people who perform and experience the work. Do not rely only on management interpretation.

### Step 4: Map the actual process

Document what happens in practice, including workarounds, queues, handoffs, exceptions, and incentives. The written procedure may not describe the real process.

### Step 5: Generate several causal hypotheses

Ask what could produce the same evidence. Include people, process, policy, information, technology, environment, workload, and incentives.

### Step 6: Test causal links

For each proposed cause, ask:

- Did it precede the problem?
- Is the mechanism credible?
- Does the pattern appear where the cause is present and weaken where it is absent?
- What alternative explanation fits the same evidence?
- What observation would disconfirm this hypothesis?
- Would changing it plausibly prevent recurrence?

### Step 7: Identify intervention points

Distinguish immediate containment, corrective action, and systemic prevention. The deepest cause is not always the best first intervention; choose based on value, feasibility, and risk.

### Step 8: Convert findings into a decision

RCA does not choose the action. Leaders still need a decision statement that names the owner, alternatives, objectives, timeframe, evidence, and constraints.

## Common RCA failures

- Stopping at “human error” without examining the system that shaped the action
- Selecting the first plausible story
- Asking only people who designed or manage the process
- Treating correlation as proof
- Searching for one root cause in a complex adaptive system
- Describing a missing control as a cause without asking why it was absent
- Recommending training for every problem
- Using RCA to validate a solution already selected

---

# 5. The 5 Whys Framework

The 5 Whys repeatedly asks why a problem occurred, using each answer as the starting point for the next question. “Five” is a prompt for depth, not a required number. Stop when the team reaches an actionable, evidence-supported causal explanation—or change tools when the problem branches or becomes too complex.

## Procedure

1. Start with a precise, observable problem statement.
2. Ask why it occurred.
3. Record the answer as a causal hypothesis, not a fact.
4. Ask what evidence supports the link.
5. Ask why that condition existed.
6. Branch when more than one cause is plausible.
7. Stop or change methods when additional “whys” become speculation, leave organizational control, or merely restate the problem.
8. Validate the important causal links before selecting a solution.

## Worked example: Northstar's delayed maintenance triage

**Problem:** Later-confirmed urgent maintenance requests are sometimes ranked too low, and priority decisions take longer than the required standard.

| Inquiry | Provisional answer | Evidence required |
|---|---|---|
| Why are some urgent requests ranked too low? | Decision makers do not consistently receive the information needed to recognize urgency. | Review misranked tickets and interview decision makers. |
| Why is decision-relevant information missing or inconsistent? | Some requests use free text and omit equipment, hazard, or impact fields. | Field-completeness audit by channel and region. |
| Why can critical fields be omitted? | The intake process was designed to record a service request, not to support prioritization. | Original form requirements and workflow history. |
| Why was prioritization not included in the design? | Regions developed local urgency practices after the intake system was introduced. | Policy timeline, regional procedures, governance records. |
| Why were local practices not reconciled? | No single owner was accountable for shared triage definitions and decision-quality inputs. | Role descriptions, governance minutes, decision rights. |

This chain suggests a governance and process-design hypothesis. It does not prove that appointing an owner alone will solve the problem. Other branches may include workload peaks, inconsistent safety language, sensor coverage, or dispatcher incentives.

## Branching example

At the first “why,” the team might find two independent paths:

- **Information path:** Requests lack the facts needed for triage.
- **Capacity path:** Even correctly identified urgent work cannot be prioritized because specialist technicians or parts are unavailable.

Solving the information path alone would improve classification but might not improve outcomes if the capacity constraint dominates. A linear 5 Whys chain would hide that interaction.

## When not to rely on 5 Whys alone

Use a causal map, fishbone diagram, fault tree, process analysis, or specialist investigation when:

- Many causes interact
- The event is rare or catastrophic
- Evidence is disputed or technically complex
- Several teams or organizations contribute
- Feedback loops exist
- The inquiry concerns safety, legal exposure, or serious harm

## Mastery check

Ask the learner to challenge the Northstar chain:

- Which answers are observations, and which are hypotheses?
- What alternative branch is missing?
- What evidence could disprove the “no single owner” explanation?
- Could the process work even without a single owner?
- What intervention could test the explanation before a major redesign?

---

# 6. The course 4P Decision Framework

The 4P framework prevents a team from defining a decision only from the technology or senior leader's perspective.

## P1 — Problem

Define the consequential gap:

- What is happening?
- What should be happening?
- Who experiences the gap?
- When and where does it occur?
- How large or frequent is it?
- What evidence supports the claim?
- What remains unknown?

**Output:** A neutral problem statement and a shortlist of tested or testable causal hypotheses.

## P2 — People

Identify authority, expertise, exposure, and incentives:

- Who owns the decision?
- Who performs the process?
- Who supplies evidence?
- Who implements the chosen action?
- Who is affected, including people with little formal power?
- Who can challenge, block, or reverse the decision?
- Whose incentives or workload could change behavior?

**Output:** A stakeholder map with roles and an engagement plan.

## P3 — Process

Understand how the current system actually works:

- What triggers the process?
- What information enters, and from where?
- Where are interpretation and choice required?
- What handoffs, queues, controls, and exceptions exist?
- Where do delays, rework, missing information, or conflicting rules occur?
- How do outcomes feed back into future decisions?

**Output:** A current-state process and decision map, with root-cause hypotheses tied to specific points.

## P4 — Parameters

Define the decision's operating boundaries:

- What outcomes and success measures matter?
- What alternatives are genuinely available?
- What is the timeframe?
- What budget, capacity, policy, safety, ethical, or legal constraints apply?
- What risk is unacceptable?
- What evidence would change the choice?
- What assumptions or dependencies could invalidate the frame?

**Output:** An actionable decision statement and prioritized assumption log.

## The completed 4P frame

| 4P | Northstar example |
|---|---|
| **Problem** | Triage is slower and less reliable than required; some urgent cases are initially ranked too low. Intake design and fragmented standards are plausible contributors, not yet fully validated causes. |
| **People** | Site contacts, intake coordinators, service directors, dispatchers, technicians, safety supervisors, customers, data/system owners, and operational risk. |
| **Process** | Request submitted → information checked → safety screen → urgency interpreted → priority approved → technician assigned → outcome recorded. Breakdowns occur at missing fields, regional labels, and handoffs. |
| **Parameters** | Preserve safety escalation; meet service obligations; target a 30-minute priority decision; compare process/rule changes before AI; work within staffing and system constraints. |

## 4P quality challenge

The four categories do not prove causation and do not automatically generate the right choice. They ensure that the team has examined the main dimensions required to frame the decision. Every important claim still needs an evidence status.

---

# 7. Identify and validate assumptions

An assumption is something treated as true for the purpose of reasoning, despite incomplete evidence. Assumptions are unavoidable; hidden assumptions are dangerous.

## Separate four evidence states

| State | Meaning | Example |
|---|---|---|
| **Fact or observation** | Directly supported within a defined source and scope | In the audited sample, 15% of requests lacked a reliable equipment ID. |
| **Interpretation** | A meaning assigned to observations | The form may not match the information needs of prioritization. |
| **Assumption** | Accepted provisionally so planning can continue | Standardizing required fields will reduce clarification time. |
| **Hypothesis** | A testable explanation or predicted relationship | Missing equipment IDs cause longer triage time and more priority errors. |

Calling something a fact does not make it universal. Every fact has a source, definition, time window, and population.

## Assumption categories

- **Causal:** We believe X contributes to Y.
- **Behavioral:** We expect people to respond in a particular way.
- **Data:** We assume data are available, representative, permitted, and meaningful.
- **Operational:** We assume the organization can execute the action.
- **Economic:** We assume benefits exceed total costs.
- **Strategic:** We assume objectives or external conditions will remain relevant.
- **Ethical or legal:** We assume the action is acceptable and permitted.
- **Technology:** We assume a system will perform, integrate, and remain available as required.

## Assumption log

| ID | Assumption | Category | Evidence today | If wrong | Uncertainty | Impact | Test or source | Owner | Review date | Status |
|---|---|---|---|---|---|---|---|---|---|---|
| A1 | Required equipment and hazard fields will reduce clarification time | Causal / operational | Misranked-ticket review suggests missing fields are common | Form redesign adds work without improving decisions | Medium | High | Pilot new form in one region; compare time and completeness | Intake Process Owner | Week 4 | Open |
| A2 | Site contacts can provide the required fields accurately | Behavioral / data | Not yet established | More mandatory fields create inaccurate entries or abandonment | High | High | Usability test and observation with site contacts | Customer Service Lead | Week 2 | Open |
| A3 | Regional urgency definitions can be harmonized without violating local obligations | Operational / policy | Definitions differ; constraints not mapped | One standard could suppress legitimate local differences | Medium | High | Policy review with all regional and safety owners | Operations Risk Lead | Week 3 | Open |

## Prioritize assumptions

Test assumptions with the highest combination of **uncertainty and consequence** first. Do not spend most of the effort proving what is already well-supported and low impact.

For every high-priority assumption, ask:

- Why do we believe this?
- What evidence supports it?
- What evidence would weaken it?
- What is the cheapest ethical test that could change our mind?
- Who owns obtaining the evidence?
- When will the decision be revisited?

---

# 8. Stakeholder mapping for decisions

A stakeholder is not merely someone who needs a project update. For decision framing, stakeholders contribute different things: authority, knowledge, implementation capacity, challenge, or exposure to consequences.

## Stakeholder roles

- **Decision owner:** Has formal authority and accountability for the choice.
- **Sponsor:** Provides mandate, resources, and risk acceptance.
- **Evidence provider:** Supplies operational, technical, financial, customer, or specialist knowledge.
- **Process performer:** Does the work and understands real workflows and exceptions.
- **Action owner:** Implements the selected alternative.
- **Control or challenger:** Tests assumptions, risks, and compliance.
- **Affected party:** Receives benefits, burdens, risks, or changes in treatment.
- **Remediation owner:** Corrects harm, complaints, or appeal outcomes.

One stakeholder can occupy several roles. The decision owner should still be singular or explicitly governed; “the committee owns it” often conceals unclear accountability.

## Power–interest is not enough

A power–interest grid helps plan engagement, but a low-power person may experience the greatest consequence. Add two questions:

1. How strongly is this stakeholder affected?
2. What unique knowledge would be lost if they were excluded?

Never interpret “low power” as “low importance.”

## Stakeholder-map template

| Stakeholder | Decision role | Power or influence | Degree affected | Knowledge contributed | Main interest or concern | Required involvement |
|---|---|---:|---:|---|---|---|
| Regional Service Director | Decision owner | High | High | Prioritization trade-offs | Service, safety, capacity | Own framing and approve decision |
| Site contact / customer | Request originator, affected party | Low–medium | High | Symptoms and operational impact | Fast, accurate service | Research, usability test, feedback route |
| Intake coordinator | Process performer | Medium | High | Real intake exceptions and workload | Practical workflow | Co-design and pilot observation |
| Field technician | Evidence provider, action performer | Medium | High | Actual equipment condition and repair needs | Safe, workable schedule | Process mapping, challenge, outcome feedback |
| Safety supervisor | Specialist authority | High | High | Hazard assessment | No unsafe bypass | Define non-negotiable controls |
| Technology/Data owner | System and data owner | Medium | Medium | Data feasibility and limitations | Integrity, integration | Validate data and implementation options |
| Operational Risk Lead | Independent challenger | High | Medium | Risk and control analysis | Residual risk and accountability | Challenge and gate approval |

## Stakeholder blind spots

- Mapping only formal leaders
- Treating consultation as decision authority
- Asking frontline staff after the solution has been selected
- Ignoring people who must provide additional data or absorb review work
- Failing to identify whose outcome worsens when another group's improves
- Assuming stakeholder positions will remain stable
- Using the map only as a communications plan rather than an evidence source

---

# 9. Write the decision statement

A decision statement converts analysis into a clearly owned choice. It should be neutral enough to allow genuine alternatives and specific enough to guide evidence gathering.

## Core template

> **[Decision owner]** must decide **[choice among types of action]** by **[time or frequency]**, using **[decision-relevant evidence]**, to achieve **[objectives and measures]**, while respecting **[constraints, boundaries, and unacceptable risks].**

## Question form

> What is the best way for **[owner]** to **[address the problem or achieve the objective]** by **[time]**, considering **[main alternatives and evidence]**, within **[constraints]?**

## Northstar decision statement

> By the end of the quarter, the Chief Operating Officer must decide how Northstar will improve the completeness and consistency of maintenance-request intake and prioritization across four regions—through process redesign, harmonized rules, capability changes, AI-supported decision tools, or a combination—to reduce median priority-decision time toward 30 minutes and reduce missed urgent cases while preserving mandatory safety review, service obligations, and feasible frontline workload.

## Decision-statement tests

- **Owner test:** Is one accountable decision maker or governing body named?
- **Choice test:** Does a real choice remain, rather than a disguised approval request?
- **Objective test:** Is the outcome different from the proposed solution?
- **Evidence test:** Does the frame reveal what information could distinguish alternatives?
- **Boundary test:** Are scope, timeframe, and major constraints explicit?
- **Neutrality test:** Could a reasonable analysis support more than one answer?
- **Actionability test:** Would a decision produce a clear next action?

## Weak-to-strong examples

| Weak framing | Why it is weak | Stronger decision framing |
|---|---|---|
| “Should we buy the AI triage tool?” | Starts with one solution and vendor | “How should we improve maintenance prioritization, and what role, if any, should AI play?” |
| “Fix customer service.” | No owner, choice, target, or boundary | “Which combination of process, staffing, and self-service changes should the Customer Care Director implement next quarter to reduce response time within budget and quality constraints?” |
| “Why are employees leaving?” | Investigation question, not yet a decision | “Which controllable working conditions should the People Leadership Team change this year to retain critical roles without creating inequitable treatment?” |

---

# 10. From root cause to actionable decision framing

Root-cause analysis and decision framing answer different questions:

- RCA asks, **“Why is the problem occurring?”**
- Decision framing asks, **“What choice must now be made?”**

The bridge between them has five steps:

1. Confirm the problem and its consequence.
2. Identify evidence-supported causes and remaining causal uncertainty.
3. Translate causes into feasible intervention points.
4. Generate alternatives that act on different intervention points.
5. Frame the choice without assuming which alternative will win.

## Alternative-generation example

Northstar's causal inquiry suggests missing fields, inconsistent labels, and fragmented ownership. Feasible alternatives include:

- Standardize the intake form and urgency definitions
- Add specialist triage during peak hours
- Introduce a fixed-rule decision aid
- Add AI-supported extraction and ranking after data improvements
- Redesign regional governance and feedback
- Combine several measures in a staged pilot
- Maintain the current process and accept the risk

The last option matters because every intervention should be compared with the real baseline and the cost of doing nothing.

## Actionable-frame checklist

A frame is ready for decision work when the team can answer:

- What gap are we addressing?
- What evidence distinguishes symptoms from probable causes?
- What remains assumed?
- Who owns the decision?
- Who is affected and who has relevant knowledge?
- What alternatives remain open?
- What objectives and constraints govern the choice?
- What data would change the preferred option?
- What decision is needed now, and what can remain uncertain?

If the team cannot answer these, it is not ready to evaluate whether AI belongs in the solution.

---

# 11. Integrated worked case: Northstar maintenance intake

## Initial symptom

> Maintenance prioritization is slow, and some urgent requests are ranked too low.

## Premature proposal

> Buy AI that automatically ranks and dispatches requests.

## Revised problem statement

> Across Northstar's four regions, priority decisions take a median of 45 minutes and an illustrative audit finds 12% of later-confirmed urgent cases were initially ranked too low. Requests arrive through several channels, 15% lack a reliable equipment ID, and regional urgency definitions differ. The resulting delay and inconsistency increase downtime and could weaken safety and service performance.

## Root-cause analysis summary

| Hypothesis | Supporting indication | Missing or disconfirming evidence | Status |
|---|---|---|---|
| Incomplete request data slows and weakens triage | Missing equipment IDs and free-text requests appear in misranked cases | Need matched comparison and direct observation | Plausible; test |
| Regional label differences create inconsistent priorities | Four different urgency definitions exist | Need to distinguish legitimate local requirements from inconsistency | Plausible; policy review |
| Intake was designed for logging, not decision support | Critical decision fields are optional | Need original requirements and user research | Plausible; investigate |
| Staff capacity, rather than information, is the main bottleneck | Peak queues are reported | Need arrival, staffing, and queue-time data | Competing hypothesis |
| AI ranking will solve the problem | Vendor claim only | No local comparative evidence | Unsupported assumption |

## 4P frame

- **Problem:** Prioritization does not consistently meet speed and quality needs.
- **People:** The decision involves customers/site contacts, intake coordinators, service directors, dispatchers, technicians, safety supervisors, and risk/data/system owners.
- **Process:** Information quality, safety screening, regional interpretation, and capacity interact across several handoffs.
- **Parameters:** Safety review is non-negotiable; the target is faster and more reliable priority decisions; workload and service obligations constrain alternatives.

## Stakeholder insight

The site contact has less formal power than the regional director but supplies the initial evidence. The intake coordinator may bear the largest increase in workload if fields are added. The technician observes whether the priority matched field reality. Excluding any of them produces a weak frame.

## Prioritized assumptions

1. Better structured intake will materially reduce decision time.
2. Site contacts and coordinators can supply the required information accurately.
3. Regional definitions can be harmonized without losing legitimate local context.
4. The outcome data are reliable enough to evaluate urgent-case misses.
5. AI adds value beyond clarified rules and improved intake.

## Final decision statement

> The Chief Operating Officer must decide by quarter end which combination of intake redesign, shared priority rules, specialist capacity, and decision-support technology should be piloted to reduce maintenance-priority decision time and missed urgent cases across four regions, while maintaining safety escalation, service obligations, data legitimacy, and workable frontline load.

## Link to Module 1

Only now should Northstar complete the AI Decision Suitability Canvas. The canvas evaluates whether AI belongs in the framed decision; it should not replace problem diagnosis.

---

# 12. Practice cases and mastery gates

## Case A: customer churn

### Situation

Churn increased from 4% to 7%. Support tickets rose 35%, app crashes 18%, and acquisition cost 12%. Management proposes predicting likely churners and automatically giving them a discount.

### Learner task

1. Identify symptoms, assumed causes, decisions, and proposed solutions.
2. Write a neutral problem statement.
3. Create at least two causal branches.
4. Apply the 4P framework.
5. Write a decision statement that leaves non-AI alternatives open.
6. Add five assumptions to the log and prioritize them.

### Challenge prompts

- Why do you believe crashes caused churn?
- What evidence supports a discount as the intervention?
- What data would change your mind?
- Who owns the product-versus-retention trade-off?
- Who is affected if loyal customers do not receive the same discount?

### Mastery requirement

The learner must distinguish prediction from causal diagnosis and must not frame “build a churn model” as the decision.

## Case B: warehouse picking delays

### Situation

Late shipments doubled after a new warehouse system launched. Managers blame employee resistance and propose mandatory retraining. Workers report that item locations and handheld-device instructions often conflict.

### Learner task

- Build a branching 5 Whys analysis.
- Identify what would count as evidence for training, system, layout, data, or incentive causes.
- Map stakeholders, including workers with little formal authority.
- Write an actionable decision statement.

### Blind spot to reveal

“Employee resistance” may be an interpretation that protects the implementation team's original design. Training can be necessary while still failing to address incorrect instructions.

## Case C: hospital appointment no-shows

### Situation

No-show rates are high. Leaders propose AI that predicts which patients will miss appointments and double-books high-risk time slots.

### Learner task

- Separate the no-show symptom from access, scheduling, communication, transport, health, and administrative causes.
- Identify who bears the cost of a false positive and double-booking.
- Produce a stakeholder map that includes patients and frontline staff.
- State which assumptions require validation before any AI suitability assessment.

### Mastery requirement

The learner must recognize that prediction may improve scheduling while worsening waiting, dignity, workload, or access if the intervention is poorly framed.

---

# 13. Artifact workshop

Use one real organizational decision. Update every artifact after each critique.

The templates below are also available together in the editable [Phase 1 Artifact Workbook](phase-1-artifact-workbook.md), which includes a revision record for tracking how evidence changes the frame.

## Artifact 1 — Root Cause Analysis

| Problem statement | Causal branch | Proposed cause | Mechanism | Evidence for | Evidence against or missing | Intervention point | Confidence |
|---|---|---|---|---|---|---|---|

## Artifact 2 — Decision Statement

> **[Owner]** must decide **[choice]** by **[time]**, using **[evidence]**, to achieve **[outcomes]**, within **[constraints and boundaries].**

## Artifact 3 — Stakeholder Map

| Stakeholder | Role | Influence | Degree affected | Knowledge | Concern | Involvement |
|---|---|---:|---:|---|---|---|

## Artifact 4 — Assumption Log

| ID | Assumption | Type | Evidence | Consequence if wrong | Priority | Validation method | Owner | Date | Status |
|---|---|---|---|---|---|---|---|---|---|

## Artifact 5 — AI Decision Suitability Canvas

Return to Module 1 only after the decision statement is sufficiently clear. Update the canvas if the problem, cause, stakeholder, boundary, or assumption changes. A change in the frame can change the answer to whether AI is appropriate.

---

# 14. Using ChatGPT as a thinking partner

ChatGPT can challenge a frame, generate alternative hypotheses, simulate stakeholder questions, and help structure artifacts. It should not silently decide what the organization values or turn unsupported claims into facts.

## Useful prompts

- “Separate the symptoms, interpretations, assumed causes, decisions, and proposed solutions in this description.”
- “Generate three competing causal explanations. For each, state the mechanism, evidence needed, and disconfirming evidence.”
- “Run a branching 5 Whys analysis, marking every answer as fact, inference, or hypothesis.”
- “Challenge this problem statement for embedded solutions, blame, missing scope, and causal assumptions.”
- “Apply Problem, People, Process, and Parameters to this situation. Do not recommend a solution.”
- “Identify stakeholders with high exposure but low formal power.”
- “Turn this proposal into a neutral decision statement with at least three alternatives.”
- “Create an assumption log and prioritize by uncertainty and consequence.”
- “Act as a skeptical executive. Ask one difficult question at a time and do not reveal the answer.”

## Required human checks

After using ChatGPT, ask:

- Why do I believe this output?
- What source or firsthand evidence supports it?
- Did the model invent context or assume causality?
- Whose perspective is missing?
- Who owns the actual decision?
- What data would change my mind?

Do not paste confidential or restricted information into an unapproved system. Verify citations, facts, calculations, and claimed stakeholder views independently.

---

# 15. Module knowledge check

## Questions

1. What is the difference between a symptom and a problem?
2. Why is “we need an AI chatbot” not a problem statement?
3. When is a cause useful to treat as a root cause?
4. Why is the number five not the essential feature of 5 Whys?
5. Why should a complex inquiry branch?
6. What do the four Ps mean in this course?
7. What is the difference between a fact, interpretation, assumption, and hypothesis?
8. Why can a low-power stakeholder still require close involvement?
9. What elements belong in an actionable decision statement?
10. Why should RCA precede AI suitability assessment?

## Suggested answers

1. A symptom is an observable sign; a problem is a consequential gap between current and desired conditions for a defined population or process.
2. It names a solution before establishing the gap, cause, alternatives, owner, or objective.
3. When it is causally plausible, supported, upstream enough, actionable, and material to recurrence or consequence.
4. The method seeks useful causal depth; it may take fewer or more questions and should stop when questions become speculative.
5. Organizational problems often have multiple interacting causes, so a single linear story can hide important mechanisms.
6. Problem, People, Process, and Parameters.
7. A fact is directly supported within scope; interpretation assigns meaning; an assumption is provisionally accepted; a hypothesis is a testable explanation or prediction.
8. Formal influence and exposure to consequences are different. Low-power stakeholders may bear harm or hold essential operational knowledge.
9. Owner, choice, timing, relevant evidence, objective or success measures, constraints, boundaries, and unacceptable risks.
10. AI suitability depends on the real decision and problem mechanism; otherwise the team may automate a symptom or evaluate the wrong task.

---

# 16. Module assessment rubric

| Dimension | 1 — Weak | 2 — Developing | 3 — Competent | 4 — Mastery |
|---|---|---|---|---|
| Symptom/problem distinction | Mixes symptoms, causes, and solutions | Recognizes some distinctions | Defines a neutral, measurable problem | Tests whether the frame hides deeper concerns or proxies |
| Root-cause reasoning | Accepts first explanation | Generates causes without validation | Builds causal branches and seeks evidence | Compares mechanisms, disconfirming evidence, and intervention value |
| 5 Whys | Performs ritual linear questioning | Reaches a plausible upstream factor | Branches and marks hypotheses | Knows when to change tools and avoids blame or speculation |
| 4P framing | Lists categories | Addresses most Ps superficially | Produces coherent Problem, People, Process, Parameters outputs | Exposes conflicts and revises the frame as evidence changes |
| Assumptions | Leaves claims implicit | Lists assumptions | Prioritizes and assigns validation | Uses disconfirming tests and updates decisions when assumptions fail |
| Stakeholders | Maps only leaders | Adds some affected groups | Separates authority, knowledge, implementation, and impact | Identifies power asymmetry and designs meaningful involvement |
| Decision statement | States an aspiration or solution | Names a choice but lacks boundaries | Names owner, choice, time, outcome, evidence, and constraints | Remains neutral, decision-relevant, and robust to challenge |

The learner should score at least **3 in every dimension** before completing the module. A high average does not compensate for a weak root-cause process or an unclear decision owner.

---

# 17. Facilitator guide

## Suggested two-session design

### Session A — Diagnose before deciding (90 minutes)

| Time | Activity |
|---|---|
| 0–10 min | Opening diagnostic: ask what the learner already knows |
| 10–25 min | Symptoms, problems, causes, decisions, and solutions |
| 25–45 min | RCA and branching 5 Whys |
| 45–60 min | Learner solves a short case |
| 60–75 min | Critique and reveal blind spots |
| 75–90 min | Revise Root Cause Analysis and Assumption Log |

### Session B — Frame an actionable decision (90 minutes)

| Time | Activity |
|---|---|
| 0–15 min | Retrieval practice and challenge questions |
| 15–35 min | 4P Decision Framework |
| 35–50 min | Stakeholder mapping |
| 50–65 min | Decision statement construction |
| 65–80 min | Learner applies tools to their own decision |
| 80–90 min | Mastery check and artifact revision |

## Facilitation rule

Do not reveal the polished answer before the learner commits to a position. Ask one question at a time, critique the reasoning, and allow revision. Progress only when the learner can transfer the concept to a new case.

## Frequent challenge questions

- Is that an observation or an explanation?
- Why do you believe it is causal?
- What evidence would prove you wrong?
- Are you solving the problem or choosing a preferred tool?
- Who experiences the problem differently?
- Who owns the decision, not merely the project?
- What alternative have you excluded through the wording?
- What assumption has the highest consequence if wrong?
- What data would change your mind?

---

# 18. Executive job aid

Before accepting a proposal, ask:

- What is the symptom?
- What is the consequential problem?
- Which causal claims are proven, plausible, or assumed?
- What competing explanation fits the evidence?
- Who experiences the problem and who owns the decision?
- What does the real process look like, including exceptions and incentives?
- Which parameters define success and unacceptable risk?
- What alternatives remain open?
- Which assumption must be tested first?
- What is the precise decision statement?
- Only then: is AI relevant to any specific decision point?

---

# 19. References and further reading

1. American Society for Quality. [Five Whys and Five Hows](https://asq.org/quality-resources/five-whys). Definition, uses, and practical procedure.
2. UK Ministry of Defence. [JSP 940: Quality Management, Part 2 Guidance](https://assets.publishing.service.gov.uk/media/687918b30263c35f52e4ddb9/JSP_940_Ministry_of_Defence_policy_for_Quality__part_2_guidance.pdf). Root-cause tools, limitations, fishbone analysis, and 5 Whys guidance.
3. UK Local Digital. [Get to the root cause of a problem](https://www.localdigital.gov.uk/resources/root-cause-of-a-problem/). User-centred, collaborative RCA guidance.
4. Structured Decision Making. [Decision Statements](https://www.structureddecisionmaking.org/the-steps/decision-statements/) and [The Steps](https://www.structureddecisionmaking.org/the-steps/). Decision context, alternatives, objectives, and concise framing.
5. UK Government Analysis Function. [Stakeholder mapping](https://analysisfunction.civilservice.gov.uk/policy-store/stakeholder-mapping/). Stakeholder definition, grouping, power, interest, and engagement.

---

# Closing message

Good decision making begins before options are compared. Leaders must first separate observations from explanations, investigate why the gap exists, identify who owns and experiences the choice, expose assumptions, and frame a decision that permits genuine alternatives.

Only after that work should the organization ask whether AI belongs in the solution.
