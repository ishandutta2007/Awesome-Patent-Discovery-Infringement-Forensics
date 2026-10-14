# Awesome-Patent-Discovery-Infringement-Forensics

# Top Patent Discovery & Infringement Forensics Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Patent Landscape Analysis, Infringement Detection & IP Portfolio Management*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Patent Discovery & Infringement Forensics**. These tools help IP teams search global patent databases, analyze competitive landscapes, detect potential infringement, and manage portfolios — combining AI-powered semantic search, litigation data, and strength metrics to surface risks and opportunities.

**Examples** include Patsnap, Anaqua, CPA Global, Clarivate Derwent, LexisNexis PatentSight, Questel, IPlytics, RPX Corporation, GreyB, and ktMINE (the category leaders).

**Open-source emphasis**: This section is expanded with the most relevant open-source projects for self-hosted patent research, portfolio management, and infringement analysis — ideal for IP teams prioritizing data sovereignty, developers building patent tools, and organizations avoiding per-seat enterprise pricing.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Patsnap](https://www.patsnap.com/)**  
  AI-powered patent and innovation intelligence platform with semantic search, claim deconstruction, and predictive risk analytics for infringement detection. Features real-time monitoring and alerts across 160+ jurisdictions. Reports users reduce manual review time by up to 70% and identify risk 3x faster than traditional methods [citation:14]. Cloud or on-prem deployment available.

- **[Anaqua](https://www.anaqua.com/)**  
  Comprehensive IP management platform covering the full lifecycle — from idea capture to patent, trademark, and design rights. Features AI-powered docketing automation, portfolio analytics, and integrated IP services for annuity payments and foreign filings. Used by over half of the top 100 US patent filers [citation:2][citation:15].

- **[CPA Global (Clarivate)](https://clarivate.com/)**  
  Patent annuity and renewals service handling 3.4 million IP rights and nearly $2 billion in payments annually. Features Patent Safety Net™ using the PatentStrength™ algorithm to flag high-value patents due to lapse [citation:3].

- **[Clarivate Derwent](https://clarivate.com/)**  
  Patent analytics platform (formerly Innography) with 165M+ patent documents across 75 full-text jurisdictions. Features human-authored DWPI summaries, AI Classifier for portfolio benchmarking, PatentStrength scoring, and integrated litigation data from 140 jurisdictions [citation:4][citation:17].

- **[LexisNexis PatentSight](https://www.lexisnexisip.com/)**  
  Patent analytics platform with the scientifically-developed Patent Asset Index measuring Competitive Impact through Technology Relevance and Market Coverage. Features Protégé AI assistant for plain-language patent analysis and SEP licensing intelligence [citation:5].

- **[Questel](https://www.questel.com/)**  
  Patent search and analytics platform (Orbit Intelligence) with Sophia AI, image-based search, molecule and sequence search, and AI classification. Covers 240+ trademark databases and 77 design issuing countries [citation:6].

- **[IPlytics](https://www.iplytics.com/)**  
  Standard Essential Patent (SEP) and standards contribution analytics platform. Features Semantic Essentiality Score mapping patent claims to standard sections on a 1-100 scale, plus undeclared patent universe for video codecs [citation:7][citation:20].

- **[RPX Corporation](https://www.rpxcorp.com/)**  
  Patent risk management platform providing defensive patent buying, acquisition syndication, and advisory services to mitigate litigation risk for a client network [citation:8].

- **[GreyB](https://greyb.com/)**  
  Patent research and analytics firm with SEP, licensing, and litigation support. Features CIPAC dashboards, prior art searches finding novelty-killing results in 83% of cases, and patent-backed research solutions [citation:9].

- **[ktMINE](https://www.ktmine.com/)**  
  Royalty rate comparables and full-text licensing agreements database. Provides royalty rates, agreement terms, and industry benchmarking for IP valuation [citation:10].

## Open-Source GitHub Projects

- **[phpIP](https://github.com/jjdejong/phpip)**  
  **Open-source patent and IP rights portfolio manager and docketing system.** Apache-MySQL-PHP stack designed for IP law firms. Features family import via EPO OPS with USPTO ODP fallback/enrichment, renewal management, task automation, and document merging. Explicitly created as an alternative to expensive proprietary tools, with flexibility to adapt to user needs [citation:12].

- **[RECON](https://github.com/anubhavaanand/recon)**  
  **Terminal-native patent research tool aggregating multiple sources.** Keyboard-first TUI/CLI searching USPTO API, PatSnap API, Google Patents, WIPO, Lens.org, and EPO. Features signal scoring (government grants, corporate investment, academic research, recency, news), ASCII citation graphs, export to JSON/CSV/BibTeX/Markdown/PDF, and optional local AI translation via Ollama [citation:11].

- **[mcp-kipris](https://github.com/nuri428/mcp_kipris)**  
  **MCP server for searching patents from 13 countries via KIPRIS international database.** Provides tools for foreign patent search by applicant, application number, free-text, PCT international application number, and international publication number. Available via Smithery, PyPI, or source. MIT licensed [citation:13].

- **[patsnap-pythonSDK](https://github.com/patsnap/patsnap-pythonSDK)**  
  **Unofficial Python SDK for accessing Patsnap's patent APIs.** Features patent search by number, assignee, semantic text, and **image search** (supporting design patents with single and multiple images). Includes analytics operations for counts, field statistics, and query execution with CLI interface for API exploration [citation:1].

### Additional Strong Open-Source Options

- **Open Patent Data Sources** — EPO OPS (Open Patent Services), USPTO ODP (Open Data Portal), WIPO PATENTSCOPE, Google Patents Public Datasets, and Lens.org offer free API access for building custom patent search and analysis tools.
- **Patent Analysis Libraries** — Python libraries for patent parsing, citation analysis, and landscape visualization.
- **Prior Art Search Tools** — Open-source implementations of semantic similarity search for patent novelty assessment.

**Frameworks for building custom systems**: Combine **phpIP** for portfolio management and docketing, **RECON** for multi-source terminal-based patent research, **mcp-kipris** for MCP-based patent search integration, and **patsnap-pythonSDK** for programmatic access to commercial patent data to build a complete open-source patent discovery and analysis stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Patent discovery and infringement tools must comply with legal ethics rules, data protection regulations, and applicable IP laws. **AI-generated infringement assessments are not legal advice** — all findings must be reviewed by qualified patent counsel before enforcement or licensing decisions. Patent validity and infringement opinions require attorney-client privileged analysis.
- Self-hosted open-source solutions require proper API access to patent databases, data quality validation, and legal counsel oversight.

---

**Made for IP attorneys, patent analysts, licensing professionals, and developers building patent intelligence platforms.**  
Let's make patent discovery and infringement forensics more open, accessible, and rigorous.
