<p align="center">
  <img src="aiarchitectureintel.png" alt="AI Architecture Banner" width="100%" style="max-height: 280px; object-fit: contain;" />
</p>

<h1 align="center">Intel AI Architecture</h1>
<p align="center">
  <strong>Enterprise Architecture documentation for Intel's three AI platform patterns</strong><br>
  SAP Joule &nbsp;|&nbsp; ECA / Azure Copilot Studio &nbsp;|&nbsp; iGPT
</p>

<p align="center">
  <img src="https://img.shields.io/badge/classification-Internal%20Use-blue" alt="Internal Use" />
  <img src="https://img.shields.io/badge/version-1.0-green" alt="Version 1.0" />
  <img src="https://img.shields.io/badge/date-March%202026-lightgrey" alt="March 2026" />
</p>

---

## Overview

This repository contains the enterprise architecture documentation for Intel's AI enablement strategy, delivered through **three complementary architecture patterns** — each purpose-built for a distinct class of use cases.

| Pattern | Best For | Entry Point |
|---------|----------|-------------|
| **SAP Joule** | SAP transactions, navigation, analytics | Joule Assistant bar in SAP apps |
| **ECA / Azure Copilot Studio** | Enterprise data analytics, agentic workflows, non-SAP integrations | Copilot Agent in Teams / MS365 |
| **iGPT** | General-purpose chat, custom assistants, document Q&A | igpt.intel.com/chat |

## Repository Structure

```
├── AI-Architecture-Selection-Guide.md    # Cross-pattern selection guide & decision framework
├── AI-Architecture-Selection-Guide.pdf   # PDF export of the selection guide
├── aiarchitectureintel.png               # Banner image for the selection guide
│
├── Joule Architecture/
│   ├── SAP-Joule-AI-Architecture-Overview.md    # SAP Joule deep-dive architecture document
│   ├── SAP-Joule-AI-Architecture-Overview.pdf   # PDF export
│   └── SAP-AI-Joule-Assistant.png               # Joule banner image
│
├── ECA Architecture/
│   ├── ECA-AI-Architecture-Overview.md           # ECA & AI Enablement architecture document
│   ├── ECA-AI-Architecture-Overview.pdf          # PDF export
│   └── ECAAIArchitecture.png                     # ECA banner image
│
└── iGPT Architecture/
    ├── iGPT-AI-Architecture-Overview.md          # iGPT platform architecture document
    ├── iGPT-AI-Architecture-Overview.pdf         # PDF export
    └── InteliGPT.jpg                             # iGPT banner image
```

## Documents

### AI Architecture Selection Guide

**Start here.** A cross-cutting guide that helps Intel employees, solution architects, and IT teams choose the right AI architecture pattern for their use case. Includes:

- Quick selection guide (one-question routing)
- Decision framework with flowchart and weighted criteria matrix
- Detailed use case catalog (30 use cases across all three patterns)
- Hybrid & multi-pattern scenarios
- Governance, cost, data sensitivity, and scalability comparisons

📄 [AI-Architecture-Selection-Guide.md](AI-Architecture-Selection-Guide.md)

---

### SAP Joule — Architecture Overview

Deep-dive into SAP Joule's AI copilot architecture embedded in SAP applications. Covers identity & access (IAS/IPS), Joule Core on BTP, AI Foundation (SAP AI Core), phased implementation roadmap, product capability matrix, and the Joule Skills architecture for custom agent development.

📄 [Joule Architecture/SAP-Joule-AI-Architecture-Overview.md](Joule%20Architecture/SAP-Joule-AI-Architecture-Overview.md)

---

### ECA & AI Enablement — Architecture Overview

Detailed architecture for Intel's Enterprise Cloud Analytics (ECA) data platform and Azure-based AI runtime. Covers the Snowflake/Databricks data lakehouse, Azure AI agent orchestration, MCP/n8n tool execution, RAG patterns, agentic workflows, and implementation phases.

📄 [ECA Architecture/ECA-AI-Architecture-Overview.md](ECA%20Architecture/ECA-AI-Architecture-Overview.md)

---

### iGPT — Architecture Overview

Architecture documentation for Intel's internal Generative AI platform. Covers the chat interface, no-code Assistant Builder, Marketplace ecosystem, RAG engine, data management pipeline, security model, and sharing/publishing workflow.

📄 [iGPT Architecture/iGPT-AI-Architecture-Overview.md](iGPT%20Architecture/iGPT-AI-Architecture-Overview.md)

---

## How to Use

| Your Role | Start With |
|-----------|------------|
| **Business User** | [Selection Guide — Quick Selection](AI-Architecture-Selection-Guide.md#3-quick-selection-guide) |
| **Solution Architect** | [Selection Guide — Decision Framework](AI-Architecture-Selection-Guide.md#4-decision-framework) |
| **IT / Developer** | Individual architecture deep-dives (Joule, ECA, or iGPT) |
| **Program Manager** | [Selection Guide — Governance](AI-Architecture-Selection-Guide.md#8-governance--compliance) |

## Authors

- **Sajiv Francis** — Enterprise Architect
- **Don Meyers** — Enterprise Architect

## Classification

> **Internal Use** — This repository contains confidential information proprietary to Intel Corporation.

## License

This project is proprietary to Intel Corporation. All rights reserved. No part of this documentation may be reproduced or distributed without prior written permission.
