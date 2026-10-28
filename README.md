# Hector Matos Cybersecurity Portfolio

I am developing my cybersecurity skills through coursework, security research, and business-focused project writing. This portfolio shows how I identify risks, explain their business impact, and recommend practical safeguards.

My current work focuses on risk assessment, identity and access management, secure configuration, vulnerability assessment planning, and security communication. These projects are relevant to entry-level cybersecurity analyst, vulnerability management, and governance, risk, and compliance work.

## Start here

- **[Restaurant system risk assessment](#1-restaurant-management-system-risk-assessment)** — how I prioritize threats and recommend defensive controls.
- **[AI security risk assessment](#2-ai-security-risk-assessment)** — how I evaluate the risks of connecting AI agents to business systems.
- **[Passive information gathering](#3-passive-information-gathering-assessment)** — research supported by screenshots, source comparisons, and documented limitations.

## Project context

These artifacts are educational work, scenario-based assessments, research, policies, or proposals. Recommendations describe what I would implement; they do not establish that a company deployed the controls or that I performed a production security engagement. Tool names below distinguish tools used in research from technologies discussed or proposed in a design.

The original Word reports are linked with each project. Some reports document AI assistance and the review or corrections made to the output; those disclosures remain in the originals.

## 1 Restaurant Management System Risk Assessment

I assessed a restaurant management system scenario using threats associated with FIN6. I ranked five threat scenarios by impact and likelihood, then recommended authentication, scripting, credential-protection, and outbound-traffic controls. The report translates technical concerns into a practical order for remediation.

- **Methods and technologies:** Five-point impact and likelihood matrix; FIN6 threat context; Windows, PowerShell, LSASS, multifactor authentication, logging, and data loss prevention discussed as safeguards.
- **Problem addressed:** Helping management decide which weaknesses to address first when account misuse and payment-data theft could disrupt operations.
- **Deliverable:** Risk table, executive summary, and prioritized recommendations.
- **Evidence boundary:** Scores are scenario estimates, not measured breach probabilities or results from scanning a live system. Encryption protects data in transit; preventing exfiltration also requires destination restrictions, monitoring, access controls, and data loss prevention.
- **[Read the original assessment](TFC%20Restaurant%20Management%20System%20%E2%80%93%20Risk%20Assessment%20Matos.docx)**

## 2 AI Security Risk Assessment

I evaluated a proposed AI deployment for a multi-site restaurant business before implementation. I identified risks involving excessive agent permissions, prompt injection, data leakage, refund abuse, and third-party dependencies. I recommended restricted access, separation of conversational and execution functions, human approval for significant actions, monitoring, and clear ownership.

- **Methods and technologies:** Attack-surface and trust-boundary analysis; AI models and agents, APIs, Flipdish, Clover POS, customer databases, and least privilege considered in the scenario.
- **Problem addressed:** Reducing the chance that an AI integration exposes sensitive information or makes unauthorized operational or financial changes.
- **Deliverable:** Five risk scenarios, priorities, technical recommendations, and governance considerations.
- **Evidence boundary:** This is a pre-deployment design assessment. It does not claim a penetration test, working AI implementation, or demonstrated exploitation.
- **[Read the original brief](TFC%20AI%20Security%20Risk%20Assessment%20Brief%20Matos%20Hector%20Revision%202.docx)**

## 3 Passive Information Gathering Assessment

I researched the public digital footprint of Olympic Eagle Distributing using passive information sources. I compared current records with archived information, distinguished shared hosting from organization-owned systems, and documented confidence levels and collection errors. The report explains how accumulated public information can support phishing and impersonation without treating every discovered record as a vulnerability.

- **Tools used:** Google, ICANN Lookup, WHOIS on Kali Linux, passive DNS and reverse-IP services, the Wayback Machine, Shodan, Maltego, and theHarvester.
- **Problem addressed:** Identifying meaningful public-information exposure while avoiding unsupported attribution and false-positive vulnerability claims.
- **Deliverable:** Research report with screenshots, an evidence inventory, confidence ratings, limitations, and recommendations.
- **Evidence boundary:** The report documents passive research only. Historical records and shared-provider results do not prove current ownership or compromise, and observations reflect the collection period.
- **[Read the original report](Olympic_Eagle_Passive_Information_Gathering_Matos_Hector.docx)** — approximately 20 MB, including screenshot evidence.

## 4 Identity and Access Management Strategy

I designed an identity and access management strategy for the TFC scenario. I mapped employee, administrator, customer, vendor, and service identities to appropriate permissions and approval responsibilities. The strategy addresses account lifecycle management, separate administrative accounts, privileged access, and access checks across connected systems.

- **Methods and technologies:** Role-based access control, multifactor authentication, privileged access management, single sign-on, federation, Windows identity systems, API identities, and architecture diagrams.
- **Problem addressed:** Preventing excessive access, shared-account misuse, and access that remains after an employee or contractor leaves.
- **Deliverable:** Proposed role and approval matrices, access conditions, system diagrams, and implementation priorities.
- **Evidence boundary:** This is an architecture proposal. Application support for federation, single sign-on, and APIs requires verification before implementation.
- **[Read the original strategy](TFC_IAM_Strategy_Hector_Matos.docx)**

## 5 Endpoint Management Policy

I wrote an endpoint management policy for a restaurant business with payment devices, office computers, mobile devices, kiosks, and specialized equipment. The policy defines responsibilities and security expectations across device types, including approved third-party and personal equipment. It connects business ownership with consistent device protection and oversight.

- **Methods and technologies:** Policy development, endpoint inventory and management, access control, security updates, monitoring, recovery, exceptions, and acceptable-use requirements.
- **Problem addressed:** Establishing consistent accountability and security expectations for a varied device environment.
- **Deliverable:** Proposed policy with scope, roles, requirements, enforcement, exception handling, and review provisions.
- **Evidence boundary:** The policy proposes requirements; it does not demonstrate deployed management software, compliance certification, or verified operating effectiveness.
- **[Read the original policy](TFC_Endpoint_Management_Policy_Hector_Matos_V2.docx)**

## 6 Secure Operating System Baseline for a Public Web Server

I developed a proposed Linux operating system baseline for a public-facing Apache host. I selected Ubuntu Server 24.04 LTS and compared it with Rocky Linux 9 using published baseline and lifecycle sources. The recommendations cover reducing unnecessary services, controlling administrative access, logging, patching, integrity monitoring, and rebuilding consistently.

- **Methods and technologies:** Ubuntu Server 24.04 LTS, Rocky Linux 9, Ubuntu Security Guide, NIST National Checklist Program, DISA STIG guidance, AppArmor, SSH, host firewalls, and audit logging.
- **Problem addressed:** Providing administrators with a repeatable secure starting point for an internet-facing server.
- **Deliverable:** Operating system selection rationale and a documented baseline summary.
- **Evidence boundary:** This is a baseline design, not a completed hardening deployment or compliance scan. Apache, TLS, application, and web application firewall settings need separate standards and validation.
- **[Read the original baseline](TFC%20Baseline%20Configuration%20for%20Operating%20System%20Under%20Public%20Web%20Servers%20Matos%20H.docx)**

## 7 Vulnerability Assessment Service Menu

I created an educational service menu to help a nontechnical customer define an assessment before testing begins. It explains a core package and optional services, the information and permissions required, expected deliverables, and relative effort. It also defines exclusions, recovery considerations, and third-party approval requirements.

- **Methods and technologies:** Assessment scoping, statements of work, rules of engagement, asset inventories, credentialed and agent-based assessment concepts, manual validation, and remediation retesting.
- **Problem addressed:** Preventing misunderstandings about assessment scope, responsibilities, operational risk, and authorization.
- **Deliverable:** Client preparation checklist, service comparison, detailed options, and scope boundaries.
- **Evidence boundary:** This is a planning artifact, not evidence of a commercial service business or completed customer assessments. Cost symbols indicate relative effort, not actual prices.
- **[Read the original service menu](Hector_Matos_Vulnerability_Assessment_Service_Menu.docx)**

## 8 Comparison of Security Assessment Methods

I compared vulnerability assessments, penetration tests, risk assessments, and security audits. I explained the question each activity answers, its strengths and limitations, and the evidence it typically produces. Applied scenarios show how an organization's needs affect the choice of assessment.

- **Methods and technologies:** NIST SP 800-115, NIST SP 800-30, CVSS, FAIR, PTES, OWASP testing guidance, and ISACA audit guidance discussed in a comparative research paper.
- **Problem addressed:** Helping readers choose the right assessment and distinguish technical severity, business risk, exploitation evidence, and compliance.
- **Deliverable:** Comparative paper, scenario examples, summary matrix, references, and documented AI-review corrections.
- **Evidence boundary:** Tools mentioned in the paper are examples; their inclusion does not establish hands-on use.
- **[Read the original comparison](Network_Security_Assessment_Comparison_Hector_Matos.docx)**

## 9 Incident Response Plan Proposal

I proposed a four-week project to develop a company incident response plan. The proposal outlines system review, responsibilities, escalation, evidence preservation, recovery procedures, and a tabletop exercise. It explains the need in terms a company owner or manager can use to make a planning decision.

- **Methods and technologies:** Incident response planning, system inventories, log preservation, credential recovery, backup restoration, stakeholder communication, and tabletop exercises.
- **Problem addressed:** Reducing uncertainty and inconsistent action during a security incident.
- **Deliverable:** Management proposal with scope, schedule, resource needs, and expected benefits.
- **Evidence boundary:** This is a proposal to create and exercise a plan, not an implemented response plan or evidence of handling a real incident.
- **[Read the original proposal](Incident%20Response%20Plan%20Proposal%20%281%29.docx)**

## Skills demonstrated

- Analyze threats and explain likely business consequences.
- Prioritize safeguards and document assumptions.
- Research public information, compare evidence, and state uncertainty.
- Design access controls, baseline requirements, and security policies.
- Explain assessment boundaries and security recommendations to nontechnical readers.
- Present findings with supporting reports, tables, diagrams, and screenshots where available.

## Development priorities

My next improvements are to add a documented hands-on lab with reproducible steps, include configuration or script evidence, and verify results before and after a security change. I also plan to add an incident response exercise with recorded observations and a tested recovery procedure. These additions would complement the portfolio's current emphasis on research, assessment, design, and professional writing.

## Portfolio owner

**Hector Matos**  
[GitHub profile](https://github.com/hectorw98-dotcom)

The reports provide evidence of learning and analysis. They do not claim professional certifications or production outcomes that are not documented.

