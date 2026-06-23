# Model Monitoring and Drift Detection

## Why Monitoring Matters
Model monitoring ensures that models continue to perform as expected after deployment. Even well-validated models can degrade over time due to changes in data, business conditions, user behavior, or external factors.

Monitoring is essential for detecting performance issues early, preventing financial loss, ensuring compliance, and maintaining trust in automated decision-making.

## Types of Drift
Drift occurs when the relationship between inputs and outputs changes. Key types include:

### Data Drift
Changes in the distribution of input data. Examples:
- New customer segments
- Shifts in economic conditions
- Changes in user behavior

### Concept Drift
Changes in the underlying relationship between inputs and outputs. Examples:
- Fraud patterns evolving
- Market dynamics shifting
- New regulatory rules affecting outcomes

### Performance Drift
Degradation in model accuracy, stability, or reliability over time.

Monitoring must detect all three forms of drift to ensure model integrity.

## Monitoring for Traditional Models
Traditional models typically require:

### Performance Tracking
- Accuracy and error metrics
- Stability and calibration checks
- Benchmark comparisons

### Input Monitoring
- Data quality checks
- Outlier detection
- Missing value patterns

### Threshold Alerts
- Predefined performance thresholds
- Automated notifications when metrics fall below acceptable levels

Traditional models are generally more stable, but still require regular monitoring.

## Monitoring for AI and ML Models
AI and ML models are more sensitive to drift and require enhanced monitoring:

### Feature-Level Monitoring
- Feature distribution tracking
- Feature importance changes
- Correlation shifts

### Model Performance Monitoring
- Real-time or near-real-time metrics
- Confidence score analysis
- Stability and robustness checks

### Drift Detection Algorithms
- Population Stability Index (PSI)
- KL divergence
- Kolmogorov-Smirnov tests
- Adaptive drift detectors

### Bias Monitoring
- Fairness metrics over time
- Protected class performance comparisons

ML monitoring must be continuous and automated wherever possible.

## Monitoring for LLMs
LLMs introduce unique monitoring challenges due to non-deterministic outputs and context sensitivity.

Key monitoring areas include:

### Hallucination Monitoring
- Accuracy of generated content
- Fact-checking pipelines
- Scenario-based evaluation

### Prompt and Response Monitoring
- Prompt drift (changes in user inputs)
- Response consistency
- Prompt injection attempts

### Safety Monitoring
- Toxicity detection
- Bias and fairness checks
- Guardrail effectiveness

### System-Level Monitoring
For RAG or agent-based systems:
- Retrieval accuracy
- Context relevance
- Latency and throughput
- Guardrail and filter performance

LLM monitoring must combine automated checks with human review for high-impact use cases.

## Alerting and Thresholds
Monitoring systems must include:

- Clear thresholds for performance degradation
- Automated alerts to model owners and risk teams
- Escalation paths for high-risk issues
- Defined timelines for remediation

Thresholds should be aligned with model risk tier.

## Reporting and Escalation
Monitoring results must be documented and communicated through:

- Regular monitoring reports
- Dashboards and automated summaries
- Issue logs and remediation plans
- Escalation to governance committees for high-risk models

Monitoring must be transparent and auditable.

## Summary
Model monitoring and drift detection ensure that models remain accurate, reliable, and safe after deployment. AI, ML, and LLM models require enhanced monitoring due to their complexity and sensitivity to data changes. Effective monitoring protects organizations from financial, operational, and regulatory harm while enabling responsible and trustworthy model use.
