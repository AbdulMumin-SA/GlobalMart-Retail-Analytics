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
| **Executive Presentation** | 12-slide PowerPoint deck with speaker notes, chart explanations, and Q&A preparation guide |
| **Technical Documentation** | 34-column data dictionary with analytical use, tenet mapping, and Power BI quick-start guide |
| **Stakeholder Communication** | Presentation guide written for two audiences simultaneously: technical reviewer and business decision-maker |

