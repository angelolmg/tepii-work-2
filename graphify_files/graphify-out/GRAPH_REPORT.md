# Graph Report - /home/william/UFRN/MESTRADO/TOPICOS/graphify_test/tepii-work-2/sources  (2026-04-28)

## Corpus Check
- Corpus is ~0 words - fits in a single context window. You may not need a graph.

## Summary
- 10 nodes · 7 edges · 4 communities detected
- Extraction: 43% EXTRACTED · 57% INFERRED · 0% AMBIGUOUS · INFERRED: 4 edges (avg confidence: 0.86)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Collaborative Agent Frameworks|Collaborative Agent Frameworks]]
- [[_COMMUNITY_Intent Decision Architectures|Intent Decision Architectures]]
- [[_COMMUNITY_Sustainable Intent Extraction|Sustainable Intent Extraction]]
- [[_COMMUNITY_Hierarchical Reinforcement Learning|Hierarchical Reinforcement Learning]]

## God Nodes (most connected - your core abstractions)
1. `Hierarchical Decision Transformer with Goal Awareness (HDTGA)` - 2 edges
2. `QLoRA-tuned LLM for Intent Processing` - 2 edges
3. `IntAgent Framework` - 2 edges
4. `Network Data Analytics Function (NWDAF)` - 2 edges
5. `LLM for Intent Extraction` - 2 edges
6. `Mobile-LLaMA` - 1 edges
7. `MAESTRO Collaborative Framework` - 1 edges
8. `Mamba-SSM for Intent-Driven Networks` - 1 edges
9. `Sustainable Multimodal Generative AI` - 1 edges
10. `Attention-based Hierarchical Reinforcement Learning` - 0 edges

## Surprising Connections (you probably didn't know these)
- `LLM for Intent Extraction` --semantically_similar_to--> `QLoRA-tuned LLM for Intent Processing`  [INFERRED] [semantically similar]
  /home/william/UFRN/MESTRADO/TOPICOS/graphify_test/tepii-work-2/sources/2403.02238v2.pdf → /home/william/UFRN/MESTRADO/TOPICOS/graphify_test/tepii-work-2/sources/2505.01841v1.pdf
- `Mamba-SSM for Intent-Driven Networks` --semantically_similar_to--> `Hierarchical Decision Transformer with Goal Awareness (HDTGA)`  [INFERRED] [semantically similar]
  /home/william/UFRN/MESTRADO/TOPICOS/graphify_test/tepii-work-2/sources/2508.06616v2.pdf → /home/william/UFRN/MESTRADO/TOPICOS/graphify_test/tepii-work-2/sources/2505.01841v1.pdf
- `MAESTRO Collaborative Framework` --conceptually_related_to--> `IntAgent Framework`  [INFERRED]
  /home/william/UFRN/MESTRADO/TOPICOS/graphify_test/tepii-work-2/sources/Maestro_LLM-Driven_Collaborative_Automation_of_Intent-Based_6G_Networks.pdf → /home/william/UFRN/MESTRADO/TOPICOS/graphify_test/tepii-work-2/sources/2601.13114v1.pdf
- `Sustainable Multimodal Generative AI` --conceptually_related_to--> `LLM for Intent Extraction`  [INFERRED]
  /home/william/UFRN/MESTRADO/TOPICOS/graphify_test/tepii-work-2/sources/s13638-025-02472-x.pdf → /home/william/UFRN/MESTRADO/TOPICOS/graphify_test/tepii-work-2/sources/2403.02238v2.pdf
- `Mobile-LLaMA` --implements--> `Network Data Analytics Function (NWDAF)`  [EXTRACTED]
  /home/william/UFRN/MESTRADO/TOPICOS/graphify_test/tepii-work-2/sources/Mobile-LLaMA.pdf → /home/william/UFRN/MESTRADO/TOPICOS/graphify_test/tepii-work-2/sources/ts_123288v160400p.pdf

## Hyperedges (group relationships)
- **Intent Processing, Validation, and Execution Pipeline** — 2505_01841v1_qlora_llm, 2505_01841v1_hdtga, 2508_06616v2_mamba_idn [EXTRACTED 0.95]

## Communities

### Community 0 - "Collaborative Agent Frameworks"
Cohesion: 0.5
Nodes (4): IntAgent Framework, MAESTRO Collaborative Framework, Mobile-LLaMA, Network Data Analytics Function (NWDAF)

### Community 1 - "Intent Decision Architectures"
Cohesion: 0.67
Nodes (3): Hierarchical Decision Transformer with Goal Awareness (HDTGA), QLoRA-tuned LLM for Intent Processing, Mamba-SSM for Intent-Driven Networks

### Community 2 - "Sustainable Intent Extraction"
Cohesion: 1.0
Nodes (2): LLM for Intent Extraction, Sustainable Multimodal Generative AI

### Community 3 - "Hierarchical Reinforcement Learning"
Cohesion: 1.0
Nodes (1): Attention-based Hierarchical Reinforcement Learning

## Knowledge Gaps
- **5 isolated node(s):** `Mobile-LLaMA`, `MAESTRO Collaborative Framework`, `Attention-based Hierarchical Reinforcement Learning`, `Mamba-SSM for Intent-Driven Networks`, `Sustainable Multimodal Generative AI`
  These have ≤1 connection - possible missing edges or undocumented components.
- **Thin community `Sustainable Intent Extraction`** (2 nodes): `LLM for Intent Extraction`, `Sustainable Multimodal Generative AI`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Hierarchical Reinforcement Learning`** (1 nodes): `Attention-based Hierarchical Reinforcement Learning`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `QLoRA-tuned LLM for Intent Processing` connect `Intent Decision Architectures` to `Sustainable Intent Extraction`?**
  _High betweenness centrality (0.111) - this node is a cross-community bridge._
- **Why does `LLM for Intent Extraction` connect `Sustainable Intent Extraction` to `Intent Decision Architectures`?**
  _High betweenness centrality (0.083) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `LLM for Intent Extraction` (e.g. with `QLoRA-tuned LLM for Intent Processing` and `Sustainable Multimodal Generative AI`) actually correct?**
  _`LLM for Intent Extraction` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `Mobile-LLaMA`, `MAESTRO Collaborative Framework`, `Attention-based Hierarchical Reinforcement Learning` to the rest of the system?**
  _5 weakly-connected nodes found - possible documentation gaps or missing edges._