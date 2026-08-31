# Power BI Report & Analytics Dashboard

## 📌 Overview
This repository contains the Power BI project file (`.pbix`) containing visual analytics, data models, and static icon assets for reporting.

## 📁 Repository Structure
* `[Content_Types].xml` - File structure definitions.
* `DataModelSchema` - Underlying Power Query / DAX data model schema.
* `Report/Layout` - Visual layout definitions, pages, and visual configurations.
* `Report/StaticResources/` - Embedded UI icons and custom branding elements:
  * `icons8-bill.png`
  * `icons8-business-analytics.png`
  * `icons8-financial-analytics.png`
  * `icons8-popular-man.png`
  * `icons8-total-sales.png`
  * `icons8-transaction.png`
* `Report/StaticResources/SharedResources/BaseThemes/` - Custom report JSON theme configuration (`CY26SU05.json`).

## 🛠️ Requirements & Setup
1. **Power BI Desktop**: Install the latest version of [Microsoft Power BI Desktop](https://powerbi.microsoft.com/).
2. **Opening the file**: Do not open the raw contents in a text editor. Download the source file and rename the extension to `.pbix` if necessary, then open directly via Power BI Desktop.
3. **Data Refresh**: Ensure your data sources are accessible and credentials are configured under `Transform Data > Data source settings`.

## 📊 Key Metrics Tracked
* Total Sales & Revenue Analytics
* Transactional Logs & History
* Customer / Popular User Demographics
* Financial Forecasts & Analytics Performance

---
*Note: If committing changes via Git, consider using **Power BI Project format (`.pbip`)** instead of binary `.pbix` files to prevent merge conflicts and track human-readable code changes.*
