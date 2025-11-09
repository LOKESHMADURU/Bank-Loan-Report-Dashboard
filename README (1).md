# Bank Loan Report Dashboard (Excel | Pivot Tables)

A clean, interactive Excel dashboard to analyze bank loan performance using **Pivot Tables**, **charts**, and **slicers**. The report tracks applications, disbursements, repayments, portfolio quality, and borrower characteristics to enable data‑driven lending decisions.

## 🔧 Tools & Skills
- **Excel**: Pivot Tables, Pivot Charts, Slicers, Conditional Formatting, basic formulas (SUMIFS, AVERAGEIF, % calc)
- **Design**: KPI cards, donut/line/bar/treemap charts, layout & formatting

## 📊 Key KPIs (from sample dashboard)
- **Total Loan Applications:** **38.6K**
- **Total Funded Amount:** **$435.8M** (MTD example: **$54.0M**)
- **Total Amount Received:** **$473.1M** (MTD example: **$58.1M**)
- **Average Interest Rate:** **12.05%**
- **Average DTI:** **13.33%**
- **Good vs Bad Loans:** **86.18%** good · **13.82%** bad

> Note: Replace the above numbers with your latest refresh if your dataset changes.

## 🗂️ Data Model (Excel)
Single flat table of loan records with columns such as:
`issue_date`, `loan_status`, `funded_amount`, `amount_received`, `interest_rate`, `dti`, `term`, `grade`, `emp_length`, `purpose`, `state`, `home_ownership`.

## 🧭 Dashboards
### 1) **Summary**
- KPI cards for Applications, Funded Amount, Amount Received, Avg Interest, Avg DTI
- Donut charts for **Good vs Bad Loan** distribution
- Status-level views for **Applications**, **Funded**, **Received**, **Interest**, **DTI**

### 2) **Overview**
- **Monthly trend** of applications (line)
- **State heat map** for regional performance
- **Loan term** distribution (donut)
- **Employee length** breakdown (bar)
- **Purpose** analysis (bar)
- **Home ownership** distribution (treemap)

### 3) **Details**
- Grid-style table for record-level exploration with all slicers applied

## 🔍 Interactivity
- **Slicers** for `grade` and `purpose` (add more: `loan_status`, `term`, `state`)
- **MTD/MoM** indicators to track short-term movements
- Drill from **Summary → Overview → Details**

## ✅ How I Built It (Steps)
1. **Cleaned** raw data (dates, text categories, blanks, numeric formats).
2. Created **Pivot Tables** for KPIs and breakdowns (status, term, purpose, region, emp length).
3. Built **Pivot Charts** (line, donut, bar, treemap) and linked **slicers**.
4. Designed **KPI cards** (custom labels, % calc, number formatting).
5. Assembled **three dashboards** with consistent theme and layout.
6. Tested slicer interactions and validated totals across views.

## 📈 Example Insights
- High share of **Good Loans (≈86%)** indicates strong portfolio quality.
- **Applications rising across months**, with certain states contributing the most.
- **60‑month terms** dominate applications; **credit card & debt consolidation** are top purposes.

## 🚀 How to Use
1. Open the Excel file.
2. Go to **Summary**, explore KPIs; filter with slicers.
3. Use **Overview** for trends and dimensional analysis.
4. Use **Details** to drill into records for audit or export.

## 🗺️ Folder Structure (suggested)
```
Bank-Loan-Excel-Dashboard/
├─ data/                 # raw or cleaned CSV/XLSX
├─ dashboard/            # final Excel dashboard
├─ docs/                 # screenshots for README
└─ README.md
```

## 🧩 Future Enhancements
- Add **date table** for robust time‑intelligence (MTD/QTD/YTD with formulas).
- Add **cohort/roll‑rate** views for delinquency tracking.
- Publish to **Power BI** for role‑based sharing (optional).

## 📣 Credits
Built by **Lokesh Maduru** using Excel Pivot Tables and charts.
```text
Project: Bank Loan Report Dashboard | Excel | Pivot Tables
```

