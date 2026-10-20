# Phase 1 Source Guide

## Purpose and scope

This guide consolidates the external foundations used in Phase 1: AI decision suitability, decision framing, root-cause analysis, human oversight, accountability, and stakeholder mapping. It supports Modules 1–2 and the Phase 1 portfolio artifacts.

The inventory was reviewed on **20 October 2026**. Consequential official sources were prioritized for currency checks; a listed source that was not independently re-opened remains a provenance record, not a current-status guarantee. For operational use, record the title, author/institution, publication or version date, identifier, direct claim supported, original URL, access date, verification result, and jurisdictional applicability. Legal and regulatory sources do not replace qualified advice.

NIST states that AI RMF 1.0 is under revision. The EU AI Act and its implementation schedule may be affected by current amendments and implementing measures. Version-lock the material used for a cohort and check the official consolidated/legal status before teaching an obligation or effective date.

---

# 1. AI risk management and decision suitability

## NIST AI Risk Management Framework 1.0

- Official publication: [NIST AI RMF 1.0](https://doi.org/10.6028/NIST.AI.100-1)
- Implementation resource: [NIST AI RMF Core](https://airc.nist.gov/airmf-resources/airmf/5-sec-core/)
- Applies to: Module 1, the AI Decision Suitability Canvas, oversight design, and portfolio review.

The framework's Govern, Map, Measure, and Manage functions support the phase's decision-first approach. Relevant practices include defining business context, documenting system scope and human roles, comparing benefits and costs, testing under deployment-like conditions, monitoring emergent risks, and providing feedback and appeal mechanisms.

Use the framework to structure judgment; do not treat it as evidence that a specific system is suitable, safe, or compliant.

## GAO AI Accountability Framework

- Source: [Artificial Intelligence: An Accountability Framework for Federal Agencies and Other Entities](https://www.gao.gov/products/gao-21-519sp)
- Applies to: Module 1 governance questions and assurance review.

The GAO framework organizes accountability practices around governance, data, performance, and monitoring. It supports questions about ownership, documentation, data quality, evaluation, ongoing oversight, and auditability.

---

# 2. Human-centered governance and accountability

## OECD AI Principles

- Overview: [OECD AI Principles](https://oecd.ai/en/ai-principles)
- Accountability detail: [OECD accountability principle](https://oecd.ai/en/dashboards/ai-principles/P9)
- Applies to: Module 1 transparency, challenge, lifecycle traceability, robustness, and accountability.

The principles support the requirement that people understand when and how AI affects a decision, can challenge material outcomes, and can identify accountable actors across the lifecycle. They provide high-level principles rather than a complete control framework for a particular system.

## Human–automation interaction research

- Source: Parasuraman, Sheridan, and Wickens, [A Model for Types and Levels of Human Interaction with Automation](https://www.cs.uml.edu/~holly/91.550/papers/sheridan-autonomy.pdf)
- Applies to: Module 1 role design and the human–AI authority ladder.

The paper distinguishes automation across information acquisition, information analysis, decision/action selection, and action implementation. The curriculum uses this distinction to avoid treating “human in the loop” as a single control design.

## EU AI Act human-oversight provisions

- Official text: [Regulation (EU) 2024/1689](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32024R1689)
- Applies to: Module 1 discussion of meaningful oversight for high-risk systems where the law is applicable.

The curriculum draws attention to oversight competence, awareness of system limitations, automation bias, interpretation, override, reversal, and interruption. Applicability depends on the organization's role, system classification, territory, and effective provisions; determine these with qualified counsel.

## UK ICO guidance on AI and data protection

- Source: [Guidance on AI and data protection](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/artificial-intelligence/guidance-on-ai-and-data-protection/)
- Applies to: Module 1 meaningful human review, authority, capability, automation bias, and individual rights.

This regulator guidance is directly relevant to organizations subject to UK data-protection law and can serve as comparative operational guidance elsewhere. It is not universally applicable law.

---

# 3. Root-cause analysis and decision framing

## Five Whys and root-cause methods

- Professional guidance: [American Society for Quality — Five Whys and Five Hows](https://asq.org/quality-resources/five-whys)
- Government guidance: [UK Ministry of Defence JSP 940, Part 2](https://assets.publishing.service.gov.uk/media/687918b30263c35f52e4ddb9/JSP_940_Ministry_of_Defence_policy_for_Quality__part_2_guidance.pdf)
- Service-design guidance: [UK Local Digital — Get to the root cause of a problem](https://www.localdigital.gov.uk/resources/root-cause-of-a-problem/)
- Applies to: Module 2 Root Cause Analysis.

These sources support iterative inquiry beyond visible symptoms while recognizing that the method may yield several plausible causes and is best suited to simple or moderately difficult problems. The curriculum therefore requires evidence, alternative explanations, and explicit uncertainty rather than accepting the fifth answer as “the root cause.”

## Structured Decision Making

- Decision framing: [Decision Statements](https://www.structureddecisionmaking.org/the-steps/decision-statements/)
- Full method: [The Steps](https://www.structureddecisionmaking.org/the-steps/)
- Applies to: Module 2 Decision Statement and the transition from diagnosis to choice.

The method informs the curriculum's attention to the decision maker, problem, alternatives, objectives, timeframe, location, constraints, consequences, and trade-offs. It is practitioner methodology rather than a binding standard.

## Stakeholder mapping

- Source: [UK Government Analysis Function — Stakeholder mapping](https://analysisfunction.civilservice.gov.uk/policy-store/stakeholder-mapping/)
- Applies to: Module 2 Stakeholder Map.

The guidance supports identifying and grouping stakeholders by characteristics such as power and interest. The curriculum extends this by distinguishing formal decision power from exposure to a decision's consequences.

---

# 4. Source-to-curriculum map

| Curriculum area | Principal sources | Contribution |
|---|---|---|
| AI decision suitability | NIST AI RMF, GAO | Context, value/risk comparison, evaluation, ownership, and monitoring |
| Human–AI authority | Parasuraman et al., NIST, OECD | Levels of automation, human roles, challenge, and accountability |
| Meaningful oversight | EU AI Act where applicable, ICO | Competence, authority, automation bias, override, and rights |
| Root-cause analysis | ASQ, UK Ministry of Defence, UK Local Digital | Iterative diagnosis, limitations, multiple causes, and collaborative inquiry |
| Decision statements | Structured Decision Making | Decision owner, alternatives, objectives, scope, timeframe, and constraints |
| Stakeholder mapping | UK Government Analysis Function | Stakeholder identification, power, interest, exposure, and engagement |

# 5. Evidence-use rules

For every material claim or control derived from these sources:

1. Record the exact source, version or publication date, link, and access date.
2. Distinguish law, regulator guidance, voluntary frameworks, research, and practitioner methods.
3. Identify the source's scope and whether it applies to the actual organization and decision.
4. Link the source to a concrete requirement, decision, test, or artifact field.
5. Record limitations, conflicting evidence, and the human judgment still required.

For publisher provenance and source classification, see the [Source Origin Map](source-origin-map.md).

# 6. Source maintenance control

The curriculum owner appoints a source steward. The steward reviews living sources quarterly, before each cohort, and immediately after a material legal, standards, security, or vendor change. The review log records source, prior/current version, status, claims affected, modules/artifacts affected, action, reviewer, date, and approval. A changed URL is not silently substituted; retain the reason and verify whether teaching or assessment must change.

