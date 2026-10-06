# 🛒 Blinkit Sales Analysis Dashboard | Power BI

An interactive Power BI dashboard that analyzes sales performance for **Blinkit (India's Last Minute App)** across products, outlets, and locations.

---

## 📌 Project Overview

This project turns Blinkit grocery sales data into a single-page dashboard. It helps answer questions like:

- How much are we selling, and what is the average sale value?
- Which item categories bring in the most revenue?
- How do different outlet locations, sizes, and types perform?
- Does fat content (Regular vs. Low Fat) affect sales?
- How have sales changed by outlet establishment year?

---

## 📊 Dashboard Features

### KPI Cards
| KPI | Description |
|-----|-------------|
| **Total Sales** | Sum of all sales |
| **Average Sales** | Average sales per item/transaction |
| **No. of Items** | Total count of items sold |
| **Average Rating** | Average customer rating |

### Visualizations
| Visual | Purpose |
|--------|---------|
| Bar Chart – *Item Type* | Sales by product category |
| Funnel Chart – *Outlet Location* | Sales across Tier 1 / 2 / 3 locations |
| Clustered Bar – *Location × Fat Content* | Fat content split within each location tier |
| Donut Chart – *Fat Content* | Share of sales by fat content |
| Donut Chart – *Outlet Size* | Share of sales by Small / Medium / High outlets |
| Line/Area Chart – *Establishment Year* | Sales trend by outlet establishment year |
| Matrix Table – *Outlet Type* | Total Sales, Items, Avg Sales and Avg Rating by outlet type |

### Interactivity
- **Filter Panel** with dropdown slicers for Outlet Location Type, Outlet Size, and Item Type
- **Dynamic metric switcher** (Field Parameter) that changes the main charts between Total Sales, Average Sales, No. of Items, and Average Rating
- Cross-filtering between all visuals

---

## 🧮 DAX Measures

The dashboard uses these measures on the `BlinkIT Grocery Data` table:

- `Total Sales`
- `Average Sales`
- `No Of Items`
- `Average Rating`

> 💡 Add your exact DAX formulas here, for example:
> ```DAX
> Total Sales = SUM('BlinkIT Grocery Data'[Sales])
> ```

---

## 🗂️ Dataset

- **Table:** `BlinkIT Grocery Data`
- **Key columns:** Item Type, Item Fat Content, Outlet Location Type, Outlet Size, Outlet Type, Outlet Establishment Year, Sales, Rating
- **Source:** *(add the source here, e.g. Kaggle – Blinkit Grocery Dataset)*

---

## 🎨 Design

- Custom theme in Blinkit's brand colours: **yellow (#FFD200)** and **green (#1CA04F / #18B339)**
- 1920 × 1080 canvas, laid out as a sidebar filter panel plus a main analytics area

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **DAX** (measures)
- **Power Query** (data cleaning and transformation)
- **Field Parameters** (dynamic metric selection)

---

---

