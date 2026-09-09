---
fetched_at: &id001 2026-09-09
freshness_window_days: 365
image_count: 0
kind: source
last_updated: *id001
last_verified: *id001
sha256: f8f70bb6ebc8bed1511684bda21deca7263ebcba218f1a0cd0fca0bdb3b3212a
sources: []
title: 'Narrative-to-Scene Generation: An LLM-Driven Pipeline for 2D Game Environments'
topic: ai-in-game-dev
url: https://arxiv.org/abs/2509.04481
---

## Excerpts

> Recent advances in large language models (LLMs) enable compelling story generation, but connecting narrative text to playable visual environments remains an open challenge in procedural content generation (PCG).

> Our pipeline transforms short narrative prompts into a sequence of 2D tile-based game scenes, reflecting the temporal structure of stories. Given an LLM-generated narrative, the system identifies three key time frames, extracts spatial predicates in the form of Object-Relation-Object triples, and retrieves visual assets using affordance-aware semantic embeddings from the GameTileNet dataset.

> A layered terrain is generated using Cellular Automata, and objects are placed using spatial rules grounded in the predicate structure. We evaluate our system on ten diverse stories, analyzing tile-object matching, affordance-layer alignment, and spatial constraint satisfaction across frames.