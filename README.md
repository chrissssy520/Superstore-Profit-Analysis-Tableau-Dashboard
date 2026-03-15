# 📊 Superstore Profit Analysis — Tableau Dashboard

An interactive **Profit Analysis Dashboard** built in Tableau, uncovering the hidden profit killers in a US Superstore dataset. The dashboard tells a data story across 6 views — from subcategory losses to geographic performance and discount impact on margins.

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

---

## 📸 Preview

![Superstore Profit Analysis Dashboard](./preview.png)

---

## 💡 Dashboard Story

Every chart has a headline — because data should tell a story, not just show numbers.

| Chart | Insight |
|-------|---------|
| 📉 Bar Chart | **"Tables and Bookcases Are Killing Our Profit"** — negative profit subcategories exposed |
| 🗺️ Map | **"Profit By State"** — geographic profit/loss breakdown across the US |
| 📈 Line Chart | **"Sales Grows But Profit Stays Flat"** — revenue up, margin stagnant |
| ⚫ Scatter Plot | **"Discount Killing Profit"** — high discounts consistently destroy margins |
| 📊 Bar Chart | **"Furniture Sells But Doesn't Profit"** — category-level profitability gap |
| 🚚 Bar Chart | **"Standard Class Dominates Shipping"** — shipping mode volume breakdown |

---

## 📌 Key Metrics

| Metric | Value |
|--------|-------|
| 💰 Total Sales | **$2,326,534** |
| 📈 Total Profit | **$292,297** |
| 🛒 Total Orders | **10,194** |
| 📊 Profit Margin | **12.6%** |

---

## 🔍 Key Insights

- **Tables and Bookcases** are the only subcategories with **negative profit** — dragging down overall margins despite decent sales volume
- **Texas, Ohio, and Illinois** are the biggest loss-making states on the profit map — red flags for regional strategy
- **Sales has been growing** year over year but **profit remains flat** — a sign of margin compression, likely from over-discounting
- **Discounts above 20%** show a clear pattern of profit turning negative — the scatter plot makes this undeniable
- **Furniture** is the #3 category in sales but the **least profitable** — high COGS or aggressive discounting likely the cause
- **Standard Class** accounts for the overwhelming majority of shipments — potential cost optimization opportunity in other shipping modes

---

## 🛠️ Tools Used

- **Tableau Desktop** — Dashboard design, calculated fields, chart building
- **Mapbox / OpenStreetMap** — Geographic profit map
- **Superstore Dataset** — Sample dataset (retail orders across US states, 2023–2027)

---

## 📁 Project Structure

```
📦 Superstore-Profit-Analysis
 ┣ 📄 Superstore_Profit_Analysis.twbx   # Tableau packaged workbook
 ┣ 📄 README.md
 ┗ 🖼️ preview.png                        # Dashboard screenshot
```

---

## 🚀 How to Open

1. Download `Superstore_Profit_Analysis.twbx`
2. Open with **Tableau Desktop** or **Tableau Public** (free)
3. All data is embedded — no external connection needed
4. Use filters to explore profit by category, region, or time period

---

## 📐 Dashboard Design Decisions

- **Green = Profit, Red = Loss** color scheme used consistently across all charts for instant readability
- Chart titles written as **insight statements** not just labels — forces the viewer to think about the data
- KPI cards placed top-right for immediate executive summary on open
- Scatter plot used intentionally to show **correlation** between discount rate and profit loss — not just summary stats

---

## 👤 Author

Built as a portfolio project demonstrating Tableau dashboard design, data storytelling, and profit analysis skills.
