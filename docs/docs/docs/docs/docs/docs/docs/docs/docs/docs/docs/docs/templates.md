# Templates

## Purpose of Templates
Templates provide standardized structures for documenting, validating, monitoring, and governing models. They ensure consistency across teams, improve auditability, and reduce the risk of missing required information.

These templates apply to traditional models, machine learning systems, and large language models (LLMs).

---

# 1. Model Documentation Template

## Basic Information
- Model Name:
- Version:
- Owner:
- Developer:
- Business Unit:
- Risk Tier:

## Purpose and Use Case
- Intended Use:
- Decision Impact:
- Regulatory Relevance:
- Customer Impact:

## Model Type
- Traditional / ML / DL / LLM / Vendor / RAG System

## Methodology
- Description of Approach:
- Key Assumptions:
- Limitations:
- Data Sources:
- Feature List (if applicable):

## Training and Testing (for ML/LLMs)
- Training Data Summary:
- Validation Data Summary:
- Hyperparameters:
- Model Architecture:
- Prompt Templates (LLMs):
- RAG Components (if applicable):

## Performance
- Key Metrics:
- Benchmark Comparisons:
- Stability and Robustness Results:

## Explainability
- Methods Used:
- Key Insights:
- Limitations:

## Bias and Fairness
- Protected Classes Evaluated:
- Metrics:
- Mitigation Steps:

## Monitoring Plan
- Metrics:
- Thresholds:
- Drift Detection Methods:
- Human-in-the-Loop Requirements:

## Change Management
- Version History:
- Material Change Criteria:
- Approval Requirements:

---

# 2. Model Validation Template

## Validation Overview
- Scope:
- Objectives:
- Validation Date:
- Validator(s):

## Conceptual Soundness
- Methodology Review:
- Assumptions:
- Limitations:
- Data Quality Assessment:

## Performance Testing
- Accuracy / Error Metrics:
- Stress Testing:
- Sensitivity Analysis:
- Benchmarking:

## AI/ML-Specific Testing
- Bias and Fairness:
- Explainability:
- Robustness:
- Hyperparameter Review:

## LLM-Specific Testing
- Hallucination Testing:
- Prompt Sensitivity:
- Safety and Toxicity:
- Data Leakage Checks:
- Guardrail Evaluation:

## Findings and Issues
- Summary of Issues:
- Severity Ratings:
- Required Remediation:

## Conclusion
- Overall Assessment:
- Approval Recommendation:

---

# 3. Monitoring Report Template

## Model Information
- Model Name:
- Version:
- Owner:
- Risk Tier:

## Monitoring Period
- Start Date:
- End Date:

## Performance Metrics
- Accuracy:
- Error Rates:
- Stability:
- Calibration:

## Drift Analysis
- Data Drift:
- Concept Drift:
- Performance Drift:

## AI/ML-Specific Monitoring
- Feature Importance Changes:
- Bias Metrics:
- Explainability Stability:

## LLM-Specific Monitoring
- Hallucination Rate:
- Prompt Drift:
- Safety Filter Performance:
- Retrieval Quality (RAG):

## Issues and Escalations
- Detected Issues:
- Severity:
- Actions Taken:

## Summary and Next Steps
- Overall Status:
- Required Remediation:
- Timeline:

---

# 4. Change Management Template

## Change Summary
- Change Type:
- Reason for Change:
- Impact Assessment:

## Technical Details
- New Version:
- Updated Parameters:
- Updated Prompts (LLMs):
- Updated Training Data:

## Validation Requirements
- Full Validation Needed? (Y/N)
- Partial Validation Needed? (Y/N)
- Tests Performed:

## Approval
- Approver:
- Date:
- Notes:

---

# 5. Model Retirement Template

## Retirement Summary
- Model Name:
- Version:
- Retirement Date:
- Reason for Retirement:

## Replacement Plan
- Successor Model:
- Transition Steps:
- Risks and Mitigations:

## Documentation Archive
- Location of Artifacts:
- Final Validation:
- Final Monitoring Report:

## Lessons Learned
- Issues Identified:
- Improvements for Future Models:

---

# Summary
These templates provide standardized structures for documenting, validating, monitoring, and managing models across their lifecycle. They support consistency, auditability, and regulatory compliance for traditional models, ML systems, and LLM-based architectures.
