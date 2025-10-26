---
title: ETHOSintel
date: 2025-09-25
links:
  - type: site
    url: https://github.com/Ash-394/ethIndia2025
    name: GitHub Repo
tags:
  - Agentic AI
  - GraphRAG
  - Cryptography
  - Blockchain
  - Web3
image: 
  filename: featured.png 
  caption: "Conceptual overview of ETHOSintel" 
  focal_point: "Smart" 
---

# ETHOSIntel: Using AI Agents and Web3 to Build Public Trust

For the ETHGlobal Delhi 2025 hackathon, my team and I wanted to tackle a real-world problem: the trust gap in public intelligence and policing. It’s hard to trust evidence you can't be sure is original or clearly linked to the witness, and it's hard for analysts to connect the dots.

## The Problem & Our Solution

So, we built ETHOSIntel. It’s a decentralized AI system that does two key things:

1.  **Builds Trust:** When a tip comes in, a "Collector" agent instantly locks the raw evidence on Filecoin, making it immutable and tamper-proof. This ensures data integrity.
2.  **Builds Intelligence:** The agent translates the "fuzzy" text (like "a blue car") into a structured fact. A "Detective" agent then adds this fact to a growing "knowledge graph" (using MeTTa), spotting hidden connections across all reports.

The application of knowledge graphs felt ideal for this use case as I always pictured knowledge graphs as forming complex networks of sticky notes and red string to find hidden relationships between entities, just like the trope in detective films. LLMs make the construction of knowledge graphs much easier as they can understand the semantic relationship between nodes as well.

The final analysis is then logged on the Flow blockchain, creating a fully transparent and verifiable audit trail. It’s a hybrid system that uses AI for insight and Web3 for trust.

## Tech Stack Overview

Here's a breakdown of the technologies used:

* **AI/Logic:** Python, Fetch.ai uAgents, ASI:One, MeTTa
* **Web3:** Filecoin (via Lighthouse), Flow EVM (Solidity)
* **Comms:** FastAPI, WebSockets