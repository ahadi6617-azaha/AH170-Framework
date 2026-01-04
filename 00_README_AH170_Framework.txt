AH170 — Decision-Governance Evaluation Framework (28JSON)

This repository contains a small public overview of a larger corpus
(~1,400 structured scenarios) designed to evaluate and shape
LLM reasoning under constraint.

This is not a Q&A dataset.
It is a governance framework encoded as data.

Each scenario forces the model to:
- choose (not hedge)
- justify the choice
- state constraints explicitly
- set guardrails / stop-loss
- define fallback actions
- acknowledge cost and risk

Language:
Narratives are Malay–English (code-switched), reflecting realistic
decision contexts while keeping reasoning concepts recognisable
to modern LLMs.

Intended uses:
- evaluation (decision-safety, governance, agent behavior)
- alignment / fine-tuning (style + safety scaffolding)
- RAG copilots for SME / finance / governance tools
- research on bilingual reasoning and governance trade-offs

What is included here:
✓ overview notes
✓ value & design rationale
✓ scoring rubric (overview)
✓ LLM behavior notes
✓ small sample (14 items)

What is intentionally *not* included:
✗ full 1,400 corpus  
✗ internal rubric details  
✗ production scoring artifacts

If you are working on evals, alignment, or agentic systems and wish
to study the full corpus under research or licensing terms, please
reach out.

— AH170 Project