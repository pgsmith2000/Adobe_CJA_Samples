# Adobe Customer Journey Analytics (CJA) Sample Projects

This repository contains a collection of sample **Adobe Customer Journey Analytics (CJA)** projects designed to demonstrate my experience in:

- Journey analysis and optimization  
- Attribution modeling (session vs person vs participation)  
- Cross-channel performance measurement  
- Data storytelling and executive-level insights  

Each project includes:
- 📄 A PDF export of the full CJA Workspace project  
- 🖼️ A PNG preview image for quick reference  

> 🚧 This is an evolving collection. Additional projects and use cases will be added over time.

---

## 📊 Project Samples

---

### 🔹 Project Name: Personalization vs Fallback Performance Analysis (CJA)

**(Advanced — Personalization Effectiveness & Decisioning Evaluation)**

<img src="https://github.com/pgsmith2000/Adobe_CJA_Samples/blob/main/cja_personalization_strategy_analysis/cja_personalization_strategy_analysis.png" alt="Personalization Effectiveness Thumbnail" width="400"/>

#### **Executive Summary**  
This project evaluates the effectiveness of personalization strategies by comparing personalized, fallback, and no-offer experiences across user interactions. The analysis separates **coverage (how often offers are shown)** from **effectiveness (how outcomes align with user behavior)** to determine whether personalization is delivering incremental value.

The project begins with a coverage analysis comparing offer exposure to outcome contribution, revealing that “No Offer” experiences generate a majority of accepted outcomes despite limited exposure. It then introduces a strategy-level effectiveness framework using an **Acceptance vs Rejection Index** to evaluate how well different approaches align with user behavior independent of exposure bias. A final panel translates technical strategies into **business-level offer types**, identifying which experiences perform best in real-world contexts.

A supporting scatterplot combines **effectiveness (index)** with **scale (accepted volume)** to highlight high-impact opportunities and underperforming strategies.

Key findings show that baseline user intent is a stronger driver of outcomes than offer exposure, with both personalized and fallback strategies underperforming relative to their reach. Behavior-driven and time-sensitive offers (e.g., abandonment prompts, flash sales) outperform generic promotional and loyalty messaging, while most strategies cluster near baseline performance, indicating incremental rather than transformative impact.

**Key Focus Areas**

- Personalization vs fallback vs no-offer coverage and contribution
- Strategy effectiveness using accepted vs rejected outcome comparison
- Offer-level performance translated into business context
- Identification of high-impact strategies using effectiveness vs scale
- Evaluation of whether personalization delivers incremental value

**Data Considerations & Limitations**

- Offer Presented metrics were inconsistent or unreliable at the experience level, preventing traditional conversion analysis
- Offer Accepted frequently exceeded Offer Presented, indicating misaligned or non-sequential event tracking
- Weak attribution between offer exposure and outcomes, with many accepted events occurring in “No Offer” contexts
- No evidence of controlled experimentation (A/B or A4T), limiting causal interpretation
- Offer Name used as a proxy for strategy type, requiring interpretive grouping rather than strict classification

**Links**

- 📄 [View PDF](https://github.com/pgsmith2000/Adobe_CJA_Samples/blob/main/cja_personalization_strategy_analysis/cja_personalization_strategy_analysis.pdf)
- 🖼 [View PNG Image](https://github.com/pgsmith2000/Adobe_CJA_Samples/blob/main/cja_personalization_strategy_analysis/cja_personalization_strategy_analysis.png)

#### 📌 Notes

- All data shown is sample/demo data from Adobe CJA sandbox environments
- Observed inconsistencies reflect **real-world data challenges in analytics implementations**
- This project emphasizes **analytical rigor, adaptability, and interpretation under imperfect data conditions**

---

### 🔹 Project Name: Call Deflection & Digital Self-Service Optimization  

**(Advanced — Call Center Analytics & Digital Journey Analysis)**

<img src="https://github.com/pgsmith2000/Adobe_CJA_Samples/blob/main/call_deflection_digital_self_service_optimization/call_deflection_digital_self_service_optimization.png" alt="AJO Journey Optimization Thumbnail" width="400"/>

**Status:** Draft / In Progress  

**Executive Summary**  
This project analyzes the relationship between digital engagement and call center demand, identifying key drivers of call volume, escalation behavior, and cost impact. The analysis highlights how customer issues, digital experience gaps, and repeat calling behavior contribute to operational load and provides a framework for improving self-service and reducing support costs.

**Key Focus Areas**
- Digital → Call conversion and repeat calling behavior  
- Call reason analysis and escalation rates  
- Cost impact and optimization opportunities  
- Digital journey failure points (pages driving calls)  

**Links**

- 📄 [View PDF](https://github.com/pgsmith2000/Adobe_CJA_Samples/blob/main/call_deflection_digital_self_service_optimization/call_deflection_digital_self_service_optimization.pdf)
- 🖼 [View PNG Image](https://github.com/pgsmith2000/Adobe_CJA_Samples/blob/main/call_deflection_digital_self_service_optimization/call_deflection_digital_self_service_optimization.png)

---

### 🔹 Project Name: AJO Journey Optimization: Engagement, Conversion, and Revenue Attribution  

**(Advanced — Attribution Modeling & Omni-Channel Analysis)**

<img src="https://github.com/pgsmith2000/Adobe_CJA_Samples/blob/main/ajo_journey_optimization_engagement/ajo_journey_optimization_engagement.png" alt="AJO Journey Optimization Thumbnail" width="400"/>


**Executive Summary**  
This project analyzes Adobe Journey Optimizer (AJO) performance across multiple customer journeys, focusing on engagement, conversion, and revenue attribution. The analysis evaluates how different journeys contribute to business outcomes using a structured framework of funnel metrics and attribution models.

The project begins with a session-based view of performance to measure immediate conversion behavior, then expands to person-based attribution to capture delayed and cross-channel conversions. A comparative attribution panel highlights the differences between **Last Touch (Session)**, **Last Touch (Person)**, and **Participation** models, revealing how journey impact evolves from conversion to influence.

Key findings show that while abandonment journeys dominate immediate conversions, earlier-stage journeys play a significant role in influencing downstream purchases—particularly in cross-session and likely in-store scenarios.

**Key Focus Areas**
- Journey performance analysis (delivery → engagement → conversion)  
- Attribution modeling (session vs person vs participation)  
- Cross-channel and delayed conversion behavior  
- Revenue attribution and channel contribution analysis  
- Identification of “closer” vs “influencer” journeys  

**Links**

- 📄 [View PDF](https://github.com/pgsmith2000/Adobe_CJA_Samples/blob/main/ajo_journey_optimization_engagement/ajo_journey_optimization_engagement.pdf)
- 🖼 [View PNG Image](https://github.com/pgsmith2000/Adobe_CJA_Samples/blob/main/ajo_journey_optimization_engagement/ajo_journey_optimization_engagement.png)

---

### 🔹 Project Name: Digital Product Views & Conversion Analysis  
**(Intermediate — Conversion Behavior & Cohort Analysis)**

<img src="https://github.com/pgsmith2000/Adobe_CJA_Samples/blob/main/digital_to_offline_product_conversion/digital_product_views_conversion.png" alt="Digital Product Views & Conversion Thumbnail" width="400"/>

**Executive Summary**  
This project analyzes digital product engagement and conversion behavior across online and offline channels. The focus is on understanding how users interact with product views and how those interactions translate into downstream purchase activity.

The analysis incorporates cohort-based views to evaluate user behavior over time, along with channel segmentation to distinguish between online and point-of-sale (POS) conversions. By comparing engagement patterns and conversion outcomes, the project highlights differences in how digital interactions contribute to both immediate and delayed purchase behavior.

Key findings emphasize the importance of cross-channel analysis, showing that while digital engagement drives strong intent, a meaningful portion of conversions may occur outside the digital channel.

**Key Focus Areas**
- Product view engagement and conversion behavior  
- Cohort analysis (daily and weekly trends)  
- Online vs offline (POS) conversion comparison  
- Channel segmentation and cross-channel insights  
- Identification of conversion drop-off and engagement patterns  

**Links**

- 📄 [View PDF](https://github.com/pgsmith2000/Adobe_CJA_Samples/blob/main/digital_to_offline_product_conversion/digital_product_views_conversion.pdf)
- 🖼 [View PNG Image](https://github.com/pgsmith2000/Adobe_CJA_Samples/blob/main/digital_to_offline_product_conversion/digital_product_views_conversion.png)

---

### 🔹 Project Name: Data View Summary  
**(Foundational — Data Modeling & CJA Structure)**

<img src="https://github.com/pgsmith2000/Adobe_CJA_Samples/blob/main/data_view_summary/data_view_summary.png" alt="Data View Summary Thumbnail" width="400"/>

**Executive Summary**  
This project provides a structured overview of a Customer Journey Analytics (CJA) data view, focusing on the underlying data model, key dimensions, and metrics available for analysis. The goal is to establish a clear understanding of how data is organized and how it can be leveraged for reporting and insights.

The analysis highlights core components such as event structure, identity stitching, and key performance metrics, serving as a foundational reference for building more advanced analyses. By documenting the data view and its capabilities, this project supports consistent and accurate use of CJA across downstream reporting and analysis.

Key findings emphasize the importance of well-defined data structures, consistent metric definitions, and a clear understanding of how dimensions and events interact within the CJA environment.

**Key Focus Areas**
- CJA data view structure and organization  
- Key dimensions, metrics, and events  
- Identity stitching and data relationships  
- Metric definition and consistency  
- Foundational setup for downstream analysis  

**Links**

- 📄 [View PDF](https://github.com/pgsmith2000/Adobe_CJA_Samples/blob/main/data_view_summary/data_view_summary.pdf)
- 🖼 [View PNG Image](https://github.com/pgsmith2000/Adobe_CJA_Samples/blob/main/data_view_summary/data_view_summary.png)

---

## 📌 Notes

- All data shown is sample/demo data from Adobe CJA sandbox environments  
- Projects are designed to demonstrate analytical thinking, not business-specific conclusions  
- Attribution models, segmentation, and KPIs are intentionally varied across projects  

---

## 🚀 Future Additions

Planned additions to this repository include:

- Funnel and fallout analysis templates  
- Cohort and retention analysis  
- Product and merchandising performance  
- Experimentation (A/B testing) analysis frameworks  
- Advanced attribution comparisons  

---