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

<img src="https://github.com/pgsmith2000/Adobe_CJA_Samples/blob/main/personalization_effectiveness_analysis_cja/cja_personalization_strategy_analysis.png" alt="Personalization Effectiveness Thumbnail" width="400"/>

#### **Executive Summary**

This project evaluates the effectiveness of personalization strategies within Adobe Customer Journey Analytics by comparing **personalized, fallback, and no-offer experiences** across user interactions. The analysis introduces a structured framework that separates **coverage (how often offers are shown)** from **effectiveness (how outcomes align with user behavior)**.

Results show that **“No Offer” experiences drive a disproportionate share of accepted outcomes (54%) despite representing only ~32% of exposure**, while both personalized and fallback strategies underperform relative to their reach . This suggests that **baseline user intent may be a stronger driver of outcomes than current offer decisioning logic**.

Further analysis at the **strategy and offer level** reveals that:

- Behavior-driven and time-sensitive offers (e.g., abandonment prompts, flash sales) align more closely with user acceptance
- Generic promotional and loyalty messaging underperform relative to other strategies
- Most strategies cluster near baseline performance, indicating **incremental—not transformative—impact from personalization**

A scatterplot combining **effectiveness (index) and scale (accepted volume)** highlights that the highest-value opportunities are those that deliver both strong alignment with user behavior and meaningful reach.

#### ⚠️ **Data Limitations & Observed Issues**

This analysis uncovered several important data constraints that impact interpretation:

##### 1. Missing / Incomplete Offer Lifecycle Tracking

- **Offer Presented metrics were unreliable or unavailable at the experience level**, preventing traditional funnel analysis (Presented → Accepted)
- As a result, effectiveness was measured using **relative outcome distribution (Accepted vs Rejected)** instead of conversion rates

##### 2. Misaligned Event Relationships

- In multiple cases, **Offer Accepted exceeded Offer Presented**, indicating:
    - Events are not strictly sequential
    - Metrics may be captured in **different contexts or containers (event vs session vs decision scope)**

👉 This required abandoning standard acceptance rate calculations

##### 3. Attribution Ambiguity

- Accepted outcomes frequently occurred in:
    - **“No Offer” contexts**
    - Or contexts not clearly tied to a presented offer

👉 This suggests:

- Weak or indirect attribution between offer exposure and outcome
- Potential gaps in **decisioning or tracking implementation**

##### 4. Lack of True Experimentation (No A/B or A4T)

- No clear evidence of:
    - Controlled experiments
    - Variant-level comparisons

👉 This limits the ability to infer **causal impact of personalization**

##### 5. Strategy Classification Constraints

- “Offer Name” was used as a **proxy for strategy type**
- These values represent **business use cases**, not standardized categories

👉 Insights are directional and require interpretation rather than strict classification

#### 🧠 **Analytical Approach**

To address these limitations, the analysis applies a consistent framework:

##### Panel 1 — Coverage & Volume

- Compares **exposure vs outcome share**
- Identifies whether personalization contributes incremental value

##### Panel 2 — Strategy Effectiveness

- Evaluates strategies using an **Acceptance vs Rejection Index**
- Measures alignment with user behavior independent of exposure bias

##### Panel 3 — Offer-Level Effectiveness (Business Context)

- Translates technical strategy data into **business-readable offer types**
- Identifies which experiences resonate most with users

##### Scatterplot — Effectiveness vs Impact

- Combines:
    - **Effectiveness (index)**
    - **Scale (accepted volume)**
- Highlights:
    - High-value opportunities
    - Underperforming high-volume strategies

#### 🔑 **Key Takeaways**

- Personalization does not inherently drive outcomes—**relevance and intent alignment matter more than offer presence**
- Many strategies operate near baseline performance, suggesting **limited incremental lift**
- Behavioral and contextual experiences outperform broad promotional messaging
- “No Offer” performance indicates that **some experiences may not require intervention at all**
- Effective optimization requires prioritizing **high-impact, high-alignment strategies**

**Links**

- 📄 [View PDF](https://github.com/pgsmith2000/Adobe_CJA_Samples/blob/main/personalization_effectiveness_analysis_cja/cja_personalization_strategy_analysis.pdf)
- 🖼 [View PNG Image](https://github.com/pgsmith2000/Adobe_CJA_Samples/blob/main/personalization_effectiveness_analysis_cja/cja_personalization_strategy_analysis.png)

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