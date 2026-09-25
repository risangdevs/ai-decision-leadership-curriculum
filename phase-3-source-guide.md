# Phase 3 Source Guide

## Purpose

This guide identifies the primary foundations used in Phase 3 and shows where they inform the curriculum. It is not a substitute for organization-specific legal, regulatory, contractual, labor, professional, or sector requirements.

Standards and product capabilities change. Record the access date when using a source in a real project and verify that a newer edition has not replaced it.

---

# 1. System governance and risk management

## NIST AI Risk Management Framework 1.0

- Source: [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework)
- Detailed core: [NIST AI RMF Core](https://airc.nist.gov/airmf-resources/airmf/5-sec-core/)
- Applies to: all Phase 3 modules and architecture reviews.

The framework’s Govern, Map, Measure, and Manage functions support the course sequence. Particularly relevant themes include lifecycle governance, defined human–AI roles, context-specific risk mapping, repeatable testing/evaluation/verification/validation, post-deployment monitoring, and documented risk treatment.

Use it to ask:

- Is governance embedded across the lifecycle?
- Are context, affected parties, benefits, and harms mapped?
- Are tests objective, repeatable, and documented?
- Are residual risks prioritized, treated, monitored, and owned?

NIST notes that AI RMF 1.0 is being revised. Treat the curriculum’s use as a stable conceptual foundation, then check the current NIST status when operationalizing it.

## NIST Generative AI Profile

- Source: [NIST AI 600-1: Generative Artificial Intelligence Profile](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf)
- Applies to: Modules 8–10 and the capstone evaluation.

This profile informs the curriculum’s emphasis on:

- data accuracy, relevance, representativeness, and suitability;
- fact-checking and information integrity;
- adversarial testing;
- content provenance;
- testing human–AI configurations;
- monitoring combined human and AI outcomes;
- involving operators and affected users in realistic testing.

The profile is a risk-management resource, not a universal checklist. Select controls based on context and consequence.

---

# 2. Security for LLM applications and agents

## OWASP Top 10 for LLM and Generative AI Applications

- Source: [OWASP GenAI Security Project — LLM Top 10](https://genai.owasp.org/llm-top-10/)
- Applies to: RAG, assistants, agents, workflows, prototypes, and attack scripts.

The 2025 list informs test cases for:

- prompt injection;
- sensitive information disclosure;
- supply-chain risk;
- data/model poisoning;
- improper output handling;
- excessive agency;
- system-prompt leakage;
- vector and embedding weaknesses;
- misinformation;
- unbounded consumption.

The course treats these as system risks. A stronger prompt alone cannot enforce permissions, sanitize tool outputs, prevent duplicate transactions, or contain cost. Controls belong across identity, data, retrieval, orchestration, validation, tools, monitoring, and incident response.

## Agent safety guidance

- Source: [OpenAI — A Practical Guide to Building AI Agents](https://openai.com/business/guides-and-resources/a-practical-guide-to-building-ai-agents/)
- Source: [OpenAI — Safety in Building Agents](https://developers.openai.com/api/docs/guides/agent-builder-safety)
- Applies to: Modules 8–10.

These product-oriented sources support several vendor-neutral practices used in the curriculum: establish evaluations before optimization, choose models by measured task performance, limit tools and permissions, set retry/action boundaries, apply guardrails, inspect traces, and route high-risk or failed work to humans.

Because these sources describe one vendor’s approach, compare implementation details with the selected platform rather than treating them as universal standards.

---

# 3. Retrieval and agent foundations

## Retrieval-augmented generation

- Source: Lewis et al., [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://papers.neurips.cc/paper/2020/file/6b493230205f780e1bc26945df7481e5-Paper.pdf), NeurIPS 2020.
- Applies to: Module 8 RAG foundations.

The original research combines a generative model with retrieved non-parametric memory. The course extends this concept to organizational systems, where document governance, metadata, access control, freshness, retrieval evaluation, source conflict, citation support, and injection resistance are necessary operational concerns.

Do not cite the original paper as proof that a specific organizational RAG implementation is accurate. Evaluate the actual corpus, retriever, generator, user interface, and workflow.

## Reasoning and acting

- Source: Yao et al., [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629), ICLR 2023.
- Applies to: Module 8 agent concepts.

ReAct is a useful conceptual foundation for interleaving model reasoning and actions in an environment. The course translates that concept into an operational loop with authorization, bounded tools, observable state, stopping conditions, audit traces, and human intervention.

The paper is not evidence that autonomous operation is appropriate for a given business workflow. That depends on consequences, observability, reversibility, permissions, and tested performance.

---

# 4. Human-centered governance and accountability

## OECD AI Principles

- Source: [OECD AI Principles overview](https://oecd.ai/en/ai-principles)
- Transparency: [Transparency and explainability](https://oecd.ai/en/dashboards/ai-principles/P7)
- Robustness: [Robustness, security and safety](https://oecd.ai/en/dashboards/ai-principles/P8)
- Accountability: [Accountability](https://oecd.ai/en/dashboards/ai-principles/P9)
- Applies to: human oversight, stakeholder impact, auditability, challenge, and lifecycle ownership.

The OECD Principles were updated in 2024. They support the Phase 3 requirements to:

- communicate capabilities and limitations;
- help affected people understand and challenge outcomes;
- maintain traceability appropriate to context;
- keep systems robust, secure, and safe throughout their lifecycle;
- provide override, repair, or decommissioning mechanisms;
- hold actors accountable based on their roles and ability to act.

Human review should therefore be evaluated as a real control: the reviewer needs competence, evidence, time, authority, and a route to challenge or reverse the outcome.

---

# 5. Evidence-use rules for the learner

## Use primary evidence for material claims

Examples:

- regulation: official legal or regulator source;
- product capability: current official documentation plus direct testing;
- company financial claim: audited filing;
- internal performance: reproducible system-of-record analysis;
- research claim: original study and method;
- customer need: direct research with documented sampling and questions.

## Do not confuse these evidence roles

| Evidence | Suitable use | Unsuitable use |
|---|---|---|
| Vendor case study | Hypothesis or implementation example | Independent proof of expected ROI |
| Benchmark | Technical comparison under stated conditions | Guarantee of workflow performance |
| Model-generated summary | Fast orientation | Final factual authority |
| Internal pilot | Evidence for tested population and period | Proof of universal scale performance |
| Expert opinion | Context and hypothesis | Substitute for outcome data |

## Citation and verification record

For every material external claim, record:

- exact claim;
- source title, publisher, link, and date;
- direct support location;
- method or sample when relevant;
- whether the source is primary and independent;
- limitations and transferability;
- access date;
- confidence and decision use.

This record belongs in the Project 5 evidence register and should be reviewed when the business case is updated.

