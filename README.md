# Gül Yıldız

I build AI execution governance systems for agentic and LLM-powered workflows.

My current work focuses on detecting and reducing execution waste in AI systems: coordination loops, repeated planning, false progress, low real work, evidence gaps, budget-aware execution, and audit-ready decision traces.

---

### Current Work

**SBR — Synthetic Bureaucracy Recompiler**

SBR is a deterministic analyzer for AI-agent workflow traces.

It validates native trace schema before scoring, rejects malformed or empty inputs, detects synthetic bureaucracy, and produces CI-grade reports with:

* Synthetic Bureaucracy Index
* workflow diagnosis
* failure modes
* production-risk badges
* gate decisions
* CI exit codes

> SBR is not an LLM judge and not employee monitoring. It analyzes workflow structure and evidence-backed execution behavior.

**Live project:** [syntheticbureaucracy.com](https://syntheticbureaucracy.com/)

**Public showcase:** [github.com/gulyetkin/synthetic-bureaucracy](https://github.com/gulyetkin/synthetic-bureaucracy)

**PermissionLayer — Permission-aware AI Memory Gateway**

PermissionLayer is a permission-scoped RAG gateway: policy runs before retrieval,
field redaction runs before prompt construction, and every decision produces a
hash-chained audit receipt.

> Alpha reference implementation — not production-certified. Same data, same question,
> different user, different allowed context.

**Repository:** [github.com/gulyetkin/permissionlayer](https://github.com/gulyetkin/permissionlayer)

**Neravo — AI Execution Governance Layer**

Neravo is an execution governance layer for AI systems.

It is designed to govern AI execution before expensive or high-risk model calls happen, including routing, budget authorization, premium-worthiness checks, quality/failure detection, provider-aware execution, and audit proof.

---

### Technical Focus

`Python` `TypeScript` `Next.js` `CI-grade validation` `AI agent workflows` `LLMOps` `AI governance` `trace analysis` `workflow risk scoring` `budget-aware model routing` `audit-oriented AI infrastructure`

---

### Positioning

My work is focused on execution governance, not simple AI wrappers.

I build systems that analyze, govern, and verify how AI workflows execute.
