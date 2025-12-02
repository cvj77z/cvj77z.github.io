# Prompt Engineering

This section showcases multi-step, domain-specific prompt systems designed for realistic use cases requiring structured reasoning, classification, contextual judgment, and safe language adaptation. Each sample includes a description of its purpose, the skills demonstrated, and why the prompt is relevant to enterprise AI workflows.

---

## 1. Crime Log Classifier  
**Domain:** Operational triage / enterprise workflows  
**Purpose:** Route incoming incident reports into strict categories using deterministic logic.

**Skills Demonstrated:**  
- taxonomy design  
- rule ordering and prioritization  
- ambiguity handling  
- structured output formats  
- differentiating overlapping intent signals  
- real-world scenario mapping  

**Description:**  
A structured classification system that assigns incoming text to categories (A through E4) based on content type, urgency, threat language, identifying details, and operational implications.  
It includes rules for:  
- identifying coded urgency  
- distinguishing employee inquiries from general complaints  
- detecting media requests  
- separating legal threats from negative sentiment  
- clarifying overlapping categories through priority rules  

**Link to full prompt:**  
➡️ `Crime-Log-Classifier.md`

---

## 2. Wildlife Transport Classifier  
**Domain:** Logistics / safety / regulatory reasoning  
**Purpose:** Determine feasibility, legality, and ethical constraints for transporting animals.

**Skills Demonstrated:**  
- conditional logic  
- risk modeling  
- rule hierarchy  
- structured approvals (Approved / Conditional / Denied)  
- combining classification with reasoning summaries  

**Description:**  
Evaluates transport requests based on species, size, danger level, legality, handling risk, containment requirements, and ethical considerations. Produces a classification plus a reasoning explanation that follows a strict safety-first rule system.

**Link to full prompt:**  
➡️ `Wildlife-Transport-Classifier.md`

---

## 3. Sociolinguistic Code-Switcher  
**Domain:** Applied sociolinguistics / tone adaptation  
**Purpose:** Analyze a user’s linguistic cues and adjust the model’s tone accordingly.

**Skills Demonstrated:**  
- register detection  
- idiom and slang analysis  
- politeness strategy mapping  
- cultural and generational language cues  
- safe tone adaptation with protective constraints  

**Description:**  
Analyzes user input (idioms,
