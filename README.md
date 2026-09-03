# Power BI Portfolio

This repository showcases Power BI dashboards built for business analytics coursework, demonstrating end-to-end dashboard design: data modeling, DAX measures, geographic visualization, and executive-level reporting.

## Projects

### 1. Geronimo Group — Corporate Travel Expense Analysis
**File:** `Geronimo_Travel_Expenses_Co.pbix`

A six-page executive dashboard analyzing corporate travel spending, built to surface cost-control risks and actionable recommendations for leadership.

**Pages:**
- **Executive Overview** — total spend, trip count, traveling employees, and average spend per trip, with a monthly spend trend line and a geographic spend map
- **Employee View** — per-employee trip counts, spend breakdowns by category, and a ranked view of top spenders by average cost per trip
- **Trip View** — spend and transaction volume by individual business trip, with full transaction-level detail
- **Geography/Location** — spend concentration by city and state on an interactive map
- **Risk Alerts** — custom DAX flags identifying high-spend employees, high-line-item trips, and high-cost cities
- **Recommendations** — key findings translated into concrete action items for stakeholders

**Key findings surfaced by the dashboard:**
- Nashville and St. Louis together account for **$441K** of total travel spend, indicating an opportunity to negotiate corporate rates with hotels and airlines
- Average spend per trip is **$1,145**, but top spenders exceed **$4,000** per trip — a variance that points to a lack of cost control
- **Miscellaneous** expenses make up over 20% of total spend for some employees, with low visibility into what's actually being purchased

**Recommendations delivered:**
- Negotiate corporate rates in high-concentration travel markets
- Set a per-trip spending cap (~$2,500) with a justification requirement for exceptions
- Standardize and expand expense categories to improve visibility into miscellaneous spend

**Skills demonstrated:** DAX measure creation, geographic (map) visualization, multi-page dashboard navigation, KPI card design, anomaly/risk flagging logic, and translating data into business recommendations.

### 2. MSBA Program Competitive Benchmarking
**File:** `Example.pbix`

A two-page competitive analysis dashboard comparing the University of Louisville's MSBA program against peer ACC-conference institutions on program length and credit-hour requirements.

**Pages:**
- **Competitive Overview** — KPI cards for number of schools compared, average program length and credit hours across competitors, and UofL's own length/credit hours for direct comparison; includes a filterable pivot table and slicers for state (KY), adjacent-state status, ACC membership, and completion time
- **ACC Comparison** — clustered column charts comparing credit hours and months-to-completion across institutions

**Skills demonstrated:** competitive/market benchmarking analysis, KPI card design, pivot tables, multi-dimensional slicers, and clustered column charts for cross-institution comparison.

## Tools & Technologies
- Power BI Desktop
- DAX (measures and calculated flags)
- Power Query
- Azure Maps visual (geographic analysis)

## Notes
Both dashboards were built as part of MSBA coursework at the University of Louisville and are structured to be reviewed by hiring managers evaluating BI/dashboard development skills.# Power-BI
