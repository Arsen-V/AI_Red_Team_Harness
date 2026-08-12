# AI Red-Team Harness

Security testing of LLMs and RAGs.

**What this project demonstrates:** I can find, reproduce, quantify, and explain
failures in LLM guardrails.

## Status
In progress.

## Targets
- Self-hosted `llama3` via Ollama
- One hosted model (TBD) — for comparison

## Approach
Manual prompting generation, then automated scanning (Garak, Promptfoo, PyRIT),
then RAG-layer indirect prompt injection.
