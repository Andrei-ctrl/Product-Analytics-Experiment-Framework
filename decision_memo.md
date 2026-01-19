# Decision Memo — Onboarding Experiment

## Context
User drop-off during onboarding was identified as a key driver of early churn.
A redesigned onboarding flow was tested to improve early retention.

## Hypothesis
Reducing onboarding friction increases 7-day user retention.

## Metric
7-day retention, defined as any user activity on day 7 after signup.

## Experiment Design
- Control: Existing onboarding flow
- Variant: Simplified onboarding flow
- Sample size: ~10,000 users
- Test: Two-sample proportion z-test

## Results
- Control retention: 34.5%
- Variant retention: 36.2%
- Absolute lift: +1.7pp
- p-value: 0.091

## Interpretation
The variant shows a positive retention lift but does not reach statistical significance
at the 95% confidence level. The effect is directionally consistent.

## Risks & Limitations
- Short time horizon
- Early retention only
- Synthetic data

## Recommendation
Continue the experiment to increase statistical power before a full rollout decision.
