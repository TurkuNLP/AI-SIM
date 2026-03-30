
# Prompt Examples for Summary Generation with LLMs: gpt-4o-mini

---

## Summary generated based on human annotated input  
**News ID:** 6  
**Company:** Tata  
**Year:** 2010  

---

### Instruction

You are a helpful, respectful, and honest risk analyst.  
Below is an instruction that describes a task, paired with an input that provides further context.  
Write a response that appropriately completes the request.

You are a domain expert in supply chain risk management. You write concise, executive-style summaries for managers.

You are given risk annotations for one news article about a specific company.

Each annotation includes:

### Risk Classes and Families

#### Financial  
Risks affecting financial performance, market position, or company value.

- Economic Outlook: Overall economic trends (growth, recession)
- Market Crisis: Financial market instability (crashes, credit risks)
- Company Outlook: Business-specific financial risks
- Economic Variables: Inflation, interest rates, commodity prices
- Trading Environment, Competition, Counterparty

#### Geopolitical  
Risks arising from political instability, geopolitical conflicts, changes in government, cross-border tensions, sanctions, or country-level regulatory environments affecting business operations.

- Business Environment (Country Risk)
- Government Business Policy
- Political Violence
- Change in Government
- Corruption & Crime

#### Technology  
Risks related to technology, data, and infrastructure.

- Disruptive Technology
- Cyber
- Critical Infrastructure
- Industrial Accident

#### Environmental  
Risks from natural or environmental factors.

- Extreme Weather
- Geophysical events
- Climate Change (physical, liability, transition risks)
- Environmental Degradation
- Natural Resource Deficiency
- Food Security

#### Social  
Risks related to people, society, or public perception.

- Socioeconomic Trends
- Human Capital
- Brand Perception
- Sustainable Living
- Health Trends
- Infectious Disease

#### Governance  
Risks from management, compliance, or strategy.

- Non-Compliance
- Litigation
- Strategic Performance
- Management Performance
- Business Model Deficiencies
- Pension Management
- Products & Services
- Process Risk (operational workflow, inventory, or supply chain failures)

---

### Task

1. Group the risks by risk class.
2. For each class, write **1–3 sentences** summarizing:
   - risk types and families
   - why they are risks for the company
3. Write a final paragraph (**3–5 sentences**) synthesizing the overall risk narrative.

---

### Requirements

- Do NOT invent risks not present in comments
- Do NOT copy comments verbatim
- Paraphrase and synthesize information
- Use professional corporate risk language
- Maximum length: **220–250 words**

---

### Output format

Risk summary for {'Company'}

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

---

### Input (Human annotated)

```json
[
  {
    "Class": "Environmental",
    "Family": "Climate Change",
    "Risk Type": "Physical Risk",
    "comments": "Climate and biodiversity concerns mentioned around Olive Ridley turtle nesting habitat. However, the court cleared Tata, but NGOs keep pressure. Environmental sensitivity could be a concern for Tata even though official clearance was received."
  },
  {
    "Class": "Geopolitical",
    "Family": "Change in Government",
    "Risk Type": "Environmentalism",
    "comments": "Greenpeace and other activists have accused the government of selectively applying environmental laws to favor Tata. Internal conflict within government suggests policy changes could impact operations."
  },
  {
    "Class": "Geopolitical",
    "Family": "Government Business Policy",
    "Risk Type": "Emerging Regulation",
    "comments": "The Supreme Court referred the matter to a special committee after conservationists requested action under the Forest Conservation Act."
  },
  {
    "Class": "Governance",
    "Family": "Litigation",
    "Risk Type": "Lawsuit",
    "comments": "Tata is involved in litigation related to trademark violation and environmental compliance issues under the Forest Conservation Act."
  },
  {
    "Class": "Social",
    "Family": "Brand Perception",
    "Risk Type": "Negative Media Coverage",
    "comments": "Activists claim environmental laws are selectively applied to corporations, potentially harming Tata’s public image."
  }
]
````

---

### Response (Human annotated summary)

Risk summary for {'Tata'}

Environmental:
Tata faces risks related to climate change and environmental sensitivity, particularly regarding impacts on protected ecosystems such as the Olive Ridley turtle habitat. Although legal clearance was granted, continued pressure from environmental organizations may lead to operational scrutiny and reputational exposure.

Geopolitical:
Risks arise from potential shifts in environmental regulation and policy enforcement. Activism and internal governmental disagreements suggest that regulatory conditions may change, potentially affecting operational approvals and compliance requirements.

Governance:
Ongoing litigation and legal scrutiny introduce governance risks, including potential financial liabilities and regulatory obligations. Legal disputes related to environmental compliance may influence the company's strategic and operational flexibility.

Social:
Negative public perception driven by activism and media attention may affect Tata’s reputation. Allegations of preferential regulatory treatment could reduce stakeholder trust and increase reputational pressure.

Overall assessment:
Tata operates in a complex risk environment shaped by environmental sensitivity, regulatory uncertainty, legal exposure, and reputational challenges. Interactions between activism, governance scrutiny, and policy changes create potential disruptions to operations and brand positioning. Proactive compliance and stakeholder engagement will be essential to mitigate long-term risks.

---

# Summary generated based on LLM annotated input

**News ID:** 6
**Company:** Tata
**Year:** 2010

---
### Instruction

You are a helpful, respectful, and honest risk analyst.  
Below is an instruction that describes a task, paired with an input that provides further context.  
Write a response that appropriately completes the request.

You are a domain expert in supply chain risk management. You write concise, executive-style summaries for managers.

You are given risk annotations for one news article about a specific company.

Each annotation includes:

### Risk Classes and Families

#### Financial  
Risks affecting financial performance, market position, or company value.

- Economic Outlook: Overall economic trends (growth, recession)
- Market Crisis: Financial market instability (crashes, credit risks)
- Company Outlook: Business-specific financial risks
- Economic Variables: Inflation, interest rates, commodity prices
- Trading Environment, Competition, Counterparty

#### Geopolitical  
Risks arising from political instability, geopolitical conflicts, changes in government, cross-border tensions, sanctions, or country-level regulatory environments affecting business operations.

- Business Environment (Country Risk)
- Government Business Policy
- Political Violence
- Change in Government
- Corruption & Crime

#### Technology  
Risks related to technology, data, and infrastructure.

- Disruptive Technology
- Cyber
- Critical Infrastructure
- Industrial Accident

#### Environmental  
Risks from natural or environmental factors.

- Extreme Weather
- Geophysical events
- Climate Change (physical, liability, transition risks)
- Environmental Degradation
- Natural Resource Deficiency
- Food Security

#### Social  
Risks related to people, society, or public perception.

- Socioeconomic Trends
- Human Capital
- Brand Perception
- Sustainable Living
- Health Trends
- Infectious Disease

#### Governance  
Risks from management, compliance, or strategy.

- Non-Compliance
- Litigation
- Strategic Performance
- Management Performance
- Business Model Deficiencies
- Pension Management
- Products & Services
- Process Risk (operational workflow, inventory, or supply chain failures)

---

### Task

1. Group the risks by risk class.
2. For each class, write **1–3 sentences** summarizing:
   - risk types and families
   - why they are risks for the company
3. Write a final paragraph (**3–5 sentences**) synthesizing the overall risk narrative.

---

### Requirements

- Do NOT invent risks not present in comments
- Do NOT copy comments verbatim
- Paraphrase and synthesize information
- Use professional corporate risk language
- Maximum length: **220–250 words**

---

### Output format

Risk summary for {'Company'}

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

---
### Input (LLM annotated)

```json
[
  {
    "Class": "Environmental",
    "Family": "Environmental Degradation",
    "Risk Type": "Potential harm to endangered species",
    "Comment": "Greenpeace highlights risks to endangered Olive Ridley turtles and crocodiles due to industrial development."
  },
  {
    "Class": "Geopolitical",
    "Family": "Government Business Policy",
    "Risk Type": "Regulatory scrutiny",
    "Comment": "Government agencies disagree on environmental compliance findings, creating regulatory uncertainty."
  },
  {
    "Class": "Governance",
    "Family": "Non-Compliance",
    "Risk Type": "Legal violation",
    "Comment": "Documents suggest potential violations of the Forest Conservation Act, posing legal risks."
  },
  {
    "Class": "Social",
    "Family": "Brand Perception",
    "Risk Type": "Activism pressure",
    "Comment": "Greenpeace campaigns may negatively influence public perception."
  }
]
```

---

### Response (LLM annotated summary)

Risk summary for {'Tata'}

Environmental:
Tata faces environmental degradation risks linked to potential impacts on protected species and ecosystems. Industrial development in ecologically sensitive areas may trigger regulatory scrutiny and operational constraints.

Geopolitical:
Regulatory uncertainty stemming from differing government views on environmental compliance could influence policy enforcement and project timelines. Shifts in regulatory interpretation may affect cost structures and operational continuity.

Governance:
Allegations of regulatory non-compliance introduce legal and operational risks. Potential violations of environmental legislation could result in legal disputes, financial penalties, or project delays.

Social:
Public campaigns led by environmental organizations may affect Tata’s brand perception. Continued activism could increase stakeholder pressure and influence reputational standing.

Overall assessment:
Tata faces interconnected environmental, governance, geopolitical, and social risks driven by regulatory scrutiny and public activism. Compliance management and transparent stakeholder communication will be critical to maintaining operational stability and reputation.


