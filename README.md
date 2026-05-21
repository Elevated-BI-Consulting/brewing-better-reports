# brewing-better-reports
Sample files from \#thebeerBIguy to implement in your own Power BI environment.

---

## 📁 What's in this repo

### `brewing-better-reports-demo.pbip`
A Power BI project (PBIP format) built around dummy beverage distributor data. Open this file in Power BI Desktop and hit **Refresh** — it loads all data directly from this repo, no local files required.

**Semantic model tables:**
| Table | Description |
|-------|-------------|
| `Invoice` | Invoice transaction data |
| `Item` | Product dimension with brand and supplier info |
| `Account` | Customer/account dimension |
| `Date` | Full date dimension |
| `Time Period` | Calculation group for time intelligence (WTD, MTD, YTD, TTD and PY variants) |

### `data/`
CSV files that back the semantic model. Loaded at refresh via `Web.Contents()` pointing to the raw GitHub URLs on `main` — no local data files needed.

### `Pop Out Menu Demo - Copy.pbix`
Sample file demonstrating a custom pop-out filter menu UI pattern in Power BI.
Watch the walkthrough video [here](https://www.linkedin.com/posts/austinbristow_powerbi-elevatedreporting-uiux-activity-7273371799344627714-5QYl?utm_source=share&utm_medium=member_desktop&rcm=ACoAAAF7xU0B6zCptSdfrwjP5lAhCfvZtQhX9g8).

### `usp_load_date`
SQL stored procedure for loading the Date dimension table.

---

## 🚀 Getting started

1. Clone or download this repo
2. Open `brewing-better-reports-demo.pbip` in Power BI Desktop
3. Hit **Refresh** — data loads automatically from GitHub
4. No credentials or local data files needed
