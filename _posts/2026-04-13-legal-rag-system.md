---
title: "Legal RAG Assistant for Case Retrieval"
date: 2026-04-13 23:59:00 +0800
categories:
  - portfolio
tags:
  - LLM
  - RAG
  - Legal AI
---

## Problem

Legal and IP teams often spend large amounts of manual effort on compliance analysis and early-stage patent drafting. The project goal was to build an AI assistant that improves drafting efficiency while reducing hallucination risk in legal text generation.

## Data

- Legal compliance documents and policy materials
- Patent-related references and structured drafting requirements
- Domain knowledge indexed into a private vector database at document-chunk level

## Approach

- Built a private RAG pipeline with LlamaIndex and FAISS
- Added hybrid retrieval to improve legal-text recall and precision
- Implemented model switching between DeepSeek cloud APIs and Ollama local models to balance privacy and performance
- Enforced structured outputs with JSON Schema to transform raw outputs into standardized patent proposal documents
- Benchmarked model variants on legal terminology understanding and inference latency

## Outcome & Impact

- Delivered an end-to-end assistant for legal compliance analysis and patent proposal drafting
- Improved retrieval quality and reduced hallucination risk through hybrid search and schema constraints
- Established a practical deployment path with cloud-local model orchestration
- Produced benchmark reports across 5 model variants on legal terminology understanding and inference latency

## Contribution

- Project Leader and Lead Developer
- Designed and implemented the core RAG retrieval pipeline and hybrid search strategy
- Built JSON-schema-based output controls for patent drafting standardization
- Led model selection experiments for cloud/local deployment decisions

## Architecture

![Legal RAG architecture]({{ '/assets/images/projects/legal-rag-architecture.svg' | relative_url }})

## Tech Stack

Python, LlamaIndex, DeepSeek, FAISS, JSON Schema, Prompt Engineering, Ollama
