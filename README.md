<h1 align="center">Maalivo · ماليفو</h1>

<p align="center"><strong>From retail sales reports to a dashboard you can trace back to the source.</strong></p>

<p align="center">
  <img src="https://img.shields.io/badge/Business%20intelligence-5B48A3?style=flat-square" alt="Business intelligence" />
  <img src="https://img.shields.io/badge/Arabic%20%2B%20English-725DAF?style=flat-square" alt="Arabic and English" />
  <img src="https://img.shields.io/badge/Prototype-3F3862?style=flat-square" alt="Prototype" />
</p>

![Maalivo’s English sales dashboard design with net sales and branch comparisons]

*Maalivo’s sales dashboard design in English, shown with illustrative sales figures.*

## What is Maalivo?

Maalivo is a bilingual business intelligence prototype for retail teams. It brings sales report imports, validation, and KPI dashboards into one workspace. A team member can review a report before publishing it, then use filters to explore sales by time period, branch, or product.

| Step | What happens |
| --- | --- |
| Import a report | Upload a spreadsheet or delimited sales file. Maalivo detects the columns it can map. |
| Review and publish | Check validation results, resolve ambiguous fields, and publish the report to the workspace. |
| Explore sales | Read the KPIs, compare branches or products, and check the source report in report history. |

## Tech stack

| Layer | Technologies | Role |
| --- | --- | --- |
| Interface | HTML, CSS, JavaScript | Bilingual dashboards and report import screens. |
| Application and API | Python, FastAPI | Report ingestion, validation, dashboard queries, and workspace access. |
| Local prototype storage | SQLite | Workspace records, reports, and published sales data. |
| Design | Figma | Dashboard and report review concepts for Arabic and English. |

## Engineering focus

The main design challenge is keeping dashboard figures traceable to the reports behind them. Validation happens before publication, and the authenticated workspace checks membership before returning company data.
