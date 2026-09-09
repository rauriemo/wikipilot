---
fetched_at: &id001 2026-09-09
freshness_window_days: 365
image_count: 0
kind: source
last_updated: *id001
last_verified: *id001
sha256: 88bc6eed63b477d2012b471db5d99d46ef382ac70ba6f0cbfcd0f0c007777bbe
sources: []
title: 'SWE-Bench Pro Verified: A Reliable Benchmark for Software Engineering Agents'
topic: agentic-coding
url: https://arxiv.org/abs/2609.08149
---

## Excerpts

> SWE-Bench Pro has emerged as a standard benchmark for evaluating software engineering agents on challenging repository-level tasks. However, its evaluation is undermined by two sources of unreliability: reward hacking, enabled by leakage of gold solutions or hidden evaluation information, and task quality issues, including misleading problem statements and improperly scoped tests.

> These issues can inflate benchmark performance and obscure agents' true coding ability. We present SWE-Bench Pro Verified, a verified version of SWE-Bench Pro that addresses both problems.

> The proposed anti-hacking controls prevent all observed hacking attempts from succeeding without impairing normal agent functionality. However, the implementation of these controls had a significant impact on model performance.

> The verification process corrected quality issues in 102 instances. Human experts identified quality issues based on publicly reported evidence, used LLMs to filter the instances and draft fixes, and engaged human experts to make minimal changes to task instructions and tests.