# Awesome-IT-Business-Management-ITBM

# Top IT Business Management (ITBM) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on IT Financial Management, Technology Business Management & Portfolio Governance*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **IT Business Management (ITBM)**. These tools enable CIOs and IT finance teams to manage IT budgets (OPEX/CAPEX), allocate technology costs to business services, govern project portfolios, and align IT investments with strategic outcomes—turning IT from a cost center into a transparent, measurable business partner.

**Examples** include ServiceNow IT Business Management, Planview, Clarity PPM, Apptio, Jira Align, Workfront, Meisterplan, Micro Focus PPM, Changepoint, ServiceNow Strategic Portfolio Management, and Sciforma (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosted IT governance, budget management, and portfolio planning—ideal for organizations building sovereign ITBM infrastructure without per-module or per-seat licensing lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ServiceNow IT Business Management](https://www.servicenow.com/)**  
  Enterprise ITBM suite on the Now Platform covering IT financial management, project portfolio management, demand management, and application portfolio management; integrates with Strategic Portfolio Management for strategy-to-execution alignment and CMDB for service costing.

- **[Planview](https://www.planview.com/)**  
  Comprehensive portfolio and work management platform spanning strategic planning, IT financial management, and resource capacity planning; AdaptiveWork (formerly Clarizen) provides real-time visibility for PMOs and professional services teams.

- **[Clarity PPM](https://www.broadcom.com/)**  
  Broadcom's enterprise PPM platform (formerly CA Clarity) with portfolio planning, IT financial governance, investment tracking, and resource management for large IT and transformation portfolios.

- **[Apptio](https://www.apptio.com/)**  
  Technology Business Management (TBM) platform (IBM company) for IT cost transparency, service costing, and showback/chargeback; provides visibility into technology spend across applications, services, and business units.

- **[Jira Align](https://www.atlassian.com/software/jira/align)**  
  Enterprise agile planning platform connecting strategy to execution across teams, with portfolio-level visibility, lean budgeting, and value stream management for SAFe-aligned organizations.

- **[Workfront](https://www.workfront.com/)**  
  Adobe's work management platform with portfolio management, resource planning, and project governance capabilities; strong for marketing and enterprise teams seeking unified work visibility.

- **[Meisterplan](https://meisterplan.com/)**  
  Lean portfolio management tool focused on resource capacity planning and scenario simulation to balance demand against capacity for IT and transformation portfolios.

- **[Micro Focus PPM](https://www.microfocus.com/)**  
  Enterprise project and portfolio management platform (now OpenText) with demand management, financial planning, and resource governance for IT organizations.

- **[Changepoint](https://www.changepoint.com/)**  
  Professional services automation and PPM platform with portfolio management, resource planning, and financial tracking for IT and consulting organizations.

- **[ServiceNow Strategic Portfolio Management](https://www.servicenow.com/)**  
  Enterprise SPM suite (formerly ITBM) covering demand management, project portfolio management, resource management, financial planning, and innovation management; activated via modular plugins with SPM and SPM Pro editions.

- **[Sciforma](https://www.sciforma.com/)**  
  PPM and work management platform with portfolio prioritization, resource capacity planning, and stage-gate governance for IT and project-driven organizations.

## Open-Source GitHub Projects

- **[KANAP](https://github.com/kanap-hq/kanap)**  
  Open-source IT governance platform (AGPL v3) built for mid-sized companies and multi-entity groups; provides one governed record for **IT budget (OPEX/CAPEX)** with multi-year planning, allocation methods, multi-currency support, chargeback, and analytics dashboards; also covers **application landscape** with interactive architecture maps, **project portfolio management** with scoring, roadmap scheduling, and capacity analysis, and **knowledge management** linked to budgets and applications; includes **Plaid**, a built-in AI agent that operates on the same governed record with permissions and audit trail; self-hostable for free with Docker .

- **[OpenProject](https://github.com/opf/openproject)**  
  Leading open-source project management software (GPL-3.0, ~16k GitHub stars) with **project and portfolio management** capabilities; features portfolio-level Gantt charts, project planning, agile boards (Kanban/Scrum/SAFe), time tracking, cost reporting, and budgeting; trusted by enterprises and public institutions for data sovereignty and transparency; available as free Community Edition (self-hosted) or paid Enterprise editions .

- **[Leantime](https://github.com/Leantime/leantime)**  
  Goal-focused open-source project management system (MIT) designed for non-project managers; includes **goal cascading with OKRs**, a Goal Matrix for effort-vs-impact prioritization, **portfolio dashboards** showing alignment against strategic pillars, and cross-project program views introduced in v3.9.7; community edition is free for unlimited users when self-hosted; covers strategy canvases (Lean, SWOT, Business Model) alongside task execution and timesheets .

- **[Plane](https://github.com/makeplane/plane)**  
  Modern open-source project management platform (AGPL-3.0, ~48k GitHub stars) positioned as a Jira/Linear/Monday alternative; features work items, cycles (sprints), modules, pages, and five layout views including Gantt; while stronger for project execution than strategic IT financial management, it provides **portfolio-level visibility** through cross-project modules and analytics; self-hostable with Docker or Railway one-click deployment .

- **[P-Track](https://github.com/DevEnchantments/ptrack)**  
  Open-source **Project Portfolio Management** platform (React + NestJS + Supabase) designed for teams reporting upward; features full project workspace with milestones, risks, KPIs, and status reports; **monthly reporting cycles** with approval workflows; portfolio Gantt with drag-to-reschedule; KPI module with achievement tracking; and a permission-bounded AI assistant that can never see more than the signed-in user; suitable for IT departments needing structured portfolio reporting without commercial PPM licensing .

### Additional Strong Open-Source Options

- **Grist** — Open-source spreadsheet-database hybrid with relational data and dashboards; can be used for IT budget tracking and cost allocation modeling when full ITBM platforms are overkill.
- **Metabase** — Open-source BI tool (AGPL) for building IT cost dashboards and chargeback reports from budget and CMDB data sources.
- **Odoo (Project + Accounting modules)** — Open-source ERP with project accounting and analytic accounting capabilities; can be configured for basic IT cost allocation and project financial tracking.

**Frameworks for building custom systems**: Combine **KANAP** for integrated IT budget, application landscape, and portfolio governance with AI assistance, **OpenProject** for portfolio-level Gantt planning and cost reporting, **Leantime** for strategy-to-OKR alignment, and **P-Track** for structured portfolio reporting cycles in a fully self-hosted ITBM stack; layer **Metabase** for executive dashboards on IT spend and service costs.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- ITBM platforms handling financial and strategic data must comply with applicable regulations and organizational governance policies; IT cost allocation models should align with finance and accounting standards.
- Self-hosted open-source solutions vary significantly in ITBM depth—KANAP is purpose-built for IT governance with budget and portfolio features, while OpenProject and Plane are stronger for project execution than IT financial management; organizations requiring full TBM/showback/chargeback capabilities may need commercial platforms like Apptio.
- Verify license terms for commercial use; KANAP uses AGPL v3, OpenProject uses GPL-3.0, Leantime uses MIT, Plane uses AGPL-3.0, and P-Track is an independent open-source project .

---

**Made for CIOs, IT finance managers, PMO leaders, and technology business management analysts.**  
Let's make IT business management more open, transparent, and value-driven.
