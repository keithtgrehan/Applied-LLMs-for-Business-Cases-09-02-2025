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
