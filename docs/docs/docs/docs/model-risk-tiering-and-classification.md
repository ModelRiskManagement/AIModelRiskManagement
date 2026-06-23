# Model Risk Tiering and Classification

## Why Tiering Matters
Model risk tiering is the process of classifying models based on their potential impact, complexity, and associated risks. Tiering ensures that higher-risk models receive stronger governance, more rigorous validation, and enhanced monitoring.

Tiering enables organizations to allocate resources efficiently and comply with regulatory expectations.

## Tiering Criteria
Models are typically assessed across several dimensions:

### Impact
- Financial exposure
- Customer impact
- Operational disruption
- Regulatory or compliance implications

### Complexity
- Model methodology
- Data dependencies
- Sensitivity to drift
- Explainability challenges

### Usage
- Frequency of use
- Level of automation
- Decision criticality

### Risk Factors
- Bias or fairness concerns
- Stability and robustness
- Sensitivity to assumptions
- Known limitations

Tiering frameworks vary by organization, but most classify models into three or four levels of risk.

## AI and ML-Specific Tiering Considerations
AI and ML models introduce additional risk factors that must be included in tiering:

- Non-linear behavior
- Sensitivity to training data
- Reduced interpretability
- Higher likelihood of drift
- Complex failure modes
- Bias amplification risks

These characteristics often result in AI and ML models being assigned higher tiers than traditional models with similar business impact.

## LLM-Specific Tiering Considerations
Large language models require specialized tiering criteria due to their unique risks:

### Hallucination Risk
LLMs may generate incorrect or fabricated outputs.

### Prompt Sensitivity
Small changes in prompts can produce inconsistent results.

### Safety and Alignment
LLMs may generate harmful, biased, or non-compliant content.

### Data Leakage
Risk of memorized training data appearing in outputs.

### Autonomy and Agents
LLM-based agents may take actions without full human oversight.

LLM tiering must consider both the model itself and the surrounding system (RAG pipelines, guardrails, human review, etc.).

## Examples of Tiering Levels
A common three-tier structure includes:

### Tier 1 (High Risk)
- High financial or regulatory impact
- Critical decision-making
- AI, ML, or LLM models with significant risks

### Tier 2 (Moderate Risk)
- Moderate business impact
- Some automation
- Traditional or ML models with manageable risks

### Tier 3 (Low Risk)
- Low-impact analytical tools
- Simple statistical models
- Models
