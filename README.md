# Awesome-Financial-Planning-Analysis-FP-A

# Top Financial Planning & Analysis (FP&A) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Budgeting, Forecasting & Variance Analysis*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Financial Planning & Analysis (FP&A)**. These tools enable finance teams to build driver-based models, run scenario analyses, compare budget vs. actuals, and produce board-ready reports—replacing fragile spreadsheet sprawl with governed, auditable planning workflows.

**Examples** include Workday Financial Planning, Anaplan, Planful, OneStream, Prophix, Vena Solutions, Datarails, Cube, Board, and Mosaic Tech (the category leaders).

**Open-source emphasis**: FP&A is a domain where open-source tooling is **fragmented and largely immature**. No open-source platform provides a complete enterprise FP&A suite comparable to Anaplan or OneStream. The strongest options are either **library-style engines** (opencashflow, KDAF), **Excel-native consolidation tools** (Konsolidat), or **local-first budgeting apps** (OpenFP&A). An independent EU sovereignty review explicitly notes that open-source in Planning & EPM "usually cover parts of the job, not a complete EPM suite," and that "calculation models, approval workflows and reporting do not come ready-made" . Organizations requiring full FP&A capability should plan for commercial platforms or substantial custom development.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Workday Financial Planning](https://www.workday.com/)**  
  Planning within Workday's financial suite, integrating budgeting, forecasting, and reporting with actuals from Workday Financial Management and HCM.

- **[Anaplan](https://www.anaplan.com/)**  
  Connected planning platform widely used for FP&A, with multi-dimensional modeling, scenario analysis, and collaborative planning across finance and operations.

- **[Planful](https://planful.com/)**  
  Financial planning and consolidation platform with budgeting, forecasting, reporting, and close management for mid-market and enterprise finance teams.

- **[OneStream](https://www.onestream.com/)**  
  Unified corporate performance management platform combining financial consolidation, planning, reporting, and analytics in a single application.

- **[Prophix](https://www.prophix.com/)**  
  FP&A software with budgeting, forecasting, reporting, and consolidation capabilities for mid-market organizations.

- **[Vena Solutions](https://www.venasolutions.com/)**  
  Excel-native FP&A platform combining the familiarity of Excel with a governed database, workflow, and audit trail.

- **[Datarails](https://www.datarails.com/)**  
  FP&A platform that layers on top of existing Excel models, providing automated data consolidation, version control, and reporting.

- **[Cube](https://cube Software)**  
  FP&A platform built for spreadsheet users, with automated data integration and multi-dimensional reporting.

- **[Board](https://www.board.com/)**  
  Decision-making platform with FP&A capabilities for integrated business planning and scenario modeling.

- **[Mosaic Tech](https://www.mosaic.tech/)**  
  Strategic finance platform with real-time dashboards, variance analysis, and collaborative planning for SaaS and tech companies.

## Open-Source GitHub Projects

- **[Konsolidat](https://konsolidat.com/)**  
  Open-source, Excel-native EPM for SAP and Microsoft Dynamics environments (MIT licensed). Provides financial consolidation with dynamic ownership/NCI, full audit traceability to source GL, and an `=EPM()` formula interface in Excel backed by ClickHouse and dbt. The stack is Airbyte → dbt → ClickHouse → Frappe, with 26 data-quality assertions run on every pipeline build (consolidation math, CTA integrity, IC elimination, allocations, budgeting, variance, trial balance, YTD/journals). **This is consolidation-focused**, not a full budgeting/forecasting FP&A suite, but it fills the open-source gap for group consolidation with genuine auditability .

- **[OpenFP&A (budgeting-and-forecasting-tool)](https://github.com/himanshusharma75035-sudo/budgeting-and-forecasting-tool)**  
  Local-first open-source FP&A tool (MIT) built with FastAPI + React 19 + SQLite. Features driver-based modeling with a safe formula engine that resolves dependencies across periods, autonomous statistical forecasting with backtested model auto-selection, four budgeting methods, and rigorous variance analysis. The tool ranks the biggest drags and offsets and can generate plain-English variance commentary deterministically offline (optional LLM polishing with a key). One-click export to a formatted multi-tab Excel board pack (summary, line detail, ranked drivers, contribution bridge). Designed for INR/Schedule III but the architecture is adaptable. **The most purpose-built open-source FP&A application** available as a working tool rather than a library .

- **[KDAF (Knowledge-Driven Analytics Framework)](https://pypi.org/project/kdaf/)**  
  Local-first, finance-focused analytics framework (MIT) that combines governed semantic context with financial warehouse evidence so answers can cite what supports them—or refuse unsupported claims. The public demo loads a small FP&A starter model, retrieves semantic context, queries a local financial DWH, builds an evidence packet, produces cited answers, and stores evaluation results. Includes a tool server with MCP-style JSON-line protocol. **Library/framework focused on evidence-backed answers** rather than a complete planning application; suitable for teams building governed FP&A analytics pipelines .

- **[opencashflow](https://pypi.org/project/opencashflow/)**  
  Open-source cash flow projection engine (Python library, not an application). Models a financial sheet as section → row → cell, where each row declares a projection rule (constant, previous_period, sum_rows, percent_of_row) and each cell can expose projected and actual values. Manual overrides are immutable and auditable. Includes a standalone CLI for seeding, listing rows, and showing computed matrices. Ships with a realistic Chilean household example and YAML import/export for sheet specifications. **Cash-flow projection engine**—useful as a calculation layer, not a full FP&A platform .

- **[au-fpa-pack / openfpa](https://pypi.org/project/au-fpa-pack/)**  
  Australian extension of openfpa by Guiderail, providing 30 June financial years, Xero AU account mapping, GST/BAS cash timing, and payroll on-cost assumptions. Builds monthly, weekly, and daily cash forecasts and a management briefing from company records. Every assumption is declared in a readable file, and the funding decision remains with a human. Includes 17 skills covering Australian rules, onboarding, monthly close, cash runway, board briefing, and CFO judgment. **Australia-specific** and forecasting-focused, not a general FP&A suite .

### Additional Strong Open-Source Options

- **OM Core** — Open-source multidimensional modeling engine (Python, updated October 2026); provides the computational foundation for building multi-dimensional financial models but not a complete FP&A application .
- **Dolibarr Budget Support** — Open-source module for Dolibarr ERP adding budget management and forecast views; features budget lines by type, hierarchical grouping, budget vs. actual comparison from paid/pending invoices, and forecast views combining past actuals with editable future periods. **ERP module** rather than a standalone FP&A platform, but practical for organizations already on Dolibarr .
- **AFIS** — Open-source AI-powered financial intelligence framework for SMEs (FastAPI + SQLite); provides ML cash flow forecasting with confidence intervals, burn rate/runway KPIs, and optional AI narrative generation with offline fallback. **SME cash intelligence** rather than full budgeting/planning .

**Frameworks for building custom systems**: No open-source platform provides the complete FP&A lifecycle (driver-based budgeting + multi-scenario forecasting + variance analysis + consolidation + board reporting). **OpenFP&A** is the closest to a working FP&A application with driver modeling and variance commentary. **Konsolidat** fills the consolidation gap for SAP/Dynamics environments. **opencashflow** and **KDAF** provide calculation and evidence frameworks for custom builds. A complete FP&A system would require assembling these components with custom development for approval workflows, multi-entity consolidation, and reporting—a substantial engineering effort with no ready-made integrated starting point.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- FP&A platforms handling financial forecasts and budgets must comply with applicable accounting standards, internal controls, and data governance policies; audit trails and version control are critical for financial planning integrity.
- **Open-source FP&A remains fragmented and incomplete**—OpenFP&A provides a working budgeting/forecasting tool, Konsolidat addresses consolidation, and opencashflow/KDAF provide calculation frameworks. None match the full capability of Anaplan, OneStream, or Planful for enterprise FP&A. An independent review explicitly notes that open-source Planning & EPM tools "usually cover parts of the job, not a complete EPM suite" and that calculation models, approval workflows, and reporting must be built or integrated separately .
- Verify license terms for commercial use; OpenFP&A uses MIT , Konsolidat uses MIT , KDAF uses MIT , and au-fpa-pack is MIT .

---

**Made for FP&A analysts, finance business partners, controllers, and strategic finance leaders.**  
Let's make financial planning and analysis more open, but with realistic expectations about what open-source can deliver today.
