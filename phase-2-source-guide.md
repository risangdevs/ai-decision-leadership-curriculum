# Phase 2 Source Guide

## Purpose and scope

This guide consolidates the external foundations used in Phase 2: analytical question design, data structure, metric quality, evidence interpretation, experimentation, and AI-enabled execution. It supports Modules 3–7 and their cumulative portfolio artifacts.

The inventory was reviewed on **20 October 2026**. Consequential official sources were prioritized for currency checks; a listed source that was not independently re-opened remains a provenance record, not a current-status guarantee. For operational use, record the title, author/institution, publication or version date, identifier, direct claim supported, original URL, access date, verification result, methodology, organizational fit, and any sector- or jurisdiction-specific requirements.

---

# 1. Causal inference, experimentation, and evidence

## Impact Evaluation in Practice

- Source: World Bank and Inter-American Development Bank, [Impact Evaluation in Practice](https://www.worldbank.org/en/programs/sief-trust-fund/publication/impact-evaluation-in-practice)
- Applies to: Modules 3 and 6.

The text supports the curriculum's distinction between description, association, prediction, and causal claims. Its counterfactual logic and treatment of randomized and quasi-experimental methods inform the Business Question Map and Experiment Plan.

## World Bank randomized controlled trials guidance

- Source: [World Bank DIME Wiki — Randomized Controlled Trials](https://dimewiki.worldbank.org/Randomized_Control_Trials)
- Applies to: Modules 3 and 6.

This implementation-oriented resource provides context for treatment and control assignment, compliance, sampling, and analysis. It does not make randomization automatically ethical, feasible, or decision-relevant.

## NIST/SEMATECH experimental-design guidance

- Handbook: [NIST/SEMATECH Engineering Statistics Handbook](https://www.nist.gov/programs-projects/nistsematech-engineering-statistics-handbook)
- Design foundation: [What Is Experimental Design?](https://itl.nist.gov/div898/handbook/pri/section1/pri11.htm)
- Design selection: [Choosing an Experimental Design](https://www.itl.nist.gov/div898/handbook/pri/section3/pri3.htm)
- Applies to: Modules 3 and 6.

These sources support advance definition of objectives, factors, responses, design, and analysis. The curriculum applies these principles to business interventions while adding decision ownership, operational constraints, ethics, guardrails, and scale criteria.

## GAO evidence practices

- Source: [Evidence-Based Policymaking, GAO-23-105460](https://www.gao.gov/products/gao-23-105460)
- Applies to: Modules 3 and 5.

The report informs practices for planning, building, assessing, using, and learning from evidence. It supports the requirement to connect evidence to an explicit decision rather than producing analysis without a decision use.

---

# 2. Data structure and analytical integrity

## Dimensional modeling

- Star schema: [Microsoft Learn — Understand Star Schema and the Importance for Power BI](https://learn.microsoft.com/en-us/power-bi/guidance/star-schema)
- Relationship design: [Microsoft Learn — Many-to-Many Relationship Guidance](https://learn.microsoft.com/en-us/power-bi/guidance/relationships-many-to-many)
- Applies to: Module 4 Data Structure Diagram and Analytical Dataset Contract.

These vendor-authored sources provide accessible definitions and examples for fact tables, dimension tables, grain, and higher-grain relationships. The concepts are broadly useful, but product-specific implementation guidance should be evaluated against the organization's actual platform and model.

## Entity–relationship modeling

- Source: [IBM — What Is an Entity Relationship Diagram?](https://www.ibm.com/think/topics/entity-relationship-diagram)
- Applies to: Module 4.

The overview supports the module's use of entities, attributes, keys, relationships, and cardinality. It is a conceptual vendor source rather than a formal data-modeling standard.

## Statistical quality

- Source: [UK Office for National Statistics — Quality Defined](https://www.ons.gov.uk/methodology/methodologytopicsandstatisticalconcepts/qualityinofficialstatistics/qualitydefined)
- Applies to: Modules 4 and 5.

The ONS fitness-for-purpose framework supports evaluation of relevance, accuracy and reliability, timeliness, accessibility, and coherence/comparability. The curriculum uses these dimensions when assessing datasets and metrics.

---

# 3. Metrics, indicators, and communication

## Results frameworks and indicator selection

- Source: [OECD — Development of a Results Framework](https://www.oecd.org/en/publications/monitoring-and-evaluation-of-child-and-youth-policies-and-outcomes-in-ireland_2bd86a9d-en/full-report/component-5.html)
- Applies to: Module 5 KPI Catalogue.

The guidance supports selecting a limited set of relevant, reliable, valid, and feasible indicators and treating proxy indicators cautiously.

## Composite indicators

- Source: [OECD and European Commission JRC — Handbook on Constructing Composite Indicators](https://www.oecd.org/content/dam/oecd/en/publications/reports/2008/08/handbook-on-constructing-composite-indicators-methodology-and-user-guide_g1gh9301/9789264043466-en.pdf)
- Applies to: Module 5.

The handbook informs the curriculum's cautions about normalization, weighting, aggregation, sensitivity, data quality, and the loss of meaning that can occur when several measures are collapsed into one score.

## Visualization integrity

- Source: [UK Office for National Statistics — Axes and Gridlines](https://service-manual.ons.gov.uk/data-visualisation/guidance/axes-and-gridlines)
- Applies to: Module 5 evidence communication.

The standard supports zero baselines for bars, consistent comparison scales, legible axes, and caution with dual axes. Chart design remains dependent on the analytical question and audience.

---

# 4. AI execution and workforce implications

## NIST AI Risk Management Framework

- Core: [NIST AI RMF Core](https://airc.nist.gov/airmf-resources/airmf/5-sec-core/)
- Full framework: [NIST AI RMF 1.0](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-1.pdf)
- Applies to: Module 7 AI Opportunity Matrix and AI Execution Specification.

The framework supports clear business context, documented human–AI roles, testing in deployment-like conditions, monitoring, appeal and override, incident response, and continual improvement.

## NIST Generative AI Profile

- Source: [NIST AI 600-1: Generative Artificial Intelligence Profile](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf)
- Applies to: Module 7 generative-AI risk analysis and controls.

The profile informs attention to data and content risks, information integrity, testing human–AI configurations, monitoring combined outcomes, and involving operators and affected people in realistic evaluation.

## International Labour Organization research

- Task exposure: [Generative AI and Jobs: A 2025 Update](https://www.ilo.org/publications/generative-ai-and-jobs-2025-update)
- Adoption and job impact: [Artificial Intelligence Adoption and Its Impact on Jobs](https://www.ilo.org/publications/artificial-intelligence-adoption-and-its-impact-jobs)
- Applies to: Module 7 workforce analysis and operating-model design.

These sources support analyzing work at task level rather than assuming that a job title is wholly automated or unaffected. Exposure does not by itself establish displacement, augmentation, productivity, or job quality outcomes in a particular organization.

---

# 5. Source-to-curriculum map

| Curriculum area | Principal sources | Contribution |
|---|---|---|
| Analytical questions and claim strength | World Bank/IDB, GAO | Counterfactuals, evidence roles, and decision-linked analysis |
| Data structure | Microsoft, IBM, ONS | Grain, entities, relationships, cardinality, and fitness for purpose |
| Metrics and evidence | OECD, ONS, GAO | Indicator selection, composite measures, chart integrity, and evidence use |
| Experiment design | NIST/SEMATECH, World Bank DIME | Objectives, assignment, design choice, validity, and analysis |
| AI-enabled execution | NIST AI RMF, NIST GenAI Profile | Context, roles, testing, controls, monitoring, and improvement |
| Workforce implications | ILO | Task-level exposure, augmentation, adoption, and job-quality considerations |

# 6. Evidence-use rules

For every material analytical or implementation claim:

1. Match the source and method to the claim being made.
2. Record definitions, population, unit, timeframe, comparison, and uncertainty.
3. Distinguish independent evidence from vendor guidance and implementation examples.
4. Do not generalize from a pilot, benchmark, or research setting without testing transferability.
5. Keep calculations, data lineage, design choices, and decision rules reproducible.
6. Record an access date and recheck living guidance before operational use.

For publisher provenance and source classification, see the [Source Origin Map](source-origin-map.md).

# 7. Source maintenance control

The curriculum owner appoints a source steward. The steward reviews living sources quarterly, before each cohort, and immediately after a material methods, workforce, technical, or vendor change. The review log records source, prior/current version, status, claims affected, modules/artifacts affected, action, reviewer, date, and approval. A changed URL is not silently substituted; retain the reason and verify whether teaching, calculations, or assessment must change.
