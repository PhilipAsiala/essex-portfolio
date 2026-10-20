---
title: "01 — Introduction unit"
permalink: /modules/01-introduction-unit/
---

# 01 — Introduction unit

| | |
| --- | --- |
| Module code | *to confirm* |
| Dates | October 2026 |
| Tutor | Dr Mohammad Aamir Turk |
| Marker | Anrich Potgieter |
| Result | Pass |

## Learning outcomes

The unit's stated outcomes, numbered as the handbook numbers them, each followed by one line on where on this page the evidence for it is.

1. *To copy from the unit handbook.*

## Artefacts and feedback

| Artefact | Due | Submitted | What it is | Feedback | Link |
| --- | --- | --- | --- | --- | --- |
| Short paper, first submission: *AI in Public Sector Tax Administration: Fraud Detection and Cognitive Governance* | *to confirm* | *to confirm* | About 550 words; four references, one uncited | [Below](#feedback-on-the-first-submission), verbatim | [draft]({{ "/artefacts/01-introduction-unit/draft/" | relative_url }}) |
| Short paper, final: *AI in Public Sector Tax Administration: Fraud Detection and Operational Change* | *to confirm* | *to confirm* | About 1,140 words; sector delimited, AI defined from Russell and Norvig, GAO and TIGTA evidence, controls specified per AI type, seven references all cited | Pass | [paper]({{ "/artefacts/01-introduction-unit/paper/" | relative_url }}) |

### Feedback on the first submission

Marker: Anrich Potgieter. Quoted in full.

> **Quality of writing.** Your writing is confident and technically fluent, with clear control of domain-specific vocabulary. However, the density of specialised terms (for example, "axiology," "policy-as-code," "multi-tenant data lakehouses," "metrological data") occasionally obstructs readability for a general academic audience. Several long sentences carry multiple ideas, which makes key points harder to follow. Aim to unpack complex terms briefly when first introduced and break long sentences into shorter, signposted statements. Maintain a consistently neutral academic tone by qualifying strong claims (e.g., "massive operational risks") with precise, evidence-based language.
>
> **Presentation and content.** The report has a logical flow (introduction → operational impact → critique/constraints → professional practice → conclusion). The focus on fraud detection and governance is relevant and the discussion of implementation constraints shows good depth. To improve: explicitly signpost the chosen industry in the introduction and keep that framing consistent throughout. The brief asks about "the way businesses operate" in the chosen industry; your focus is predominantly on public sector agencies. Either reframe as the Finance industry (with tax administration as a subdomain) or explicitly justify "Public Sector" as your chosen sector and comment on how AI affects organisational operations in that sector in business-like terms (e.g., workflows, decision rights, service delivery, cost/risk controls). Strengthen the discussion with a clearer distinction between predictive vs. generative AI impacts, and link each to concrete operational changes (process redesign, staffing, audit workflows, performance metrics). Where you raise risks (hallucinations, transparency, bias), add concise examples of controls (model monitoring, policy enforcement points, human-in-the-loop checkpoints) and briefly evaluate trade-offs, not just challenges.
>
> **Following instructions.** You define AI and assess impacts, and you include reflection on professional practice, which aligns with the task. Clarity about the industry needs tightening to fully meet the brief. Also ensure the discussion explicitly links AI technologies to changes in how organisations "operate" (processes, governance, controls, outcomes) rather than focusing mostly on architectural principles.
>
> **Understanding.** You demonstrate strong conceptual understanding of machine learning pipelines, governance, and MLOps. Your critique of embedding values into infrastructure is thoughtful. To deepen academic understanding for an induction module, balance philosophical framing (axiology) with practical, evidenced operational outcomes (e.g., detection rates, false positive impacts, workload shifts, cost-benefit), supported by sources.
>
> **Referencing.** You use credible core sources and integrate in-text citations. Improve by: (1) citing a clear, widely accepted definition of AI when you first define it; (2) adding sector-specific reports or peer-reviewed studies that evidence operational impacts and controls in tax/fraud contexts; (3) ensuring consistent reference formatting (capitalisation, punctuation) according to a specified style. Where you present claims about capabilities or risks, anchor them with citations, not only practitioner assertions.
>
> **Actionable recommendations.**
> 1. State the chosen industry explicitly in the introduction and align the analysis to "how organisations operate" in that industry, using concrete operational examples.
> 2. Reduce jargon density: define key terms briefly on first use and split longer sentences to improve readability.
> 3. For each AI capability (predictive vs. generative), add 1–2 evidenced operational effects and one control measure, each with a supporting citation.
> 4. Tighten and standardise referencing; add a source for the AI definition and sector-specific evidence on fraud detection outcomes.
> 5. Include concise signposting throughout (e.g., "Impact on workflows," "Risk controls," "Implications for practice").

### What I did with it

| Recommendation | In the final |
| --- | --- |
| 1. State the industry; analyse how organisations operate | Introduction names public sector tax administration as the sector, distinguishes it from private financial services, and the whole paper is organised around workflows, decision rights, staffing, service delivery, and cost/risk controls |
| 2. Reduce jargon; shorter sentences | Axiology, policy-as-code, and metrological data are each defined on first use; "massive" and similar intensifiers removed; sentences split |
| 3. Per capability, evidenced effects plus a control | Predictive: GAO (2026) $88 billion prevented and TIGTA (2026) false-positive reduction, control = monitoring and threshold calibration. Generative: narrative drafting for auditors, control = mandatory human-in-the-loop review, surfaced features, logging |
| 4. Referencing | AI defined from Russell and Norvig (2021, p. viii); GAO, TIGTA, and IBM added as sector and definitional sources; all seven references cited; formatting standardised |
| 5. Signposting | "Impact on workflows", "Risk controls and trade-offs", "Embedding constraints", "Practical evaluation", "Implications for Professional Practice" used as bold lead-ins and headings |

The side-by-side of the two texts is on the [artefact page]({{ "/artefacts/01-introduction-unit/" | relative_url }}).

Feedback is quoted verbatim where I have permission; otherwise summarised. Under each piece of feedback: what I did with it.

## Reflection

*To write after the result.* Three questions: what I believed before the unit, what the evidence from the unit did to that belief, and what I will do differently.

## Meeting notes

| Date | With | Purpose | Decisions and actions |
| --- | --- | --- | --- |
| | | | |

## Professional skills matrix and action plan

| Skill | Before (1–5) | After (1–5) | Evidence on this page | Action to use or extend it |
| --- | --- | --- | --- | --- |
| Academic writing with Harvard referencing | | | the revision: every reference cited, page-level citation for the definition, British register | |
| Writing for a general academic reader (defining terms, sentence length, neutral tone) | | | marker's "Quality of writing" and recommendation 2; the final's first-use definitions | |
| Arguing from documented evidence rather than assertion | | | GAO and TIGTA figures replacing unquantified claims | |
| Framing an engineering problem as a governance problem | | | the policy-as-code and value-constraints section | |

Rolled up into the [programme skills record]({{ "/skills/" | relative_url }}) when the unit is finished.

## Connection to the thesis

The paper's central move, that the metrological data of a filing establishes what is the case while policy-as-code enforces what may be done with it, and that confidence is not a licence to act, is the seed of the axiology layer and the admission gate in [moepa-thesis](https://github.com/PhilipAsiala/moepa-thesis). The paper's open problem (translating qualitative values into enforceable rules at scale) is what the thesis's commitment function is meant to answer.
