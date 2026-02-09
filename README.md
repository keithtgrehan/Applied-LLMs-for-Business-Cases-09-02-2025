# A7: Audio quality complaints

Scoping Philosophy

This repository does not start with models.

It starts with problem framing.

In real business settings, leadership often asks to “use AI” before the problem is clearly defined. The purpose of this repository is to demonstrate disciplined scoping before modeling begins.

The approach follows these principles:
	•	Clarify the real decision first
What decision will this system inform? Who acts on the output?
	•	Avoid automatic supervised learning assumptions
If labels do not exist, supervised learning is not the starting point.
	•	Start with non-ML baselines
Instrumentation, dashboards, cohort analysis, and rule-based checks often solve a significant portion of the problem.
	•	Use ML only where it adds marginal value
Anomaly detection, weak supervision, or causal analysis are introduced only when appropriate.
	•	Separate detection from diagnosis
Identifying an issue is not the same as explaining it. Both must be addressed.
	•	Treat LLMs as thinking partners, not decision-makers
LLMs are used to explore framing and unknown methods, but final reasoning is constrained by product impact, feasibility, and data realism.

This reflects the Machine Learning Workflow principles applied throughout the Master AI folder: define goals, understand data, establish baselines, then model incrementally.


# B4 — Feature Success Evaluation

Overview

Leadership asked to “use ML to determine whether the feature was successful.”

This case reframes the problem properly.

Feature success is not a prediction problem.
It is a causal impact problem.

The goal is to determine whether the feature caused a meaningful change in business outcomes — not whether we can predict engagement.

⸻

Core Principle

Correlation is not success.

This case focuses on:
	•	Causal inference
	•	Experimental design
	•	Metric hierarchy discipline
	•	Decision-grade impact estimation

If an A/B test exists, use it properly.
If it doesn’t, apply structured quasi-experimental methods (Difference-in-Differences, Interrupted Time Series, Synthetic Control).

⸻

What This Case Demonstrates
	•	Correct problem framing before modeling
	•	Metric hierarchy design (North Star + drivers + guardrails)
	•	Step-by-step evaluation plan
	•	Clear separation between prediction and causation
	•	Disciplined ML workflow thinking

⸻

Why This Matters

In business environments, “use AI” is often the default response to ambiguous problems.

This case shows that:
	•	The right solution is sometimes better experimentation, not better models.
	•	Product decisions require causal reasoning.
	•	ML should only be used where it adds marginal value.
