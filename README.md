# Helio Eval — AI Quality Studio

A responsive, dependency-free prototype for a combined LLM, RAG, agent, and code-generation evaluation workspace.

## Run locally

Open `index.html` in any modern browser. The prototype has no server or package-manager dependency.

## What is included

- A unified command center for quality, regression risk, coverage, and run activity.
- Evaluation-suite library spanning chat, retrieval, agents, and code.
- Versioned-style scenario catalog with interactive case creation.
- Model comparison with quality, faithfulness, agent success, latency, cost, and release gates.
- A human-review workflow for calibrating automated graders.
- Simulated evaluation runs, plus exportable JSON reports.

## Recommended production next steps

1. Add an API service for persisted suites, cases, versions, runs, and annotations.
2. Build runner adapters for model providers, vector stores, agent frameworks, and code sandboxes.
3. Support deterministic assertions, LLM graders, embedding similarity, and calibrated human labels as first-class evaluators.
4. Enforce CI/CD release gates and alert policies from the result store.

