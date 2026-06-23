# SR 11-7 for AI Models

## Overview
SR 11-7 is the foundational supervisory guidance for model risk management in the United States. Although originally written with traditional models in mind, regulators have made it clear that AI, ML, and LLM-based systems fall fully within its scope.

Any system that uses data, assumptions, and processing to produce outputs that inform decisions is considered a “model” under SR 11-7 — including generative AI.

## Core Principles of SR 11-7
SR 11-7 is built on three pillars:

### 1. Model Development, Implementation, and Use
Models must be:
- Conceptually sound  
- Based on appropriate data  
- Properly implemented  
- Used within their intended purpose  

For AI models, this includes:
- Documenting training data  
- Explaining methodology  
- Understanding limitations  
- Ensuring appropriate use cases  

### 2. Model Validation
Validation must be:
- Independent  
- Comprehensive  
- Well-documented  

For AI and ML models, validation expands to include:
- Bias and fairness testing  
- Explainability analysis  
- Robustness and stability testing  
- Hyperparameter and training methodology review  

For LLMs, validation must also address:
- Hallucination testing  
- Prompt sensitivity  
- Safety and toxicity risks  
- Data leakage concerns  

### 3. Governance, Policies, and Controls
Organizations must maintain:
- Clear roles and responsibilities  
- Model inventories  
- Risk tiering frameworks  
- Change management processes  
- Ongoing monitoring  

AI and LLM systems require additional governance such as:
- Prompt governance  
- Guardrails and filters  
- Human-in-the-loop controls  
- System-level monitoring (e.g., RAG pipelines)  

## How SR 11-7 Applies to AI and ML Models
Regulators expect AI and ML models to meet **all** SR 11-7 requirements, plus additional controls due to:
- Non-linearity  
- Reduced interpretability  
- Sensitivity to data drift  
- Bias and fairness risks  

Key expectations include:
- Stronger documentation  
- Enhanced validation  
- Continuous monitoring  
- Clear explanation of model behavior  

## How SR 11-7 Applies to LLMs
LLMs introduce risks not present in traditional models. Under SR 11-7, firms must address:

### Hallucinations
LLMs may generate incorrect or fabricated content.

### Prompt Sensitivity
Small prompt changes can produce inconsistent outputs.

### Safety and Alignment
Outputs may be biased, harmful, or non-compliant.

### Data Leakage
LLMs may reveal memorized training data.

### System-Level Behavior
LLMs often operate within:
- RAG systems  
- Agent frameworks  
- Workflow automation  

These must be validated and monitored as part of the model ecosystem.

## Documentation Requirements
SR 11-7 requires documentation that allows an independent reviewer to understand and evaluate the model. For AI and LLMs, this includes:

- Model purpose and intended use  
- Data sources and preprocessing  
- Training methodology  
- Hyperparameters  
- Performance metrics  
- Explainability analysis  
- Bias and fairness testing  
- Monitoring plans  
- Known limitations and failure modes  

Documentation must be complete, accurate, and updated throughout the lifecycle.

## Monitoring Expectations
Monitoring must detect:
- Data drift  
- Concept drift  
- Performance degradation  
- Bias changes over time  
- LLM hallucination rates  
- Prompt drift  
- Guardrail failures  

High-risk models require more frequent and detailed monitoring.

## Governance and Accountability
Regulators expect:
- Senior management oversight  
- Formal approval processes  
- Clear ownership  
- Independent challenge  
- Auditability  

AI and LLM governance must integrate with enterprise model risk management.

## Summary
SR 11-7 applies fully to AI, ML, and LLM-based systems. These models introduce additional risks that require expanded validation, documentation, monitoring, and governance. Aligning AI governance with SR 11-7 ensures regulatory compliance, reduces operational risk, and strengthens trust in model-driven decisions.
