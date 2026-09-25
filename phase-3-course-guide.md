# Phase 3 Course Guide: AI Systems, Organizational Workflows, and Business Value

## Phase goal

By the end of Phase 3, the learner can design, evaluate, and operationalize an AI-enabled work system for an organization. The learner will be able to move from a business problem to a bounded assistant, a controlled workflow, an evidence-based evaluation, and a defensible business case.

This phase does **not** teach prompt engineering as the search for a magical phrase. A prompt is one configurable component of a larger system. Reliable performance comes from explicit requirements, suitable data, constrained tools, evaluation cases, human authority, monitoring, and continuous improvement.

The phase contains:

- [Phase 3 Modules](phase-3-modules[GROUP].md)
- [Phase 3 Artifact Workbook](phase-3-artifact-workbook.md)
- [Phase 3 Source Guide](phase-3-source-guide.md)

The learning sequence is:

> **Define the work and risk → specify the system → design authority and controls → evaluate decisions and evidence → prove value → pilot, monitor, and improve**

---

# 1. Learning outcomes

At the end of Phase 3, the learner can:

1. Explain an LLM-based application as a system rather than a model or prompt.
2. Decide whether a task needs a fixed prompt, retrieval, deterministic automation, an agent, or no AI.
3. Write testable assistant specifications and system instructions.
4. Map an end-to-end workflow, including decisions, data, approvals, exceptions, and audit events.
5. Create evaluation sets with normal, edge, adversarial, and failure-recovery cases.
6. Use AI to expand strategic alternatives without delegating strategy or accountability.
7. Analyze tables and charts while separating observation, calculation, interpretation, and recommendation.
8. Conduct evidence-disciplined market research and expose unsupported claims.
9. Build a business case using total cost, measurable benefits, risk, sensitivity analysis, and adoption requirements.
10. Defend one production-ready AI workflow in an architecture review.

---

# 2. What “systematic AI engineering” means

Systematic AI engineering treats performance as an end-to-end property:

```text
Business objective
  → workflow and decision rights
  → data and knowledge
  → model, prompt, retrieval, tools, and deterministic logic
  → user interface and human review
  → actions and outcomes
  → evaluation, logs, monitoring, and improvement
```

A polished response is not evidence of a reliable system. The system must be evaluated on the work it is meant to improve and the harm it must avoid.

## The Phase 3 design doctrine

1. **Begin with the work.** Define the decision, task, user, outcome, and baseline before selecting technology.
2. **Use the least autonomous design that works.** Prefer deterministic rules for deterministic work; use LLMs where language ambiguity or unstructured information creates genuine value.
3. **Separate knowledge from behavior.** System instructions govern conduct; approved sources provide changing facts; tools perform actions.
4. **Treat model output as untrusted.** Validate structure, permissions, citations, calculations, and action parameters.
5. **Design abstention and escalation.** “I cannot safely complete this” is a valid system behavior.
6. **Evaluate the workflow, not only the answer.** Include review time, rework, error cost, adoption, and downstream outcomes.
7. **Keep authority human where consequences require it.** Human review must have information, time, competence, and actual power to intervene.
8. **Log enough to investigate.** Preserve relevant inputs, source versions, model/configuration versions, tool calls, approvals, and outcomes subject to privacy and retention policy.
9. **Expect change.** Models, data, policies, attackers, and user behavior drift. Re-evaluation is part of operation.
10. **Earn autonomy with evidence.** Expand permissions only after performance and control effectiveness are demonstrated.

---

# 3. Required projects

The learner builds five connected deliverables. Each is versioned and revised after review.

| Project | Primary module | Purpose | Minimum evidence of quality |
|---|---:|---|---|
| **1. Prompt Library** | 8 and 11 | Reusable, tested task specifications | Use cases, variables, output schemas, examples, failure tests, scores, version history |
| **2. AI Assistant Specification** | 9 | Contract for a bounded assistant | Users, scope, sources, rules, tools, escalation, human review, metrics, prohibited behavior |
| **3. AI Workflow** | 10 | End-to-end operating design | Current/future maps, decision table, data contracts, approvals, fallback, audit trail, prototype |
| **4. Analytics Notebook** | 12 | Reproducible evidence analysis | Data lineage, calculations, validation, chart/table interpretations, limitations, recommendations |
| **5. AI Business Case** | 13 | Defensible investment proposal | Baseline, alternatives, costs, benefits, risks, KPIs, adoption plan, ROI range, stage gates |

The final exercise integrates all five into one production-ready AI workflow package.

---

# 4. Running practice case

Use this fictional case for demonstrations. The learner should apply the same tools to a real or chosen organizational problem.

## Asteria Appliances warranty operations

Asteria sells household appliances through retailers and direct channels. Warranty requests arrive by web form, email, and call-center notes. Agents search product manuals, warranty terms, service history, and regional policies. They classify eligibility, request missing information, propose next actions, and sometimes approve low-value remedies.

Current concerns:

- median resolution time is believed to be six days, but channel definitions differ;
- customers repeat information across handoffs;
- reviewers apply regional warranty exceptions inconsistently;
- approximately 18% of cases are reportedly reopened, but the denominator is disputed;
- leadership wants “an autonomous warranty agent” within one quarter;
- legal, security, operations, and frontline teams have not agreed on decision authority;
- manuals and policies contain outdated and conflicting versions;
- the organization has no labeled evaluation set.

Possible AI roles include intake summarization, missing-information detection, retrieval from approved policies, eligibility recommendation, response drafting, routing, and limited execution. The learner must determine which roles are appropriate; autonomy is not assumed.

## Hidden traps

- The proposed solution precedes a reliable baseline.
- “Eligibility” mixes policy rules with discretionary judgment.
- Retrieval may surface obsolete documents.
- Customer text and external documents can contain prompt injection.
- A reviewer may rubber-stamp plausible recommendations.
- Automation may shorten handling time while increasing reopening or unfair denial.
- Vendor/model costs are only a fraction of total operating cost.

---

# 5. Recommended sequence

The phase can run as twelve 2–3 hour sessions plus independent build work.

| Session | Focus | Learner performance | Artifact milestone |
|---:|---|---|---|
| 1 | AI system anatomy and LLM fundamentals | Explains the full system and identifies nondeterministic boundaries | System context sketch |
| 2 | RAG, agents, automation, augmentation | Selects a suitable pattern and rejects unnecessary autonomy | Architecture options |
| 3 | Prompt engineering as specification and evaluation | Creates a task contract and test set | Prompt Library v0.1 |
| 4 | Assistant scope and requirements | Defines users, in/out of scope, and success | Assistant Spec v0.1 |
| 5 | Instructions, rules, tools, and escalation | Separates policy, knowledge, data, and behavior | Assistant Spec v0.2 |
| 6 | Workflow mapping and approvals | Maps current and future states with decision rights | AI Workflow v0.1 |
| 7 | Prototype, fallback, audit, and controls | Builds and failure-tests a thin vertical slice | AI Workflow v0.2 |
| 8 | Strategic alternatives and trade-offs | Uses AI to expand and challenge a decision | Decision prompt set |
| 9 | Assumptions, risks, and confidence | Defends confidence using evidence and sensitivity | Prompt Library v1.0 |
| 10 | AI-powered analytics | Produces reproducible, cross-validated analysis | Analytics Notebook |
| 11 | Market intelligence and business case | Builds an evidence register and ROI range | Business Case v0.1 |
| 12 | Architecture review and production gate | Defends the integrated system under adversarial review | Final production package |

---

# 6. Learning method

## Build–attack–revise cycle

Every concept must become an artifact and survive challenge:

1. **Build:** the learner creates a design, prompt, workflow, analysis, or business claim.
2. **Attack:** the mentor tests assumptions, edge cases, incentives, security, and failure recovery.
3. **Measure:** the learner runs predefined cases and records results.
4. **Diagnose:** failures are attributed to requirements, data, retrieval, model behavior, tools, interface, or process.
5. **Revise:** the learner updates the artifact and version history.
6. **Defend:** the learner explains why the revised design is acceptable and what remains uncertain.

The mentor does not repair the artifact immediately. First ask the learner to identify the failure mechanism and propose the smallest effective change.

## Core mentor questions

- What exact work outcome improves, and compared with what baseline?
- Why does this step require an LLM?
- What would a deterministic rule do better?
- Which facts are model memory, retrieved evidence, user input, or inference?
- Who can be harmed when this is wrong?
- Can the error be detected before action?
- What is the system permitted to do, and with which credentials?
- What happens when data are missing, contradictory, stale, malicious, or unavailable?
- When must the system abstain?
- Does the reviewer have enough evidence and time to disagree?
- Which metric could improve while the real outcome worsens?
- What evidence would cause you to stop the pilot?

## Required adversarial categories

Every artifact review must include cases from all of these categories:

1. Normal high-frequency case.
2. Ambiguous request.
3. Missing required data.
4. Conflicting sources.
5. Outdated source.
6. Out-of-scope request.
7. Prompt injection or malicious content.
8. Sensitive-data request.
9. Low-confidence but plausible output.
10. Tool/API timeout or partial failure.
11. Duplicate or replayed action.
12. High-impact exception requiring escalation.
13. Distribution shift or novel case.
14. Biased or uneven performance across relevant groups.
15. Human reviewer error, fatigue, or automation bias.

---

# 7. Architecture review standard

Each project is reviewed as if it will enter a real organizational environment.

## Review roles

- **Business owner:** value, baseline, adoption, and outcome accountability.
- **Workflow owner:** process fit, queues, exceptions, and operating capacity.
- **Domain expert:** factual and policy correctness.
- **Data owner:** access, quality, lineage, retention, and permitted use.
- **AI/engineering reviewer:** architecture, tests, reliability, latency, and cost.
- **Security/privacy reviewer:** threats, permissions, secrets, personal data, and incident response.
- **Risk/legal reviewer:** affected parties, rights, obligations, contestability, and documentation.
- **Frontline representative:** usability, workarounds, training, and actual review behavior.
- **Red-team reviewer:** misuse, adversarial inputs, and failure combinations.

One person may play multiple roles in a small organization, but every perspective must be addressed.

## Review gates

| Gate | Question | Required evidence |
|---|---|---|
| **Problem gate** | Is there a validated problem worth solving? | Decision owner, workflow baseline, affected parties, non-AI alternatives |
| **Design gate** | Is the proposed system bounded and controllable? | Specification, data flow, permissions, human authority, threat model |
| **Evaluation gate** | Does it meet predefined quality and safety thresholds? | Representative test set, adversarial results, error analysis, reviewer study |
| **Pilot gate** | Can it operate safely in a limited environment? | Runbook, monitoring, fallback, training, incident path, stop criteria |
| **Scale gate** | Is value repeatable and residual risk acceptable? | Outcome data, total cost, subgroup analysis, audit evidence, change plan |

## Scoring rubric

Score each dimension from 0 to 4.

| Score | Meaning |
|---:|---|
| 0 | Missing |
| 1 | Claimed but unsupported |
| 2 | Partially specified or tested |
| 3 | Complete and supported for pilot |
| 4 | Demonstrated under realistic and adversarial conditions |

Dimensions:

- problem and outcome clarity;
- workflow and decision rights;
- data and evidence fitness;
- functional performance;
- safety, security, privacy, and fairness;
- human oversight and contestability;
- reliability, fallback, and recovery;
- observability and auditability;
- cost and business value;
- adoption and operating ownership.

No average score can hide a critical control gap. Security, legal, human-impact, and recovery blockers are pass/fail gates.

---

# 8. Evaluation model

Use an evaluation portfolio rather than one accuracy number.

## Evaluation layers

| Layer | Question | Examples |
|---|---|---|
| Component | Does one part work? | retrieval recall, schema validity, tool argument accuracy |
| Task | Is the output fit for the task? | groundedness, classification F1, rubric score, calculation accuracy |
| Workflow | Does the process improve? | cycle time, handoffs, review time, rework, escalation quality |
| Outcome | Does the organization benefit? | resolution, retention, loss avoided, customer outcome |
| Risk | Are harms within tolerance? | severe-error rate, privacy incidents, subgroup disparity, unauthorized actions |
| Human factors | Do people use it appropriately? | override quality, automation bias, adoption, cognitive load |

## Test-set structure

A defensible initial evaluation set includes:

- real historical cases sampled across relevant segments;
- synthetic cases for rare but foreseeable failures;
- adversarial cases designed to break rules or corrupt instructions;
- counterfactual pairs where one material fact changes the correct result;
- regression cases for every previously discovered failure;
- holdout cases not used while tuning prompts or rules.

Document the test-set source, labeling instructions, reviewer agreement, exclusions, known gaps, and refresh schedule.

---

# 9. Final exercise: production-ready AI workflow

“Production-ready” in this phase means ready for a controlled organizational pilot, not universal proof of safety.

## Required package

1. One-page problem, user, outcome, scope, and baseline.
2. Current-state and future-state workflow maps.
3. System context and data-flow diagram.
4. Assistant specification and versioned prompt library.
5. Knowledge-source register and data contracts.
6. Tool and permission matrix.
7. Decision, approval, escalation, and abstention table.
8. Threat model and risk/control register.
9. Evaluation plan, test set, thresholds, and results.
10. Prototype demonstrating one end-to-end thin slice.
11. Audit event schema, dashboard, and alert definitions.
12. Fallback, incident, rollback, and change-management runbooks.
13. Analytics notebook supporting the baseline and outcome measures.
14. Business case with cost/benefit range and sensitivity analysis.
15. Pilot plan, training plan, owners, stage gates, and stop criteria.

## Final defense

The learner receives 15 minutes to present, 25 minutes for adversarial review, and 10 minutes to revise one decision live.

The reviewers should ask:

- Show the highest-severity failure and the control that contains it.
- Demonstrate an injection attempt, a stale document, and a tool timeout.
- Show how a human sees evidence and rejects a recommendation.
- Explain which log records reconstruct one decision.
- Show a counterfactual test that changes the output correctly.
- Defend the ROI under lower adoption, higher review time, and doubled error cost.
- State exactly what would stop the pilot.

## Pass standard

The learner passes when the package is coherent end to end, critical risks have controls and owners, evaluation thresholds are met on a representative holdout set, the prototype fails safely, and the business case remains credible under reasonable downside assumptions.

---

# 10. Evidence base

The curriculum is aligned to the [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework), organized around Govern, Map, Measure, and Manage, and to the [NIST Generative AI Profile](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf), which emphasizes documented data fitness, fact-checking, adversarial testing, human–AI configuration, and ongoing monitoring. Security exercises use the [OWASP Top 10 for LLM and Generative AI Applications](https://genai.owasp.org/llm-top-10/), including prompt injection, sensitive information disclosure, improper output handling, excessive agency, vector/embedding weaknesses, misinformation, and unbounded consumption.

Human authority, traceability, and contestability reflect the updated [OECD AI Principles](https://oecd.ai/en/ai-principles). Technical foundations draw on the original [retrieval-augmented generation paper](https://papers.neurips.cc/paper/2020/file/6b493230205f780e1bc26945df7481e5-Paper.pdf) and [ReAct paper](https://arxiv.org/abs/2210.03629). These sources are general guidance, not a substitute for applicable sector, jurisdiction, privacy, employment, safety, procurement, or professional requirements.
