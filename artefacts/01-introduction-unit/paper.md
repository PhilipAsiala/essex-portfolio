---
title: "Artificial Intelligence in Public Sector Tax Administration: Fraud Detection and Operational Change"
permalink: /artefacts/01-introduction-unit/paper/
---

# Artificial Intelligence in Public Sector Tax Administration: Fraud Detection and Operational Change

*Philip C. Asiala. Final version, introduction unit, University of Essex, revised after feedback on the [first submission]({{ "/artefacts/01-introduction-unit/draft/" | relative_url }}). Result: pass. See the [module page]({{ "/modules/01-introduction-unit/" | relative_url }}).*

## Introduction

This report examines the operational impact of artificial intelligence (AI) within public sector tax administration. The chosen sector is public sector tax administration, a distinct domain of government finance and compliance operations rather than private-sector financial services. Tax authorities such as the Internal Revenue Service (IRS) manage high-volume, regulated workflows that directly affect revenue protection, taxpayer service delivery, and organisational risk controls. AI technologies are reshaping how these organisations detect fraud, allocate staff, and enforce policy.

Artificial intelligence is defined here following Russell and Norvig (2021, p. viii) as the study of agents that receive percepts from their environment and perform actions. In practice, current enterprise systems divide this capability into predictive and generative forms. Predictive AI, primarily through machine learning (ML), analyses large volumes of numerical and categorical data to identify patterns and estimate the probability of future states, such as fraudulent filings (Jordan and Mitchell, 2015). Generative AI produces new text, summaries, or recommendations based on those learned patterns. Distinguishing the two is essential because each changes organisational operations differently: predictive systems alter case selection and process timing, while generative systems alter how human staff interpret and act on model outputs.

## Predictive AI and Changes to Fraud Detection Workflows

**Impact on workflows.** Before widespread ML deployment, tax fraud detection relied mainly on post-disbursement audits. Staff reviewed selected returns after funds had already been paid, creating both revenue loss and delayed recovery. Predictive models now enable real-time screening of incoming returns. Systems evaluate micro-patterns associated with synthetic identity fraud or anomalous claims and can hold or reject a filing before payment (Bao et al., 2020).

This redesign shifts decision rights and performance metrics. Automated filters now perform the initial selection function that previously required substantial human review. According to the U.S. Government Accountability Office (GAO, 2026), the IRS Return Review Program prevented approximately $88 billion in invalid and potentially fraudulent refund payments between fiscal years 2018 and 2024. Parallel identity-theft filters selected millions of returns annually, with the agency reporting that it stopped the large majority of confirmed fraudulent refunds before payment (TIGTA, 2026). These figures illustrate a concrete operational outcome: a measurable reduction in funds disbursed to fraudulent claims and a reallocation of auditor capacity toward higher-risk residual cases.

**Risk controls and trade-offs.** Continuous model monitoring and threshold calibration serve as primary controls. Agencies track false-positive rates because excessive selection of legitimate returns increases taxpayer burden and call-centre workload. TIGTA (2026) noted that the IRS reduced the proportion of legitimate returns selected by identity-theft filters from 55 percent in one processing year to 52 percent in the next, illustrating ongoing adjustment. The trade-off is clear: tighter thresholds protect more revenue but raise legitimate-taxpayer friction and administrative cost; looser thresholds reduce burden but increase residual fraud risk. Staffing implications follow: fewer routine reviews and more specialised investigation of model-flagged cases.

## Generative AI and Support for Audit Decision-Making

**Impact on workflows.** Once a predictive model flags a return, generative systems can convert statistical outputs and data excerpts into plain-language case narratives. Auditors receive a structured summary rather than raw feature scores, which can accelerate initial review and improve consistency of documentation. This supports service delivery by shortening the time between detection and human decision while preserving an audit trail.

**Risk controls and trade-offs.** Generative outputs carry well-recognised risks of factual error or misstatement of statutory requirements. A practical control is mandatory human-in-the-loop review: the generated narrative is treated as a draft that an authorised examiner must verify against source data and applicable law before any adverse action. Additional controls include requiring the system to surface the specific data fields and model features that underpin each claim, and logging every generation for later audit. The trade-off is latency and residual human workload; full automation of narrative acceptance would reduce cost but elevate the risk of erroneous determinations. In high-stakes tax environments, the operational preference remains assisted rather than autonomous decision-making.

## Governance Controls, Policy-as-Code and Value Constraints

**Embedding constraints.** Predictive and generative systems operate on metrological data—the measured characteristics of filings, identities, and historical patterns. These measurements establish empirical regularities but do not themselves encode legal or equity requirements. Policy-as-code is the practice of expressing organisational and statutory rules as machine-readable logic that a policy engine evaluates at runtime (IBM, 2026). In tax administration, such rules can enforce, for example, that a model may not alter a refund decision without an authorised human checkpoint, or that certain protected attributes are excluded from feature sets.

Axiology, the philosophical study of value, supplies a conceptual frame for these constraints: the architecture must privilege legally mandated outcomes and fairness standards over pure statistical optimisation (Floridi et al., 2018). Translating qualitative values into binary or rule-based checks, however, requires explicit design choices. Those choices can inadvertently embed institutional bias if the training data or rule definitions reflect historical disparities. Computational overhead is a second constraint; evaluating dynamic policy checks across large, multi-tenant data platforms increases latency and infrastructure cost. Traceability also declines as model complexity grows, making post-hoc explanation harder in secure federal environments.

**Practical evaluation.** The operational response is layered controls rather than a single technical fix: model monitoring dashboards, periodic bias audits, documented human override authority, and version-controlled policy rules. These measures improve accountability and align automated decisions with statutory intent, yet they do not eliminate residual risk or performance cost. Future research and practice must therefore quantify the marginal revenue protected against the combined cost of false positives, human review, and policy-evaluation overhead.

## Implications for Professional Practice

In roles that support national-scale tax analytics and machine-learning operations, the daily task set has shifted from pure computational optimisation toward the design and maintenance of operational guardrails. Infrastructure-as-code still provisions compute clusters for peak filing season, and security perimeters protect Federal Tax Information. The additional requirement is the construction of routing and policy engines that restrict model behaviour to authorised actions. Practitioners must therefore balance detection performance metrics against taxpayer burden, audit-cycle time, and the reliability of human-in-the-loop checkpoints. The work is less about maximising model accuracy in isolation and more about ensuring that automated processes remain controllable, auditable, and consistent with organisational decision rights.

## Conclusion

Predictive and generative AI enable tax authorities to intercept a larger share of fraudulent filings before funds are disbursed and to support more consistent auditor review. Realised outcomes include substantial revenue protected, as documented by GAO and TIGTA figures, together with measurable shifts in workflow timing and staff allocation. These gains depend on explicit controls—model monitoring, human checkpoints, and policy-as-code enforcement—that introduce their own costs and residual risks of bias or reduced transparency. The limiting factor is therefore not raw computational speed but the capacity to translate statutory and equity requirements into reliable, performant operational constraints. Continued improvement will require both stronger sector-specific evidence of net operational impact and disciplined engineering of those constraints.

## References

Bao, Y., Hilary, G. and Ke, B. (2020) 'Artificial intelligence and fraud detection', in *Innovative Technology at the Interface of Finance and Operations*. Springer, pp. 223–247.

Floridi, L., Cowls, J., Beltrametti, M. et al. (2018) 'AI4People—an ethical framework for a good AI society: opportunities, risks, principles and recommendations', *Minds and Machines*, 28(4), pp. 689–707.

GAO (2026) *Tax fraud: IRS needs an antifraud strategy to better address estimated annual losses of $116 billion to $304 billion*. GAO-26-107810. Washington, DC: U.S. Government Accountability Office.

IBM (2026) *What is policy as code?* Available at: <https://www.ibm.com/think/topics/policy-as-code> (Accessed: 16 October 2026).

Jordan, M.I. and Mitchell, T.M. (2015) 'Machine learning: trends, perspectives, and prospects', *Science*, 349(6245), pp. 255–260.

Russell, S. and Norvig, P. (2021) *Artificial intelligence: a modern approach*. 4th edn. Hoboken, NJ: Pearson.

TIGTA (2026) *Identity theft detection and prevention efforts protect billions in revenue*. Washington, DC: Treasury Inspector General for Tax Administration.
