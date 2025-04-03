# 🧪 Vanguard A/B Testing Analysis

## 📌 Project Overview
This project analyzes the impact of a **redesigned user interface (UI)** on user behavior using A/B testing data provided by *The Vanguard Group*. The analysis evaluates whether the new UI improves the **completion rate**, reduces **error rate**, and saves time in completing an online process.

---

## 🎯 Objectives
- Assess if the **new UI increases completion rates**
- Determine if the **UI reduces errors and improves efficiency**
- Evaluate if the improvement exceeds the **5% cost-effectiveness threshold**

---

## 📊 Datasets Used
- `df_final_demo` – Client demographics and segmentation
- `df_final_experiment_clients` – Experiment group assignments (Control vs Test)
- `df_final_web_data` – Digital footprints and user step tracking

---

## 📈 Key Metrics
- **Completion Rate**  
- **Error Rate** (total & per step)  
- **Time to Completion**  

---

## 🔬 Statistical Tests Applied
- **Proportion Z-Test** – To compare completion and error rates between groups  
- **Welch’s t-test** – To compare time taken between groups  
- **Cost-Effectiveness Test** – To validate if Test Group exceeds the +5% threshold in completion rate

---

## 📊 Visualizations
[View Tableau Dashboard](https://public.tableau.com/views/Vanguard_V7/Dashboard1backup?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  
Created in **Tableau** to support insight delivery:
- **Demographics & Segment Breakdown**
- **Completion Funnel**
- **Error Rate Trends**
- **Time per Step Analysis**

---

## 🔍 Key Findings

### Overall Results
**Higher Completion Rates in Test Group, But Slightly Slower Progress**  
The redesigned interface encouraged more users to complete the process, with the Test group achieving a **54% completion rate** compared to **48%** in the Control group. However, the Test group took slightly longer to complete the process (**342 seconds vs. 330 seconds**). The **error rate** for the Test group was also slightly higher.

---

### Step-by-Step Performance

#### Step 1: Higher Error Rate in Test Group  
The error rate **doubled** in the Test group compared to the Control group. This suggests that users encountered early difficulties with the new UI, possibly due to unclear navigation or instructions.

#### Step 2: Faster Despite Higher Error Rate  
Despite more errors, users in the Test group completed this step **faster** than those in the Control group, indicating a smoother flow despite some usability issues.

#### Step 3: Test Group Outperformed Control Group  
The Test group outperformed the Control group across all KPIs in Step 3 – including **completion rate**, **faster mean time**, and **fewer errors**.

#### Confirm Step: Higher Completion Rate and Lower Error Rate  
At the final confirmation step, the Test group had a **54% completion rate** (vs. 48%) and a **lower error rate** of **2%** (vs. 5%).

---

### Performance by Age Group

#### Under 30  
- **Completion Rate**: 61% (Test) vs. 52% (Control)  
- **Fastest time**: 263 seconds (~4 mins)  
- **Errors**: Slightly higher at 8%, but Step 3 had significantly lower errors

#### Age 31–50  
- Users in this group completed Step 3 **17 seconds faster** than Control, indicating smoother flow in the new UI.

#### Age 51–70  
- Largest user segment.  
- Time increased to **391 seconds vs. 371 seconds**  
- Error rate also rose to **11% (Test) vs. 7% (Control)**

#### Age 71+  
- **Completion dropped to 38%**  
- **Longest time**: 416 seconds (~7 mins)  
- **Highest error rate**: 13% vs. 8%  
- Demographic data suggests this group has **higher bank balances** and **longer tenure**, highlighting the need for better accessibility.

---

## 💡 Recommendations for Improvement

### 1. Optimize UI for Speed (Step 1)  
Streamline the interface and remove unnecessary elements to reduce user delay in the early steps.

### 2. Reduce Error Rates with Real-Time Guidance  
Add **tool-tip notifications** or **inline hints** to help users navigate Step 1 more easily and reduce the initial error spike.

### 3. Enhance Accessibility for Older Users (Step 3)  
Improve user experience for senior users by:
- Increasing **font sizes**
- Simplifying complex interactions
- Using clear, concise instructions

---

## 🧠 Key Learnings
- Applied real-world **UX metrics** and **A/B testing evaluation methods**
- Translated raw digital footprint data into actionable performance insights
- Strengthened skills in **Python**, **pandas**, **scipy**, **statsmodels**, and **Tableau**

---

## 🧰 Tools & Technologies
- **Python**, **pandas**, **NumPy**, **SciPy**, **statsmodels**
- **Tableau** (for dashboarding)
- **Jupyter Notebook**
- **Statistical Testing**, **Funnel Analysis**, **UX Metrics**

---

## 👩‍💻 Author
Rebecca Woo  
March | 2025
