# 📊 CJA Sandbox Template - Data View Summary

type:: cja-template
platform:: Adobe CJA
environment:: Sandbox

## 📁 Workspace Project

**Name:** Data View Summary  
**Link:** https://analytics.adobe.com/?linkId=07305ec4-7c43-489d-9c88-1beb20e46049&dpc=acc  

---

<img src="https://github.com/pgsmith2000/Adobe_CJA_Samples/blob/main/data_view_summary/data_view_summary.png" width="200">

## 📎 Assets

**Purpose:**  
Provides a structured overview of a CJA Data View, including key metrics, dimensions, and usage guidance.

Project Description [Markdown](https://github.com/pgsmith2000/Adobe_CJA_Samples/blob/main/data_view_summary/data_view_summary.md)
- PDF [data_view_summary.pdf](https://github.com/pgsmith2000/Adobe_CJA_Samples/blob/main/data_view_summary/data_view_summary.pdf)
- Image [data_view_summary.png](https://github.com/pgsmith2000/Adobe_CJA_Samples/blob/main/data_view_summary/data_view_summary.png)

## 📌 Description

A comprehensive **Data View exploration template** designed to:
- Provide a high-level understanding of available data
- Surface key KPIs and trends
- Validate schema completeness and data quality
- Serve as a starting point for analysis

## 📊 Key Panels & Insights

### 1. Overview KPIs
- Total People: 610,457  
- Total Sessions: 1,816,030  
- Total Events: 18,573,524  
- Total Orders: 272,064  
- Total Revenue: $221,963,415

👉 Strong “at-a-glance” orientation for new users

### 2. Trend Panels
- People / Sessions / Events over time
- Time per Person vs Time per Session

👉 Useful for identifying anomalies (e.g., drop to zero on Mar 4)

### 3. Revenue Analysis
- Daily revenue trend
- Revenue + Orders summary

### 4. Data Overview Table
- Daily breakdown across:
  - People
  - Sessions
  - Events
  - Time metrics
  - Orders
  - Revenue

👉 Acts as a **validation layer** for data completeness and consistency

### 5. Channel Analysis

#### Interaction Channel Summary
- Website, Mobile App, Call Center, POS, etc.
- Mix of behavioral + revenue metrics

#### Orders by Channel
- Online vs Offline split

#### Marketing Channel Summary
- Email, SMS, Push, Paid Search, Social, etc.

👉 Strong cross-channel performance view

## 🔍 Key Observations

- Clear daily variability in traffic and revenue
- Potential data gap on **Mar 4 (0 values)** → useful QA example
- Strong contribution from:
  - Mobile App
  - Call Center (high revenue impact)
- Marketing channels show heavy distribution across owned + paid

## 🎯 Use Cases

- Data View onboarding
- Implementation QA / anomaly detection
- KPI baseline analysis
- Channel performance exploration
- Demo template for stakeholders

## 🚧 Opportunities for Enhancement

- Add calculated metrics (conversion rate, AOV)
- Add segmentation (device, user type, geo)
- Include funnel visualization
- Add annotations for known anomalies (e.g., outages)

## 🧠 Pattern / Design Insight

This template follows a strong structure:

1. **Top-line KPIs**
2. **Trend validation**
3. **Detail breakdown**
4. **Channel segmentation**

👉 This is essentially a **CJA “starter dashboard blueprint”**

## 🔗 Related

- [[CJA Sandbox Templates]]
- [[digital_to_offline_product_conversion]]
