# 📊 Jobs Dashboard — Power BI

A multi-page interactive Power BI report analyzing data job market trends, salaries, and job characteristics across various roles and countries.

---

## 📁 Dashboard Pages

The report contains the following pages (visible in the tab bar):

| Page | Description |
|------|-------------|
| Bar | Horizontal bar chart view of job counts |
| Line and Area Chart | Trend lines for job postings over time |
| Pie Chart | Proportional breakdowns |
| Tables | Raw tabular data |
| Matrix | Cross-tabulated data |
| Cards | KPI summary cards |
| Gauge Cards | Visual gauges for key metrics |
| Slicers | Filter controls |
| **Job Dashboard** | Main overview dashboard (default view) |
| **Drill Through** | Detailed role-specific deep-dive |
| Page 1 | Additional views |

---

## 🏠 Job Dashboard (Main Page)

The primary dashboard provides a high-level overview of the data job market.

### Key KPIs
- **478.895K** total job listings
- **3/5 stars** median salary rating
- **$113.25K** median yearly salary
- **$47.62** median hourly salary average

### Visualizations

**Count of Jobs by Month (Line Chart)**
Tracks monthly job posting volume from January to November 2024, showing an overall declining trend from ~53K–60K in early 2024 to ~14K–31K by late 2024. A dashed trendline highlights the general downward trajectory.

**What is the Highest Paying Job in Data? (Bar Chart)**
Horizontal bar chart ranking job titles by posting count:
1. Data Engineer
2. Data Analyst
3. Data Scientist
4. Senior Data Engineer
5. Business Analyst
6. Software Engineer
7. Senior Data Scientist

**Median Hourly vs. Median Yearly Salary (Scatter Plot)**
Plots each job role as a bubble showing the relationship between hourly and yearly compensation. Senior and specialized roles (e.g., Senior Data Scientist, Machine Learning Engineer, Software Engineer) cluster in the high-pay quadrant.

**Summary Table**

| Job Title | Count of Jobs | Median Yearly Salary | Hourly Median Salary |
|---|---|---|---|
| Business Analyst | 28,584K | $95.35K | $43,000 |
| Cloud Engineer | 6,839K | $113.838K | $50,000 |
| Data Analyst | 112,866K | $90K | $32,500 |
| Data Engineer | 128,994K | $126.268K | $59,160 |
| Data Scientist | 97,664K | $125K | $43,035 |
| Machine Learning Engineer | 12,860K | $155K | $60,750 |
| Senior Data Analyst | 15,347K | $107.31K | $39,450 |
| Senior Data Engineer | 30,608K | $146.5K | $58,680 |
| Senior Data Scientist | 21,731K | $155.5K | $49,895 |
| **Total** | **478,895K** | **$113.25K** | **$47.62** |

### Filters
- **job_title_short** slicer (top of page) — filter by specific job role
- **Job Drill Through** button — navigate to the drill-through detail page

---

## 🔍 Drill Through Page — Data Engineer (Example)

Activated by right-clicking a job title in the main dashboard and selecting "Drill Through." The example below shows the **Data Engineer** detailed view.

### Summary Metrics
- **Yearly Salary Range:** $15K – $640K (median $126.27K)
- **Hourly Salary Range:** $9 – $221

### Visualizations

**Work from Home vs. Offline Jobs (Donut Chart)**
- Remote/WFH: **14.74%**
- On-site: **85.26%**

**Degree vs. No-Degree (Donut Chart)**
- Degree required: **47.41%**
- No degree required: **52.59%**

**Health Insurance or Not (Donut Chart)**
- Includes health insurance: **10.25%**
- No health insurance: **89.75%**

**Count of Job Listings by Country (World Map)**
Bubble map showing geographic distribution of Data Engineer roles, with the largest concentrations in North America and Europe.

**Count of Jobs by Source Platform (Bar Chart)**
Top sources for job listings:
1. via LinkedIn (highest)
2. via Indeed
3. via BeBee
4. LinkedIn (direct)
5. via ZipRecruiter
6. via Jooble
7. BeBee, via Dice, via GrabJobs, Indeed, via Recruit...

**Job Role Types (Treemap)**
- **Full-time: 88.73%** (dominant)
- Contract: ~8.65%
- Other full-time variants: ~2.62%

---

## 🛠️ Technical Details

- **Tool:** Microsoft Power BI Desktop
- **Data:** Aggregated data job postings (2024)
- **Features Used:**
  - Drill-through navigation between pages
  - Cross-filtering between visuals
  - Donut/pie charts, scatter plots, line charts, bar charts, maps, treemaps, tables
  - KPI cards and gauge visuals
  - Slicers for interactive filtering

---

## 🚀 How to Use

1. Open the `.pbix` file in **Power BI Desktop**.
2. Start on the **Job Dashboard** tab for the high-level overview.
3. Use the **job_title_short** slicer at the top to filter all visuals by job role.
4. Right-click any job title in the table and select **Drill Through → job drill through** to explore role-specific details.
5. Use the **back arrow** (←) on the drill-through page to return to the main dashboard.

---

## 📌 Key Insights

- **Data Engineer** has the highest number of job postings (~129K) and a strong median yearly salary of ~$126K.
- **Machine Learning Engineer** and **Senior Data Scientist** command the highest median yearly salaries (~$155K+).
- Job postings trended **downward** from January to November 2024.
- The **majority of data jobs (85%)** are on-site, with only ~15% offering remote/WFH options.
- **LinkedIn** is the dominant platform for data job postings.
- Most Data Engineer roles are **full-time (88.7%)** and do **not require a specific degree (52.6%)**.

<img width="1174" height="741" alt="{37D785F1-562D-4CCB-92F2-D0316E52294B}" src="https://github.com/user-attachments/assets/73504165-6a41-4fb1-8376-7b26c2bec046" />


<img width="1165" height="723" alt="{E63154B1-D51C-406C-8B75-6355251AC8F0}" src="https://github.com/user-attachments/assets/a4be4aa0-b9b0-4a78-9b44-683e2c6d37df" />


