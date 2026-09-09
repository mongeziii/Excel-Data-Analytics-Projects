# Geo Restaurant Insights: Location, Capacity & Customer Engagement Analysis

A Power BI dashboard analyzing restaurant distribution, reservations, chef experience, and social media reach across geographic locations (Downtown, Rural, Suburban).

---

## 📋 Overview

This dashboard provides a geographic breakdown of restaurant performance, covering:
- Restaurant count per location
- Parking availability
- Weekend & weekday reservation volumes
- Average chef experience
- Social media followers per location

Interactive slicers allow filtering by **Cuisine, Location, Rating, Ambience Score, and Service Quality**.

---

## 🔍 Key Insights

### 1. Downtown dominates demand
Downtown has the most restaurants (2,821), the highest weekend reservations (111,488), and the highest weekday reservations (109,517) — clear evidence of urban dining demand.

### 2. Parking availability is nearly balanced
4,189 restaurants offer parking vs. 4,179 without — a 50/50 split. Parking isn't a differentiator yet, but could be a competitive opportunity in high-traffic areas like Downtown.

### 3. Weekend vs. Weekday gap reveals location behavior
- **Downtown:** nearly identical weekday/weekend volume (~110K) — consistent daily traffic.
- **Rural:** 53,520 weekend vs. 54,137 weekday — stable, suggesting a loyal, routine customer base.
- **Suburban:** 81,779 weekend vs. 80,987 weekday — also balanced.

### 4. Followers are heavily concentrated in Downtown
Downtown holds ~14.7M followers vs. ~7.7M Rural and ~7.8M Suburban — roughly **double the audience reach**, likely due to higher foot traffic and social media visibility.

### 5. Chef experience is remarkably consistent
Average experience is ~10 years across all locations (9.99–10.16). Talent quality isn't a differentiator — location and reach are the real performance drivers.

---

## 🎨 Design Recommendations

### Typography & Consistency
- Use a single title style (Title Case recommended) — current dashboard mixes lowercase and uppercase.
- Fix typos: "number of weekend resavations" → "number of weekend reservations".

### Chart Type Improvements
- Replace the **3D pie chart** for chef experience with a bar chart — 3D distorts proportions and reduces readability.
- Replace the follower pie chart with a **donut chart** or **horizontal bar chart** for easier comparison.
- Convert 3D column charts to **flat 2D bars** for cleaner, more accurate visuals.

### Visual Hierarchy & Layout
- Group all "per location" charts together in one row; position parking/followers as secondary KPIs.
- Add **KPI cards** at the top: Total Restaurants, Total Reservations, Avg Chef Experience, Total Followers.
- Collapse the right-side slicer panel to an icon to give charts more screen space.

### Color Usage
- Use **color to encode meaning**: assign one consistent color per location across all charts (e.g., Downtown = blue, Rural = green, Suburban = orange).
- Keep green as the brand accent, not the primary data color.

### Data Labels & Formatting
- Round long decimals (9.985637943 → 9.99 years).
- Add total labels on pie charts (e.g., "Total Followers: 30M").
- Remove placeholder text like "Horizontal (Value) Axis Title".

### Interactivity
- Add **tooltips** with % of total on hover.
- Consider a **bubble map** visual to reinforce the geographic story — a fitting addition given the "geo" theme.

---

## 📊 Data Summary

| Metric | Downtown | Rural | Suburban |
|---|---|---|---|
| Number of Restaurants | 2,821 | 2,762 | 2,786 |
| Weekend Reservations | 111,488 | 53,520 | 81,779 |
| Weekday Reservations | 109,517 | 54,137 | 80,987 |
| Avg Chef Experience (yrs) | 10.16 | 10.01 | 9.99 |
| Followers | ~14.7M | ~7.7M | ~7.8M |
| Parking: Yes / No (total) | — | 4,189 / 4,179 | — |

---

*Dashboard: Geo Restaurant Insights | Last updated: September 2026*
