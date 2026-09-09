# Products Sales Insights: Regional Performance & Profitability Analysis

A Power BI dashboard analyzing product sales, net profit, and profitability across regions, market segments, and product categories.

---

## 📋 Overview

This dashboard provides a comprehensive view of sales performance, covering:
- Total sales per region
- Net profit per region
- Profit per product category (Furniture, Office Supplies, Technology)
- Sales per market segment (Consumer, Corporate, Home Office)
- Profit per segment

Interactive slicers allow filtering by **Market, Region, Segment, Sub-Category, and Category**.

---

## 🔍 Key Insights

### 1. Consumer segment drives the business
Consumer segment leads with **~6.5M in total sales** and **~3.1M in profit** — significantly ahead of Corporate (~3.8M sales / ~1.8M profit) and Home Office (~2.3M sales / ~1.1M profit). The Consumer segment should remain the primary focus for growth initiatives.

### 2. Western regions dominate net profit
The horizontal bar chart shows **Western Asia** and **Southern Asia** generating the highest net profits (~800K+), while **Canada** trails at the bottom with the lowest net profit among major regions.

### 3. Technology is the most profitable category
Technology leads category profit with **~2.26M**, followed by Office Supplies (~1.83M) and Furniture (~1.96M). Notably, Furniture shows strong sales volume but relatively lower profit conversion — a potential margin optimization opportunity.

### 4. Strong regional sales concentration
Peak regional sales approach **~1.8M in Western markets**, with most regions clustering between 500K–1.2M. A small set of high-performing regions contributes disproportionately to total revenue.

### 5. Segment profit mirrors sales distribution
Profit per segment follows the same ranking as sales (Consumer > Corporate > Home Office), indicating consistent profit margins across segments rather than margin-driven differences.

---

## 📊 Data Summary

| Metric | Consumer | Corporate | Home Office |
|---|---|---|---|
| Total Sales | ~6,507,949 | ~3,824,697 | ~2,309,854 |
| Profit | ~3,094,952 | ~1,839,658 | ~1,110,974 |

| Category | Profit |
|---|---|
| Technology | ~2,256,733 |
| Furniture | ~1,964,434 |
| Office Supplies | ~1,827,296 |

---

## 🎨 Design Recommendations

### Typography & Consistency
- Standardize chart titles to Title Case — current dashboard mixes styles ("Net profit made per region" vs "Profit made per segement").
- Fix typos: "segement" → "segment" (appears in two chart titles).

### Chart Type Improvements
- **"Profit made per category" pie chart:** values overlap and pie slices are hard to compare — replace with a **bar chart**.
- **"Profit made per segment" donut chart:** consider a bar chart or KPI cards for cleaner comparison.
- **"Total sales per region" column chart:** x-axis labels are rotated and crowded — switch to a **horizontal bar chart** for readability.

### Visual Hierarchy & Layout
- Add **KPI cards** at the top: Total Sales, Total Profit, Profit Margin %, Top Region.
- Remove the visible Excel gridlines/cell references around the dashboard canvas for a polished embedded look.
- Give the "Total sales per region" chart more height so labels don't overlap.

### Color Usage
- Avoid using green uniformly across all charts — assign **meaningful colors per category/segment** consistently (e.g., Consumer = blue, Corporate = orange, Home Office = green across every chart).
- Use a single accent color for profit/sales emphasis rather than green everywhere.

### Data Labels & Formatting
- Format large numbers: 6,507,949.418 → **6.5M** or **$6.5M** for readability.
- Add data labels to the regional profit chart bars.
- Add a currency symbol ($) to all sales/profit axes.

### Interactivity
- Add **tooltips** with margin % and rank on hover.
- Enable **drill-through** from region → sub-category for deeper analysis.
- Consider a **map visual** given the regional focus — a filled map would outperform the bar charts for geographic storytelling.

---

*Dashboard: Products Sales Insights | Last updated: September 2026*
