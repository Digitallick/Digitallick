### Product builder working on applied AI for regulated industries

I build 0-to-1 products and AI-enabled platforms across fintech, capital markets, insurance, SaaS and mobility. Most of my work sits where software meets compliance: products that have to be correct, explainable and auditable before they can ship.

**What I'm working on**

- Evidence-backed research and diligence tools for wealth management, private equity and M&A
- Evaluation and guardrails for LLM features: source fidelity, claim status, retrieval failures, latency and cost per call
- Agentic workflows with human review, step-level traceability and access controls

**Featured projects**

[**regulated-ai-pm**](https://github.com/Digitallick/regulated-ai-pm) is a Claude Code plugin with seven product management skills that take an AI feature in a regulated product from customer interviews to a launch decision: discovery synthesis, PR-FAQ, AI feature brief, eval plan, pre-mortem, launch readiness and an executive update. Each skill is grounded in a published method and tested with its own evals, including trap cases, against the same model without the plugin. A worked example carries one fictional broker-dealer feature through all seven, ending in an evidence-based NO-GO.

[**attestor**](https://github.com/Digitallick/attestor) checks LLM outputs for compliance and keeps the evidence. It verifies that cited statements match their sources, figures included, and catches uncited claims, PII and promissory wording. Each finding is mapped to the FINRA or SEC rule it relates to, and every run lands in a tamper-evident audit log. Python, runs offline, with an optional LLM judge for the hard cases.

**How I work**

- Start from the customer problem and the ways the product can fail, then prototype
- Treat evaluation as part of the product, with golden sets and clear pass and fail rules
- Build governance in early: provenance, review steps and audit trails

**Toolbox:** Python · TypeScript · RAG and vector search · LLM tool calling and orchestration · AWS · SQL and product analytics · SOC 2, securities and privacy requirements
