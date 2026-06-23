# Model Inventory Requirements

## Purpose of a Model Inventory
A model inventory is the authoritative record of all models used within an organization. It enables effective governance, risk management, regulatory compliance, and operational oversight.

For AI, ML, and LLM systems, the inventory becomes even more critical due to increased complexity, opacity, and risk.

## What Must Be Included in the Inventory
A complete model inventory typically includes:

### Basic Model Information
- Model name
- Unique identifier
- Version number
- Model owner and developer
- Business unit and stakeholders

### Model Purpose and Use Case
- Intended use
- Decision impact
- Customer or regulatory relevance
- Whether the model is customer‑facing or internal

### Model Type
- Traditional statistical model
- Machine learning model
- Deep learning model
- Large language model (LLM)
- Vendor or third‑party model
- RAG or agent‑based system

### Risk Tier
- Tier 1 (High)
- Tier 2 (Moderate)
- Tier 3 (Low)

Risk tier determines the level of required controls, validation, and monitoring.

### Data Information
- Data sources
- Data quality considerations
- Sensitive or regulated data usage
- Training vs. production data differences (for ML/LLMs)

### Technical Details
- Methodology or algorithm
- Key assumptions
- Model architecture (for ML/LLMs)
- Prompt templates (for LLMs)
- RAG pipeline components (if applicable)

### Validation and Testing
- Date of last validation
- Validation results summary
- Known limitations
- Bias and fairness considerations
- Explainability constraints

### Monitoring and Controls
- Performance metrics
- Drift detection methods
- Human‑in‑the‑loop requirements
- Guardrails and safety filters (for LLMs)

### Change Management
- Version history
- Material change indicators
- Retraining or prompt updates
- Governance approvals

### Vendor Information (if applicable)
- Vendor name
- Model documentation availability
- Contractual rights to audit or review
- Known vendor limitations

## Special Requirements for AI and ML Models
AI and ML models require additional inventory fields:

- Training data description
- Hyperparameters
- Feature list
- Model lineage (training → validation → deployment)
- Retraining schedule
- Bias and fairness metrics
- Explainability method used (e.g., SHAP, LIME)

These fields support deeper validation and monitoring.

## Special Requirements for LLMs
LLMs introduce unique inventory requirements:

### Prompt Governance
- Prompt templates
- Prompt versioning
- Safety prompts or system messages

### System Components
- Retrieval sources (for RAG)
- Embedding models
- Guardrails and filters
- Human‑review checkpoints

### Risk Considerations
- Hallucination risk
- Data leakage risk
- Safety and toxicity concerns
- Prompt injection exposure

LLMs must be treated as full model systems, not standalone components.

## Why Regulators Care
Regulators expect a complete, accurate, and up‑to‑date inventory because it:

- Ensures all models are governed
- Enables risk‑based oversight
- Supports auditability and transparency
- Prevents “shadow models”
- Ensures high‑risk models receive proper controls

Inventories are often the first item requested during examinations.

## Summary
A model inventory is the foundation of model risk management and AI governance. It must include detailed information about traditional models, ML systems, and LLM‑based architectures. A complete inventory enables effective oversight, regulatory compliance, and safe, responsible use of AI across the organization.
