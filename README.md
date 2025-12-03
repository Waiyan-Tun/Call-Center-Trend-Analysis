# **Call Center Trends Analysis**

## **Data Analysis & Visualization Project**

### **Introduction**

This Call Center Trends Analysis project explores customer service performance by analyzing **call volume**, **agent efficiency**, and **customer satisfaction (CSAT)**.

The goal is to uncover operational trends and performance insights within the call center to enhance customer satisfaction and optimize service quality.

This project follows the six-step data analysis framework:
**Ask → Prepare → Process → Analyze → Share → Act**

---

## **Background of Study**

The dataset consists of **call center customer satisfaction survey data**, including call details, agent performance metrics, and service outcomes. This dataset enables analysis of agent workload patterns, resolution efficiency, and customer satisfaction trends.

---

## **1. Ask**

### **Business Task**

Identify key performance trends in the call center by analyzing:

* How agents differ in performance and satisfaction outcomes
* What factors affect customer satisfaction
* Overall call volume and resolution efficiency

### **Key Questions**

* Which agents are performing best in terms of **answers**, **resolutions**, and **CSAT**?
* What is the **overall satisfaction score**, and how does it vary by agent?
* How many calls were made and answered each month?
* What is the **average speed of answer**, and how does it influence CSAT?
* What trends exist in **resolved vs. unresolved** calls?

### **Key Stakeholders**

* **Customer Service Manager** – Oversees agent performance and service quality
* **Operations Team** – Focuses on improving response time and efficiency
* **Quality Assurance Team** – Monitors customer satisfaction and feedback
* **Executive Leadership** – Uses insights for staffing, training, and process improvements

---

## **2. Prepare**

### **Data Source**

* Dataset: **Call Center Customer Satisfaction Survey Dataset**
* Source: Internal call center survey data
* Data includes call details such as:

  ```
  agent_name, call_id, date, answered, resolved,
  satisfaction_score, speed_of_answer, topic
  ```

### **Data Integrity (ROCCC Principles)**

* **Reliable**: Contains structured call records and survey responses
* **Original**: Directly extracted from internal systems
* **Comprehensive**: Includes call outcomes, response times, and CSAT
* **Current**: Covers the analysis period of **January to March 2021**
* **Cited**: Internal dataset used for performance reporting

### **Tools Used**

* **Power BI** – Data cleaning, modeling, and visualization
* **Excel** – Initial data exploration
* **GitHub** – Documentation & version control

---

## **3. Process**

### **Data Preparation & Cleaning**

* Checked for missing values and standardized columns (Y/N, dates, scores)
* Removed invalid satisfaction scores outside the valid range
* Ensured consistency in `answered` and `resolved` fields
* Extracted **month** and **week** fields for trend analysis
* Created measures in Power BI for:

  * Average satisfaction score
  * Average speed of answer
  * Total calls, answered calls, resolved calls
  * Agent-level KPIs

---

## **4. Analyze**

### ***Key Insights from Analysis***

#### **1. Agent Performance Ranking**

* Each agent evaluated by:

  * **# of calls answered**
  * **# of calls resolved**
  * **Average satisfaction rating**
  * **Average speed of answer**
* Top-performing agents show a strong balance between **high call resolution** and **high satisfaction scores**.

#### **2. Average Speed of Answer**

* Overall average speed of answer: **67.52 seconds**
* Faster response correlates with **higher CSAT scores**.

#### **3. Overall Satisfaction**

* Overall CSAT score: **3.40 / 5**
* Several agents exceed the overall average score.

#### **4. Monthly Call Volume**

* January: 1455 calls
* February: 1298 calls
* March: 1301 calls

#### **5. Call Outcomes**

* **Answered calls:** ~81%
* **Resolved calls:** ~73%

#### **6. Agent-Level CSAT & Resolved Calls**

* Visual scatter plot shows the relationship between:

  * **Number of calls resolved**
  * **Agent satisfaction score**
* Helps identify high-performing agents and those needing training.

---

## **5. Share**

### **Dashboard Overview**

The Power BI dashboard includes:

* Agent performance ranking table
* KPIs (Average Speed of Answer, Overall Satisfaction)
* Monthly call volume visualization
* Answered vs. unresolved donut charts
* CSAT vs. resolved calls scatter plot
* Filters by agent, topic, and date

### **Key Findings Summary**

| Category                  | Insight                                                |
| ------------------------- | ------------------------------------------------------ |
| **Call Volume**           | Peak in January, stable in Feb–Mar                     |
| **Answer Rate**           | ~81% of all calls were answered                        |
| **Resolution Rate**       | ~73% successful resolutions                            |
| **Satisfaction**          | Overall CSAT is 3.40 with agent variance               |
| **Top Performers**        | Dan, Martha, Greg show high CSAT & high resolutions    |
| **Areas for Improvement** | Some agents have slower response times, affecting CSAT |

---

## **6. Act**

### **Recommendations & Actionable Insights**

1. **Improve Speed of Answer**

   * High wait times reduce satisfaction.
   * Introduce staffing adjustments or queue management improvements.

2. **Coaching for Low-Performing Agents**

   * Identify agents with low CSAT or low resolution rates.
   * Provide targeted training sessions.

3. **Recognize High-Performing Agents**

   * Acknowledge agents with high CSAT and high resolution rates.
   * Use their methods as best-practice examples.

4. **Enhance Customer Feedback Process**

   * Capture more detailed satisfaction reasons for better root-cause analysis.

5. **Focus on Topics with Lower Satisfaction**

   * Identify problematic call topics using filters.
   * Improve scripts, training materials, or backend processes.

6. **Use Data for Workforce Planning**

   * Monthly trend analysis helps forecast call volume.
   * Adjust staffing based on expected peaks.

---

## **7. Conclusion**

This Call Center Trends Analysis project provides meaningful insights into overall performance trends, agent efficiency, customer satisfaction, and monthly workload patterns.

By addressing key improvement areas and leveraging agent strengths, the call center can significantly enhance customer experience and operational efficiency.

---

### 📌 **Project By:**

**Wai Yan Tun**

### 📊 Dashboard

Download "Call Center Trends Analysis.pbix" and open in Power BI to see the Dashboard (As dashboard is for internal access only)

---
