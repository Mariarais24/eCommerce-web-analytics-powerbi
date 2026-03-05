# 🛒 E-Commerce Web Analytics Dashboard

**Identifying where slow pages are killing conversions in an e-commerce store.**

---

## 🔗 [View Live Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMDhkZWU3NjgtZmFlZi00NWU0LWFmMjItOGU2YmM5NDU4YWZkIiwidCI6IjNiNWIwMDgyLTczNmQtNGIwNi1hYjU1LWUyYzQ0ZGI3YWIzMSIsImMiOjl9)

---

## 🛠 Tech Stack

- 📊 Power BI Desktop
- 🧠 DAX (custom KPI measures)
- 📂 Power Query
- 📝 Data Modeling (3-table relational schema)

---

## 📂 Data Source

Simulated e-commerce dataset — **3 months of data (July – September 2025)**, structured across three tables:
- **Sessions** — session-level behavior (device, source, duration, bounce)
- **Page Performance** — page-level load times, exits, and add-to-cart events
- **Sales Activity** — completed orders and transaction values

---

## 📊 Dashboard

> 🎥 *GIF walkthrough — coming soon*

| Executive Overview | Session-Level Analysis |
|---|---|
| ![Executive Overview](https://raw.githubusercontent.com/Mariarais24/eCommerce-web-analytics-powerbi/main/executive-overview.png) | ![Sessions](https://raw.githubusercontent.com/Mariarais24/eCommerce-web-analytics-powerbi/main/sessions.png) |

| Page-Level Performance | Checkout & Conversion |
|---|---|
| ![Page Performance](https://raw.githubusercontent.com/Mariarais24/eCommerce-web-analytics-powerbi/main/page-performance.png) | ![Conversion](https://raw.githubusercontent.com/Mariarais24/eCommerce-web-analytics-powerbi/main/conversion.png) |

--

## 💡 Dashboard Breakdown

**Business Problem**
The store had steady traffic but weak conversions. The question was: is page speed the cause — and if so, where exactly in the journey?

**Goal**
Diagnose whether performance issues are affecting user behavior and revenue, and pinpoint which pages need fixing first.

**Key Visuals**
- **Executive Overview** — KPI snapshot (bounce rate, conversion, abandonment) + purchase funnel drop-off
- **Session Analysis** — slow session distribution by device; bounce risk by traffic source
- **Page Performance** — load time vs exit rate per page; bubble chart mapping speed to abandonment risk
- **Checkout & Conversion** — conversion trend over time; lowest-converting pages; where users drop off most

**Business Impact & Insights**
- 🔴 Product page loads at **18.5s** — the slowest page and a major exit point
- 📱 **48.57% of slow sessions** come from mobile — biggest experience gap
- 🛒 Checkout abandonment at **37.50%**, directly tied to a 13.2s load time
- 💰 Slower sessions consistently convert less — performance is a revenue issue, not just a UX one

---

## ✅ Recommendations

| # | Action |
|---|---|
| 1 | Optimize **Product & Checkout pages** first — highest load times, highest exit rates |
| 2 | Prioritize **mobile performance** — nearly half of slow sessions are on mobile |
| 3 | Track **Slow Session Rate** weekly as an operational KPI |
| 4 | Avoid driving paid traffic to slow pages — it's wasted ad spend |
