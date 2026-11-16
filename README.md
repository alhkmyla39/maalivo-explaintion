# Maalivo

**Bilingual business intelligence prototype** · In development

Maalivo helps retail teams turn sales reports into dashboard figures. The project covers report imports, validation, and review in Arabic and English.

## How it works

1. Import a spreadsheet or a delimited sales report into a company workspace.
2. Review the detected columns and validation results, then publish the report.
3. Explore published sales KPIs and check the source report in report history.

## Engineering focus

The prototype separates the sample-data workspace from the authenticated company workspace. The import flow checks report contents before publication, and workspace reads check membership on the server.

| Area | Technologies |
| --- | --- |
| Backend | Python, FastAPI |
| Local data store | SQLite |
| Interface | HTML, CSS, JavaScript |
