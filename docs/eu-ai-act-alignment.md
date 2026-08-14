# HESI–5P and the EU AI Act

> Practical alignment guide · August 2026

The European Union Artificial Intelligence Act is a binding, risk-based legal framework. HESI–5P is a broader innovation and governance model. Used together, they can help a project assemble evidence for legal review while also examining human, environmental, social and institutional outcomes that may go beyond minimum compliance.

This guide is an orientation and working template. It is **not legal advice**, does not determine whether a system is legally compliant, and is not a certification, conformity assessment or CE-marking process. Classification and obligations depend on the facts, the organisation's role, the intended purpose, the deployment context and other applicable EU or national law. Obtain qualified legal and technical advice for consequential uses.

## At a glance

| EU AI Act question | HESI–5P contribution | Evidence to retain |
| --- | --- | --- |
| Is the activity in scope, and what role does each organisation hold? | Define the real-world need, boundaries, actors and accountable people. | System inventory, use-case description, value-chain map, contracts and named owners |
| Is a practice prohibited? | Test dignity, autonomy, safety, rights, inclusion and potential exploitation. | Prohibited-practice screening record, legal review and decision not to proceed where applicable |
| Is the system high-risk or subject to transparency duties? | Examine impact and evidence across People, Planet, Prosperity, Peace and Partnership. | Classification rationale, intended purpose, affected groups, notices and impact assessments |
| Is a general-purpose AI model involved? | Examine upstream and downstream responsibilities, capabilities, limitations and systemic effects. | Model/provider documentation, acceptable-use terms, evaluation results and supply-chain responsibilities |
| Are required controls effective throughout the lifecycle? | Use evidence-led review, human accountability, monitoring, participation and stop conditions. | Risk register, data records, logs, testing, oversight procedures, incidents, monitoring and review decisions |

Legal compliance is the floor, not the whole assessment. A system may be legally permitted yet still perform poorly against HESI–5P because its benefits are weak, its resource use is excessive, its burdens are unfairly distributed or affected people lack meaningful participation and redress.

## Current application timeline

This summary reflects the EU AI Act as consolidated on **27 July 2026** following Regulation (EU) 2026/1744 (the AI Omnibus). Always check the latest consolidated text and Commission guidance before relying on a date.

| Date | Main milestone |
| --- | --- |
| **1 August 2024** | Regulation (EU) 2024/1689 entered into force. |
| **2 February 2025** | Chapters I and II began to apply, including AI literacy and most prohibited-practice rules. |
| **2 August 2025** | Governance provisions, obligations for general-purpose AI models and most penalty provisions began to apply. |
| **27 July 2026** | Regulation (EU) 2026/1744 entered into force and amended the AI Act. |
| **2 August 2026** | The Act became generally applicable; enforcement governance and Article 50 transparency duties are in operation. Certain pre-existing synthetic-content systems have a transition until 2 December 2026 for Article 50(2). |
| **2 December 2026** | New prohibitions introduced by the AI Omnibus concerning non-consensual intimate material and child sexual abuse material begin to apply. |
| **2 December 2027** | Requirements for Annex III high-risk uses begin to apply, including specified uses in biometrics, critical infrastructure, education, employment, essential services, law enforcement, migration and justice. |
| **2 August 2028** | Requirements for high-risk systems connected to products in Annex I begin to apply. |

Earlier or additional duties may arise under data protection, equality, employment, consumer protection, product safety, cybersecurity, sectoral and national law.

## A seven-step alignment process

### 1. Describe the system and intended use

Start with the operational reality rather than the product label.

- Name the system, model, version, provider and deployer.
- Describe the intended purpose, users, decisions supported and people affected.
- Record where the system and its outputs are placed on the market, put into service or used.
- Map data sources, model dependencies, interfaces, downstream uses and reasonably foreseeable misuse.
- State the desired public or organisational outcome and the credible non-AI alternative, including taking no action.

The Act can apply to organisations outside the EU, including where an AI system or GPAI model is placed on the EU market or an AI system's output is used in the EU. Do not infer territorial scope from headquarters alone.

### 2. Identify every legal role

Obligations attach to roles, and one organisation may hold more than one role. Record whether each party is acting as a:

- **provider**, including an organisation developing a system or having it developed and supplying or using it under its own name;
- **deployer**, meaning an organisation using an AI system under its authority;
- **importer**, **distributor**, **authorised representative** or **product manufacturer**;
- **GPAI model provider** or downstream provider; or
- party whose branding, substantial modification or change of intended purpose could cause it to assume provider obligations.

Confirm contractual responsibilities, access to documentation, incident cooperation and change-control duties across the value chain. Contracts can allocate work, but cannot be assumed to remove statutory responsibilities.

### 3. Screen prohibited practices first

Do not continue to a benefit-versus-risk balancing exercise if the proposed practice is prohibited. Article 5 requires a fact-specific screen covering, among other matters:

- harmful manipulation, deception or exploitation of vulnerabilities;
- prohibited social scoring and certain individual criminal-risk prediction;
- untargeted scraping to create or expand facial-recognition databases;
- certain emotion-recognition uses in workplaces and educational institutions;
- biometric categorisation used to infer specified sensitive characteristics;
- real-time remote biometric identification for law enforcement in public spaces, subject to narrowly framed exceptions and safeguards; and
- from 2 December 2026, specified generation or manipulation of non-consensual intimate material and child sexual abuse material.

Use the consolidated Article 5 text and current Commission guidance. Record the facts reviewed, exceptions considered, reviewer, decision and date. Escalate any uncertainty for specialist legal review before development, procurement or deployment continues.

### 4. Classify the system and any model

Classification should be written, evidenced and reviewed whenever the intended purpose, model, users or deployment context changes.

| Layer | Key question | Typical next action |
| --- | --- | --- |
| **High-risk system** | Is the system a safety component of, or itself, an Annex I regulated product; or is its intended use listed in Annex III? | Determine the exact high-risk category, exceptions and applicable date; plan provider/deployer duties, conformity and registration. |
| **Article 50 transparency** | Does the system interact directly with people, generate synthetic content, perform emotion recognition or biometric categorisation, or generate/manipulate deepfakes or public-interest text? | Implement clear, accessible notice, machine-readable marking or disclosure as the relevant paragraph requires. |
| **GPAI model** | Is the organisation providing a model with significant generality, and does it have systemic risk? | Apply model documentation, downstream information, copyright and training-content-summary duties; add systemic-risk controls where applicable. |
| **Other AI system** | Is it neither prohibited nor high-risk and outside specific transparency duties? | Continue applicable general duties, including AI literacy, and apply proportionate voluntary governance. Other laws still apply. |

Avoid treating the four-level risk diagram as the complete legal test. System rules, operator duties and GPAI-model duties can overlap.

### 5. Build the applicable control and evidence set

For **providers of high-risk AI systems**, the Act's control set includes continuous lifecycle risk management, data and data governance, technical documentation, automatic logging, information for deployers, human oversight, accuracy, robustness and cybersecurity. Provider obligations also include a quality management system, conformity assessment, declaration of conformity, CE marking where required, registration, corrective action and post-market monitoring.

For **deployers of high-risk AI systems**, relevant duties include using the system in accordance with instructions, assigning competent and authorised human oversight, ensuring controlled input data is relevant and sufficiently representative, monitoring operation, retaining logs under their control, responding to risks and incidents, informing affected people in specified cases, cooperating with authorities and completing a fundamental-rights impact assessment where Article 27 applies. A data protection impact assessment may also be required under data-protection law.

For **Article 50 systems**, determine the exact provider or deployer disclosure duty. Depending on the use, this can include informing a person that they are interacting with AI, machine-readable marking of synthetic outputs, informing people exposed to emotion recognition or biometric categorisation, or disclosing deepfakes and certain AI-generated public-interest text. Notices must be timely, clear, distinguishable and accessible, subject to the Article's exceptions.

For **GPAI model providers**, Article 53 includes model technical documentation, information for downstream system providers, a copyright-compliance policy and a public summary of training content. Providers of GPAI models with systemic risk also have duties concerning evaluation and adversarial testing, systemic-risk assessment and mitigation, serious-incident reporting and cybersecurity.

For **all providers and deployers**, take context-sensitive measures that support the development of AI literacy among staff and others operating or using AI on the organisation's behalf. The Act does not require a particular certificate or a separately titled AI officer for Article 4, but an internal record of training and guidance is useful evidence. High-risk deployers must ensure the people assigned to human oversight have the necessary competence, training, authority and support.

### 6. Apply the HESI principles and five Ps

The legal workstream and the HESI–5P assessment should share evidence while keeping distinct conclusions.

| HESI principle | Alignment contribution | Questions beyond a narrow compliance checklist |
| --- | --- | --- |
| **Human-centred** | Human oversight, affected-person information, rights, safety and complaint or redress routes | Can a person understand, challenge and obtain meaningful human review? Are dignity and autonomy protected in practice? |
| **Evidence-led** | Classification rationale, risk management, data governance, testing, documentation, logging and monitoring | Are claims independently testable? Are limitations, uncertainty, subgroup performance and failed tests visible to decision-makers? |
| **Sustainable** | Lifecycle risk management and the Act's concern for environmental protection | What energy, water, carbon, material, hardware and e-waste impacts occur across development, deployment and retirement? Could a lower-resource option achieve the same outcome? |
| **Inclusive** | Representative data, accessibility, non-discrimination and fundamental-rights review | Who was absent from design and testing? Are outcomes disaggregated? Who receives benefits and who carries error, cost or surveillance burdens? |

| Five-P lens | EU AI Act connection | HESI–5P evidence |
| --- | --- | --- |
| **People** | Health, safety, fundamental rights, human oversight and AI literacy | Participation, accessibility, wellbeing, autonomy, worker impact and routes to human review |
| **Planet** | Environmental protection, lifecycle risk and emerging sustainability practices | Energy, water, emissions, materials, biodiversity, rebound effects and retirement plan |
| **Prosperity** | Innovation, product assurance and support for SMEs and sandboxes | Affordability, decent work, capability-building, productivity evidence and distribution of economic value |
| **Peace** | Rule of law, accountability, transparency, cybersecurity and enforcement | Named accountability, security testing, traceability, contestability, incident response and public trust |
| **Partnership** | Value-chain responsibilities and cooperation with providers, deployers and authorities | Affected communities, workers, civil society, researchers, suppliers and regulators involved at the right stages |

See also the [HESI–5P Sustainable Development Goal Alignment Guide](sdg-alignment.md). SDG claims and AI Act compliance claims must each be supported separately; neither proves the other.

### 7. Decide, monitor and improve

Before release or continued use, the accountable human decision-maker should record one of four outcomes: **proceed**, **proceed with conditions**, **pause for evidence or remediation**, or **stop**.

The decision should identify:

- the legal classification and unresolved legal questions;
- required safeguards, owners and completion evidence;
- accepted residual risks and the authority accepting them;
- indicators for performance, rights, inclusion, environmental effects and incidents;
- monitoring frequency, review dates and retained logs;
- thresholds that trigger investigation, suspension, rollback or withdrawal;
- routes for complaints, human review and remedy; and
- how material system, model, data or purpose changes will trigger reassessment.

Providers of high-risk systems must establish documented post-market monitoring. Serious incidents must be escalated and reported under the applicable provider, deployer and authority procedures. HESI–5P adds review of whether intended benefits actually materialise and whether harms or burdens shift between groups, places or generations.

## Minimum combined assessment record

Copy this template into a project record and attach the supporting evidence rather than answering with unsupported yes/no statements.

```markdown
# AI Act + HESI–5P assessment record

## Control information
- System/use case:
- Version and date:
- Provider(s), model(s) and supplier(s):
- Business/public owner:
- Legal/compliance reviewer:
- Technical assurance reviewer:
- Accountable decision-maker:

## Purpose and scope
- Intended purpose and material decisions supported:
- Users, affected people and deployment locations:
- Non-AI alternative and no-action option:
- Data, model and system boundaries:
- Reasonably foreseeable misuse:

## EU AI Act position
- Territorial scope rationale:
- Role(s) by organisation:
- Prohibited-practice screen and evidence:
- High-risk classification and legal basis:
- Article 50 transparency duties:
- GPAI role, obligations and systemic-risk status:
- Other applicable laws and assessments:
- Applicable dates and source version checked:
- Open legal questions:

## Required controls and evidence
- Risk-management record:
- Data governance and provenance:
- Testing, accuracy, robustness and cybersecurity:
- Technical documentation and logs:
- Human oversight and AI literacy:
- Notices, marking and accessibility:
- Conformity, registration and supplier evidence:
- Fundamental-rights and data-protection assessments:
- Post-market monitoring and incident process:

## HESI–5P assessment
- Human-centred findings:
- Evidence-led findings and uncertainty:
- Sustainable lifecycle findings:
- Inclusive participation and distributional findings:
- People:
- Planet:
- Prosperity:
- Peace:
- Partnership:
- Material trade-offs and alternatives:

## Decision and follow-up
- Outcome: proceed / conditional / pause / stop
- Reasons and evidence:
- Conditions, owners and deadlines:
- Residual risks and acceptance authority:
- Indicators, baseline and targets:
- Review date and change triggers:
- Stop, rollback or withdrawal thresholds:
- Complaint, human-review and remedy route:
```

## Common mistakes to avoid

- Treating a vendor's assurance or a HESI–5P score as proof of legal compliance.
- Classifying only the model and ignoring the intended use of the complete system.
- Assuming that adding a human automatically creates meaningful human oversight.
- Relying on a contract without verifying role changes, technical access and supplier evidence.
- Recording accuracy only at aggregate level while hiding performance for affected groups.
- Publishing an AI notice that is late, inaccessible or unclear about the actual use.
- Completing a one-off pre-launch review without logs, incident handling, change control and post-market monitoring.
- Claiming sustainability or SDG alignment without lifecycle evidence and measurable outcomes.

## Primary official sources

- [Consolidated EU AI Act as at 27 July 2026](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:02024R1689-20260727)
- [Regulation (EU) 2024/1689 — original Official Journal act](https://eur-lex.europa.eu/eli/reg/2024/1689/oj/eng)
- [Regulation (EU) 2026/1744 — AI Omnibus amending regulation](https://eur-lex.europa.eu/eli/reg/2026/1744/oj/eng)
- [European Commission AI Act overview, risk levels and application timeline](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai)
- [European Commission AI literacy questions and answers](https://digital-strategy.ec.europa.eu/en/faqs/ai-literacy-questions-answers)
- [European Commission guidance on Article 50 transparency obligations](https://digital-strategy.ec.europa.eu/en/news/commission-publishes-guidelines-transparency-obligations-providers-and-deployers-certain-ai-systems)
- [European Commission overview of GPAI obligations](https://digital-strategy.ec.europa.eu/en/factpages/general-purpose-ai-obligations-under-ai-act)

Because guidance, standards and the law can change, record the version and access date of every legal source used in an assessment.
