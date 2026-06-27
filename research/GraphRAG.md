# GraphRAG

## Overview
GraphRAG is a structured, hierarchical approach to Retrieval Augmented Generation (RAG) that uses knowledge graphs to improve reasoning over complex information. Introduced by Microsoft Research, it constructs knowledge graphs from corpora for better query answering, especially multi-hop and global questions.

## Key Concepts
- **Knowledge Graph Construction**: Extracts entities and relationships from text.
- **Hybrid Retrieval**: Combines graph traversal, vector search, and summarization.
- **Provenance and Verifiability**: Provides traceable sources for answers.

## Benchmarks
- Significant improvements over naive RAG on comprehensiveness (50-70%), multi-hop QA.
- GraphRAG 2.0: +39.8% Exact Match on HotpotQA.
- Cost reductions: from high indexing costs to much lower.

## Related to Data Webs
Enhances verifiable data through provenance chains in graphs.

## Sources
- Microsoft GraphRAG repo and papers.
- Benchmarks from arXiv papers.

[[Knowledge Graphs]]
[[Hybrid Retrieval]]
[[Verifiable Data]]
