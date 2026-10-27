# Awesome Financial Planning & Analysis (FP&A) Tools & Software [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated directory of top Financial Planning & Analysis (FP&A) SaaS software, Enterprise Performance Management (CPM/EPM) platforms, and open-source GitHub projects for corporate budgeting, rolling forecasts, driver-based financial modeling, variance analysis, and board reporting.

**Last updated: October 2026**

---

## Table of Contents

- [Overview & What is FP&A?](#overview--what-is-fpa)
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS & Enterprise FP&A Platforms](#saas--enterprise-fpa-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [Key Features of Modern FP&A Software](#key-features-of-modern-fpa-software)
- [How to Contribute](#how-to-contribute)
- [Disclaimer & License](#disclaimer--license)

---

## Overview & What is FP&A?

Financial Planning & Analysis (FP&A) solutions empower CFOs, finance business partners, controllers, and FP&A analysts to forecast operational revenues, model cost drivers, track budget-vs-actual variances, run scenario simulations, and deliver executive board packs. 

While enterprise finance historically relied on fragile spreadsheet sprawl in Microsoft Excel, modern cloud FP&A and Corporate Performance Management (CPM/EPM) software integrate directly with ERP systems (NetSuite, SAP, Workday, QuickBooks) and CRM databases (Salesforce, HubSpot) to enable governed, auditable, and automated collaborative financial workflows.

---

## Sector Overview & Market Dynamics

The global Financial Planning and Analysis (FP&A) and Corporate Performance Management (CPM) software market is estimated at **$4.8 billion in 2025 and projected to reach over $5.5–$6.0+ billion by 2026**, expanding at a compound annual growth rate (CAGR) of **~9–10%**.

The sector exhibits a **hybrid market concentration structure**:
- **Highly concentrated at the enterprise tier:** Dominated by mega-cap ERP suites and consolidated EPM giants (Workday, Anaplan, OneStream, Oracle EPM, SAP) who capture over two-thirds of total enterprise contract value through large multi-year enterprise commitments.
- **Moderately fragmented across the mid-market and SMB space:** A vibrant ecosystem of specialized, spreadsheet-native, and cloud-first platforms (Vena, Datarails, Cube, Planful, Mosaic Tech) fiercely compete on native Excel sync, fast deployment times, and AI-assisted narrative variance intelligence.

---

## SaaS & Enterprise FP&A Platforms

The following SaaS and hosted platforms represent the leading commercial FP&A and CPM solutions, ranked in descending order by company valuation/revenue scale:

| Platform | Starting Price | Free Tier / Free Trial Limits | Company Scale (Valuation / Revenue) | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Workday Financial Planning](https://www.workday.com/)** | ~$25,000–$36,000/year (pilot/entry tier; mid-market ~$80k–$300k/yr) | 30-day free trial (guided evaluation of core planning, dashboards & financial reporting) | ~$52B Market Cap / ~$9.55B Annual Revenue | Enterprise-grade cloud planning suite (formerly Adaptive Planning) integrating budgeting, forecasting, and workforce modeling with core ERP/HCM actuals. |
| **[Anaplan](https://www.anaplan.com/)** | ~$30,000–$50,000/year (departmental entry; enterprise contracts $150k–$1M+/yr) | No commercial free tier; 90-day learning sandbox available via Anaplan Talent Builder program | $10.7B Acquisition Valuation (Thoma Bravo) / ~$600M+ ARR | Connected planning engine featuring hyperblock in-memory multidimensional modeling, complex driver scenario analysis, and cross-functional operational planning. |
| **[OneStream](https://www.onestream.com/)** | ~$100,000+/year (annual enterprise subscription + implementation) | No free tier or trial; custom POC and sales-led live demos only | $6.4B Buyout Valuation (Hg Capital / General Atlantic) / ~$600M ARR | Unified corporate performance management platform consolidating complex financial close, multi-entity group consolidation, budgeting, and predictive analytics. |
| **[Board](https://www.board.com/)** | ~$35,000–$50,000/year (custom enterprise quote based on seats & data volume) | No open self-serve trial; tailored guided proof-of-concept (POC) on request | ~$100M+ ARR (backed by Nordic Capital) | Unified decision-making platform integrating business intelligence (BI), simulation modeling, financial budgeting, and corporate performance management. |
| **[Vena Solutions](https://www.venasolutions.com/)** | ~$27,000–$50,000/year (approx. $450/user/month; first-year TCO ~$75k–$150k+) | No free tier or trial; guided interactive product tours only | $100M+ ARR ("Centaur" status; backed by Vista Equity Partners & JMI) | Excel-native CPM and FP&A platform combining an authentic Microsoft Excel interface with an OLAP database, role-based workflows, and automated audit trails. |
| **[Planful](https://planful.com/)** | ~$24,000/year (~$2,000/month baseline tier; scaling by user volume and modules) | No free tier or trial; customized sales demonstration and scoping sessions only | ~$80M–$100M ARR (backed by Vector Capital) | Comprehensive financial planning and consolidation engine providing automated close management, driver-based forecasting, and board-ready reporting. |
| **[Prophix](https://www.prophix.com/)** | ~$50,000–$65,000/year (typically 3-year subscription; first-year TCO ~$120k–$250k) | No free tier or trial; personalized 1-on-1 enterprise demo only | ~$75M–$100M ARR (backed by Hg Capital) | Next-generation Corporate Performance Management (Prophix One) providing budgeting, cash flow forecasting, multi-currency consolidation, and account reconciliation. |
| **[Datarails](https://www.datarails.com/)** | ~$12,000–$24,000/year (FP&A Professional entry tier; scaling to $60k+/yr) | No self-serve trial or free tier; custom guided product demo upon request | ~$40M+ ARR / $400M+ Valuation (Series B) | Financial planning platform that integrates on top of existing Excel spreadsheets, automating data consolidation, version control, and variance reporting. |
| **[Cube](https://www.cubesoftware.com/)** | ~$12,500–$22,000/year (Bronze/Silver tier minimum contract) | No self-serve free trial; custom consultation and guided sandbox demo only | ~$25M+ ARR / $150M+ Valuation (backed by Battery Ventures) | Spreadsheet-native FP&A software that seamlessly bidirectionally connects Excel and Google Sheets to ERP, CRM, and HR systems for collaborative modeling. |
| **[Mosaic Tech](https://www.mosaic.tech/)** | ~$10,000–$15,000/year (Standard starter tier; scaling based on headcount and integrations) | No self-serve free trial or free tier; interactive live walkthrough with finance engineers | ~$15M–$20M ARR / $250M+ Valuation (backed by Founders Fund & General Catalyst) | Strategic finance and real-time analytics platform featuring automated SaaS metrics, predictive cash forecasting, and AI assistant (Chello) for tech finance teams. |

---

## Open-Source GitHub Projects

Open-source financial planning & analysis tools provide code-first flexibility, local data governance, and customizable analytics pipelines. The repositories below are sorted in descending order by GitHub stargazers count:

| Repository | GitHub Stars | Primary Stack | Key Capabilities & Architecture |
| :--- | :--- | :--- | :--- |
| **[Dolibarr ERP (Budget Module)](https://github.com/Dolibarr/dolibarr)** | [![Stars](https://img.shields.io/github/stars/Dolibarr/dolibarr?style=social&color=white)](https://github.com/Dolibarr/dolibarr/stargazers) | PHP / MariaDB | Comprehensive open-source ERP/CRM suite featuring native budgeting and financial forecasting modules, hierarchical account grouping, and real-time budget-vs-actual variance tracking from invoices. |
| **[jimlindstrom/FinModeling](https://github.com/jimlindstrom/FinModeling)** | [![Stars](https://img.shields.io/github/stars/jimlindstrom/FinModeling?style=social&color=white)](https://github.com/jimlindstrom/FinModeling/stargazers) | Python / Jupyter | Modular financial modeling toolkit for corporate finance analysts, featuring cash flow models, capital budgeting evaluations, and automated multi-scenario forecasting routines. |
| **[willpowerju-lgtm/3-statement-ultra-for-finance](https://github.com/willpowerju-lgtm/3-statement-ultra-for-finance)** | [![Stars](https://img.shields.io/github/stars/willpowerju-lgtm/3-statement-ultra-for-finance?style=social&color=white)](https://github.com/willpowerju-lgtm/3-statement-ultra-for-finance/stargazers) | Excel / Claude Skill | Institutional-grade automated 3-statement financial model builder (P&L, Balance Sheet, Cash Flow) with dynamic formula linkages, zero hardcoded forecast cells, and a 9-step QC integrity suite. |
| **[skapebolt/SquirrelPlan](https://github.com/skapebolt/SquirrelPlan)** | [![Stars](https://img.shields.io/github/stars/skapebolt/SquirrelPlan?style=social&color=white)](https://github.com/skapebolt/SquirrelPlan/stargazers) | TypeScript / React | Privacy-first client-side web application for multi-year cash flow forecasting, asset/liability modeling, and interactive scenario simulations with dynamic visual runaways. |
| **[leonarduschen/pyfinmod](https://github.com/leonarduschen/pyfinmod)** | [![Stars](https://img.shields.io/github/stars/leonarduschen/pyfinmod?style=social&color=white)](https://github.com/leonarduschen/pyfinmod/stargazers) | Python / Pandas | Python financial modeling library providing programmatic balance sheet, income statement, and cash flow statement reconciliations, IRR/NPV, and enterprise valuation metrics. |
| **[jeremylongshore/excel-analyst-pro-skill-md](https://github.com/jeremylongshore/excel-analyst-pro-skill-md)** | [![Stars](https://img.shields.io/github/stars/jeremylongshore/excel-analyst-pro-skill-md?style=social&color=white)](https://github.com/jeremylongshore/excel-analyst-pro-skill-md/stargazers) | Markdown / Skill | Professional financial modeling skill suite for automated variance reporting, DCF projections, financial ratio diagnostics, and automated spreadsheet generation using natural language. |
| **[Emanuel-Allely/Fisy](https://github.com/Emanuel-Allely/Fisy)** | [![Stars](https://img.shields.io/github/stars/Emanuel-Allely/Fisy?style=social&color=white)](https://github.com/Emanuel-Allely/Fisy/stargazers) | Excel / Financial Model | Battle-tested provisional financial planning framework and open model allowing startups and mid-market ventures to construct multi-year cash flow forecasts and P&L projections. |
| **[cloudcell/om-core](https://github.com/cloudcell/om-core)** | [![Stars](https://img.shields.io/github/stars/cloudcell/om-core?style=social&color=white)](https://github.com/cloudcell/om-core/stargazers) | Python | Open-source multi-dimensional modeling engine (dimensions, cubes, groups, and calculation rules) that serves as a high-performance computation engine for custom OLAP and FP&A tools. |
| **[JeffBrines/openfpa](https://github.com/JeffBrines/openfpa)** | [![Stars](https://img.shields.io/github/stars/JeffBrines/openfpa?style=social&color=white)](https://github.com/JeffBrines/openfpa/stargazers) | Python | Agent-native Financial Planning & Analysis workbench and memory kernel designed for autonomous AI agents to construct financial models, run close routines, and model cash runways. |
| **[Hassan0397/Financial-Planning-and-Analysis-AI-Agent](https://github.com/Hassan0397/Financial-Planning-and-Analysis-AI-Agent)** | [![Stars](https://img.shields.io/github/stars/Hassan0397/Financial-Planning-and-Analysis-AI-Agent?style=social&color=white)](https://github.com/Hassan0397/Financial-Planning-and-Analysis-AI-Agent/stargazers) | Python / Streamlit | Modular enterprise FP&A AI agent automating data pipeline cleansing, multi-dimensional statement analysis, revenue/cost forecasting, what-if simulations, and executive board decks. |
| **[redmoon1945/gbp](https://github.com/redmoon1945/gbp)** | [![Stars](https://img.shields.io/github/stars/redmoon1945/gbp?style=social&color=white)](https://github.com/redmoon1945/gbp/stargazers) | Python / GUI | Graphical Budget Planner (GBP) desktop application facilitating corporate budget forecasting, line-item variance tracking, and interactive actual-vs-target variance graphs. |
| **[afild/AFIS](https://github.com/afild/AFIS)** | [![Stars](https://img.shields.io/github/stars/afild/AFIS?style=social&color=white)](https://github.com/afild/AFIS/stargazers) | FastAPI / SQLite / ML | Open-source AI-powered financial intelligence framework for SMEs featuring automated data ingestion, ML cash flow forecasting with confidence intervals, and runway analytics. |
| **[slunyakin/FPA-KDAF](https://github.com/slunyakin/FPA-KDAF)** | [![Stars](https://img.shields.io/github/stars/slunyakin/FPA-KDAF?style=social&color=white)](https://github.com/slunyakin/FPA-KDAF/stargazers) | Python / MCP Protocol | Knowledge-Driven Analytics Framework for finance-focused analytical systems combining semantic context with governed numerical analytics and verifiable evidence packets. |
| **[himanshusharma75035-sudo/budgeting-and-forecasting-tool](https://github.com/himanshusharma75035-sudo/budgeting-and-forecasting-tool)** | [![Stars](https://img.shields.io/github/stars/himanshusharma75035-sudo/budgeting-and-forecasting-tool?style=social&color=white)](https://github.com/himanshusharma75035-sudo/budgeting-and-forecasting-tool/stargazers) | FastAPI / React 19 / SQLite | Local-first open-source FP&A app (OpenFP&A) featuring driver-based modeling, dependency graph formula engine, autonomous statistical forecasting, and automated board pack Excel exports. |
| **[grynn-in/konsol-cli](https://github.com/grynn-in/konsol-cli)** | [![Stars](https://img.shields.io/github/stars/grynn-in/konsol-cli?style=social&color=white)](https://github.com/grynn-in/konsol-cli/stargazers) | Python / Frappe / ClickHouse | Open-source CLI and MCP client for [Konsolidat](https://konsolidat.com/), an Excel-native EPM and financial consolidation system running dbt and ClickHouse with GL audit traceability. |
| **[Reckonry/OpenCashFlow](https://github.com/Reckonry/OpenCashFlow)** | [![Stars](https://img.shields.io/github/stars/Reckonry/OpenCashFlow?style=social&color=white)](https://github.com/Reckonry/OpenCashFlow/stargazers) | .NET / JavaScript | Open-source modular cash flow and receipts management system released under AGPL for non-profit and enterprise operational finance planning. |
| **[ryanduguid/au-fpa-pack](https://github.com/ryanduguid/au-fpa-pack)** | [![Stars](https://img.shields.io/github/stars/ryanduguid/au-fpa-pack?style=social&color=white)](https://github.com/ryanduguid/au-fpa-pack/stargazers) | Python / openfpa | Australian extension of OpenFPA providing 30 June fiscal year modeling, Xero AU account mapping, GST/BAS cash timing rules, and automated CFO board briefing skills. |

---

## Key Features of Modern FP&A Software

1. **Driver-Based Financial Modeling:** Move away from hardcoded figures to variable drivers (e.g., website visitors $\times$ conversion rate $\times$ ACV = ARR) to forecast P&L, balance sheets, and cash flow dynamically.
2. **Rolling Forecasts & Scenario Analysis:** Rapidly toggle between Best Case, Base Case, and Downside recessionary scenarios to assess runway, liquidity, and hiring pace.
3. **Automated Budget vs. Actual (BvA) Variance Analysis:** Directly ingest General Ledger (GL) actuals from your ERP at month-end close and rank variances by absolute value and percentage deviation.
4. **Excel and Google Sheets Bi-directional Sync:** Preserve the speed and flexibility of spreadsheets while maintaining centralized database governance, row-level access control, and complete audit history.
5. **AI-Powered Narrative Variance Commentary:** Automatically transform numerical variances into human-readable board presentation commentary and executive summaries.

---

## How to Contribute

Contributions to this ecosystem list are very welcome!

1. Fork this repository.
2. Create a new branch: `git checkout -b add-fpa-tool`.
3. Add the SaaS platform or open-source GitHub repository following the existing table formatting.
4. Ensure descriptions are objective, verified, and include transparent starting pricing or GitHub star badges.
5. Submit a Pull Request with a clear description of the project.

---

## Disclaimer & License

- This list is community-curated for informational and educational purposes only and does not constitute financial, investment, or legal advice.
- Financial Planning & Analysis systems handling sensitive corporate ledgers, confidential payrolls, and material non-public forecasts must comply with SOC 1 / SOC 2 standards, internal corporate controls, and data governance policies.
- Open-source tools are distributed under their respective licenses (MIT, AGPL, Apache 2.0).

---

**Made with ❤️ for FP&A Analysts, Finance Business Partners, CFOs, and Strategic Finance Leaders.**
