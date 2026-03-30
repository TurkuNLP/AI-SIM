# Prompt Examples for Summary Generation with LLMs: gpt-4o-mini


=============================================================================

This suammary is generated based on human annotated input
News ID: 6 | Company: Tata | Year: 2010 

=============================================================================

You are a helpful, respectful, and honest ris analyst.
Below is an instruction that describes a task, paired with an input that provides further context.
Write a response that appropriately completes the request.
### Instruction:

You are a domain expert in supply chain risk management. You write concise, executive-style summaries for managers.

You are given risk annotations for one news article about a specific company.
Each annotation includes:
-Risk Classes, and Families(with definitions):
    Financial — Risks affecting financial performance, market position, or company value.
        - Economic Outlook: Overall economic trends (growth, recession).
        - Market Crisis: Financial market instability (crashes, credit risks).
        - Company Outlook: Business-specific financial risks.
        - Economic Variables: Inflation, interest rates, commodity prices.
        - Trading Environment, Competition, Counterparty.

    Geopolitical — Risks arising from political instability, geopolitical conflicts, changes in government, cross-border tensions, sanctions, or country-level regulatory environments that affect business operations.
        - Business Environment (Country Risk): Regulatory, legal, and operational risks in specific countries.
        - Government Business Policy: Taxes, trade policies, license revocations.
        - Political Violence, Change in Government, Corruption & Crime.

    Technology — Risks related to technology, data, and infrastructure.
        - Disruptive Technology: Emerging technologies affecting the business.
        - Cyber: Data breaches, malware, or hacking.
        - Critical Infrastructure, Industrial Accident.

    Environmental — Risks from natural or environmental factors.
        - Extreme Weather, Geophysical, Space events.
        - Climate Change: Physical, liability, or transition risks.
        - Environmental Degradation, Natural Resource Deficiency, Food Security.

    Social — Risks related to people, society, or public perception.
        - Socioeconomic Trends: Demographic or societal shifts.
        - Human Capital: Workforce-related risks.
        - Brand Perception: Reputation and public image risks.
        - Sustainable Living, Health Trends, Infectious Disease.

    Governance — Risks from management, compliance, or strategy.
        - Non-Compliance: Legal or regulatory failures.
        - Litigation: Lawsuits or legal disputes.
        - Strategic Performance: Business strategy risks (investment, restructuring).
        - Management Performance: Executive or operational failures.
        - Business Model Deficiencies, Pension Management, Products & Services.
        - Process Risk: Operational workflow, inventory, or supply chain failures.
- risk_type (fine-grained label)
- comment (1–3 sentences describing why this is a risk for the company)

Your task:
1. Group the risks by risk class (Environmental, Geopolitical, Governance, Social, etc.).
2. For each class, write 1–3 sentences summarizing:
   - what kinds of risks appear (families / risk types)
   - why they are risks for the company, using clues from the comments
3. Then write a final short paragraph (3–5 sentences) synthesizing all classes into an overall risk narrative.

Requirements:
- Do NOT invent risks that are not in the comments.
- Do NOT copy the comments verbatim; paraphrase and synthesize them.
- Write in neutral, professional language suitable for a corporate risk report.
- Maximum length: about 220–250 words.

Output format:
Risk summary for {'Tata'}

Environmental:
...
Geopolitical:
...
Governance:
...
Social:
...
Overall assessment:
...

### Input:
[
  {
    "Class": "Environmental",
    "Family": "Climate Change",
    "Risk Type": "Physical Risk",
    "comments": "Climate and biodiversity concerns mentioned around Olive Ridley turtle nesting habitat. However,  the court cleared Tata, but NGOs keep pres. Environmental Sensitivity  could be a concern for Tata even though the official clearance was received, external environmental pressure continues."
  },
  {
    "Class": "Geopolitical",
    "Family": "Change in Government",
    "Risk Type": "Environmentalism",
    "comments": "Greenpeace and other activists have accused the government of selectively applying forest and environmental laws to favor Tata. Internal conflict within the government and legal referrals suggest that future shifts in environmental policy or enforcement could impact Tata Steel's operations."
  },
  {
    "Class": "Geopolitical",
    "Family": "Government Business Policy",
    "Risk Type": "Emerging Regulation",
    "comments": "Last year the Supreme Court referred the matter to a special committee after three conservationists filed an application asking the court to take action under the Forest Conservation Act."
  },
  {
    "Class": "Governance",
    "Family": "Litigation",
    "Risk Type": "Lawsuit",
    "comments": "One of their efforts involves a Pacman-style video game, over which Tata is now suing them for trademark violation. Last year the Supreme Court referred the matter to a special committee after three conservationists filed an application asking the court to take action under the Forest Conservation Act . The federal ministry in a letter to the special committee disagreed with this allegation and the Orissa office 's finding ."
  },
  {
    "Class": "Social",
    "Family": "Brand Perception",
    "Risk Type": "Negative Media Coverage",
    "comments": "Greenpeace activist Ashish Fernandes said that the 'government is selectively applying forest and environmental laws to corporations,' implying that the Government was being partial to Tata."
  }
]
### Response:

Risk summary for {'Tata'}

Environmental:
Tata faces risks related to climate change, specifically concerning the physical impacts on sensitive ecosystems, such as the Olive Ridley turtle nesting habitat. While the company received legal clearance, ongoing environmental pressures from NGOs could pose reputational and operational risks.

Geopolitical:
The company is exposed to risks from potential changes in government policies, particularly regarding environmental regulations. Activism from groups like Greenpeace highlights concerns over selective enforcement of environmental laws that may favor Tata, suggesting that shifts in government stance could disrupt operations.

Governance:
Tata is currently involved in litigation related to trademark violations, which could lead to financial liabilities and distract from core business activities. Additionally, ongoing legal scrutiny concerning environmental practices could result in further regulatory challenges and impact the company’s strategic direction.

Social:
Tata's brand perception is at risk due to negative media coverage and public sentiment surrounding its environmental practices. Accusations of preferential treatment by the government could damage the company's reputation, leading to potential backlash from stakeholders and consumers.

Overall assessment:
Tata is navigating a complex risk landscape characterized by environmental sensitivities, potential geopolitical shifts, and governance challenges. The interplay between regulatory scrutiny and public perception poses significant risks to the company's operations and reputation. Proactive management of these risks is essential to safeguard Tata's market position and ensure sustainable business practices.


=============================================================================

This suammary is generated based on LLM annotated input
News ID: 6 | Company: Tata | Year: 2010 

=============================================================================

You are a helpful, respectful, and honest ris analyst.
Below is an instruction that describes a task, paired with an input that provides further context.
Write a response that appropriately completes the request.
### Instruction:

You are a domain expert in supply chain risk management. You write concise, executive-style summaries for managers.

You are given risk annotations for one news article about a specific company.
Each annotation includes:
-Risk Classes, and Families(with definitions):
    Financial — Risks affecting financial performance, market position, or company value.
        - Economic Outlook: Overall economic trends (growth, recession).
        - Market Crisis: Financial market instability (crashes, credit risks).
        - Company Outlook: Business-specific financial risks.
        - Economic Variables: Inflation, interest rates, commodity prices.
        - Trading Environment, Competition, Counterparty.

    Geopolitical — Risks arising from political instability, geopolitical conflicts, changes in government, cross-border tensions, sanctions, or country-level regulatory environments that affect business operations.
        - Business Environment (Country Risk): Regulatory, legal, and operational risks in specific countries.
        - Government Business Policy: Taxes, trade policies, license revocations.
        - Political Violence, Change in Government, Corruption & Crime.

    Technology — Risks related to technology, data, and infrastructure.
        - Disruptive Technology: Emerging technologies affecting the business.
        - Cyber: Data breaches, malware, or hacking.
        - Critical Infrastructure, Industrial Accident.

    Environmental — Risks from natural or environmental factors.
        - Extreme Weather, Geophysical, Space events.
        - Climate Change: Physical, liability, or transition risks.
        - Environmental Degradation, Natural Resource Deficiency, Food Security.

    Social — Risks related to people, society, or public perception.
        - Socioeconomic Trends: Demographic or societal shifts.
        - Human Capital: Workforce-related risks.
        - Brand Perception: Reputation and public image risks.
        - Sustainable Living, Health Trends, Infectious Disease.

    Governance — Risks from management, compliance, or strategy.
        - Non-Compliance: Legal or regulatory failures.
        - Litigation: Lawsuits or legal disputes.
        - Strategic Performance: Business strategy risks (investment, restructuring).
        - Management Performance: Executive or operational failures.
        - Business Model Deficiencies, Pension Management, Products & Services.
        - Process Risk: Operational workflow, inventory, or supply chain failures.
- risk_type (fine-grained label)
- comment (1–3 sentences describing why this is a risk for the company)

Your task:
1. Group the risks by risk class (Environmental, Geopolitical, Governance, Social, etc.).
2. For each class, write 1–3 sentences summarizing:
   - what kinds of risks appear (families / risk types)
   - why they are risks for the company, using clues from the comments
3. Then write a final short paragraph (3–5 sentences) synthesizing all classes into an overall risk narrative.

Requirements:
- Do NOT invent risks that are not in the comments.
- Do NOT copy the comments verbatim; paraphrase and synthesize them.
- Write in neutral, professional language suitable for a corporate risk report.
- Maximum length: about 220–250 words.

Output format:
Risk summary for {'Tata'}

Environmental:
...
Geopolitical:
...
Governance:
...
Social:
...
Overall assessment:
...

### Input:
[
  {
    "Class": "Environmental",
    "Family": "Environmental Degradation",
    "Risk Type": "Potential harm to endangered species and ecosystems",
    "Comment": "\"Greenpeace is fighting against ... one of which is a breeding ground for the endangered Olive Ridley sea turtles, while another is home to saltwater crocodiles.\" The environmental group believes industrial activity and increased human presence in the area will affect the nesting of these animals. This poses a risk to Tata's operations as it could lead to increased scrutiny, regulatory challenges, and potential project delays or modifications to protect the environment."
  },
  {
    "Class": "Geopolitical",
    "Family": "Government Business Policy",
    "Risk Type": "Regulatory scrutiny and potential policy changes",
    "Comment": "\"The federal ministry in a letter to the special committee disagreed with this allegation and the Orissa office's finding.\" The ongoing scrutiny and differing opinions within government bodies regarding environmental compliance could lead to changes in policy or enforcement that may affect Tata's project timelines and costs."
  },
  {
    "Class": "Governance",
    "Family": "Non-Compliance",
    "Risk Type": "Allegations of regulatory non-compliance",
    "Comment": "\"In response to a Right-to-Information request filed by an environmental activist, the government released documents that showed that an Orissa office of the federal environment ministry had told the latter that the port violated the Forest Conservation Act.\" Allegations of non-compliance with environmental laws could lead to legal challenges, fines, or project halts, impacting Tata's operations and reputation."
  },
  {
    "Class": "Social",
    "Family": "Brand Perception",
    "Risk Type": "Negative public perception and activism",
    "Comment": "\"Greenpeace has been somewhat unsuccessfully spearheading a campaign against a deep-water port along the coast of Orissa.\" Ongoing activism and negative campaigns by Greenpeace could harm Tata's public image and lead to increased pressure from stakeholders to address environmental concerns."
  }
]
### Response:

Risk summary for {'Tata'}

Environmental:
Tata faces risks related to environmental degradation, specifically concerning potential harm to endangered species and ecosystems. Increased industrial activity could lead to scrutiny from environmental groups, resulting in regulatory challenges and possible project delays as measures are taken to protect vulnerable wildlife.

Geopolitical:
The company is exposed to risks from government business policy, particularly regulatory scrutiny and potential changes in policy regarding environmental compliance. Disagreements among government bodies about compliance may lead to shifts in enforcement that could adversely affect project timelines and associated costs.

Governance:
Allegations of regulatory non-compliance present significant governance risks for Tata. Reports of violations of the Forest Conservation Act could result in legal challenges, financial penalties, or operational disruptions, thereby impacting both the company's operations and its reputation.

Social:
Tata is at risk from negative brand perception due to activism from organizations like Greenpeace, which campaigns against the company's projects. Such public opposition can damage the company's image and increase pressure from stakeholders to address the environmental issues raised.

Overall assessment:
Tata's risk landscape is characterized by environmental, geopolitical, governance, and social challenges. The interplay of regulatory scrutiny, allegations of non-compliance, and public activism could significantly impact the company's operational efficiency and reputation. Proactive engagement and compliance strategies will be essential for mitigating these risks and maintaining stakeholder trust.

