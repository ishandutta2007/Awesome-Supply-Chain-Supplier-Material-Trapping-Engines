# Awesome-Supply-Chain-Supplier-Material-Trapping-Engines

## Top Supply Chain Supplier & Material Trapping Engines Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Early-Warning Risk Intelligence, Component Deficit Detection & Supplier Network Monitoring*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Supply Chain Supplier & Material Trapping Engines**. These tools help organizations detect supplier risks, flag component shortages, monitor geopolitical and financial disruptions, and maintain visibility across multi-tier supply networks — turning scattered signals into actionable early warnings.



**Examples** include Resilinc, Everstream Analytics, Interos, Craft.co, Prewave, Sphera Supply Chain, Riskmethods, Coupa, Overhaul, and Project44 (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom risk scoring, and transparent supply chain monitoring — ideal for organizations prioritizing data sovereignty, developers building risk intelligence platforms, and teams avoiding per-supplier pricing.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Resilinc](https://www.resilinc.com/)**  

  Supply chain risk management platform with early-warning alerts, multi-tier mapping, and disruption monitoring across global supplier networks.



- **[Everstream Analytics](https://www.everstream.ai/)**  

  Predictive supply chain risk analytics platform with AI-powered disruption forecasting and supplier risk scoring.



- **[Interos](https://www.interos.ai/)**  

  Supply chain risk intelligence platform with continuous monitoring of suppliers, geopolitical risks, and financial health.



- **[Craft.co](https://www.craft.co/)**  

  Supplier intelligence platform with company data, risk monitoring, and supply chain analytics.



- **[Prewave](https://www.prewave.com/)**  

  AI-powered supply chain risk management platform with early warning system for supplier disruptions and sustainability risks.



- **[Sphera Supply Chain](https://sphera.com/)**  

  Supply chain risk and ESG management platform with supplier monitoring and compliance tracking.



- **[Riskmethods](https://www.riskmethods.net/)**  

  Supply chain risk management platform with automated risk detection and mitigation workflows.



- **[Coupa](https://www.coupa.com/)**  

  Business spend management platform with supply chain risk and supplier intelligence capabilities.



- **[Overhaul](https://overhaul.com/)**  

  Supply chain visibility and risk management platform with real-time tracking and risk monitoring.



- **[Project44](https://www.project44.com/)**  

  Supply chain visibility platform with real-time transportation tracking and disruption alerts.



## Open-Source GitHub Projects



- **[SupplyChain-Risk-Engine](https://github.com/Ali-datasmith/SupplyChain-Risk-Engine)**  

  Real-time supply chain risk intelligence engine built with Polars, DuckDB & Streamlit. Scores geo/delay/financial risk per supplier, simulates disruption scenarios, aggregates 8 RSS feeds (Supply Chain Dive, FreightWaves, JOC, Reuters Trade, Bloomberg Supply Chain), and exports executive PDF reports. Zero-auth, CI-tested on Python 3.12/3.13, deployed free on Streamlit Community Cloud. MIT licensed .



- **[supplychain_resilience_copilot](https://github.com/Bhardwaj-Saurabh/supplychain_resilience_copilot)**  

  Multi-agent supply chain decision-support system built on the **ML-as-Agent-Tool** pattern. Real trained models (Chronos-2 forecasting, XGBoost stockout classifier, Isolation Forest anomaly detector) are served as tools that LangGraph agents call. Features uncertainty-aware escalation, human-in-the-loop gating, and full decision auditing. Python 3.11+ with hexagonal monorepo architecture .



- **[Supply-Chain-Intelligence-System](https://github.com/akshxnsh/Supply-Chain-Intelligence-System)**  

  AI agent that monitors disruption events (news, geopolitical incidents, infrastructure failures), weather alerts, port activity, and tariff updates. Cross-references signals with supplier relationships, shipment timetables, pending orders, and inventory to estimate fulfillment impact, suggest alternative suppliers, and generate purchase orders. Uses Google ADK multi-agent orchestration with BigQuery backend .



- **[supply-chain-sentinel](https://github.com/jadzoghaib/supply-chain-sentinel)**  

  Supply-chain risk sentinel combining GDELT data with LLM risk pipeline and n8n autonomous watch layer. Features scheduled per-supplier sweeps (6-hour intervals), geospatial impact scoring using haversine proximity, approval-gated client notices, and daily digests. FastAPI backend with 3 n8n workflows for continuous monitoring .



- **[supply-chain-knowledge-graph](https://github.com/virbahu/supply-chain-knowledge-graph)**  

  Knowledge graph construction pipeline for supply chain visibility. Fine-tuned spaCy NER extracts companies, products, facilities, and certifications from procurement records and ESG reports. Neo4j backend with FastAPI REST/GraphQL and Streamlit explorer. Enables multi-hop queries impossible in SQL: "Which Tier 3+ suppliers are in flood zones?" .



- **[supplier-risk-ai-v3](https://github.com/virbahu/supplier-risk-ai-v3)**  

  Supplier risk AI with real-time monitoring and auto-mitigation. Academically grounded methodology from Professor Christopher Tang, UCLA Anderson. Configurable for 1K to 100K+ SKUs with comprehensive output metrics and sensitivity analysis. API-ready for ERP/WMS/TMS integration. Claims 60-80% fewer disruptions and 15-30% cost reduction .



- **[sc-control-tower](https://github.com/virbahu/sc-control-tower)**  

  Supply chain control tower for real-time tracking and monitoring. Based on Professor Yossi Sheffi's work at MIT CTL. Provides visibility optimization with configurable parameters, production-ready Python implementation, and sensitivity analysis. Claims 15-30% cost reduction and 20-40% working capital freed .



- **[open-source-supply-chain-risk-mcp](https://github.com/apifyforge/open-source-supply-chain-risk-mcp)**  

  Open-source supply chain risk analysis via MCP for AI agent integration. Provides direct access to CVE records, CISA KEV exploits, maintainer bus-factor scores, and typosquat detection across 7 live intelligence sources. Features `map_dependency_network`, `analyze_community_health`, and `assess_research_security_landscape` tools. Pay-per-event pricing at $0.035 per tool call .



- **[Manifest](https://github.com/hock/Manifest)**  

  Investigative toolkit for researchers, journalists, and scholars interested in visualizing, analyzing, and documenting supply chains and trade networks. Common data standards, flexible geospatial viewer, and basic analytics for evaluating supply chain measures. Browser-based with no data storage — designed for distributed, partial, and temporary supply chain narratives .



- **[eeve](https://github.com/JadeSamLee/eeve)**  

  Evolving Supply Chain Resilience using graph analytics via ArangoDB and cuGraph. Clusters products and suppliers with Louvain community detection, highlights risks, and answers queries like "Which suppliers are at risk?" using AI. Built for ArangoDB Hackathon with Amazon Co-Purchase dataset .



- **[AI-Driven-Supply-Chain-Disruption-Predictor](https://github.com/AnulipiJana/AI-Driven-Supply-Chain-Disruption-Predictor-and-Inventory-Optimization-System)**  

  Infosys Spring Board project for predicting supply chain disruptions and optimizing inventory in real-time. Monitors global news, supplier information, and transportation updates via APIs (NewsApi, GoMaps, WeatherApi). Uses LLM models (Bert, T5, MetaLLM) for risk and sentiment analysis, then suggests inventory adjustments with real-time Slack/email alerts .



- **[autonomous-supply-chain-watchdog](https://github.com/aniket-work/autonomous-supply-chain-watchdog)**  

  Experimental PoC using Phidata agent with OpenAI GPT-4o and DuckDuckGo Search. Scans global news for disruptions ranging from geopolitical tensions to raw material shortages, then generates structured markdown reports with actionable advice. Streamlit dashboard for interactive commodity/company queries .



### Additional Strong Open-Source Options



- **[stochastic-learning-optimization](https://github.com/adeel498/stochastic-learning-optimization)** — Bayesian learning combined with stochastic optimization for resilient automotive supply chains. Claims 7.4% cost reduction in normal conditions and 5.7% improvement during supply problems .

- **[AI-Driven-Forecast-Resilience-Simulator](https://github.com/AquarlisPrime/AI-Driven-Forecast-Resilience-Simulator-for-Supply-Chain)** — Digital twin for supply chain simulation with Prophet/XGBoost/LSTM forecasting, Monte Carlo disruption simulation, and cost-emissions-risk tradeoff analysis .

- **OpenEPCIS Community Edition** — GS1 EPCIS 2.0 repository for supply chain event data sharing. Kafka-powered event pipelines with OpenSearch integration and RESTful APIs for real-time visibility .

- **AI Inventory Management System** — Full-stack inventory platform with AI-powered forecasting, reorder recommendations, and anomaly detection. React/FastAPI/PostgreSQL stack .

- **traceRoot** — Blockchain-based supply chain transparency with QR code tracking from origin through logistics to retail .

- **SQNC** — Open-source supply chain tracking using blockchain for secure cross-organizational data sharing .



**Frameworks for building custom systems**: Combine **SupplyChain-Risk-Engine** for risk scoring and RSS intelligence, **supplychain_resilience_copilot** for ML-powered decision support with HITL gating, **Supply-Chain-Intelligence-System** for multi-signal disruption detection, **supply-chain-knowledge-graph** for multi-tier supplier mapping, and **supply-chain-sentinel** for autonomous watch workflows to build a complete self-hosted supply chain risk intelligence stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Supply chain risk intelligence tools must comply with data protection regulations (GDPR, CCPA), trade compliance requirements, and contractual obligations with suppliers.

- Self-hosted open-source solutions require proper security hardening, data source management, and ongoing model validation.



---



**Made for supply chain risk managers, procurement teams, operations leaders, and developers building early-warning intelligence platforms.**  

Let's make supply chain risk intelligence more open, proactive, and supplier-friendly.
