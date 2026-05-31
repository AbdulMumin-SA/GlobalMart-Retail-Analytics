# GlobalMart-Retail-Analytics
A full-cycle retail data analysis project covering 6 continents, and 4 fiscal years (2021–2024)


## TABLE OF CONTENTS

- [Overview](#overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Processing](#data-processing)
- [Skills Demonstrated](#skills-demonstrated)
- [Objectives / Problem Statement](#objectivesproblem-statement)
- [Data Analysis and Visualization](#data-analysis-and-visualization)
- [Insights](#insights)
- [Recommendations](#recommendations)

- ## OVERVIEW

This project delivers a comprehensive retail performance analysis for
**GlobalMart**, a fictional B2C e-commerce company operating across
six continents. The analysis examines four years of transactional data
(2021–2024) to answer one central business question:

> *What is driving GlobalMart's revenue growth — and what structural
> problems are quietly eroding the profitability that growth should
> be generating?*

The project is structured around the **four tenets of data analysis**,
each building on the last to form a single, connected analytical argument:

| Tenet | Question Answered |
|---|---|
| 📊 **Descriptive** | What happened? — Revenue, profit, orders, and customer behaviour across all dimensions |
| 🔍 **Diagnostic** | Why did it happen? — Root causes of profit leakage, return spikes, and margin compression |
| 📈 **Predictive** | What is likely to happen? — 2025 revenue and profit forecast using trend extrapolation |
| 🎯 **Prescriptive** | What should the business do? — Six data-backed, quantified recommendations |

**Key findings at a glance:**
- 💰 **$2,637,250** total revenue across 2021–2024
- 📉 **31.74%** blended gross margin — declining in 2024 despite revenue recovery
- ⚠️ **24.5%** of orders are loss-making — driven by a discount policy with no floor
- 🔄 **8.62%** return rate — 72% above the 5% industry benchmark
- 🌍 **Oceania** has the highest average order value ($549) yet is the
  most underinvested continent

## DATA SOURCE

| Attribute | Detail |
|---|---|
| **Dataset Name** | GlobalMart B2C Retail Transaction Dataset |
| **Source** | Blossom Academy |
| **Period Covered** | January 2021 — December 2024 |
| **Records** | 5,000 order transactions |
| **Columns** | 34 fields |
| **Unique Customers** | 600 |
| **Unique Products** | 130 across 5 categories and 24 sub-categories |
| **Geographic Scope** | 23 countries across 6 continents |
| **Currency** | USD throughout |

## TOOLS

| Tool | Purpose in This Project |
|---|---|
| 📊 **Microsoft Excel** | Pivot table analysis, summary reporting, and structured analytical workbook |
| 📋 **Power BI** | Interactive dashboard covering all four analytical tenets with DAX measures, time intelligence, and scenario planning |
| 📝 **Microsoft Word** | Executive presentation guide and speaker notes documentation |
| 🖥️ **PowerPoint** | Executive presentation deck |


## DATA PROCESSING
| Step | Purpose in This Project |
|---|---|
|**Cleaning** | Removed duplicates, standardised date formats, resolved missing values in shipping and return fields|
|**Enrichment** | Calculated derived fields: gross margin %, YoY growth, AOV by segment/channel, return cost estimates|
|**Segmentation** | Grouped customers by segment (Professional, Consumer, etc.), channel, geography, and payment method|
|**Validation** | Cross-checked order totals and revenue figures across years before visualization|
  

## SKILLS DEMONSTRATED

### Technical Skills

| Skill | How It Is Demonstrated |
|---|---|
| **DAX (Power BI)** | 47 custom measures across core financials, time intelligence, diagnostic ratios, predictive modelling, and indexing |
| **Time Intelligence DAX** | `SAMEPERIODLASTYEAR`, `DATESYTD`, `DATEADD`, `CALENDARAUTO` — full date table with marked relationships |
| **Excel Analytical Modelling** | Pivot-based multi-tenet workbook with conditional formatting, embedded charts, and structured cross-sheet referencing |
| **Data Modelling** | Star schema in Power BI: fact table (Dataset) + DateTable with active relationships |
| **Statistical Analysis** | Linear trend extrapolation, CAGR calculation, correlation analysis (discount vs profit), index-based benchmarking |
| **What-If Analysis** | Power BI numeric range parameter for interactive 2025 growth rate scenario planning |

### Analytical Skills

| Skill | How It Is Demonstrated |
|---|---|
| **Descriptive Analysis** | Revenue, profit, margin, and volume summarised across 8 dimensions (year, quarter, category, sub-category, market, continent, segment, channel) |
| **Diagnostic Analysis** | Five sequential investigations connecting discount policy → profit destruction → return behaviour → geographic margin pressure → channel profitability |
| **Root Cause Analysis** | Identified two independent root causes of margin compression: discount policy (addressable) and geographic shipping cost structure (structural) |
| **Predictive Modelling** | CAGR-based revenue forecast with confidence interval, augmented by interactive scenario planning |
| **Prescriptive Reasoning** | Six recommendations with named actions, quantified financial impact, and sequenced implementation timeline |
| **Data Storytelling** | All four tenets structured as a single connected narrative — each tenet's finding motivates the next tenet's question |

### Communication Skills

| Skill | How It Is Demonstrated |
|---|---|
| **Stakeholder Communication** | Presentation guide written for two audiences simultaneously: technical reviewer and business decision-maker |


## OBJECTIVES / PROBLEM STATEMENT

GlobalMart is a B2C retail company with operations across six continents.
Despite generating $2.6M in revenue over four years and recovering
strongly in 2024 (+15.3% YoY), the business faces three unresolved
structural problems:

### Problem 1 — Revenue Growth Is Not Translating to Profit Growth
2024 was the highest-revenue year on record ($702,533) — yet the gross
margin *declined* to 30.86%, down from 32.49% in 2023. The business is
growing the top line while the bottom line compresses.

**The question:** What is causing margin to decline as
revenue grows?

### Problem 2 — A Quarter of All Orders Are Loss-Making
24.5% of all 5,000 orders generated negative gross profit. This is not
a rounding issue or a small anomaly — it represents a structural leak
in the business model.

**The question:** What is causing nearly one in four orders
to lose money — and is it the same root cause across all categories
and markets?

### Problem 3 — Operational Inefficiency Is Compounding the Financial Damage
An 8.62% return rate (72% above the 5% industry benchmark) and a 7.84%
cancellation rate mean that roughly 16% of all orders never complete
successfully — generating costs without generating retained revenue.

**The question:** Are the return and cancellation problems
connected to the discount and margin problems, or are they independent
issues requiring separate interventions?

### The Overarching Objective

> Determine whether GlobalMart has a revenue problem, a cost problem,
> a pricing problem, or a policy problem — and deliver a prioritised,
> evidence-based action plan that distinguishes between what needs
> to be fixed immediately and what needs to be restructured
> strategically.


## DATA ANALYSIS AND VISUALIZATION
### Tenet 1 — Descriptive Analysis: What Happened?

**Year-over-Year Performance**
<img width="606" height="446" alt="image" src="https://github.com/user-attachments/assets/4f5b190a-a01d-47fe-9f0f-b11ef1901c6d" />

<img width="784" height="435" alt="image" src="https://github.com/user-attachments/assets/676194fa-d84b-40a1-8779-be26c4c50c33" />
<img width="580" height="283" alt="image" src="https://github.com/user-attachments/assets/9dbe3095-2954-48dc-a0f2-98e7e9744182" />


**Key descriptive findings:**
- Revenue declined two consecutive years (2022–2023) before recovering
  strongly in 2024
- AOV hit its lowest point in 2023 ($493) then its highest in 2024
  ($560) — a $67 swing in a single year
- Gross margin has never returned to its 2021 baseline of 32.32%
- Q4 and July are consistently the highest-revenue periods across
  all four years
- February is the lowest-revenue month in every single year

**Category Performance**

| Category | Revenue Share | Gross Margin | Profile |
|---|---|---|---|
| Home & Living | 56% | 21.9% | High volume, low efficiency |
| Beauty & Health | — | 53.7% | Low volume, highest efficiency |
| Electronics | — | ~25% | Balanced — strong absolute profit |
| Clothing & Apparel | — | ~45% | Strong margin, high return risk |
| Books & Media | Lowest ($77K) | Lowest | Candidate for rationalisation |

